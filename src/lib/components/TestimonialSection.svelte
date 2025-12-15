<script>
    import { ArrowLeft, ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-[#F9F7F2] py-24 overflow-hidden">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <!-- Navigation Buttons -->
        <div class="flex justify-end gap-2 mb-8">
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowLeft size={16} />
            </button>
            <button class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center bg-white hover:bg-gray-50 transition-colors text-gray-400 hover:text-gray-900">
                <ArrowRight size={16} />
            </button>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <!-- Quote Content -->
            <div class="pr-8">
                <div class="mb-8">
                    <span class="text-sm font-bold tracking-widest uppercase">MILLENNIAL PROFESSIONAL</span>
                </div>
                <blockquote class="text-2xl md:text-3xl font-light text-gray-900 leading-relaxed mb-12">
                    "I always knew I should be investing differently for my home down payment versus retirement, but every advisor wanted me to consolidate everything. Fulfilled gave me custom portfolios for each goal without the hassle of moving my accounts. It's like having a personal CIO."
                </blockquote>
                <div>
                    <div class="font-medium text-gray-900">Sarah Chen</div>
                    <div class="text-[10px] uppercase tracking-widest text-gray-500 mt-1">Product Manager, San Francisco</div>
                </div>
            </div>

            <!-- Image -->
            <div class="relative h-[600px] w-full overflow-hidden rounded-lg">
                <img 
                    src="/generated/image-happy-millennial-professional-in-casual--1765820785233-1.webp" 
                    alt="Happy professional investor" 
                    class="absolute inset-0 h-full w-full object-cover"
                />
            </div>
        </div>
    </div>
</section>
