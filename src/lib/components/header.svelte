<script lang="ts">
  // 3rd Party Imports
  import { AppBar } from "@skeletonlabs/skeleton";
</script>

<AppBar>
  <svelte:fragment slot="lead">Idaho Runs</svelte:fragment>
  <svelte:fragment slot="trail"
    ><a
      href="https://github.com/MichaelCduBois/idaho-runs/issues/new?assignees=MichaelCduBois&labels=enhancement&projects=&template=event-request.md&title=%5BEVENT%5D"
      target="_blank noreferrer nofollow"
      class="btn variant-filled">Add Missing Event</a
    ></svelte:fragment>
</AppBar>
