<script lang="ts">
  // No external dependencies
</script>

<section class="py-24 bg-brand relative overflow-hidden text-white">
  <!-- Pattern Background -->
  <div class="absolute inset-0 opacity-10 flex flex-wrap content-start select-none pointer-events-none overflow-hidden text-[10px] leading-none font-mono">
      {#each Array(4000) as _}
        <span class="mr-2 mb-2">NEW</span>
      {/each}
  </div>

  <div class="container-custom mx-auto relative z-10">
    <div class="flex flex-col items-start max-w-2xl">
        <div class="mb-6">
            <svg width="48" height="48" viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
                <path d="M11.0001 21.0001L12.0001 23.0001L13.0001 21.0001C13.0001 21.0001 18.0001 19.5001 19.5001 15.0001C21.0001 10.5001 18.0001 6.0001 18.0001 6.0001C18.0001 6.0001 16.0001 6.5001 14.5001 8.0001C14.5001 8.0001 15.0001 4.0001 12.0001 2.0001C9.0001 4.0001 9.5001 8.0001 9.5001 8.0001C8.0001 6.5001 6.0001 6.0001 6.0001 6.0001C6.0001 6.0001 3.0001 10.5001 4.5001 15.0001C6.0001 19.5001 11.0001 21.0001 11.0001 21.0001Z"/>
            </svg>
        </div>
        <h2 class="text-4xl md:text-5xl font-semibold mb-4">Maple Research</h2>
        <p class="text-xl text-blue-100 mb-8">Insights from the Future of Voice AI</p>
        
        <button class="bg-white text-brand px-6 py-2 rounded font-medium flex items-center justify-between w-48 hover:bg-gray-100 transition-colors">
            Visit
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
        </button>
    </div>
  </div>
</section>
