<script lang="ts">
  // No external dependencies
</script>

<section class="py-24 bg-brand text-white relative overflow-hidden">
  <!-- Background Tech Visuals -->
  <div class="absolute inset-0 opacity-10">
      <svg width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
          <defs>
              <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
                  <path d="M 40 0 L 0 0 0 40" fill="none" stroke="white" stroke-width="0.5"/>
              </pattern>
          </defs>
          <rect width="100%" height="100%" fill="url(#grid)" />
          <circle cx="80%" cy="50%" r="300" stroke="white" stroke-width="1" fill="none" opacity="0.5" />
          <circle cx="80%" cy="50%" r="200" stroke="white" stroke-width="1" fill="none" opacity="0.5" />
          <circle cx="80%" cy="50%" r="100" stroke="white" stroke-width="1" fill="none" opacity="0.5" />
      </svg>
  </div>

  <div class="container-custom mx-auto relative z-10 text-center">
    <h2 class="text-4xl md:text-5xl font-semibold mb-16">
      Behind the Voice.<br/>How Maple Works.
    </h2>

    <div class="max-w-3xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8 text-left mb-12">
        <div class="flex gap-4">
            <div class="flex-shrink-0 w-6 h-6 rounded-full bg-white/20 flex items-center justify-center mt-1">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
            </div>
            <div>
                <h3 class="font-bold text-lg mb-1">Listens & Understands</h3>
                <p class="text-blue-100 text-sm">From modifications to allergy notes</p>
            </div>
        </div>

        <div class="flex gap-4">
            <div class="flex-shrink-0 w-6 h-6 rounded-full bg-white/20 flex items-center justify-center mt-1">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
            </div>
            <div>
                <h3 class="font-bold text-lg mb-1">Upsells Intelligently</h3>
                <p class="text-blue-100 text-sm">Increases ticket sizes by 25%</p>
            </div>
        </div>

        <div class="flex gap-4">
            <div class="flex-shrink-0 w-6 h-6 rounded-full bg-white/20 flex items-center justify-center mt-1">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
            </div>
            <div>
                <h3 class="font-bold text-lg mb-1">Sends Orders Instantly</h3>
                <p class="text-blue-100 text-sm">Real-time POS integration</p>
            </div>
        </div>

        <div class="flex gap-4">
            <div class="flex-shrink-0 w-6 h-6 rounded-full bg-white/20 flex items-center justify-center mt-1">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
            </div>
            <div>
                <h3 class="font-bold text-lg mb-1">Speaks Every Language</h3>
                <p class="text-blue-100 text-sm">Handles any accent or dialect your customers use</p>
            </div>
        </div>
    </div>

    <div class="flex justify-center">
        <button class="bg-white text-brand px-6 py-3 rounded-lg font-medium flex items-center gap-2 hover:bg-gray-100 transition-colors">
            Get Free Demo
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
        </button>
    </div>
  </div>
</section>
