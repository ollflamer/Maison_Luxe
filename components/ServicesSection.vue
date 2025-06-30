<template>
  <section class="bg-white py-20 px-4 text-black">
    <div class="max-w-7xl mx-auto text-center">
      <!-- Заголовок с градиентом -->
      <h2 class="text-4xl md:text-6xl font-serif font-bold mb-6 bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] bg-clip-text text-transparent">
        Наши услуги
      </h2>
      <p class="text-lg md:text-xl text-gray-700 max-w-3xl mx-auto mb-16">
        Полный спектр премиальных кейтеринговых услуг для самых взыскательных клиентов. От интимных ужинов до грандиозных торжеств
      </p>

      <!-- Крупные карточки -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16 text-left">
        <!-- Карточка 1 -->
        <div class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] p-[1px] rounded-md shadow-xl">
          <div class="bg-white p-8 rounded-md h-full flex flex-col gap-y-4 text-gray-600">
            <img src="/icons/services/corporate.png" alt="Корпоративные мероприятия" class="w-20 h-20 mx-auto mt-4" />
            <h3 class="text-2xl  font-serif text-center text-black">Корпоративные мероприятия</h3>
            <p class="text-[#4B5563] text-sm leading-relaxed">
              Деловые завтраки, презентации, корпоративы и конференции. Профессиональный сервис для бизнес-событий любого масштаба.
            </p>
            <ul class="text-[#4B5563] text-sm list-disc pl-5 space-y-1">
              <li>Бизнес-ланчи и фуршеты</li>
              <li>Корпоративные банкеты</li>
              <li>Кофе-брейки и презентации</li>
              <li>VIP-обслуживание руководства</li>
            </ul>
          </div>
        </div>

        <!-- Карточка 2 -->
        <div class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] p-[1px] rounded-md shadow-xl">
          <div class="bg-white p-8 rounded-md h-full flex flex-col gap-y-4 text-gray-600">
            <img src="/icons/services/wedding.png" alt="Свадьбы и торжества" class="w-20 h-20 mx-auto mt-4" />
            <h3 class="text-2xl font-serif text-center text-black">Свадьбы и торжества</h3>
            <p class="text-[#4B5563] text-sm leading-relaxed">
              Деловые завтраки, презентации, корпоративы и конференции. Профессиональный сервис для бизнес-событий любого масштаба.
            </p>
            <ul class="text-[#4B5563] text-sm list-disc pl-5 space-y-1">
              <li>Бизнес-ланчи и фуршеты</li>
              <li>Корпоративные банкеты</li>
              <li>Кофе-брейки и презентации</li>
              <li>VIP-обслуживание руководства</li>
            </ul>
          </div>
        </div>

        <!-- Карточка 3 -->
        <div class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] p-[1px] rounded-md shadow-xl">
          <div class="bg-white p-8 rounded-md h-full flex flex-col gap-y-4 text-gray-600">
            <img src="/icons/services/private.png" alt="Частные мероприятия" class="w-20 h-20 mx-auto mt-4" />
            <h3 class="text-2xl font-serif text-center text-black">Частные мероприятия</h3>
            <p class="text-[#4B5563] text-sm leading-relaxed">
              Деловые завтраки, презентации, корпоративы и конференции. Профессиональный сервис для бизнес-событий любого масштаба.
            </p>
            <ul class="text-[#4B5563] text-sm list-disc pl-5 space-y-1">
              <li>Бизнес-ланчи и фуршеты</li>
              <li>Корпоративные банкеты</li>
              <li>Кофе-брейки и презентации</li>
              <li>VIP-обслуживание руководства</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Маленькие карточки -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-4">
        <!-- Сомелье сервис -->
        <div class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] p-[0.5px] rounded-xl">
          <div class="bg-white py-4 px-4 rounded-xl flex flex-col items-center space-y-2 text-center">
            <img src="/icons/services/sommelier.png" alt="Сомелье сервис" class="mt-4" />
            <h4 class="text-sm font-semibold font-serif leading-tight">Сомелье сервис</h4>
            <p class="text-xs text-[#4B5563]">Подбор вин и напитков</p>
          </div>
        </div>

        <!-- Декор -->
        <div class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] p-[0.5px] rounded-xl">
          <div class="bg-white py-4 px-4 rounded-xl flex flex-col items-center space-y-2 text-center">
            <img src="/icons/services/decor.png" alt="Декор" class="mt-4" />
            <h4 class="text-sm font-semibold font-serif leading-tight">Декор</h4>
            <p class="text-xs text-[#4B5563]">Подбор вин и напитков</p>
          </div>
        </div>

        <!-- Выездной кейтринг -->
        <div class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] p-[0.5px] rounded-xl">
          <div class="bg-white py-4 px-4 rounded-xl flex flex-col items-center space-y-2 text-center">
            <img src="/icons/services/catering.png" alt="Выездной кейтринг" class="mt-4" />
            <h4 class="text-sm font-semibold font-serif leading-tight">Выездной кейтринг</h4>
            <p class="text-xs text-[#4B5563]">Подбор вин и напитков</p>
          </div>
        </div>

        <!-- Шеф на дом -->
        <div class="bg-gradient-to-r from-[#D4AF37] via-[#F7E98E] to-[#B8860B] p-[0.5px] rounded-xl">
          <div class="bg-white py-4 px-4 rounded-xl flex flex-col items-center space-y-2 text-center">
            <img src="/icons/services/chef.png" alt="Шеф на дом" class="mt-4" />
            <h4 class="text-sm font-semibold font-serif leading-tight">Шеф на дом</h4>
            <p class="text-xs text-[#4B5563]">Подбор вин и напитков</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
