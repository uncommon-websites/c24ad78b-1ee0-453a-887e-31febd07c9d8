<section class="py-12 bg-lupa-dark">
  <div class="container-custom">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-lupa-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-center justify-center relative">
            <!-- Calendar Grid -->
            <div class="grid grid-cols-4 gap-3 opacity-60 group-hover:opacity-100 transition-opacity">
                {#each Array(8) as _}
                <div class="w-8 h-8 rounded bg-gray-800 border border-gray-700"></div>
                {/each}
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Smart Scheduling</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Intelligent appointment management that understands your practice flow. Book consultations, surgeries, and follow-ups with zero conflicts.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="bg-lupa-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-end justify-center gap-1 pb-4">
            <!-- Bar Chart -->
            <div class="w-3 bg-primary-900/40 h-12 rounded-t"></div>
            <div class="w-3 bg-primary-800/60 h-16 rounded-t"></div>
            <div class="w-3 bg-primary-700/80 h-10 rounded-t"></div>
            <div class="w-3 bg-primary-600 h-24 rounded-t"></div>
            <div class="w-3 bg-primary-500 h-20 rounded-t"></div>
            <div class="w-3 bg-primary-400 h-28 rounded-t shadow-[0_0_15px_rgba(74,222,128,0.5)]"></div>
            <div class="w-3 bg-primary-500 h-14 rounded-t"></div>
            <div class="w-3 bg-primary-600 h-18 rounded-t"></div>
            
            <!-- Tooltip-like badge -->
            <div class="absolute top-10 bg-white text-black text-[10px] font-bold px-2 py-1 rounded shadow-lg transform translate-x-4">
                AI Transcription
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Lupa Notes AI</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Stop typing. Start caring. AI transcription captures every consultation detail automatically, saving hours of admin work daily.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="bg-lupa-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex flex-col items-center justify-center gap-3">
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-primary-600 text-white text-xs rounded font-medium">Appointment reminder</div>
                 <div class="px-3 py-1 bg-primary-600/20 text-primary-400 border border-primary-600/30 text-xs rounded font-medium">Follow-up</div>
             </div>
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-primary-600/20 text-primary-400 border border-primary-600/30 text-xs rounded font-medium">Lab results</div>
                 <div class="px-3 py-1 bg-primary-600/20 text-primary-400 border border-primary-600/30 text-xs rounded font-medium">Prescription ready</div>
             </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Automated Client Communications</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Keep pet owners informed automatically. Appointment reminders, lab results, and follow-ups sent at the perfect time, every time.
        </p>
      </div>

    </div>
  </div>
</section>
