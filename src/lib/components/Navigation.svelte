<!-- Navigation -->
<nav class="navbar bg-base-100 shadow-lg fixed top-0 z-50">
  <div class="navbar-start">
    <button on:click={() => document.getElementById('home')?.scrollIntoView({behavior: 'smooth'})} class="btn btn-ghost text-xl font-bold">Portföy</button>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal px-1">
      <li><button on:click={() => document.getElementById('home')?.scrollIntoView({behavior: 'smooth'})} class="btn btn-ghost">Ana Sayfa</button></li>
      <li><button on:click={() => document.getElementById('about')?.scrollIntoView({behavior: 'smooth'})} class="btn btn-ghost">Hakkımda</button></li>
      <li><button on:click={() => document.getElementById('projects')?.scrollIntoView({behavior: 'smooth'})} class="btn btn-ghost">Projeler</button></li>
      <li><button on:click={() => document.getElementById('contact')?.scrollIntoView({behavior: 'smooth'})} class="btn btn-ghost">İletişim</button></li>
    </ul>
  </div>
  <div class="navbar-end">
    <div class="dropdown dropdown-end">
      <button class="btn btn-ghost lg:hidden" aria-label="Menüyü aç">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
        </svg>
      </button>
      <ul class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52">
        <li><button on:click={() => document.getElementById('home')?.scrollIntoView({behavior: 'smooth'})}>Ana Sayfa</button></li>
        <li><button on:click={() => document.getElementById('about')?.scrollIntoView({behavior: 'smooth'})}>Hakkımda</button></li>
        <li><button on:click={() => document.getElementById('projects')?.scrollIntoView({behavior: 'smooth'})}>Projeler</button></li>
        <li><button on:click={() => document.getElementById('contact')?.scrollIntoView({behavior: 'smooth'})}>İletişim</button></li>
      </ul>
    </div>
  </div>
</nav>
