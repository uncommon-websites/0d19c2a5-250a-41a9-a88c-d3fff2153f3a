<script lang="ts">
</script>

<main class="pt-32 pb-0 bg-gradient-to-br from-gray-900 via-gray-800 to-black text-white overflow-x-hidden">
	<!-- Hero Content -->
	<section class="max-w-[1000px] mx-auto px-6 text-center flex flex-col items-center pt-10 pb-16">
		
		<!-- Announcement Badge -->
		<a href="#" class="animate-fade-in-up delay-100 inline-flex items-center gap-2 px-4 py-1.5 rounded-full border border-gray-700 bg-gray-800/50 text-sm font-medium text-gray-300 hover:bg-gray-800 transition-colors mb-8 shadow-sm">
			Meet the open-source scheduling infrastructure
			<svg class="w-3.5 h-3.5 text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
		</a>

		<!-- Headline -->
		<h1 class="animate-fade-in-up delay-200 text-5xl md:text-7xl lg:text-[84px] font-extrabold tracking-tight text-white leading-tight text-balance mb-6">
			Own your<br />scheduling stack.
		</h1>

		<!-- Subheadline -->
		<p class="animate-fade-in-up delay-300 text-xl md:text-[22px] text-gray-400 font-medium text-pretty leading-relaxed max-w-2xl mb-10">
			Cal.com is the white-label, open-source scheduling platform with deep API and app integrations.
		</p>

		<!-- CTAs -->
		<div class="animate-fade-in-up delay-400 flex flex-col sm:flex-row items-center gap-4">
			<a href="#" class="w-full sm:w-auto text-base font-medium bg-primary-500 text-white px-6 py-3 rounded-lg hover:bg-primary-600 transition-colors duration-200 active:scale-[0.97]">
				Start for free
			</a>
			<a href="#" class="w-full sm:w-auto text-base font-medium bg-gray-800 text-white border border-gray-700 px-6 py-3 rounded-lg hover:opacity-90 hover:bg-gray-700 transition-colors duration-200 active:scale-[0.97]">
				Talk to sales
			</a>
		</div>
	</section>

	<!-- Tabs & UI Mockup Section -->
	<section class="w-full relative mt-4">
		
		<!-- Full width dashed line top -->
		<div class="absolute top-0 left-0 w-full border-t border-dashed border-gray-800"></div>

		<!-- Tabs Container -->
		<div class="w-full border-b border-dashed border-gray-800 overflow-x-auto">
			<div class="min-w-[800px] max-w-[1080px] mx-auto grid grid-cols-4 border-x border-dashed border-gray-800 animate-fade-in-up delay-500">
				
				<!-- Active Tab -->
				<button class="relative py-5 text-center text-[15px] font-medium text-white bg-gray-800 border-r border-dashed border-gray-800 transition-colors">
					Open Source
					<!-- Active Indicator Line -->
					<div class="absolute -bottom-[1px] left-1/2 -translate-x-1/2 w-24 h-[2px] bg-white"></div>
				</button>

				<!-- Inactive Tabs -->
				<button class="py-5 text-center text-[15px] font-medium text-gray-400 hover:text-white border-r border-dashed border-gray-800 transition-colors bg-gray-900/50">
					API & Apps
				</button>
				<button class="py-5 text-center text-[15px] font-medium text-gray-400 hover:text-white border-r border-dashed border-gray-800 transition-colors bg-gray-900/50">
					Governance
				</button>
				<button class="py-5 text-center text-[15px] font-medium text-gray-400 hover:text-white transition-colors bg-gray-900/50">
					Self-Hosting
				</button>
			</div>
		</div>

		<!-- UI Mockup -->
		<div class="w-full pb-24 overflow-x-auto">
			<div class="min-w-[800px] max-w-[1080px] mx-auto border-x border-dashed border-gray-800">
				<div class="animate-scale-in delay-600 w-full bg-gray-900">
					<img 
						src="/generated/image-a-modern-clean-web-application-dashboard-1772668492614-0.webp" 
						alt="Cal.com Dashboard Interface" 
						class="w-full h-auto block"
					/>
				</div>
			</div>
		</div>

	</section>
</main>

<style>
	@keyframes fadeInUp {
		from { opacity: 0; transform: translateY(20px); }
		to { opacity: 1; transform: translateY(0); }
	}
	@keyframes scaleIn {
		from { opacity: 0; transform: scale(0.98); }
		to { opacity: 1; transform: scale(1); }
	}

	.animate-fade-in-up {
		opacity: 0;
		animation: fadeInUp 0.6s cubic-bezier(0.16, 1, 0.3, 1) forwards;
	}
	.animate-scale-in {
		opacity: 0;
		animation: scaleIn 0.6s cubic-bezier(0.16, 1, 0.3, 1) forwards;
	}

	.delay-100 { animation-delay: 100ms; }
	.delay-200 { animation-delay: 200ms; }
	.delay-300 { animation-delay: 300ms; }
	.delay-400 { animation-delay: 400ms; }
	.delay-500 { animation-delay: 500ms; }
	.delay-600 { animation-delay: 600ms; }

	.text-balance { text-wrap: balance; }
	.text-pretty { text-wrap: pretty; }

	@media (prefers-reduced-motion: reduce) {
		.animate-fade-in-up, .animate-scale-in {
			animation: none;
			opacity: 1;
			transform: none;
		}
	}
</style>