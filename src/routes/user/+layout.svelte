<script type="ts">
  import UserBar from '$lib/UserBar.svelte';
  import BottomBar from '../../lib/BottomBar.svelte';
  import NavBar from '../../lib/NavBar.svelte';
</script>

<UserBar/>
<NavBar />
<main>
  <slot />
</main>
<BottomBar />


<style>
  main {
    padding: 1rem 2rem;
    width: 100%;
    height: 4000px;
  }
</style>