<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import Counter from './components/Counter.svelte'
</script>

<main>
  <div>
    <a href="https://vitejs.dev" target="_blank"> 
      <img src="/vite.svg" class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1 class="text-3xl">Never before</h1>

  <Counter />

  <p>
    My portfolio with my projects
  </p>
</main>
