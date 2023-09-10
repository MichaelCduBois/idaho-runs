<script lang="ts">
  import "../app.postcss";

  // Floating UI for Popups
  import { computePosition, autoUpdate, flip, shift, offset, arrow } from "@floating-ui/dom";
  import { storePopup } from "@skeletonlabs/skeleton";
  storePopup.set({ computePosition, autoUpdate, flip, shift, offset, arrow });

  // App Shell
  import { AppShell } from "@skeletonlabs/skeleton";
</script>

<AppShell>
  <!-- <svelte:fragment slot="header">Header</svelte:fragment> -->
  <slot />
  <!-- <svelte:fragment slot="footer">Footer</svelte:fragment> -->
</AppShell>
