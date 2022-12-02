<script lang="ts">
    import Typewriter from 'svelte-typewriter';
    
    const introHeader: string = "I am...";
    const introText: string = "A Software Engineering Professional & Hacker of Things..";

    
</script>

<main>
    <div class="showcase-container">
        <div class="showcase-intro">
            <h2>{introHeader}</h2>
            <p><Typewriter>{introText}</Typewriter></p>
        </div>
    </div>
</main>