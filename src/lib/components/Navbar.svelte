<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="text-2xl font-medium tracking-tight">PairsWell</a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#" class="hover:text-white transition-colors">Features</a>
      <a href="#" class="hover:text-white transition-colors">How it works</a>
      <a href="#" class="hover:text-white transition-colors">Pricing</a>
      <a href="#" class="hover:text-white transition-colors">About</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <a href="#" class="text-gray-300 hover:text-white transition-colors text-[13px] font-medium">
      Sign in
    </a>
    <a href="#" class="bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Try PairsWell
    </a>
  </div>
</nav>
