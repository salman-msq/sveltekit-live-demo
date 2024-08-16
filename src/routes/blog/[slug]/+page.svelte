<!-- <script>
  export let data;
</script>

<p class="font-bold text-center">{data.content}</p> -->

<script lang="ts">
  export let data;
</script>

<div>
  {#each data.names as { name }}
    <div class="font-semibold">{name}</div>
  {/each}
</div>
