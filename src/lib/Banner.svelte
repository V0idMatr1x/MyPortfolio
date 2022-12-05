<script lang="ts">
    const skill: Array<string> = [];
    
    skill.push("Enterprise Development");
    skill.push(" Software Optimization");
    skill.push(" Systems Programming");
    skill.push(" Desktop Applications");
    skill.push(" Full Stack Web");
    skill.push(" Linux");
    skill.push(" Cybersecurity");
    skill.push(" DevOps (CI/CD)");
    skill.push(" Research");
    skill.push(" Problem Solving");
    skill.push(" Agile");
</script>

<div class="skill-banner">
    <div class="skill-banner__content">
        <p id="skill">{skill.map(skill => skill).join(" |")}</p>
    </div>
</div>