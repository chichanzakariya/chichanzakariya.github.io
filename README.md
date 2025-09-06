<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محسن شيشان | صباغ محترف</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        .section-header {
            position: relative;
            text-align: center;
            padding-bottom: 2rem;
            margin-bottom: 2rem;
        }
        .section-header:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background-color: #f97316;
            border-radius: 999px;
        }
        .card-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 0.5rem;
        }
    </style>
</head>
<body class="bg-gray-100">

    <!-- Header Section -->
    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-4 py-6 flex flex-col md:flex-row justify-between items-center text-center md:text-right">
            <h1 class="text-3xl font-bold text-gray-800">محسن شيشان</h1>
            <nav class="mt-4 md:mt-0">
                <a href="#about" class="mx-2 text-gray-600 hover:text-orange-500 transition-colors duration-300 font-semibold">من أنا</a>
                <a href="#portfolio" class="mx-2 text-gray-600 hover:text-orange-500 transition-colors duration-300 font-semibold">أعمالي</a>
                <a href="#contact" class="mx-2 text-gray-600 hover:text-orange-500 transition-colors duration-300 font-semibold">تواصل معي</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-orange-500 text-white py-20 px-4 text-center">
        <div class="container mx-auto">
            <h2 class="text-5xl md:text-6xl font-extrabold leading-tight mb-4 animate-fade-in-down">
                أعمال دهان احترافية لمنزلك
            </h2>
            <p class="text-lg md:text-xl font-medium mb-8">
                نحول رؤيتك إلى واقع بأفضل جودة ودقة.
            </p>
            <a href="#contact" class="bg-white text-orange-500 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-100 transition-all duration-300">
                اطلب خدمة الآن
            </a>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="py-20 px-4">
        <div class="container mx-auto text-center md:text-right">
            <div class="section-header">
                <h3 class="text-4xl font-bold text-gray-800 mb-2">من أنا</h3>
                <p class="text-gray-500">خبرة أكثر من 20 عاماً في مجال الدهان</p>
            </div>
            <div class="bg-white rounded-xl shadow-lg p-8 transform transition-transform duration-500 hover:scale-105">
                <p class="text-gray-700 text-lg leading-relaxed">
                    أنا محسن شيشان، صباغ محترف متخصص في جميع أنواع الدهانات الداخلية والخارجية.
                    أقدم خدماتي للمنازل، المكاتب، والمحلات التجارية.
                    هدفي هو تقديم عمل فني متقن يرضي العميل ويضيف لمسة جمالية تدوم طويلاً.
                    أعمل بدقة عالية وألتزم بالمواعيد المحددة، مع استخدام أفضل أنواع الدهانات وأحدث التقنيات.
                </p>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-20 px-4 bg-gray-50">
        <div class="container mx-auto text-center md:text-right">
            <div class="section-header">
                <h3 class="text-4xl font-bold text-gray-800 mb-2">أعمالي</h3>
                <p class="text-gray-500">جولة في بعض المشاريع التي قمت بها</p>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition-transform duration-300 hover:scale-105">
                    <img src="https://placehold.co/600x400/FFA500/FFFFFF?text=قبل" onerror="this.src='https://placehold.co/600x400/f3f4f6/374151?text=صورة+غير+متوفرة';" alt="صورة عمل قبل الدهان" class="card-image">
                    <div class="p-6">
                        <h4 class="text-xl font-bold text-gray-800 mb-2">دهان شقة سكنية - تصميم عصري</h4>
                        <p class="text-gray-600">استخدام ألوان فاتحة لإعطاء شعور بالاتساع والنظافة.</p>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition-transform duration-300 hover:scale-105">
                    <img src="https://placehold.co/600x400/FFA500/FFFFFF?text=بعد" onerror="this.src='https://placehold.co/600x400/f3f4f6/374151?text=صورة+غير+متوفرة';" alt="صورة عمل بعد الدهان" class="card-image">
                    <div class="p-6">
                        <h4 class="text-xl font-bold text-gray-800 mb-2">تجديد مكتب تجاري</h4>
                        <p class="text-gray-600">دهانات سريعة الجفاف ومناسبة للبيئة التجارية.</p>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transform transition-transform duration-300 hover:scale-105">
                    <img src="https://placehold.co/600x400/FFA500/FFFFFF?text=تفاصيل" onerror="this.src='https://placehold.co/600x400/f3f4f6/374151?text=صورة+غير+متوفرة';" alt="صورة عمل بعد الدهان" class="card-image">
                    <div class="p-6">
                        <h4 class="text-xl font-bold text-gray-800 mb-2">أعمال دهان خارجية - فيلا</h4>
                        <p class="text-gray-600">دهانات مقاومة للعوامل الجوية وتدوم طويلاً.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-4">
        <div class="container mx-auto text-center md:text-right">
            <div class="section-header">
                <h3 class="text-4xl font-bold text-gray-800 mb-2">تواصل معي</h3>
                <p class="text-gray-500">يسعدني الرد على استفساراتك وتقديم عرض سعر مجاني</p>
            </div>
            <div class="bg-white rounded-xl shadow-lg p-8">
                <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-8 md:space-x-reverse">
                    <div class="flex items-center space-x-2 space-x-reverse text-gray-700">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-orange-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.948V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                        </svg>
                        <a href="tel:0661667489" class="text-lg font-medium hover:underline">0661667489</a>
                    </div>
                    <div class="flex items-center space-x-2 space-x-reverse text-gray-700">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-orange-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                        </svg>
                        <a href="mailto:contact@muhsinshishan.com" class="text-lg font-medium hover:underline">contact@muhsinshishan.com</a>
                    </div>
                </div>
                <p class="mt-8 text-gray-600">
                    <span class="font-bold">الموقع:</span> وادي زم، المغرب
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6 mt-12 text-center">
        <div class="container mx-auto px-4">
            <p>&copy; 2024 محسن شيشان | جميع الحقوق محفوظة</p>
        </div>
    </footer>

</body>
</html>
