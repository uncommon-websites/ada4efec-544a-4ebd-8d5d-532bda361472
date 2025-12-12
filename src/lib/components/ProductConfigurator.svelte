<script lang="ts">
  let selectedPlan = 'premium';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Three plans. <span class="text-gray-400">One perfect pairing system.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Premium Collector</h3>
      <p class="text-gray-500 text-sm">For serious wine enthusiasts with extensive cellars.</p>
    </div>

    <!-- App Preview -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-wine-collector-examining-a-wine-bottle-l-1765524748725-1.webp" class="h-[90%] object-cover rounded-lg" alt="PairsWell App" />
    </div>

    <!-- Plan Options -->
    <div class="flex justify-center gap-4 mb-8">
      <button class="px-4 py-2 rounded-full bg-primary-100 border-2 border-primary-500 text-primary-900 text-sm font-medium">Premium</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-sm font-medium hover:bg-gray-200">Standard</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-600 text-sm font-medium hover:bg-gray-200">Starter</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>Unlimited pairings</span>
      <span>AI analysis</span>
      <span>Taste learning</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Starting at <span class="font-bold text-gray-900">$29/month</span> or $290/year.<br>
      14-day free trial available. ⓘ
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Compare all plans</span>
        <span class="text-primary-600">See pricing details</span>
      </button>
      <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M8 2h8l4 10H4L8 2z"/><path d="M12 12v10"/><path d="M8 22h8"/></svg>
        Start free trial ->
      </button>
    </div>
  </div>
</section>
