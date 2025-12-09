<script lang="ts">
  // No external dependencies
</script>

<section class="py-20 bg-gray-50">
  <div class="container-custom mx-auto">
    <div class="flex flex-col lg:flex-row items-center gap-16">
      
      <!-- Left Content -->
      <div class="lg:w-1/2">
        <h2 class="text-4xl font-semibold text-gray-900 mb-6 leading-tight">
          Capture Every Order<br/>with 99% Accuracy
        </h2>
        <p class="text-lg text-gray-600 mb-8 leading-relaxed">
          Maple handles complex orders, allergy requests, and custom combos — just like your best employee. With direct POS integration, every detail flows straight to your kitchen, error-free.
        </p>

        <ul class="space-y-4 mb-10">
          {#each [
            "Complex order handling (modifications, combos, allergies)",
            "Automatic upselling increases ticket size 25%",
            "Real-time POS integration",
            "Multi-language support for diverse customers"
          ] as item}
            <li class="flex items-start gap-3">
              <div class="mt-1 flex-shrink-0 w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center text-brand">
                <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"></polyline></svg>
              </div>
              <span class="text-gray-700">{item}</span>
            </li>
          {/each}
        </ul>

        <div class="flex items-center gap-6">
          <button class="bg-brand hover:bg-brand-dark text-white px-6 py-3 rounded-lg font-medium flex items-center gap-2 transition-colors">
            Get Free Demo
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="bg-white/20 rounded-sm p-[1px]"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
          </button>
          <a href="#" class="text-gray-600 font-medium hover:text-gray-900">Contact Us</a>
        </div>
      </div>

      <!-- Right Content: Mockup -->
      <div class="lg:w-1/2 w-full">
        <div class="bg-brand rounded-2xl p-8 relative overflow-hidden shadow-xl">
            <!-- Background Pattern -->
            <div class="absolute inset-0 opacity-10" style="background-image: radial-gradient(circle at 2px 2px, white 1px, transparent 0); background-size: 24px 24px;"></div>
            
            <!-- Phone/Interface Mockup -->
            <div class="relative z-10 space-y-4 max-w-sm mx-auto">
                
                <!-- Notification 1 -->
                <div class="bg-white rounded-xl p-4 shadow-lg transform translate-x-4 opacity-90 scale-95">
                    <div class="flex justify-between items-start mb-2">
                        <div class="flex items-center gap-2">
                            <div class="w-8 h-8 bg-gray-200 rounded-full flex items-center justify-center text-xs font-bold text-gray-600">JL</div>
                            <div>
                                <div class="font-bold text-sm text-gray-900">Jack Lee</div>
                                <div class="text-xs text-gray-500">Order # 2189</div>
                            </div>
                        </div>
                        <span class="text-xs text-brand font-medium bg-blue-50 px-2 py-0.5 rounded-full">• 1 min ago</span>
                    </div>
                    <div class="space-y-1 text-xs text-gray-600 border-t border-gray-100 pt-2">
                        <div class="flex justify-between"><span>Order Qty:</span> <span>6 items</span></div>
                        <div class="flex justify-between"><span>Payment:</span> <span>Paying in store</span></div>
                        <div class="flex justify-between font-medium text-gray-900"><span>Total:</span> <span>$36.00</span></div>
                    </div>
                </div>

                <!-- Notification 2 -->
                <div class="bg-white rounded-xl p-4 shadow-lg transform translate-x-2 opacity-95 scale-98">
                    <div class="flex justify-between items-start mb-2">
                        <div class="flex items-center gap-2">
                            <div class="w-8 h-8 bg-gray-200 rounded-full flex items-center justify-center text-xs font-bold text-gray-600">AK</div>
                            <div>
                                <div class="font-bold text-sm text-gray-900">Alex Kho</div>
                                <div class="text-xs text-gray-500">Order # 2188</div>
                            </div>
                        </div>
                        <span class="text-xs text-brand font-medium bg-blue-50 px-2 py-0.5 rounded-full">• 2 mins ago</span>
                    </div>
                    <div class="space-y-1 text-xs text-gray-600 border-t border-gray-100 pt-2">
                        <div class="flex justify-between"><span>Order Qty:</span> <span>3 items</span></div>
                        <div class="flex justify-between"><span>Payment:</span> <span>Paying in store</span></div>
                        <div class="flex justify-between font-medium text-gray-900"><span>Total:</span> <span>$17.49</span></div>
                    </div>
                </div>

                <!-- Notification 3 (Main) -->
                <div class="bg-white rounded-xl p-4 shadow-xl ring-4 ring-blue-400/30">
                    <div class="flex justify-between items-start mb-2">
                        <div class="flex items-center gap-2">
                            <div class="w-8 h-8 bg-gray-200 rounded-full flex items-center justify-center text-xs font-bold text-gray-600">AS</div>
                            <div>
                                <div class="font-bold text-sm text-gray-900">Ayush Soni</div>
                                <div class="text-xs text-gray-500">Order # 2187</div>
                            </div>
                        </div>
                        <span class="text-xs text-green-600 font-medium bg-green-50 px-2 py-0.5 rounded-full flex items-center gap-1">
                            <span class="w-1.5 h-1.5 bg-green-500 rounded-full"></span> Captured Order
                        </span>
                    </div>
                    <div class="space-y-1 text-xs text-gray-600 border-t border-gray-100 pt-2">
                        <div class="flex justify-between"><span>Order Qty:</span> <span>10 items</span></div>
                        <div class="flex justify-between"><span>Payment:</span> <span>Paying in store</span></div>
                        <div class="flex justify-between font-medium text-gray-900"><span>Total:</span> <span>$105.99</span></div>
                    </div>
                </div>

            </div>
        </div>
      </div>

    </div>
  </div>
</section>
