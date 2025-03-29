<script>
  import { goto } from '$app/navigation';
  function navigate() {
    goto('/to-db');
  }
</script>
<p>yes</p>
<button onclick={navigate}>to DB</button>