<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Everything You Need to<br />Achieve Your Goals
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Goal-Based Planning -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Goal-Based Planning</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="space-y-3 w-full max-w-[200px]">
                        {#each [{icon: "🏠", color: "bg-primary-500"}, {icon: "🎓", color: "bg-blue-500"}, {icon: "🏖️", color: "bg-purple-500"}] as goal}
                            <div class="flex items-center gap-3 bg-white p-3 rounded shadow-sm">
                                <div class="h-8 w-8 {goal.color} rounded-full flex items-center justify-center text-sm">
                                    {goal.icon}
                                </div>
                                <div class="flex-1">
                                    <div class="h-1.5 bg-gray-100 rounded w-3/4 mb-1"></div>
                                    <div class="h-1 bg-gray-50 rounded w-1/2"></div>
                                </div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Create separate portfolios for each of your financial goals with custom timelines, risk profiles, and investment strategies tailored to what matters most.
                </p>
            </div>

            <!-- 50+ Asset Classes -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">50+ Asset Classes</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="text-[10px] font-medium text-gray-500 mb-3">DIVERSIFIED ALLOCATION</div>
                        {#each [{name: "US Stocks", width: "w-full", color: "bg-blue-500"}, {name: "Int'l Stocks", width: "w-4/5", color: "bg-green-500"}, {name: "Bonds", width: "w-3/5", color: "bg-purple-500"}, {name: "Real Estate", width: "w-2/5", color: "bg-orange-500"}, {name: "Commodities", width: "w-1/4", color: "bg-yellow-500"}] as asset}
                            <div class="flex items-center gap-2">
                                <div class="h-1.5 {asset.color} rounded {asset.width}"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Access institutional-grade diversification across global equities, fixed income, real estate, commodities, and alternative investments—all optimized for your goals.
                </p>
            </div>

            <!-- Expert Guidance -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Expert Guidance</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded-lg shadow-sm w-full max-w-[180px]">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-primary-500 flex items-center justify-center text-primary-700 text-xs font-bold">CF</div>
                            <div class="flex-1">
                                <div class="h-1.5 bg-gray-100 rounded w-full mb-1"></div>
                                <div class="h-1 bg-gray-50 rounded w-2/3"></div>
                            </div>
                        </div>
                        <div class="text-[8px] text-gray-400 leading-relaxed">
                            "Based on your timeline, I recommend increasing your equity allocation..."
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Get personalized advice from financial experts who understand your goals. We're here to answer questions and guide you every step of the way.
                </p>
            </div>

            <!-- Automatic Rebalancing -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Rebalancing Alerts</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-6 w-6 bg-yellow-100 rounded-full flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-yellow-600"><path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3Z"/><path d="M12 9v4"/><path d="M12 17h.01"/></svg>
                            </div>
                            <span class="text-[10px] font-medium text-gray-700">Rebalance Needed</span>
                        </div>
                        <div class="text-[8px] text-gray-500 leading-relaxed mb-2">
                            Your portfolio has drifted 8% from target allocation.
                        </div>
                        <button class="w-full bg-primary-500 text-white text-[9px] py-1.5 rounded font-medium">
                            View Recommendations
                        </button>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Stay on track with intelligent monitoring and rebalancing recommendations. We'll alert you when your portfolio drifts from its target allocation.
                </p>
            </div>

            <!-- Performance Tracking -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Performance Tracking</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div>
                                <div class="text-[10px] text-gray-500">Total Return</div>
                                <div class="text-lg font-bold text-green-600">+12.4%</div>
                            </div>
                            <div class="text-right">
                                <div class="text-[10px] text-gray-500">vs. Target</div>
                                <div class="text-lg font-bold text-primary-600">+2.1%</div>
                            </div>
                        </div>
                        <div class="space-y-1">
                            <div class="flex items-center gap-2">
                                <div class="h-1 bg-green-200 rounded w-full relative overflow-hidden">
                                    <div class="absolute inset-0 bg-green-500 rounded" style="width: 75%"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Monitor your progress toward each goal with clear, comprehensive performance metrics. See how your portfolios are performing and stay on track to achieve your objectives.
                </p>
            </div>

            <!-- Tax Optimization -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Tax Optimization</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="text-[10px] text-gray-500 mb-3">TAX-EFFICIENT PLACEMENT</div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between text-[9px]">
                                <span class="text-gray-600">401(k)</span>
                                <span class="text-gray-900 font-medium">Bonds</span>
                            </div>
                            <div class="flex items-center justify-between text-[9px]">
                                <span class="text-gray-600">Roth IRA</span>
                                <span class="text-gray-900 font-medium">Growth Stocks</span>
                            </div>
                            <div class="flex items-center justify-between text-[9px]">
                                <span class="text-gray-600">Taxable</span>
                                <span class="text-gray-900 font-medium">Index Funds</span>
                            </div>
                        </div>
                        <div class="mt-3 pt-3 border-t border-gray-100">
                            <div class="flex items-center gap-1 text-[8px] text-green-600">
                                <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                                <span>Est. $2,400/yr tax savings</span>
                            </div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Maximize after-tax returns with intelligent asset location strategies. We help you place investments in the right account types to minimize your tax burden.
                </p>
            </div>
        </div>
    </div>
</section>
