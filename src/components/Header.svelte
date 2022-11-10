<script lang="ts">
</script>

<header>
  <div class="logo">
    <a href="/">
      <img src="/logo.svg" width="160" height="90" alt="閑古鳥" />
    </a>
  </div>
  <nav>
    <ul>
      <li><a href="/">About</a></li>
      <li><a href="/product">Product</a></li>
      <li><a href="/blog">Blog</a></li>
      <li>
        <a href="https://github.com/kanko-dori">GitHub</a>
      </li>
      <li><a href="/privacy-policy">Privacy</a></li>
    </ul>
  </nav>
</header>

<style>
  ul {
    display: flex;
    list-style: none;
    padding: 0;
  }
  li {
    margin: 0;
  }
  nav ul > li + li::before {
    content: "/";
    margin: 0 0.5em;
  }
</style>
