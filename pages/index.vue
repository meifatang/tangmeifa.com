<template>
<div class="flex flex-col py-2">
  <header class="w-full px-4">
    <nav class="relative flex flex-wrap items-center justify-between px-2 py-3 bg-emerald-500 rounded">
      <div class="container px-4 mx-auto flex flex-wrap items-center justify-between">
        <div class="w-full relative flex justify-between lg:w-auto px-4 lg:static lg:block lg:justify-start">
          <a class="text-base font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercas" href="/">
            Felix.
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
              <a class="px-4 py-2 flex items-center text-xs uppercase font-bold leading-snu hover:opacity-75" href="/blog/">
                Blog
              </a>
            </li>
            <li class="nav-item">
              <a class="px-4 py-2 flex items-center text-xs uppercase font-bold leading-snug hover:opacity-75" href="https://blog.tangmeifa.com/">
                博客
              </a>
            </li>
            <li class="nav-item">
              <a class="px-4 py-2 flex items-center text-xs uppercase font-bold leading-snug hover:opacity-75" href="/about/">
                About
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <main class="mb-48 px-28">
    <h1 class="text-4xl font-black mb-3">
      Felix Tang's Web App
    </h1>
    <p>An Engineer and Hacker</p>
  </main>

  <footer class="flex justify-between mt-0 px-24">
    <div class="">© 2021 by 汤美法. All rights reserved.</div>
  </footer>
</div>
</template>
