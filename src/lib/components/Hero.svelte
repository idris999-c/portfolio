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
    
 
    </div>
  </div>

</section>