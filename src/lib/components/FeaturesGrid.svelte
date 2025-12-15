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

            <!-- Guided Implementation -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Guided Implementation</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="flex -space-x-2">
                        <div class="h-10 w-10 rounded-full bg-blue-100 border-2 border-white flex items-center justify-center text-blue-600 text-xs">A</div>
                        <div class="h-10 w-10 rounded-full bg-green-100 border-2 border-white flex items-center justify-center text-green-600 text-xs">B</div>
                        <div class="h-10 w-10 rounded-full bg-purple-100 border-2 border-white flex items-center justify-center text-purple-600 text-xs">C</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    White-glove engagement and implementation with our team of ex-bankers and private equity investors.
                </p>
            </div>

            <!-- Custom-Trained Models -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Custom-Trained Models</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <!-- Tree structure visualization -->
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-gray-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-[#0B231E] rounded flex items-center justify-center text-white text-xs">AI</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Custom-trained LLMs built for finance, using professionally labeled data tailored to the workflows and precision standards of investment banking.
                </p>
            </div>

            <!-- Governance & Permissions -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Governance & Permissions</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold">122</div>
                            <div class="text-[10px] font-bold">2.14</div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-px bg-gray-100 w-full"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-1/2"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            <div class="h-1.5 bg-gray-100 rounded w-2/3"></div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Granular permission controls, role-based access management, comprehensive audit trails, and customizable governance policies to streamline compliance and safeguard your data.
                </p>
            </div>

            <!-- Single Tenant Deployment -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Single Tenant Deployment</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as i}
                            <div class={`h-8 w-8 border border-gray-200 ${i === 5 ? 'bg-[#0B231E] flex items-center justify-center' : 'bg-white'}`}>
                                {#if i === 5}
                                    <div class="h-2 w-2 bg-white rounded-full"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Flexible deployment options to meet your security and infrastructure needs.
                </p>
            </div>
        </div>
    </div>
</section>
