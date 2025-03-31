<script>
  import { goto } from '$app/navigation';
  function navigate() {
    goto('/to-db');
  }
</script>
<p>yes</p>
<p>yes2</p>
<button onclick={navigate}>to DB</button>