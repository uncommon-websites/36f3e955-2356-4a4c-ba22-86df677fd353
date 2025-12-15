<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                How Fulfilled Works<br />For You
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Define Your Goals -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-primary-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Your Financial Goals</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between text-xs">
                                <span class="text-gray-600">🏠 Home Down Payment</span>
                                <span class="text-gray-900 font-medium">$150K in 5 yrs</span>
                            </div>
                            <div class="flex items-center justify-between text-xs">
                                <span class="text-gray-600">🎓 Kids Education</span>
                                <span class="text-gray-900 font-medium">$200K in 15 yrs</span>
                            </div>
                            <div class="flex items-center justify-between text-xs">
                                <span class="text-gray-600">🏖️ Retirement</span>
                                <span class="text-gray-900 font-medium">$2M in 30 yrs</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Define Your Goals</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Tell us what you're investing for—whether it's a home, education, retirement, or multiple goals. We'll create custom portfolios optimized for each timeline and risk tolerance.
                </p>
            </div>

            <!-- Card 2: Institutional-Grade Allocation -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Your Portfolio Allocation</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-700 rounded flex items-center justify-center text-white text-[8px]">50+</div>
                            <span class="text-[10px] text-gray-400">Global Asset Classes</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Asset Class</div>
                                <div class="col-span-2 text-right">Allocation</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-blue-500 rounded-sm"></div> US Equities</div>
                                <div class="col-span-2 h-1.5 bg-blue-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-green-500 rounded-sm"></div> Int'l Equities</div>
                                <div class="col-span-2 h-1.5 bg-green-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-purple-500 rounded-sm"></div> Fixed Income</div>
                                <div class="col-span-2 h-1.5 bg-purple-100 rounded w-1/2 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-orange-500 rounded-sm"></div> Alternatives</div>
                                <div class="col-span-2 h-1.5 bg-orange-100 rounded w-1/3 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Institutional-Grade Allocation</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Access sophisticated asset allocation strategies across 50+ global asset classes. Get the same diversification and risk management that institutions use to protect and grow wealth.
                </p>
            </div>

            <!-- Card 3: Guidance Without Transfers -->
            <div class="group">
                <div class="mb-6 bg-primary-950 rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-600 rounded flex items-center justify-center text-white text-[8px]">✓</div>
                            <span class="text-[10px] text-gray-500">Connected Accounts</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            We'll guide you on what to do with your existing accounts—no transfers required.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-green-600 rounded-sm flex items-center justify-center text-white text-[6px]">✓</div>
                                    <span class="text-[9px] font-medium">Vanguard 401(k)</span>
                                </div>
                                <span class="text-[8px] text-gray-400">$125K</span>
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-green-600 rounded-sm flex items-center justify-center text-white text-[6px]">✓</div>
                                    <span class="text-[9px] font-medium">Fidelity Brokerage</span>
                                </div>
                                <span class="text-[8px] text-gray-400">$85K</span>
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-green-600 rounded-sm flex items-center justify-center text-white text-[6px]">✓</div>
                                    <span class="text-[9px] font-medium">Schwab IRA</span>
                                </div>
                                <span class="text-[8px] text-gray-400">$42K</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Guidance Without Transfers</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Keep your money where it is. We provide expert guidance on how to optimize your existing accounts across all your brokerages, eliminating the hassle and risk of transferring assets.
                </p>
            </div>
        </div>
    </div>
</section>
