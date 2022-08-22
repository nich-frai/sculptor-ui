<script lang="ts">
  import { setContext } from "svelte";

  import { TabViewportController } from "./tab_viewport.controller";

  const controller = new TabViewportController();

  setContext("tab-viewport", controller);
</script>

<div class="tabbed-viewport">
  <slot />
</div>
