<svelte:head>
  <script src="https://cdn.tailwindcss.com"></script>
</svelte:head>

<div>
  <h1 class="text-3xl underline">
    <slot><!-- optional fallback --></slot>
  </h1>
</div>


<style>
h1 {
  font-size: 4rem;
  font-weight: 500;
}
</style>
