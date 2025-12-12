<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-epiture-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-epiture-primary)]"></span>
                        <span class="text-white text-sm font-medium">New Tokyo PoP</span>
                        <span class="text-gray-400 text-sm">now live</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Enterprise infrastructure across Asia-Pacific.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Carrier-neutral colocation and multi-terabit transit networks. Get sub-5ms latency between Seoul and Tokyo with 99.99% uptime SLA. Built for growing tech companies who need reliable connectivity.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Contact Sales
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            View Network Status
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Network Stats -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500 uppercase">Seoul PoP</div>
                                <div class="px-3 py-1 bg-green-100 rounded-full text-green-700 text-xs font-bold">Operational</div>
                            </div>
                            <div class="space-y-4">
                                <div>
                                    <div class="text-xs text-gray-500 mb-1">Transit Capacity</div>
                                    <div class="text-2xl font-bold text-gray-900">120 Gbps</div>
                                </div>
                                <div class="grid grid-cols-2 gap-3">
                                    <div class="bg-gray-50 p-3 rounded-lg">
                                        <div class="text-xs text-gray-500">Facilities</div>
                                        <div class="text-lg font-bold">4</div>
                                    </div>
                                    <div class="bg-gray-50 p-3 rounded-lg">
                                        <div class="text-xs text-gray-500">Uptime</div>
                                        <div class="text-lg font-bold">99.9%</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Datacenter Image -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <img src="/generated/image-modern-datacenter-server-racks-with-glow-1765513275569-0.webp" alt="Modern datacenter infrastructure" class="w-full h-full object-cover" />
                    </div>

                    <!-- Card 3 - Tokyo Stats -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500 uppercase">Tokyo PoP</div>
                                <div class="px-3 py-1 bg-green-100 rounded-full text-green-700 text-xs font-bold">Operational</div>
                            </div>
                            <div class="space-y-4">
                                <div>
                                    <div class="text-xs text-gray-500 mb-1">Transit Capacity</div>
                                    <div class="text-2xl font-bold text-gray-900">40 Gbps</div>
                                </div>
                                <div class="grid grid-cols-2 gap-3">
                                    <div class="bg-gray-50 p-3 rounded-lg">
                                        <div class="text-xs text-gray-500">Facilities</div>
                                        <div class="text-lg font-bold">4</div>
                                    </div>
                                    <div class="bg-gray-50 p-3 rounded-lg">
                                        <div class="text-xs text-gray-500">Latency</div>
                                        <div class="text-lg font-bold">&lt;5ms</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by leading organizations</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-16 opacity-60">
                    <div class="text-white font-semibold text-lg">Daejeon Metro Gov</div>
                    <div class="text-white font-semibold text-lg">Tefexia</div>
                    <div class="text-white font-semibold text-lg">Phylaxis</div>
                    <div class="text-white font-semibold text-lg">4096 SVCS</div>
                    <div class="text-white font-semibold text-lg">BMYM</div>
                    <div class="text-white font-semibold text-lg">The Dreamer</div>
                    <div class="text-white font-semibold text-lg">Craft Studio</div>
                </div>
            </div>
        </section>

        <!-- Infrastructure Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-epiture-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Enterprise Infrastructure</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Carrier-neutral connectivity.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Built for scale.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Network Visualization -->
                    <div class="rounded-3xl overflow-hidden shadow-2xl">
                        <img src="/generated/image-abstract-visualization-of-network-connec-1765513288965-5.webp" alt="Network connectivity visualization" class="w-full h-full object-cover" />
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">2+ Tbps backbone capacity.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Connect to 11+ carriers across Seoul and Tokyo. Our Tier III+ facilities and carrier-neutral positioning give you the flexibility to grow without vendor lock-in.
                        </p>
                        <div class="grid grid-cols-2 gap-4">
                            <div class="bg-white/5 border border-white/10 rounded-xl p-4">
                                <div class="text-3xl font-bold text-white mb-1">20+</div>
                                <div class="text-sm text-gray-400">Interconnection Points</div>
                            </div>
                            <div class="bg-white/5 border border-white/10 rounded-xl p-4">
                                <div class="text-3xl font-bold text-white mb-1">99.99%</div>
                                <div class="text-sm text-gray-400">Uptime SLA</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Our Services</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything you need to expand across Asia-Pacific.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">From colocation to transit.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        View all services
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-epiture-primary)]"></span>
                                Colocation Services
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">IP Transit</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">IP Leasing</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">DDoS Protection</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Carrier Connectivity</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">24/7 Support</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Colocation Services" 
                            description="Tier III+ facilities at NetRealty Gasan. Get redundant power (A+B, N+1 UPS), 24/7 security, and up to 8.8kW per rack in Seoul's premier technology hub."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="IP Transit" 
                            description="Multi-terabit backbone capacity. 120Gbps in Seoul, 40Gbps in Tokyo with 99.9% uptime SLA and best-effort DDoS protection included."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="IP Leasing" 
                            description="KRNIC and ARIN allocations available. Minimum 1x /24 with volume discounts at 5+ blocks. RPKI support included for routing security."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="DDoS Protection" 
                            description="Always-on protection included. Advanced mitigation available through our upstream providers with real-time traffic analysis and automated response."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Carrier Connectivity" 
                            description="11+ carrier options available. Connect to KT, LG U+, SK Telecom, KINX, and international carriers including PCCW Global, China Mobile, and Telstra."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="24/7 Support" 
                            description="Expert NOC team ready to help. Remote hands support, facility tours by appointment, and direct access to network engineers via noc@epiture.net."
                            icon="guard"
                            image="guard"
                        />
                    </div>
                </div>

                <!-- Network Peering Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-cyan-100 to-teal-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-cyan-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Open peering policy with 10G increments. Join AS401450 and connect to our growing network.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        View peering policy
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Case Studies Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by growing tech companies. Learn from our customers.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- 4096 SVCS Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 opacity-30">
                                <img src="/generated/image-modern-office-building-exterior-in-seoul-1765513286365-4.webp" alt="NetRealty Gasan facility" class="w-full h-full object-cover" />
                            </div>
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/80 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">4096 SVCS</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-epiture-primary)] flex items-center justify-center text-black font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <rect x="3" y="3" width="8" height="8" stroke="white" stroke-width="2" rx="1"/>
                                            <rect x="13" y="3" width="8" height="8" stroke="white" stroke-width="2" rx="1"/>
                                            <rect x="3" y="13" width="8" height="8" stroke="white" stroke-width="2" rx="1"/>
                                            <rect x="13" y="13" width="8" height="8" stroke="white" stroke-width="2" rx="1"/>
                                        </svg>
                                        Epiture
                                    </div>
                                </div>
                                <p class="text-gray-300 mb-4 text-lg italic">
                                    "After moving into Epiture's NetRealty Gasan data center, we connected to Korean Tier-1 networks and maintained flawless local connectivity even during peak hours."
                                </p>
                                <div class="text-sm text-gray-400">
                                    — Michael Lee, Infrastructure Lead at 4096 SVCS LLC
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Cloud Migration Card -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <h4 class="text-white font-bold text-lg mb-2">Cloud Migration</h4>
                                    <p class="text-gray-400 text-sm">Financial services company achieved zero downtime migration</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- System Integration Card -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <h4 class="text-white font-bold text-lg mb-2">Infrastructure Upgrade</h4>
                                    <p class="text-gray-400 text-sm">Retail platform scaled to 10x traffic capacity</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-cyan-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-teal-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Reliable infrastructure. <span class="text-[var(--color-epiture-primary)]">Competitive pricing.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Built for network engineers who need Asia-Pacific connectivity without expensive transit costs. Get started with our team today.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                            Network Status
                            <span class="bg-green-500 w-2 h-2 rounded-full"></span>
                        </div>
                    </div>
                </div>

                <!-- Carriers -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        Domestic carriers. International transit.<br>
                        Direct peering. <span class="text-gray-400">Connect to the carriers<br>that matter for your business.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        View all carriers
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['KT', 'LG U+', 'SK Telecom', 'KINX', 'PCCW Global', 'Telstra', 'GCORE', 'China Mobile'] as carrier}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{carrier}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Latest from our blog.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <img src="/generated/image-professional-asian-network-engineer-work-1765513283981-3.webp" alt="Network engineer" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Case Study • 5 min read</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-cyan-600 transition-colors">How Daejeon Metropolitan Government Achieved Over 10M in Brand Exposure</h3>
                            <p class="text-gray-600 mt-2">A Public-Private Partnership Reigniting Youth Engagement and City Competitiveness</p>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <img src="/generated/image-close-up-of-fiber-optic-cables-with-glow-1765513281287-2.webp" alt="Fiber optic cables" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Network Infrastructure</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-cyan-600 transition-colors">Why carrier-neutral colocation matters for Asia-Pacific expansion</h3>
                            <p class="text-gray-600 mt-2">Understanding the benefits of multi-carrier connectivity in growing tech markets</p>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

