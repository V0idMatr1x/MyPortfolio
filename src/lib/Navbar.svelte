<script lang="ts">
  const branding: string = "V0idMatr1x";
  const githubIcon: string = "fa-brands fa-github";
  const emailIcon: string = "fa-solid fa-envelope";
  const githubLink: string = "https://github.com/V0idMatr1x";
  const emailLink: string = "mailto:matr1xware@v0idmatr1x.com";
</script>

<nav class="nav-container">
  <span>{branding}</span>

  <ul>
    <li>
        <a href={githubLink} target="_blank" rel="noopener noreferrer">
          <i class={githubIcon}></i>
        </a>
    </li>
    <li>
        <a href={emailLink}>
          <i class={emailIcon}></i>
        </a>
      </li>
    </ul>
</nav>
