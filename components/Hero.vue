<template>
  <section
    id="home"
    class="relative h-screen bg-cover bg-center flex items-center justify-center text-white"
    :style="{
      backgroundImage: 'url(/hero-bg.jpg)',
    }"
  >
    <!-- затемнение -->
    <div class="absolute inset-0 bg-black bg-opacity-50"></div>

    <!-- контент -->
    <div class="relative z-10 text-center px-4">
      <h1 class="text-4xl md:text-6xl font-serif mb-2 bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] bg-clip-text text-transparent">
        Maison Luxe
      </h1>
      <h2 class="text-3xl md:text-5xl font-serif text-white mb-6">
        Catering
      </h2>

      <p class="text-lg md:text-2xl font-light mb-8 max-w-3xl mx-auto">
        Изысканный кейтеринг премиум-класса для особых моментов. Мы создаем
        незабываемые кулинарные шедевры для ваших торжеств, деловых мероприятий и
        эксклюзивных событий.
      </p>

      <!-- Кнопки -->
      <div class="flex flex-col md:flex-row items-center justify-center gap-4">
        <a
          href="#menu"
          class="relative inline-block group p-[2px] bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] transition"
        >
          <span
            class="block px-8 py-3 bg-transparent text-black group-hover:bg-white group-hover:text-black transition"
          >
            Посмотреть меню
          </span>
        </a>

        <a
          href="#contact"
          class="relative inline-block group p-[2px] bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] transition"
        >
          <span
            class="block px-8 py-3 bg-black text-white group-hover:bg-opacity-80 transition"
          >
            Заказать мероприятие
          </span>
        </a>
      </div>

      <!-- Иконки с подписями -->
      <div class="mt-10 flex flex-col md:flex-row items-center justify-center gap-8 max-w-5xl mx-auto">
        <!-- Item 1 -->
        <div class="flex items-center gap-4 text-left">
          <img src="/icons/Star.png" alt="Мишленовские повара" class="w-10 h-10 object-contain" />
          <span class="text-white text-lg font-light">Мишленовские повара</span>
        </div>

        <!-- Item 2 -->
        <div class="flex items-center gap-4 text-left">
          <img src="/icons/Mark.png" alt="Премиум продукты" class="w-10 h-10 object-contain" />
          <span class="text-white text-lg font-light">Премиум продукты</span>
        </div>

        <!-- Item 3 -->
        <div class="flex items-center gap-4 text-left">
          <img src="/icons/Mr.png" alt="Эксклюзивный сервис" class="w-10 h-10 object-contain" />
          <span class="text-white text-lg font-light">Эксклюзивный сервис</span>
        </div>
      </div>
    </div>
  </section>
</template>
