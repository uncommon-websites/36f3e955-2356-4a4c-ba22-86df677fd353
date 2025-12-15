<script>
    const partners = [
        { name: "Fidelity", icon: "F", color: "bg-green-700" },
        { name: "Vanguard", icon: "V", color: "bg-red-700" },
        { name: "Charles Schwab", icon: "S", color: "bg-blue-600" },
        { name: "TD Ameritrade", icon: "TD", color: "bg-green-600" },
        { name: "E*TRADE", icon: "E", color: "bg-purple-700" },
        { name: "Robinhood", icon: "R", color: "bg-green-500" },
        { name: "Interactive Brokers", icon: "IB", color: "bg-blue-800" },
        { name: "Merrill Edge", icon: "M", color: "bg-red-600" },
        { name: "Wealthfront", icon: "W", color: "bg-purple-600" },
        { name: "Betterment", icon: "B", color: "bg-blue-500" },
        { name: "Ally Invest", icon: "A", color: "bg-purple-800" },
        { name: "M1 Finance", icon: "M1", color: "bg-red-500" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Works With Your Accounts</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                Fulfilled integrates with all major brokerages and investment platforms. Connect your existing accounts to get a complete view of your portfolio and receive personalized guidance—no transfers needed.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color ? partner.color : 'bg-gray-200 text-gray-600'}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
