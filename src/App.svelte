<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
  import logo from './assets/svelte-welcome.png'
</script>

<main>
  <div>
    <!-- <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
      <img src={viteLogo} class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a> -->
    <img src={logo} class="logo svelte" alt="Svelte Logo" />

  </div>
  <h1>Vite + Svelte</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite, and <a href="https://fleek.xyz" target="_blank" rel="noreferrer">Fleek ⚡️</a> for deployment!
  </p>


  <p class="read-the-docs">
    Check out <a href="https://docs.fleek.xyz" target="_blank" rel="noreferrer">Fleek Docs</a> to learn more about Fleek
  </p>
</main>

<style>
  .logo {
    height: 20em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
