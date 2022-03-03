<script>
  import himage from "../../static/treetoppurple.png";
  import Hamburger from 'svelte-hamburger';

  let open = false;
</script>
<!--Navigation bar-->



<nav class=" text-white h-12 w-full mx-auto flex justify-between items-center">
  <h1 class="text-xl font-bold md:text-xl font-bold lg:text-4xl font-bold">Jeffrey Freiwald</h1>
  <div class="hidden md:flex text-xl lg:text-2xl">
      <a class="ml-4" href="/">home</a>
      <a class="ml-4" href="/projects">projects</a>
      <a href="https://github.com/p0wa5" target="_blank" class="ml-4">github</a>
  </div>

  <div class="flex md:hidden">
    <Hamburger {open} on:click={() => open = !open} />
  </div>
</nav>

{#if open}
  <div class="text-white w-1/3 float-right h-auto px-3 py-2 block">
      <a class="float-right mt-2 font-bold" href="/">home</a>
      <a class="float-right mt-2 font-bold" href="/projects">projects</a>
      <a class="float-right mt-2 font-bold" target="_blank" href="https://github.com/p0wa5">github</a>
  </div>
{/if}
