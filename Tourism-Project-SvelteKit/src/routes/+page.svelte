<!--
<script>
    import svelteLogo from './assets/svelte.svg'
    import viteLogo from '/vite.svg'
    import Counter from './lib/Counter.svelte'
</script>
-->
<script>
    import "../../src/app.css";
</script>
  
  <svelte:head>
    <title>Niagara Falls Tourism</title>
    <meta name="description" content="A English project based upon the city Niagara Falls focused on the tourism related to Niagara Falls">
  </svelte:head>
  
  <header class="fade-in">
    <div class="grid grid-cols-5 grid-rows-1 gap-10 no-underline text-black my-12 place-items-center">
      <div class="hover:underline">
        <a href="/" class="hover:no-underline">History</a>
      </div>
      <div class="hover:underline">
        <a href="/">Attractions</a>
      </div>
      <div class="hover:underline">
        <a href="/">Sports</a>
      </div>
      <div class="hover:underline">
        <a href="/">Your Stay in Niagara Falls</a>
      </div>
      <div class="hover:underline"><a href="/">Work Cited Page</a></div>
    </div>
    <p>Hello World</p>
  </header>
  
  <!--
  <main class ="fade-in">
    <div>
      <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
        <img src={viteLogo} class="logo" alt="Vite Logo" />
      </a>
      <a href="https://svelte.dev" target="_blank" rel="noreferrer">
        <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
      </a>
    </div>
    <h1>Vite + Svelte</h1>
    <div class=""></div>
    <div class="card">
      <Counter />
    </div>
  
    <p>
      Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
    </p>
  
    <p class="read-the-docs">
      Click on the Vite and Svelte logos to learn more
    </p>
  </main>
  -->
  
  <style>
    .logo {
      height: 6em;
      padding: 1.5em;
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
  