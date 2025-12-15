<script>
  export let active = "Product";
</script>

<header class="sticky top-0 z-50 w-full border-b border-gray-100 bg-white/95 backdrop-blur-sm">
  <div class="mx-auto flex h-16 max-w-7xl items-center justify-between px-4 sm:px-6 lg:px-8">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2">
        <svg width="32" height="32" viewBox="0 0 67 66" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" clip-rule="evenodd" d="M0.625 24.7527V41.621L42.246 0H25.3777L0.625 24.7527ZM9.25909 0H0.625V8.6341L9.25909 0ZM0.625 66V57.7396L58.3646 0H66.625V8.60796L9.23297 66H0.625ZM25.3516 66H42.22L66.625 41.595V24.7266L25.3516 66ZM58.3386 66L66.625 57.7136V66H58.3386Z" fill="black"/>
        </svg>
        <span class="text-2xl font-bold tracking-tight font-sans">Fulfilled</span>
      </a>
      
      <nav class="hidden md:flex items-center gap-6">
        {#each ["Features", "How It Works", "About", "Careers"] as item}
          <a href="#{item.toLowerCase().replace(/ /g, '-')}" class="text-sm font-medium text-gray-600 hover:text-gray-900 transition-colors">
            {item}
          </a>
        {/each}
      </nav>
    </div>

    <div class="flex items-center gap-4">
      <a href="#login" class="text-sm font-medium text-gray-900 hover:text-gray-700">
        Log in
      </a>
      <a href="#get-started" class="rounded-full bg-black px-4 py-2 text-sm font-medium text-white hover:bg-gray-800 transition-colors">
        Get Started
      </a>
    </div>
  </div>
</header>
