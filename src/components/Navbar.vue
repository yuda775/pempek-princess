<template>
  <div class="navbar bg-white fixed top z-10 shadow-md">
    <div class="navbar-start">
      <div class="dropdown">
        <label tabindex="0" class="btn btn-ghost lg:hidden">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" />
          </svg>
        </label>
        <ul tabindex="0" class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-white rounded-box w-52">
          <li><a>Beranda</a></li>
          <li><a>Tentang Kami</a></li>
          <li><a>Menu</a></li>
          <li class="lg:hidden  py-1 rounded-lg bg-amber-400 text-center text-white font-bold"><a>Kontak</a></li>
        </ul>
      </div>
      <div class="lg:ml-10">
        <img src="../../public/images/brand-logo.png" alt="brand-logo" width="125">
      </div>
    </div>
    <div class="navbar-end hidden lg:flex">
      <ul class="menu menu-horizontal px-1 text-gray-700 font-semibold">
        <li><a>Beranda</a></li>
        <li><a>Tentang Kami</a></li>
        <li><a>Menu</a></li>
        <li><a class="px-5 rounded-lg bg-amber-400 text-white font-bold">Kontak</a></li>
      </ul>
    </div>
  </div>
</template>
