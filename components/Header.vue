<template>
  <header class="w-full bg-black text-gray-900 shadow-sm fixed top-0 z-40">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
      <!-- Логотип -->
    <div class="text-2xl font-serif tracking-wide">
        <span class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] bg-clip-text text-transparent">Maison Luxe </span>
        <span class="text-white">Catering</span>
    </div>

      <!-- Навигация -->
      <nav class="hidden md:flex space-x-8 text-base font-medium text-white">
        <a href="#services" class="hover:text-primary transition">Услуги</a>
        <a href="#menu" class="hover:text-primary transition">Меню</a>
        <a href="#chef" class="hover:text-primary transition">Шеф-повара</a>
        <a href="#review" class="hover:text-primary transition">Отзывы</a>
        <a href="#about" class="hover:text-primary transition">О нас</a>
        <a href="#contact" class="hover:text-primary transition">Контакты</a>
      </nav>


      <!-- Мобильное меню -->
      <div class="md:hidden">
        <button @click="toggleMobileMenu">
          <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>
    </div>
  </header>
</template>

<script setup>
const toggleMobileMenu = () => {
  // можно реализовать drawer-меню
}
</script>
