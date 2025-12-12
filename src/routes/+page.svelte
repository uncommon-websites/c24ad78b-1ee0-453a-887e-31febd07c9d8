<script>
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import Logos from '$lib/components/Logos.svelte';
  import ProblemStatement from '$lib/components/ProblemStatement.svelte';
  import Orchestration from '$lib/components/Orchestration.svelte';
  import FeaturesGrid from '$lib/components/FeaturesGrid.svelte';
  import FeatureAri from '$lib/components/FeatureAri.svelte';
  import FeatureSidekick from '$lib/components/FeatureSidekick.svelte';
  import FeatureLookup from '$lib/components/FeatureLookup.svelte';
  import FeatureRoadmap from '$lib/components/FeatureRoadmap.svelte';
  import FeatureScale from '$lib/components/FeatureScale.svelte';
  import SpeedSection from '$lib/components/SpeedSection.svelte';
  import Testimonials from '$lib/components/Testimonials.svelte';
  import TimeSavings from '$lib/components/TimeSavings.svelte';
  import Security from '$lib/components/Security.svelte';
  import CTA from '$lib/components/CTA.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen bg-white font-body selection:bg-primary-100 selection:text-primary-900">
  <Navbar />
  
  <main>
    <Hero />
    <Logos />
    <ProblemStatement />
    <Orchestration />
    <FeaturesGrid />
    <FeatureAri />
    <FeatureSidekick />
    <FeatureLookup />
    <FeatureRoadmap />
    <FeatureScale />
    <SpeedSection />
    <Testimonials />
    <TimeSavings />
    <Security />
    <CTA />
  </main>

  <Footer />
  
  <!-- Floating Chat Button Mockup -->
  <div class="fixed bottom-6 right-6 z-50">
      <button class="w-14 h-14 bg-black rounded-full flex items-center justify-center shadow-2xl hover:scale-105 transition-transform">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
      </button>
  </div>
</div>

