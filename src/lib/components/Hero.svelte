<script>
  // No imports needed as we use inline SVGs for specific styling control
</script>

<section class="relative flex flex-col items-center justify-start pt-20 pb-32 overflow-hidden">
  <!-- Content -->
  <div class="z-10 mx-auto max-w-4xl px-4 text-center mb-16">
    <h1 class="mb-6 text-5xl md:text-6xl lg:text-7xl font-serif text-gray-900 leading-tight">
      Achieve Every Financial Goal
    </h1>
    <p class="mx-auto mb-10 max-w-2xl text-lg text-gray-600 leading-relaxed">
      Institutional-grade investment portfolios tailored to your unique goals. Get expert guidance across 50+ global asset classes without moving your existing accounts.
    </p>
    
    <div class="flex justify-center">
        <div class="relative group">
            <button class="relative rounded-full bg-black px-8 py-3 text-base font-medium text-white hover:bg-gray-800 transition-all">
                Start Building Your Portfolio
            </button>
            <!-- Decorative corners -->
            <div class="absolute -top-2 -left-2 h-4 w-4 border-t-2 border-l-2 border-black"></div>
            <div class="absolute -bottom-2 -right-2 h-4 w-4 border-b-2 border-r-2 border-black"></div>
        </div>
    </div>
  </div>

  <!-- Hero Image & Goal Selection Interface -->
  <div class="relative w-full max-w-7xl mx-auto px-4">
    <div class="relative aspect-[21/9] w-full overflow-hidden rounded-lg shadow-2xl">
      <img 
        src="https://images.unsplash.com/photo-1554224311-beee460c201f?q=80&w=2070&auto=format&fit=crop" 
        alt="Professional planning finances" 
        class="h-full w-full object-cover"
      />
      
      <!-- Overlay Goal Selection -->
      <div class="absolute inset-0 flex items-center justify-center bg-black/20">
        <div class="w-full max-w-2xl rounded-xl bg-white p-6 shadow-2xl animate-fade-in-up">
            <div class="mb-4">
                <h3 class="text-sm font-medium text-gray-900 mb-3">What are you investing for?</h3>
                <div class="grid grid-cols-2 gap-3">
                    <div class="flex items-center gap-3 p-3 bg-primary-50 border-2 border-primary-500 rounded-lg">
                        <div class="h-10 w-10 rounded-full bg-primary-500 flex items-center justify-center text-white">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m3 9 9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
                        </div>
                        <span class="text-sm font-medium text-gray-900">Home Purchase</span>
                    </div>
                    <div class="flex items-center gap-3 p-3 bg-gray-50 border border-gray-200 rounded-lg hover:bg-gray-100 transition-colors cursor-pointer">
                        <div class="h-10 w-10 rounded-full bg-gray-200 flex items-center justify-center text-gray-600">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect width="20" height="14" x="2" y="7" rx="2" ry="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg>
                        </div>
                        <span class="text-sm font-medium text-gray-600">Retirement</span>
                    </div>
                    <div class="flex items-center gap-3 p-3 bg-gray-50 border border-gray-200 rounded-lg hover:bg-gray-100 transition-colors cursor-pointer">
                        <div class="h-10 w-10 rounded-full bg-gray-200 flex items-center justify-center text-gray-600">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 10v6M2 10l10-5 10 5-10 5z"/><path d="M6 12v5c3 3 9 3 12 0v-5"/></svg>
                        </div>
                        <span class="text-sm font-medium text-gray-600">Education</span>
                    </div>
                    <div class="flex items-center gap-3 p-3 bg-gray-50 border border-gray-200 rounded-lg hover:bg-gray-100 transition-colors cursor-pointer">
                        <div class="h-10 w-10 rounded-full bg-gray-200 flex items-center justify-center text-gray-600">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4"/><path d="M12 8h.01"/></svg>
                        </div>
                        <span class="text-sm font-medium text-gray-600">Other Goals</span>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
    .animate-fade-in-up {
        animation: fadeInUp 0.8s ease-out forwards;
    }
    @keyframes fadeInUp {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
