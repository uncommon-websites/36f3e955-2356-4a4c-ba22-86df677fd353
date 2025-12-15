<script>
    import { FileText, Database, Settings, Search } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-20">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight max-w-4xl">
                Institutional investing was once reserved for the ultra-wealthy. <span class="font-semibold">Fulfilled brings that same sophistication to everyone.</span>
            </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <!-- Left: Image/Interface -->
            <div class="relative">
                <div class="relative rounded-lg overflow-hidden shadow-2xl bg-gray-900 aspect-[4/3]">
                    <img 
                        src="/generated/image-diverse-group-of-professionals-collabora-1765820788075-2.webp" 
                        alt="Professionals planning finances together" 
                        class="absolute inset-0 w-full h-full object-cover opacity-50"
                    />
                    
                    <!-- Floating Interface Element -->
                    <div class="absolute inset-0 flex items-center justify-center p-8">
                        <div class="bg-white rounded-lg shadow-xl w-full max-w-md p-6">
                            <div class="flex items-center gap-3 mb-4">
                                <div class="h-8 w-8 bg-primary-600 rounded flex items-center justify-center text-white">
                                    <Database size={16} />
                                </div>
                                <span class="font-medium text-gray-900">Your Financial Goals</span>
                            </div>
                            <div class="space-y-3">
                                <div class="flex items-center justify-between">
                                    <div class="h-2 bg-primary-100 rounded w-2/3"></div>
                                    <span class="text-xs text-gray-500">$150K</span>
                                </div>
                                <div class="flex items-center justify-between">
                                    <div class="h-2 bg-blue-100 rounded w-1/2"></div>
                                    <span class="text-xs text-gray-500">$200K</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Right: Features List -->
            <div class="space-y-12">
                <h3 class="text-2xl font-serif text-gray-900">
                    A Personalized Approach <br/> Built Around Your Goals
                </h3>

                <div class="space-y-8">
                    {#each [
                        { id: '01', title: 'Goal-based portfolio design', icon: Database },
                        { id: '02', title: 'Institutional-grade allocation', icon: Search },
                        { id: '03', title: 'Keep your existing accounts', icon: Settings },
                        { id: '04', title: 'Ongoing guidance & rebalancing', icon: FileText }
                    ] as feature}
                        <div class="flex items-start gap-4 group cursor-pointer">
                            <div class="flex-shrink-0 relative">
                                <div class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center text-xs font-mono text-gray-500 group-hover:border-black group-hover:text-black transition-colors bg-white z-10 relative">
                                    {feature.id}
                                </div>
                                {#if feature.id !== '04'}
                                    <div class="absolute top-10 left-1/2 -translate-x-1/2 w-px h-8 bg-gray-100 -z-0"></div>
                                {/if}
                            </div>
                            <div class="pt-2">
                                <h4 class="text-lg text-gray-600 group-hover:text-gray-900 transition-colors font-light">
                                    {feature.title}
                                </h4>
                            </div>
                        </div>
                    {/each}
                </div>
            </div>
        </div>
    </div>
</section>
