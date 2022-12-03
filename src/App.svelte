<script lang="ts">
  import NavBar from './lib/Navbar.svelte';
  import Banner from './lib/Banner.svelte';
  import Showcase from './lib/Showcase.svelte';
  import Footer from './lib/Footer.svelte';
  import Typewriter from 'svelte-typewriter';
</script>

<div>
  <NavBar />
  <Typewriter><Banner /></Typewriter>
  <Showcase />
  <Footer />
</div>