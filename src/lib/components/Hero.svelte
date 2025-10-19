<!-- Hero Section -->
<section id="home" class="hero min-h-screen relative overflow-hidden">
  <!-- Modern Gradient Background -->
  <div class="absolute inset-0 bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900"></div>
  <div class="absolute inset-0 bg-gradient-to-tr from-blue-600/20 via-transparent to-purple-600/20"></div>
  
  <!-- Animated Background Pattern -->
  <div class="absolute inset-0 opacity-30">
    <div class="absolute inset-0" style="background-image: radial-gradient(circle at 25% 25%, rgba(120, 119, 198, 0.3) 0%, transparent 50%), radial-gradient(circle at 75% 75%, rgba(255, 119, 198, 0.3) 0%, transparent 50%); background-size: 400px 400px; animation: float 20s ease-in-out infinite;"></div>
  </div>
  
  <!-- Floating Geometric Shapes -->
  <div class="absolute top-20 left-10 w-32 h-32 bg-gradient-to-br from-blue-400/20 to-purple-400/20 rounded-full animate-pulse blur-xl"></div>
  <div class="absolute top-40 right-20 w-24 h-24 bg-gradient-to-br from-pink-400/20 to-blue-400/20 rounded-full animate-bounce blur-lg"></div>
  <div class="absolute bottom-40 left-20 w-20 h-20 bg-gradient-to-br from-purple-400/30 to-pink-400/30 rounded-full animate-ping blur-md"></div>
  <div class="absolute top-1/2 right-1/4 w-16 h-16 bg-gradient-to-br from-cyan-400/20 to-blue-400/20 rounded-full animate-pulse blur-sm"></div>
  
  <div class="hero-content text-center text-white relative z-10">
    <div class="max-w-5xl">
      <!-- Profile Image with Modern Glow Effect -->
      <div class="avatar mb-12 group">
        <div class="w-48 rounded-full ring-4 ring-white/20 ring-offset-4 ring-offset-transparent group-hover:ring-blue-400/50 transition-all duration-500 group-hover:scale-110 group-hover:shadow-2xl group-hover:shadow-blue-500/25">
          <img src="https://via.placeholder.com/400x400/6366F1/FFFFFF?text=Profil" alt="Profil Fotoğrafı" class="rounded-full" />
        </div>
        <!-- Glow effect -->
        <div class="absolute inset-0 rounded-full bg-gradient-to-r from-blue-400/30 to-purple-400/30 blur-xl group-hover:blur-2xl transition-all duration-500"></div>
      </div>
      
      <!-- Main Title with Enhanced Gradient -->
      <h1 class="text-8xl font-black mb-8 bg-gradient-to-r from-white via-blue-100 to-purple-100 bg-clip-text text-transparent animate-pulse leading-tight">
        Merhaba! 👋
      </h1>
      
      <!-- Subtitle with Better Typography -->
      <p class="text-4xl mb-6 font-bold text-blue-50 animate-fade-in-up leading-tight">
        Ben <span class="text-yellow-300 font-extrabold">[Adınız]</span>, 
        <span class="bg-gradient-to-r from-blue-300 to-purple-300 bg-clip-text text-transparent">Web Geliştirici</span>
      </p>
      
      <p class="text-2xl mb-12 text-gray-100 max-w-3xl mx-auto leading-relaxed animate-fade-in-up-delay font-light">
        Modern web teknolojileri ile yaratıcı çözümler üretiyorum. 
        <span class="text-blue-300 font-semibold">Svelte</span>, 
        <span class="text-green-300 font-semibold">TypeScript</span> ve 
        <span class="text-pink-300 font-semibold">Tailwind CSS</span> kullanarak 
        hızlı ve kullanıcı dostu uygulamalar geliştiriyorum.
      </p>
      
      <!-- Action Buttons with Modern Glass Effect -->
      <div class="flex flex-col sm:flex-row gap-8 justify-center items-center">
        <button 
          on:click={() => document.getElementById('projects')?.scrollIntoView({behavior: 'smooth'})} 
          class="group relative px-8 py-4 bg-gradient-to-r from-blue-500/90 to-purple-600/90 backdrop-blur-sm text-white font-semibold rounded-2xl shadow-2xl hover:shadow-blue-500/25 hover:scale-105 transition-all duration-500 border border-white/20 hover:border-white/40"
        >
          <div class="absolute inset-0 bg-gradient-to-r from-blue-500 to-purple-600 rounded-2xl blur opacity-0 group-hover:opacity-75 transition-opacity duration-500"></div>
          <div class="relative flex items-center gap-3">
            <svg class="w-6 h-6 group-hover:rotate-12 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
            </svg>
            <span class="text-lg">Projelerim</span>
          </div>
        </button>
        
        <button 
          on:click={() => document.getElementById('contact')?.scrollIntoView({behavior: 'smooth'})} 
          class="group relative px-8 py-4 bg-white/10 backdrop-blur-sm text-white font-semibold rounded-2xl border-2 border-white/30 hover:border-white/60 hover:bg-white/20 hover:scale-105 transition-all duration-500"
        >
          <div class="flex items-center gap-3">
            <svg class="w-6 h-6 group-hover:rotate-12 transition-transform duration-300" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
            </svg>
            <span class="text-lg">İletişim</span>
          </div>
        </button>
      </div>
      
      <!-- Tech Stack Icons -->
      <div class="mt-12 flex flex-wrap justify-center gap-4 opacity-70">
        <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm rounded-full px-4 py-2">
          <div class="w-6 h-6 bg-orange-500 rounded"></div>
          <span class="text-sm font-medium">Svelte</span>
        </div>
        <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm rounded-full px-4 py-2">
          <div class="w-6 h-6 bg-blue-500 rounded"></div>
          <span class="text-sm font-medium">TypeScript</span>
        </div>
        <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm rounded-full px-4 py-2">
          <div class="w-6 h-6 bg-cyan-500 rounded"></div>
          <span class="text-sm font-medium">Tailwind</span>
        </div>
        <div class="flex items-center gap-2 bg-white/10 backdrop-blur-sm rounded-full px-4 py-2">
          <div class="w-6 h-6 bg-green-500 rounded"></div>
          <span class="text-sm font-medium">DaisyUI</span>
        </div>
      </div>
    </div>
  </div>
  
  <!-- Scroll Indicator -->
  <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce">
    <div class="flex flex-col items-center text-white/60">
      <span class="text-sm mb-2">Aşağı Kaydır</span>
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
      </svg>
    </div>
  </div>
</section>
