<script>
  import { Button } from "sveltestrap";

  const colors = [
    "primary", "secondary", "success", "danger", "warning", "info", "light", "dark"
  ];
</script>

{#each colors as color}
  <div>
    <Button {color}>
      {color}
    </Button>
  </div>
{/each}
