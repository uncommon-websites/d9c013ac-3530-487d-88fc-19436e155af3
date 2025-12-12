<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-skuuudle-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-skuuudle-primary)]"></span>
                        <span class="text-white text-sm font-medium">Trusted since 2007</span>
                        <span class="text-gray-400 text-sm">16+ years of expertise</span>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Trustworthy competitor pricing intelligence.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        AI-powered scraping meets human quality control. Get 99% match accuracy on competitor pricing data. Trusted by hundreds of enterprise retailers, brands, and distributors worldwide.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-[var(--color-skuuudle-primary)] hover:bg-[var(--color-skuuudle-primary-hover)] text-white px-6 py-3 rounded-full font-semibold transition-colors flex items-center gap-2">
                            Request a Demo
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            See How It Works
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
                    <!-- Card 1 - Pricing Comparison -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500 uppercase">Competitor Analysis</div>
                                <div class="px-3 py-1 bg-green-100 rounded-full text-green-700 text-xs font-bold">99% Match</div>
                            </div>
                            <div class="space-y-3">
                                <div class="flex justify-between items-center py-2 border-b border-gray-100">
                                    <span class="text-sm text-gray-600">Your Price</span>
                                    <span class="text-lg font-bold text-gray-900">$49.99</span>
                                </div>
                                <div class="flex justify-between items-center py-2 border-b border-gray-100">
                                    <span class="text-sm text-gray-600">Competitor A</span>
                                    <span class="text-lg font-bold text-red-600">$44.99</span>
                                </div>
                                <div class="flex justify-between items-center py-2">
                                    <span class="text-sm text-gray-600">Competitor B</span>
                                    <span class="text-lg font-bold text-gray-900">$52.99</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Product Match -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-gradient-to-br from-[var(--color-skuuudle-primary)] to-[var(--color-skuuudle-primary-hover)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-bold text-sm">Product Matching</div>
                                    <div class="px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white text-xs font-semibold">AI + Human</div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="space-y-4">
                                    <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                                        <div class="w-12 h-12 bg-gray-200 rounded"></div>
                                        <div class="flex-grow">
                                            <div class="h-3 w-full bg-gray-200 rounded mb-2"></div>
                                            <div class="h-2 w-2/3 bg-gray-100 rounded"></div>
                                        </div>
                                        <svg class="w-5 h-5 text-green-600" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                                    </div>
                                    <div class="flex items-center gap-3 p-3 bg-gray-50 rounded-lg">
                                        <div class="w-12 h-12 bg-gray-200 rounded"></div>
                                        <div class="flex-grow">
                                            <div class="h-3 w-full bg-gray-200 rounded mb-2"></div>
                                            <div class="h-2 w-2/3 bg-gray-100 rounded"></div>
                                        </div>
                                        <svg class="w-5 h-5 text-green-600" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Quality Control -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-6">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500 uppercase">Quality Control</div>
                                <div class="px-3 py-1 bg-blue-100 rounded-full text-blue-700 text-xs font-bold">Verified</div>
                            </div>
                            <div class="space-y-3">
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <div class="text-xs text-gray-500 mb-1">Analyst</div>
                                    <div class="font-semibold text-gray-900">Dan Hope</div>
                                </div>
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <div class="text-xs text-gray-500 mb-1">Accuracy</div>
                                    <div class="font-semibold text-gray-900">99.2%</div>
                                </div>
                                <div class="p-3 bg-gray-50 rounded-lg">
                                    <div class="text-xs text-gray-500 mb-1">Products Verified</div>
                                    <div class="font-semibold text-gray-900">12,847</div>
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
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by hundreds of enterprise retailers worldwide</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-60">
                    <!-- Primark -->
                    <div class="text-white font-bold text-xl md:text-2xl tracking-wider">PRIMARK</div>
                    <!-- ASDA -->
                    <div class="text-white font-bold text-xl md:text-2xl tracking-wider">ASDA</div>
                    <!-- Groupon -->
                    <div class="text-white font-bold text-xl md:text-2xl tracking-tight">groupon</div>
                    <!-- Decathlon -->
                    <div class="text-white font-bold text-xl md:text-2xl tracking-wide">DECATHLON</div>
                    <!-- Boots -->
                    <div class="text-white font-bold text-xl md:text-2xl tracking-wide">Boots</div>
                </div>
            </div>
        </section>

        <!-- The Skuuudle Difference Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-skuuudle-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">The Skuuudle Way</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">AI-powered scraping.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Human-verified accuracy.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Teal Card -->
                    <div class="bg-gradient-to-br from-[var(--color-skuuudle-primary)] to-[var(--color-skuuudle-primary-hover)] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Data Quality Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="space-y-4 relative z-10">
                                    <div class="flex items-center justify-between">
                                        <div class="text-white/80 text-xs uppercase tracking-wider font-medium">Data Accuracy</div>
                                        <div class="text-white font-bold text-2xl">99%</div>
                                    </div>
                                    <div class="h-2 bg-white/20 rounded-full overflow-hidden">
                                        <div class="h-full bg-white w-[99%] rounded-full"></div>
                                    </div>
                                    <div class="flex items-center gap-2 text-white/80 text-xs">
                                        <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                                        <span>Human-verified</span>
                                    </div>
                                </div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center text-blue-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path></svg>
                                    </div>
                                    Premium quality
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-white/30 flex items-center justify-center text-white">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z" clip-rule="evenodd"></path></svg>
                                    </div>
                                    60+ experts
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Trust built on precision.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            16 years of expertise. Every dataset signed off by named quality control analysts. We sweat the small stuff so you can focus on strategic pricing decisions that drive real results.
                        </p>
                        <div class="flex items-center gap-4">
                            <div class="text-center">
                                <div class="text-3xl font-bold text-white">16+</div>
                                <div class="text-sm text-gray-500">Years</div>
                            </div>
                            <div class="h-12 w-px bg-white/10"></div>
                            <div class="text-center">
                                <div class="text-3xl font-bold text-white">60+</div>
                                <div class="text-sm text-gray-500">Experts</div>
                            </div>
                            <div class="h-12 w-px bg-white/10"></div>
                            <div class="text-center">
                                <div class="text-3xl font-bold text-white">100s</div>
                                <div class="text-sm text-gray-500">Customers</div>
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
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Platform</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Complete pricing intelligence.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">Fully managed.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore our platform
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
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-skuuudle-primary)]"></span>
                                AI-Powered Scraping
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Human Quality Control</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Product Matching</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Real-time Monitoring</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Multi-region Support</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Data Accuracy</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="AI-Powered Scraping" 
                            description="Scrape any website, anywhere. Our AI-powered technology collects competitor pricing data from any website in any region and language, processing millions of products daily."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Human Quality Control" 
                            description="Every dataset verified by experts. Named quality control analysts sign off on every dataset, ensuring the accuracy your pricing decisions depend on."
                            icon="guard"
                            image="guard"
                        />
                         <FeatureRow 
                            title="Product Matching" 
                            description="End-to-end matching you can trust. We handle product matching completely, maintaining accurate matches even as competitors change product IDs and URLs."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Real-time Monitoring" 
                            description="Stay ahead of the market. Track competitor prices from hourly to weekly, with daily and weekly being most popular among enterprise retailers."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Multi-region Support" 
                            description="Global coverage, local precision. Collect region-specific pricing down to zip-code or store level across US, UK, Europe, and Canada."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Data Accuracy Guarantee" 
                            description="99% match accuracy, guaranteed. Three-pronged quality approach: preventative maintenance, active monitoring, and robust quality control before delivery."
                            icon="lock"
                            image="collateral"
                        />
                    </div>
                </div>

                <!-- ROI Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-green-100 to-teal-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-green-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Customers typically see returns of at least 10x. Often exceeding 100x.
                    </h2>
                    <p class="text-lg text-gray-600 mb-8">
                        A $500M revenue company spending $50k-$100k annually could make $2.5M extra profit with just a 1% price increase on half of revenue. That's a 25x ROI.
                    </p>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        Calculate your ROI
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by enterprise retailers worldwide. Hear from our customers.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Paperstone Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-between">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-8">
                                    <div class="text-white font-bold text-2xl tracking-tight">Paperstone</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-skuuudle-primary)] flex items-center justify-center text-white font-bold">✓</div>
                                </div>
                                <blockquote class="text-2xl md:text-3xl font-medium text-white mb-6 leading-relaxed">
                                    "Skuuudle has played an essential role in enabling us to stay ahead of the game when it comes to competitive pricing."
                                </blockquote>
                                <div class="flex items-center gap-4">
                                    <div class="w-12 h-12 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white font-bold">JB</div>
                                    <div>
                                        <div class="text-white font-semibold">Jim Brown</div>
                                        <div class="text-gray-400 text-sm">CEO, Paperstone</div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 - Primark -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-bold text-xl mb-2">PRIMARK</div>
                                    <div class="text-gray-400 text-sm">Enterprise Retailer</div>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 - Decathlon -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-bold text-xl mb-2">DECATHLON</div>
                                    <div class="text-gray-400 text-sm">Sporting Goods Retailer</div>
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
                    <div class="absolute left-0 top-0 w-64 h-64 bg-[var(--color-skuuudle-primary)]/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-blue-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Make strategic pricing decisions. <span class="text-[var(--color-skuuudle-primary)]">With confidence.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Fully managed service with end-to-end product matching. Get operational within 6-12 weeks with dedicated account manager support.
                        </p>
                        <button class="inline-flex items-center gap-2 bg-[var(--color-skuuudle-primary)] hover:bg-[var(--color-skuuudle-primary-hover)] border border-[var(--color-skuuudle-primary)] rounded-full px-6 py-3 text-white text-sm font-semibold transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path></svg>
                            Talk to Our Team
                        </button>
                    </div>
                </div>

                <!-- Data Collection Capabilities -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        Any website. Any region.<br>
                        Any language. <span class="text-gray-400">We collect the data<br>you need to compete.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        See what we collect
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Base Price', 'Shelf Price', 'Promo Price', 'Stock Status', 'Product Names', 'Barcodes/MPNs', 'Review Scores', 'Delivery Fees'] as dataPoint}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center hover:bg-white transition-all duration-300">
                            <span class="font-semibold text-sm text-gray-700">{dataPoint}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn more about competitive pricing intelligence.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-[var(--color-skuuudle-primary-light)] to-[var(--color-skuuudle-primary)] rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-30">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-white transform -rotate-45" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Pricing Strategy</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-[var(--color-skuuudle-primary)] transition-colors">Why data accuracy matters more than you think</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-[var(--color-skuuudle-primary)] blur-xl opacity-60"></div>
                                    <div class="w-20 h-20 rounded-full bg-blue-400 blur-xl opacity-60"></div>
                                    <div class="w-12 h-12 rounded-full bg-green-400 blur-xl opacity-60"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Case Study</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-[var(--color-skuuudle-primary)] transition-colors">How enterprise retailers achieve 100x ROI with pricing intelligence</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

