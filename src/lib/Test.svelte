<svelte:head>
  <script src="https://cdn.tailwindcss.com"></script>
</svelte:head>

<script>
  import {Tester} from "https://raw.githubusercontent.com/mateomorris/primo-components/de0a89dae443d902b963374ab9ef281acbe4bf15/dist/Heading.svelte"
</script>

<div>
  <Tester>
    <slot><!-- optional fallback --></slot>
  </Tester>
  <h1 class="text-3xl">
    {hello}
  </h1>
</div>


<style>
h1 {
  font-size: 4rem;
  font-weight: 500;
}
</style>
