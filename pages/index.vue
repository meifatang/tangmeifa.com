<template>
<div>
  <div class="flex flex-wrap py-2">
    <div class="w-full px-4">
      <nav class="relative flex flex-wrap items-center justify-between px-2 py-3 bg-emerald-500 rounded">
        <div class="container px-4 mx-auto flex flex-wrap items-center justify-between">
          <div class="w-full relative flex justify-between lg:w-auto px-4 lg:static lg:block lg:justify-start">
            <a class="text-sm font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercas" href="/">
              Felix Tang
            </a>
            <button class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none" type="button">
              <span class="block relative w-6 h-px rounded-sm"></span>
              <span class="block relative w-6 h-px rounded-sm mt-1"></span>
              <span class="block relative w-6 h-px rounded-sm mt-1"></span>
            </button>
          </div>
          <div class="flex lg:flex-grow items-center" id="example-navbar-info">
            <ul class="flex flex-col lg:flex-row list-none ml-auto">
              <li class="nav-item">
                <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snu hover:opacity-75" href="/blog/">
                  Blog
                </a>
              </li>
              <li class="nav-item">
                <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug hover:opacity-75" href="https://blog.tangmeifa.com/">
                  博客
                </a>
              </li>
              <li class="nav-item">
                <a class="px-3 py-2 flex items-center text-xs uppercase font-bold leading-snug hover:opacity-75" href="/about/">
                  About
                </a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</div>
</template>

<script>
export default {}
</script>

<style>

</style>