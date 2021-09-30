<script lang="ts">
  // core components
  import CardSettings from "../../notusComponents/Cards/CardSettings.svelte";
  import CardProfile from "../../notusComponents/Cards/CardProfile.svelte";
  export let location: string;
</script>

<div class="flex flex-wrap">
  <div class="w-full lg:w-8/12 px-4">
    <CardSettings />
  </div>
  <div class="w-full lg:w-4/12 px-4">
    <CardProfile />
  </div>
</div>
