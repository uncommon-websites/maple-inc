<script lang="ts">
  // No external dependencies
</script>

<section class="py-20 bg-gray-50">
  <div class="container-custom mx-auto">
    <div class="text-center mb-12">
      <h2 class="text-3xl md:text-4xl font-semibold text-gray-900 mb-4">
        1,000+ Restaurant Owners<br/>Trust Maple
      </h2>
      <div class="flex justify-center gap-6 text-sm text-gray-600">
        <div class="flex items-center gap-2">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-brand"><polyline points="20 6 9 17 4 12"></polyline></svg>
          No Per Minute Fees
        </div>
        <div class="flex items-center gap-2">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-brand"><polyline points="20 6 9 17 4 12"></polyline></svg>
          Unlimited Menu Sizes
        </div>
      </div>
    </div>

    <!-- Carousel Container -->
    <div class="relative max-w-6xl mx-auto">
      <!-- Main Card -->
      <div class="bg-brand rounded-2xl overflow-hidden shadow-2xl text-white flex flex-col md:flex-row relative z-10">
        
        <!-- Content -->
        <div class="p-8 md:p-12 md:w-1/2 flex flex-col justify-between relative">
           <!-- Logos at top -->
           <div class="flex gap-6 mb-8 opacity-80">
                <div class="text-xs font-bold border border-white/30 px-2 py-1 rounded">YUMMY'S<br>KOREAN BBQ</div>
                <div class="text-xs font-bold opacity-50">Lee's<br>Kitchen</div>
           </div>

           <blockquote class="text-xl md:text-2xl font-medium leading-relaxed mb-8">
             "Maple keeps the phones moving and the kitchen calm. It's like adding a second front desk that never gets tired."
           </blockquote>

           <div class="mb-8">
             <div class="text-sm font-medium opacity-80">Owner - Yummy's Korean BBQ</div>
           </div>

           <div class="bg-white/10 backdrop-blur-sm rounded-lg p-4 flex items-center gap-4">
              <div class="bg-white/20 p-2 rounded-full">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 20V10"/><path d="M18 20V4"/><path d="M6 20v-4"/></svg>
              </div>
              <div>
                <div class="text-sm opacity-80">Annual Staffing Savings</div>
                <div class="font-medium">Saved $18,000 annually by automating phone coverage.</div>
              </div>
           </div>

           <!-- Navigation Buttons -->
           <div class="flex gap-2 mt-8">
              <button class="p-2 border border-white/30 rounded hover:bg-white/10 transition-colors">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M19 12H5"/><path d="M12 19l-7-7 7-7"/></svg>
              </button>
              <button class="p-2 border border-white/30 rounded hover:bg-white/10 transition-colors">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
              </button>
           </div>
        </div>

        <!-- Image -->
        <div class="md:w-1/2 bg-gray-800 relative min-h-[400px]">
            <!-- Placeholder for restaurant interior -->
            <div class="absolute inset-0 bg-gray-700 flex items-center justify-center text-gray-500">
                <svg width="64" height="64" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"/><circle cx="8.5" cy="8.5" r="1.5"/><polyline points="21 15 16 10 5 21"/></svg>
            </div>
            <img src="https://images.unsplash.com/photo-1552566626-52f8b828add9?q=80&w=2070&auto=format&fit=crop" alt="Restaurant Interior" class="absolute inset-0 w-full h-full object-cover opacity-80 mix-blend-overlay" />
        </div>
      </div>

      <!-- Peek Next Card -->
      <div class="absolute top-8 bottom-8 -right-4 md:-right-12 w-24 bg-white rounded-r-2xl shadow-lg z-0 hidden md:flex items-center justify-center">
          <!-- Content of next card peeking -->
      </div>
    </div>
  </div>
</section>
