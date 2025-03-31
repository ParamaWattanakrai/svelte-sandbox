<script lang="ts">
  import { goto } from '$app/navigation';

  let { data } = $props();

  function navigate() {
    goto('/');
  }
</script>

<ul>
  {#each data.instruments as instrument}
    <li>{instrument.name}</li>
  {/each}
</ul>

<button onclick={navigate}>to home</button>