<script lang="ts">
  // No external dependencies
</script>

<nav class="bg-white border-b border-gray-100 sticky top-0 z-50">
  <div class="container-custom mx-auto">
    <div class="flex justify-between items-center h-16">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center gap-2 cursor-pointer">
        <!-- Maple Leaf Logo Approximation -->
        <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor" class="text-brand w-7 h-7" xmlns="http://www.w3.org/2000/svg">
            <path d="M11.0001 21.0001L12.0001 23.0001L13.0001 21.0001C13.0001 21.0001 18.0001 19.5001 19.5001 15.0001C21.0001 10.5001 18.0001 6.0001 18.0001 6.0001C18.0001 6.0001 16.0001 6.5001 14.5001 8.0001C14.5001 8.0001 15.0001 4.0001 12.0001 2.0001C9.0001 4.0001 9.5001 8.0001 9.5001 8.0001C8.0001 6.5001 6.0001 6.0001 6.0001 6.0001C6.0001 6.0001 3.0001 10.5001 4.5001 15.0001C6.0001 19.5001 11.0001 21.0001 11.0001 21.0001Z" fill="currentColor"/>
        </svg>
        <span class="text-xl font-bold text-gray-900 tracking-tight">Maple</span>
      </div>

      <!-- Desktop Menu -->
      <div class="hidden md:flex items-center space-x-8">
        <div class="relative group">
          <button class="text-gray-600 hover:text-gray-900 font-medium text-sm flex items-center gap-1">
            Product 
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
          </button>
        </div>
        <div class="relative group">
          <button class="text-gray-600 hover:text-gray-900 font-medium text-sm flex items-center gap-1">
            Resources 
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
          </button>
        </div>
        <div class="relative group">
          <button class="text-gray-600 hover:text-gray-900 font-medium text-sm flex items-center gap-1">
            Company 
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
          </button>
        </div>
        <a href="#" class="text-gray-600 hover:text-gray-900 font-medium text-sm">Pricing</a>
      </div>

      <!-- Right Side -->
      <div class="flex items-center gap-4">
        <a href="#" class="text-gray-600 hover:text-gray-900 font-medium text-sm hidden sm:block">Login</a>
        <a href="#" class="bg-brand hover:bg-brand-dark text-white px-4 py-2 rounded text-sm font-medium transition-colors flex items-center gap-1">
          Get Free Demo
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="bg-white/20 rounded-sm p-[1px]"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
        </a>
      </div>
    </div>
  </div>
</nav>
