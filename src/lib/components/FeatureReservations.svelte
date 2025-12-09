<script lang="ts">
  // No external dependencies
</script>

<section class="py-20 bg-brand text-white overflow-hidden relative">
  <div class="container-custom mx-auto relative z-10">
    <div class="flex flex-col lg:flex-row gap-16">
      
      <!-- Left Content -->
      <div class="lg:w-1/3 pt-10">
        <h2 class="text-4xl font-semibold mb-6 leading-tight">
          Book your<br/>reservations<br/>easily
        </h2>
        <p class="text-lg text-blue-100 mb-8 leading-relaxed">
          Maple's Voice AI helps you answer inbound phone calls so your staff can focus on what matters.
        </p>
      </div>

      <!-- Right Content: Visualization -->
      <div class="lg:w-2/3 relative">
        <!-- Grid of letters -->
        <div class="grid grid-cols-12 gap-4 text-center text-xs font-mono opacity-30 select-none" style="mask-image: linear-gradient(to bottom, transparent, black 10%, black 90%, transparent);">
            {#each Array(10) as _, row}
                {#each Array(12) as _, col}
                    <div>{['A','P','L','E','M'][Math.floor(Math.random()*5)]}</div>
                {/each}
            {/each}
        </div>

        <!-- Highlighted "Table" -->
        <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-32 h-48 border-2 border-white rounded-full flex items-center justify-center shadow-[0_0_30px_rgba(255,255,255,0.3)]">
            <div class="grid grid-cols-2 gap-2">
                <div class="w-2 h-2 bg-white rounded-full"></div>
                <div class="w-2 h-2 bg-white rounded-full"></div>
                <div class="w-2 h-2 bg-white rounded-full"></div>
                <div class="w-2 h-2 bg-white rounded-full"></div>
            </div>
            
            <!-- Hand Cursor -->
            <div class="absolute -bottom-10 -right-10">
                <svg width="40" height="40" viewBox="0 0 24 24" fill="white" stroke="none" class="drop-shadow-lg"><path d="M10 24l-1-6-5-1 9-13 2 12 5 2-10 6z"/></svg>
            </div>
        </div>

        <!-- Bottom Card -->
        <div class="absolute bottom-0 right-0 bg-white/10 backdrop-blur-md border border-white/20 p-6 rounded-xl max-w-sm">
            <h3 class="text-xl font-semibold mb-2">Allow guests to book, modify, or cancel reservations with ease.</h3>
            <button class="bg-white text-brand px-4 py-2 rounded font-medium text-sm flex items-center gap-2 hover:bg-gray-100 transition-colors mt-4">
                Book Demo
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
            </button>
        </div>

      </div>
    </div>
  </div>
</section>
