<script>
  import { goto } from '$app/navigation';
  function navigate() {
    goto('/to-db');
  }
</script>
<button onclick={navigate}>to DB</button>