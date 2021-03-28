<script>
  import Calendar from './Calendar.svelte';
  import List from './List.svelte';
  let date = null;
</script>

<Calendar bind:date />
<List bind:date />
