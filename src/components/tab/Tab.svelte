<script lang="ts">
  import { setContext } from "svelte";

  import { TabController } from "./tab.controller";

  const controller = new TabController();
  setContext("tab", controller);
</script>

<div class="tab">
  <slot />
</div>
