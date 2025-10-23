<!-- Hero Section -->
<section id="home" class="hero min-h-screen relative overflow-hidden">
  <!-- Modern Gradient Background -->
  <div class="absolute inset-0 bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900"></div>
  <div class="absolute inset-0 bg-gradient-to-tr from-blue-600/20 via-transparent to-purple-600/20"></div>
  
  <!-- Animated Background Pattern -->
  <div class="absolute inset-0 opacity-30">
    <div class="absolute inset-0" style="background-image: radial-gradient(circle at 25% 25%, rgba(120, 119, 198, 0.3) 0%, transparent 50%), radial-gradient(circle at 75% 75%, rgba(255, 119, 198, 0.3) 0%, transparent 50%); background-size: 400px 400px; animation: float 20s ease-in-out infinite;"></div>
  </div>
  
  
  <!-- Left Vertical Navigation Links -->
  <div class="absolute left-8 top-8 z-20 hidden lg:block">
    <div class="flex flex-col space-y-16">
      <!-- Profile Picture Section -->
      <div class="flex justify-center">
        <img src="https://media.licdn.com/dms/image/v2/D4E03AQEJcyx0DhzrIw/profile-displayphoto-scale_200_200/B4EZfZZU9RHIAY-/0/1751698985544?e=1762992000&v=beta&t=QO0zZ-vSr5vU92xpuSOprdkOkDl6OYcKbfm2SEqVzIE" alt="Profil" class="w-16 h-16 rounded-full object-cover" />
      </div>
      
      <!-- Navigation Links Section -->
      <div class="flex flex-col space-y-28">
        <button 
          on:click={() => document.getElementById('home')?.scrollIntoView({behavior: 'smooth'})} 
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            Ana Sayfa
          </div>
        </button>
        
        <button 
          on:click={() => document.getElementById('about')?.scrollIntoView({behavior: 'smooth'})} 
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            Hakkımda
          </div>
        </button>
        
        <button 
          on:click={() => document.getElementById('projects')?.scrollIntoView({behavior: 'smooth'})} 
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            Projeler
          </div>
        </button>
        
        <button 
          on:click={() => document.getElementById('contact')?.scrollIntoView({behavior: 'smooth'})} 
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            İletişim
          </div>
        </button>
      </div>
    </div>
  </div>

  <!-- Right Vertical Social Links -->
  <div class="absolute right-8 top-8 z-20 hidden lg:block">
    <div class="flex flex-col space-y-16">
      <!-- Empty Space for Profile Picture Alignment -->
      <div class="flex justify-center">
        <div class="w-16 h-16"></div>
      </div>
      
      <!-- Social Media Links Section -->
      <div class="flex flex-col space-y-28">
        <!-- GitHub -->
        <a 
          href="https://github.com" 
          target="_blank" 
          rel="noopener noreferrer"
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            GitHub
          </div>
        </a>
        
        <!-- LinkedIn -->
        <a 
          href="https://linkedin.com" 
          target="_blank" 
          rel="noopener noreferrer"
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            LinkedIn
          </div>
        </a>
        
        <!-- Twitter -->
        <a 
          href="https://twitter.com" 
          target="_blank" 
          rel="noopener noreferrer"
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            Twitter
          </div>
        </a>
        
        <!-- Instagram -->
        <a 
          href="https://instagram.com" 
          target="_blank" 
          rel="noopener noreferrer"
          class="group text-white/60 hover:text-white transition-all duration-300"
        >
          <div class="text-lg font-light tracking-wider transform rotate-90 origin-center whitespace-nowrap">
            Instagram
          </div>
        </a>
      </div>
    </div>
  </div>
  
  <div class="hero-content text-center text-white relative z-10">
    <div class="max-w-5xl">
    
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
  

</section>
