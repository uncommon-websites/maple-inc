<script lang="ts">
  let missedCalls = 10;
  let ticketSize = 30;
  
  $: monthlyRevenue = missedCalls * ticketSize * 30;
</script>

<section class="py-20 bg-gray-50">
  <div class="container-custom mx-auto">
    <div class="flex flex-col lg:flex-row items-center gap-16">
      
      <!-- Left Content -->
      <div class="lg:w-1/2">
        <h2 class="text-4xl font-semibold text-gray-900 mb-6 leading-tight">
          Never Miss Revenue with<br/>Always-On AI Call<br/>Handling
        </h2>
        <p class="text-lg text-gray-600 mb-8 leading-relaxed">
          Capture late-night orders, early morning catering requests, and holiday bookings automatically. Our AI phone system works when you're closed, ensuring no profitable call goes unanswered.
        </p>

        <button class="bg-brand hover:bg-brand-dark text-white px-6 py-3 rounded-lg font-medium flex items-center gap-2 transition-colors mb-12">
            Get Free Demo
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="bg-white/20 rounded-sm p-[1px]"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
        </button>

        <!-- ROI Calculator -->
        <div class="bg-white p-8 rounded-2xl shadow-lg border border-gray-100 max-w-md">
            <div class="flex items-center gap-2 mb-6 text-gray-900 font-semibold">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="7" width="20" height="14" rx="2" ry="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg>
                ROI Calculator
            </div>

            <div class="space-y-6">
                <div>
                    <div class="flex justify-between text-sm font-medium mb-2">
                        <label for="missed-calls">Missed calls per day: {missedCalls}</label>
                    </div>
                    <input id="missed-calls" type="range" min="1" max="50" bind:value={missedCalls} class="w-full h-2 bg-gray-200 rounded-lg appearance-none cursor-pointer accent-brand">
                </div>

                <div>
                    <div class="flex justify-between text-sm font-medium mb-2">
                        <label for="ticket-size">Average ticket size: ${ticketSize}</label>
                    </div>
                    <input id="ticket-size" type="range" min="10" max="200" step="5" bind:value={ticketSize} class="w-full h-2 bg-gray-200 rounded-lg appearance-none cursor-pointer accent-brand">
                </div>

                <div class="pt-4 border-t border-gray-100">
                    <div class="text-sm text-gray-500 mb-1">Estimated Monthly Lost Revenue:</div>
                    <div class="text-3xl font-bold text-gray-900">${monthlyRevenue.toLocaleString()}</div>
                </div>
            </div>
        </div>
      </div>

      <!-- Right Content: Mockup -->
      <div class="lg:w-1/2 w-full relative">
         <div class="bg-blue-100 rounded-2xl p-4 md:p-8 relative overflow-hidden min-h-[500px] flex items-center justify-center">
            <!-- Background Texture -->
            <div class="absolute inset-0 opacity-20 mix-blend-multiply" style="background-image: url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5?q=80&w=1974&auto=format&fit=crop'); background-size: cover;"></div>
            
            <!-- Phone UI -->
            <div class="bg-white rounded-3xl shadow-2xl w-full max-w-xs overflow-hidden relative z-10 border-8 border-gray-900">
                <!-- Header -->
                <div class="bg-gray-50 p-4 border-b border-gray-100 flex items-center justify-between">
                    <div class="flex items-center gap-2">
                        <div class="w-2 h-2 bg-green-500 rounded-full"></div>
                        <span class="text-xs font-medium text-gray-500">On Call</span>
                    </div>
                    <div class="w-8 h-1 bg-gray-300 rounded-full"></div>
                </div>

                <!-- Chat/Call Content -->
                <div class="p-4 space-y-4 bg-white h-96 flex flex-col">
                    <div class="flex justify-center my-2">
                        <span class="text-[10px] text-gray-400 uppercase tracking-wide">Today 9:41 AM</span>
                    </div>

                    <!-- AI Message -->
                    <div class="flex items-end gap-2">
                        <div class="w-8 h-8 bg-brand rounded-full flex items-center justify-center text-white text-xs font-bold">M</div>
                        <div class="bg-gray-100 p-3 rounded-2xl rounded-bl-none text-xs text-gray-700 max-w-[80%]">
                            Hi, thanks for calling Maple Burger. How can I help you today?
                        </div>
                    </div>

                    <!-- User Message -->
                    <div class="flex items-end gap-2 flex-row-reverse">
                        <div class="w-8 h-8 bg-gray-200 rounded-full flex items-center justify-center text-gray-600 text-xs font-bold">U</div>
                        <div class="bg-brand text-white p-3 rounded-2xl rounded-br-none text-xs max-w-[80%]">
                            I'd like to order a cheeseburger with no pickles and a large fries.
                        </div>
                    </div>

                    <!-- AI Processing -->
                    <div class="flex items-end gap-2">
                        <div class="w-8 h-8 bg-brand rounded-full flex items-center justify-center text-white text-xs font-bold">M</div>
                        <div class="bg-gray-100 p-3 rounded-2xl rounded-bl-none text-xs text-gray-700 max-w-[80%]">
                            <div class="flex gap-1">
                                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full animate-bounce"></span>
                                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full animate-bounce delay-100"></span>
                                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full animate-bounce delay-200"></span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Call Controls -->
                <div class="bg-gray-50 p-4 border-t border-gray-100 flex justify-around">
                    <div class="w-10 h-10 bg-white rounded-full shadow flex items-center justify-center text-gray-600">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M19 11a7 7 0 0 1-7 7m0 0a7 7 0 0 1-7-7m7 7v4m0 0H8m4 0h4"/></svg>
                    </div>
                    <div class="w-10 h-10 bg-red-500 rounded-full shadow flex items-center justify-center text-white">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M10.68 13.31a16 16 0 0 0 3.41 2.6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7 2 2 0 0 1 1.72 2v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.42 19.42 0 0 1-3.33-2.67m-2.67-3.34a19.79 19.79 0 0 1-3.07-8.63A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91"/></svg>
                    </div>
                </div>
            </div>
         </div>
      </div>

    </div>
  </div>
</section>
