<script lang="ts">
  let openIndex: number | null = null;

  const faqs = [
    { question: "What is Maple and how does it help my restaurant?", answer: "Maple is an AI-powered voice assistant that handles inbound phone calls for restaurants. It takes orders, answers questions, and manages reservations, freeing up your staff to focus on in-person guests." },
    { question: "How quickly can we set up the restaurant AI phone system?", answer: "Setup typically takes less than 30 minutes. We integrate directly with your existing POS and phone system." },
    { question: "Does Maple work with my current POS system?", answer: "Yes, Maple integrates with all major POS systems including Toast, Square, Clover, and many others." },
    { question: "Can Maple manage both reservations and takeout orders?", answer: "Absolutely. Maple can handle complex takeout orders with modifications and also book, modify, or cancel reservations directly into your reservation system." }
  ];

  function toggle(index: number) {
    openIndex = openIndex === index ? null : index;
  }
</script>

<section class="py-20 bg-[#f5f5f0]">
  <div class="container-custom mx-auto max-w-3xl">
    <h2 class="text-3xl font-semibold text-center mb-12 text-gray-900">Questions we can answer</h2>

    <div class="space-y-4">
      {#each faqs as faq, i}
        <div class="border-b border-gray-200 pb-4">
          <button 
            class="w-full flex justify-between items-center text-left py-4 focus:outline-none group"
            on:click={() => toggle(i)}
          >
            <span class="text-lg font-medium text-gray-800 group-hover:text-brand transition-colors">{faq.question}</span>
            <svg 
                class="w-5 h-5 text-gray-500 transform transition-transform duration-200 {openIndex === i ? 'rotate-180' : ''}" 
                viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
            >
                <polyline points="6 9 12 15 18 9"></polyline>
            </svg>
          </button>
          {#if openIndex === i}
            <div class="pb-4 text-gray-600 leading-relaxed">
              {faq.answer}
            </div>
          {/if}
        </div>
      {/each}
    </div>
  </div>
</section>
