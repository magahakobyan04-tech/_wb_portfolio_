<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ПОРТФОЛИО – Маргарита Акопян</title>
    <!-- Подключение Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome для иконок -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" xintegrity="sha512-iecdL5vS6cI1lVjT/k4oX3+Qx9E1g7z9r7/B6w6dK2x9o5qWw1Jd2Wq5e2+0b8gJgQ+w5yBq0z+g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f5;
            color: #2c2c2c;
            scroll-behavior: smooth;
        }
        .portfolio-page {
            min-height: 100vh;
            width: 100%;
            padding: 4rem 1rem;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            box-sizing: border-box;
        }
        .premium-frame {
            box-shadow: 0 20px 40px -10px rgba(0, 0, 0, 0.1), 0 0 0 1px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .premium-frame:hover {
            transform: translateY(-5px);
            box-shadow: 0 30px 60px -15px rgba(0, 0, 0, 0.15), 0 0 0 1px rgba(0, 0, 0, 0.08);
        }
        .cover-gradient {
            background: linear-gradient(180deg, #f7f7f5 0%, #e8e8e6 100%);
        }
    </style>
</head>
<body>

    <!-- 1. Титульная страница -->
    <section id="cover" class="portfolio-page cover-gradient text-center p-8">
        <div class="max-w-4xl w-full">
            <div class="relative mx-auto w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden shadow-2xl shadow-neutral-400 mb-8">
                <img src="data:image/jpeg;base64,uploaded:IMG_8440.jpeg-ab4530ed-1501-4f51-8e56-b136125b4f4a" 
                     alt="Портрет Маргариты Акопян в стиле high-fashion" 
                     class="object-cover w-full h-full filter brightness-105"
                />
                <div class="absolute inset-0 bg-white/10 mix-blend-overlay"></div>
            </div>
            <h1 class="text-4xl sm:text-6xl md:text-7xl font-extrabold tracking-tight mb-4 text-neutral-800" style="text-shadow: 1px 1px 2px rgba(0,0,0,0.05);">
                ПОРТФОЛИО
            </h1>
            <h2 class="text-xl sm:text-3xl md:text-4xl font-light tracking-wider uppercase text-neutral-600 border-b-2 border-neutral-300 pb-2 inline-block">
                Маргарита Акопян
            </h2>
            <p class="mt-8 text-lg md:text-xl font-medium text-neutral-500">
                ГРАФИЧЕСКИЙ ДИЗАЙН | ПРОДАЮЩАЯ ИНФОГРАФИКА ДЛЯ WILDBERRIES & OZON
            </p>
        </div>
    </section>

    <!-- 2. Раздел "Обо мне" -->
    <section id="about" class="portfolio-page bg-white p-8">
        <div class="max-w-5xl w-full grid md:grid-cols-3 gap-8 items-center">
            <div class="md:col-span-1 flex justify-center md:justify-start">
                <div class="w-48 h-48 rounded-lg overflow-hidden premium-frame shadow-neutral-200">
                     <img src="data:image/jpeg;base64,uploaded:IMG_8440.jpeg-ab4530ed-1501-4f51-8e56-b136125b4f4a" 
                          alt="Маленький портрет Маргариты" 
                          class="object-cover w-full h-full"
                    />
                </div>
            </div>
            <div class="md:col-span-2 text-left">
                <h2 class="text-4xl font-bold mb-6 text-neutral-800 border-b-2 border-neutral-300 pb-2">Обо мне</h2>
                <p class="text-lg leading-relaxed text-neutral-700">
                    Я – Маргарита Акопян, графический дизайнер, специализирующийся на создании продающей инфографики для Wildberries и Ozon. Моя главная задача – превратить ваш продукт в визуальный бестселлер, используя принципы минимализма, премиального стиля и чистой композиции. За годы работы я разработала сотни карточек, которые стабильно повышают конверсию и выделяют товар среди конкурентов. Я работаю быстро, четко и нацелена на результат, который вы увидите в своих продажах.
                </p>
            </div>
        </div>
    </section>

    <!-- 3. Раздел "Что я делаю" - Часть 1 -->
    <section id="work-1" class="portfolio-page bg-neutral-50 p-8">
        <div class="max-w-6xl w-full">
            <h2 class="text-4xl font-bold mb-12 text-center text-neutral-800 border-b-2 border-neutral-300 pb-2 inline-block">Что я делаю: Премиальные решения</h2>
            <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-white rounded-xl overflow-hidden premium-frame shadow-neutral-300">
                    <img src="data:image/jpeg;base64,uploaded:IMG_8386.jpeg-36650f1b-8c71-4fa0-b254-44b2c7056904" 
                         alt="Инфографика: Диффузор" 
                         class="w-full h-auto object-cover rounded-t-xl"
                    />
                    <p class="p-4 text-sm font-semibold text-center text-neutral-600">Ароматический диффузор</p>
                </div>
                <div class="bg-white rounded-xl overflow-hidden premium-frame shadow-neutral-300">
                    <img src="data:image/jpeg;base64,uploaded:IMG_8394.jpg-69d9d9b9-79fb-4b24-9b50-6c3229c3cdb4" 
                         alt="Инфографика: Сыворотка (Serum)" 
                         class="w-full h-auto object-cover rounded-t-xl"
                    />
                    <p class="p-4 text-sm font-semibold text-center text-neutral-600">Косметическая сыворотка</p>
                </div>
                <div class="bg-white rounded-xl overflow-hidden premium-frame shadow-neutral-300">
                    <img src="data:image/jpeg;base64,uploaded:IMG_8395.jpg-27eac396-674d-46bc-9dfb-f8d7a182f29a" 
                         alt="Инфографика: Топор" 
                         class="w-full h-auto object-cover rounded-t-xl"
                    />
                    <p class="p-4 text-sm font-semibold text-center text-neutral-600">Универсальный топор</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Раздел "Что я делаю" - Часть 2 -->
    <section id="work-2" class="portfolio-page bg-neutral-50 p-8 pt-0">
        <div class="max-w-6xl w-full">
             <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-white rounded-xl overflow-hidden premium-frame shadow-neutral-300">
                    <img src="data:image/jpeg;base64,uploaded:IMG_8366.jpeg-f3fa6a06-b598-4bcb-b33a-6bfee79de0b0" 
                         alt="Инфографика: Наушники" 
                         class="w-full h-auto object-cover rounded-t-xl"
                    />
                    <p class="p-4 text-sm font-semibold text-center text-neutral-600">Беспроводные наушники</p>
                </div>
                 <div class="bg-white rounded-xl overflow-hidden premium-frame shadow-neutral-300">
                    <img src="data:image/jpeg;base64,uploaded:IMG_8436.jpeg-fd896665-ffef-4794-8bec-b8625ae44f9a" 
                         alt="Инфографика: Танграм" 
                         class="w-full h-auto object-cover rounded-t-xl"
                    />
                    <p class="p-4 text-sm font-semibold text-center text-neutral-600">Деревянный танграм</p>
                </div>
                <div class="bg-white rounded-xl overflow-hidden premium-frame shadow-neutral-300">
                    <img src="data:image/jpeg;base64,uploaded:IMG_8393.jpg-40a18f94-3c62-42aa-bfd7-85b473e08bbc" 
                         alt="Инфографика: Форма для выпечки" 
                         class="w-full h-auto object-cover rounded-t-xl"
                    />
                    <p class="p-4 text-sm font-semibold text-center text-neutral-600">Форма для выпечки</p>
                </div>
            </div>
            <div class="mt-10 md:mt-16 text-center">
                <div class="w-full max-w-lg mx-auto bg-neutral-200/50 rounded-xl p-8 border-2 border-dashed border-neutral-300">
                    <p class="text-xl font-medium text-neutral-500">
                        Ваше инфографическое изображение здесь
                    </p>
                    <p class="text-sm text-neutral-400 mt-2">
                        Чистый макет с бликами и тенью
                    </p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- 5. Раздел "Мой стиль" -->
    <section id="style" class="portfolio-page bg-white p-8">
        <div class="max-w-5xl w-full text-center">
            <h2 class="text-4xl font-bold mb-10 text-neutral-800 border-b-2 border-neutral-300 pb-2 inline-block">Мой стиль: Премиум-Минимализм</h2>
            <p class="text-lg leading-relaxed mb-10 text-neutral-700">
                Мой подход к дизайну инфографики основан на трех принципах:
            </p>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="p-6 rounded-xl bg-yellow-50/70 border border-yellow-100 shadow-md shadow-yellow-100">
                    <div class="text-3xl text-yellow-700 mb-3">
                        <i class="fa-solid fa-gem"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-neutral-800">Премиум-Минимализм</h3>
                    <p class="text-neutral-600 text-sm">
                        Исключительно чистые композиции, где каждый элемент работает на продажу. Ничего лишнего, только акценты на ключевых преимуществах.
                    </p>
                </div>
                <div class="p-6 rounded-xl bg-yellow-50/70 border border-yellow-100 shadow-md shadow-yellow-100">
                    <div class="text-3xl text-yellow-700 mb-3">
                        <i class="fa-solid fa-lightbulb"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-neutral-800">Профессиональное Освещение</h3>
                    <p class="text-neutral-600 text-sm">
                        Использование мягких теней, бликов и правильной цветокоррекции для придания продукту роскошного, дорогого вида.
                    </p>
                </div>
                <div class="p-6 rounded-xl bg-yellow-50/70 border border-yellow-100 shadow-md shadow-yellow-100">
                    <div class="text-3xl text-yellow-700 mb-3">
                        <i class="fa-solid fa-list-ol"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-neutral-800">Читаемость и Иерархия</h3>
                    <p class="text-neutral-600 text-sm">
                        Быстрое донесение информации с помощью современных шрифтов и продуманной визуальной иерархии, которая ведет взгляд покупателя.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. Раздел "Почему выбирают меня" -->
    <section id="why" class="portfolio-page bg-neutral-50 p-8">
        <div class="max-w-4xl w-full">
            <h2 class="text-4xl font-bold mb-10 text-center text-neutral-800 border-b-2 border-neutral-300 pb-2 inline-block">Почему выбирают меня</h2>
            <div class="grid gap-6">
                <div class="flex items-center p-5 rounded-xl bg-neutral-100 shadow-lg border-l-4 border-yellow-600">
                    <div class="text-2xl text-yellow-600 mr-4 w-8 text-center"><i class="fa-solid fa-bolt"></i></div>
                    <div>
                        <h3 class="text-xl font-semibold text-neutral-800">Быстрое выполнение</h3>
                        <p class="text-neutral-600">Выполнение проектов в кратчайшие сроки без потери качества. Ваше время – мой приоритет.</p>
                    </div>
                </div>
                <div class="flex items-center p-5 rounded-xl bg-neutral-100 shadow-lg border-l-4 border-yellow-600">
                    <div class="text-2xl text-yellow-600 mr-4 w-8 text-center"><i class="fa-solid fa-sack-dollar"></i></div>
                    <div>
                        <h3 class="text-xl font-semibold text-neutral-800">Премиальный продающий стиль</h3>
                        <p class="text-neutral-600">Дизайн, который не просто красив, а действительно повышает конверсию и выделяет ваш товар.</p>
                    </div>
                </div>
                <div class="flex items-center p-5 rounded-xl bg-neutral-100 shadow-lg border-l-4 border-yellow-600">
                    <div class="text-2xl text-yellow-600 mr-4 w-8 text-center"><i class="fa-solid fa-ruler-combined"></i></div>
                    <div>
                        <h3 class="text-xl font-semibold text-neutral-800">Аккуратность и безупречность</h3>
                        <p class="text-neutral-600">Внимание к деталям: идеальное выравнивание, чистые фоны, безупречная ретушь продукта.</p>
                    </div>
                </div>
                <div class="flex items-center p-5 rounded-xl bg-neutral-100 shadow-lg border-l-4 border-yellow-600">
                    <div class="text-2xl text-yellow-600 mr-4 w-8 text-center"><i class="fa-solid fa-comments"></i></div>
                    <div>
                        <h3 class="text-xl font-semibold text-neutral-800">Отличная коммуникация</h3>
                        <p class="text-neutral-600">Отличное понимание задачи и оперативная обратная связь на всех этапах работы.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- 7. Раздел "Контакты" -->
    <section id="contact" class="portfolio-page bg-white p-8">
        <div class="max-w-xl w-full text-center">
            <h2 class="text-4xl font-bold mb-10 text-neutral-800 border-b-2 border-neutral-300 pb-2 inline-block">Свяжитесь со мной</h2>
            <p class="text-lg mb-8 text-neutral-600">
                Готовы создать бестселлер? Напишите мне!
            </p>
            <div class="flex flex-col items-center space-y-6 text-center p-8 bg-neutral-50 rounded-xl premium-frame shadow-neutral-200">
                <div class="flex items-center justify-center">
                    <div class="text-4xl text-yellow-600 w-12"><i class="fa-brands fa-instagram"></i></div>
                    <div class="ml-4 text-left">
                        <p class="text-base uppercase font-semibold text-neutral-500">Instagram</p>
                        <a href="https://instagram.com/_wb_infografika_" class="text-2xl font-bold text-neutral-800 hover:text-yellow-600 transition">@_wb_infografika_</a>
                    </div>
                </div>
            </div>
            <p class="mt-16 text-sm text-neutral-400">© 2025 Портфолио Маргариты Акопян. Все права защищены.</p>
        </div>
    </section>

</body>
</html>
