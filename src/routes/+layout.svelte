<script lang="ts">
  import "../app.postcss";

  // Floating UI for Popups
  import { computePosition, autoUpdate, flip, shift, offset, arrow } from "@floating-ui/dom";
  import { storePopup } from "@skeletonlabs/skeleton";
  storePopup.set({ computePosition, autoUpdate, flip, shift, offset, arrow });

  // App Shell
  import { AppShell } from "@skeletonlabs/skeleton";

  // Idaho Runs Imports
  import Footer from "$lib/components/footer.svelte";
  import Header from "$lib/components/header.svelte";
</script>

<AppShell>
  <Header slot="header" />
  <slot />
  <Footer slot="footer" />
</AppShell>
