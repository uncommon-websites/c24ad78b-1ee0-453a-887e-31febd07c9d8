<script>
  const logos = [
    { name: "Heart Vets", font: "font-serif font-bold" },
    { name: "MAX & MIN", font: "font-sans font-black tracking-tight" },
    { name: "Polden Hills", font: "font-sans font-bold" },
    { name: "Essex Vets", font: "font-sans font-bold" },
    { name: "Creature Comforts", font: "font-serif italic font-bold" },
    { name: "MADRA", font: "font-mono font-bold tracking-widest" },
    { name: "Anderson's", font: "font-sans font-bold" },
    { name: "Optivet", font: "font-sans font-bold tracking-tight" },
    { name: "Skylark", font: "font-sans font-light tracking-wide" },
    { name: "Luna", font: "font-serif font-bold italic" },
    { name: "Wag Works", font: "font-sans font-black" },
    { name: "Fyfield", font: "font-sans font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by leading veterinary practices across the UK
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
