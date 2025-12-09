<script lang="ts">
  // No external dependencies
</script>

<section class="bg-gray-50 pt-20 pb-16 overflow-hidden relative">
  <div class="container-custom mx-auto text-center relative z-10">
    <h1 class="text-5xl md:text-6xl font-semibold text-gray-900 mb-6 tracking-tight leading-tight">
      24/7 AI Voice for<br/>Restaurants
    </h1>
    <p class="text-xl text-gray-600 mb-12 max-w-2xl mx-auto leading-relaxed">
      Maple's Voice AI helps you answer inbound phone calls<br/>so your staff can focus on what matters.
    </p>

    <div class="relative max-w-5xl mx-auto flex flex-col md:flex-row items-center justify-center gap-8 md:gap-0">
      
      <!-- Left Illustration: Milk Carton -->
      <div class="hidden md:block absolute left-0 bottom-0 transform -translate-x-4 translate-y-4 w-48 h-48 opacity-100">
         <!-- Labels -->
         <div class="absolute -top-8 left-0 text-[10px] font-bold text-brand tracking-widest uppercase">Add Revenue</div>
         <div class="absolute top-10 -right-10 text-[10px] font-bold text-brand tracking-widest uppercase">Get Insights</div>
         
         <!-- Blue Line -->
         <div class="absolute top-0 left-4 w-0.5 h-8 bg-brand"></div>
         <div class="absolute top-14 right-0 w-8 h-0.5 bg-brand"></div>

         <!-- Carton SVG -->
         <svg viewBox="0 0 100 120" class="w-full h-full text-brand fill-none stroke-current stroke-[1.5]" xmlns="http://www.w3.org/2000/svg">
            <path d="M20 30 L50 10 L80 30 L80 100 L20 100 Z" />
            <path d="M20 30 L50 45 L80 30" />
            <path d="M50 45 L50 100" />
            <path d="M35 20 L65 20" stroke-dasharray="2 2" />
            <!-- Details -->
            <rect x="30" y="60" width="15" height="20" />
            <circle cx="65" cy="70" r="8" />
         </svg>
      </div>

      <!-- Center Card -->
      <div class="bg-white rounded-xl shadow-xl p-2 w-full max-w-md mx-auto relative z-20">
        <div class="bg-gray-50 rounded-lg p-6 mb-2 flex flex-col items-center justify-center h-48 relative overflow-hidden">
            <div class="text-sm font-medium text-gray-900 mb-4">Hear Maple in Action</div>
            
            <!-- Waveform -->
            <div class="flex items-center gap-1 h-12 mb-4">
                {#each Array(20) as _, i}
                    <div class="w-1.5 bg-gray-200 rounded-full" style="height: {20 + Math.random() * 30}px; animation: pulse 1s infinite {i * 0.1}s"></div>
                {/each}
                <!-- Play Button Overlay -->
                <div class="absolute inset-0 flex items-center justify-center">
                    <button class="w-12 h-12 bg-gray-900 rounded-full flex items-center justify-center text-white hover:scale-105 transition-transform shadow-lg">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" class="ml-1"><path d="M5 3l14 9-14 9V3z"/></svg>
                    </button>
                </div>
            </div>

            <div class="flex items-center gap-2 text-xs text-gray-500">
                <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
                <span>Taking Orders...</span>
                <span class="ml-2">0:05</span>
            </div>
        </div>
        <button class="w-full bg-brand hover:bg-brand-dark text-white py-3 rounded-lg font-medium flex items-center justify-center gap-2 transition-colors">
            Get Free Demo
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="bg-white/20 rounded-sm p-[1px]"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
        </button>
      </div>

      <!-- Right Illustration: Noodle Box -->
      <div class="hidden md:block absolute right-0 bottom-0 transform translate-x-4 translate-y-4 w-48 h-48">
         <!-- Labels -->
         <div class="absolute -top-8 right-0 text-[10px] font-bold text-brand tracking-widest uppercase">Add Revenue</div>
         <div class="absolute top-10 -left-10 text-[10px] font-bold text-brand tracking-widest uppercase">Get Insights</div>

         <!-- Blue Line -->
         <div class="absolute top-0 right-4 w-0.5 h-8 bg-brand"></div>
         <div class="absolute top-14 left-0 w-8 h-0.5 bg-brand"></div>

         <!-- Noodle Box SVG -->
         <svg viewBox="0 0 100 120" class="w-full h-full text-brand fill-none stroke-current stroke-[1.5]" xmlns="http://www.w3.org/2000/svg">
             <!-- Box shape -->
            <path d="M20 40 L80 40 L70 110 L30 110 Z" />
            <!-- Flaps -->
            <path d="M20 40 L10 20 L40 30" />
            <path d="M80 40 L90 20 L60 30" />
            <path d="M20 40 L50 50 L80 40" />
            <!-- Chopsticks/Noodles -->
            <path d="M40 30 L60 10" />
            <path d="M50 30 L70 10" />
         </svg>
      </div>

    </div>
  </div>
</section>

<style>
    @keyframes pulse {
        0%, 100% { height: 20px; }
        50% { height: 40px; }
    }
</style>
