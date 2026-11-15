<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>dry for you | İzmir Kuru Temizleme ve Terzi</title>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- FontAwesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            900: '#1e3a8a',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        html {
            scroll-behavior: smooth;
        }
        .hero-pattern {
            background-color: #eff6ff;
            background-image: radial-gradient(#3b82f6 0.5px, transparent 0.5px), radial-gradient(#3b82f6 0.5px, #eff6ff 0.5px);
            background-size: 20px 20px;
            background-position: 0 0, 10px 10px;
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-gray-50 flex flex-col min-h-screen antialiased">

    <!-- Navigation -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex-shrink-0 flex items-center">
                    <a href="#" class="text-3xl font-bold text-brand-600 tracking-tighter lowercase">
                        <i class="fa-solid fa-shirt mr-2"></i>dry for you.
                    </a>
                </div>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-8">
                    <a href="#hizmetlerimiz" class="text-gray-600 hover:text-brand-600 font-medium transition-colors">Hizmetlerimiz</a>
                    <a href="#subelerimiz" class="text-gray-600 hover:text-brand-600 font-medium transition-colors">Şubelerimiz</a>
                    <a href="#iletisim" class="text-gray-600 hover:text-brand-600 font-medium transition-colors">İletişim</a>
                </div>

                <div class="hidden md:flex">
                    <a href="#iletisim" class="bg-brand-600 text-white px-6 py-2.5 rounded-full font-medium hover:bg-brand-700 transition-colors shadow-md hover:shadow-lg">
                        Fiyat Alın
                    </a>
                </div>

                <!-- Mobile menu button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-gray-600 hover:text-brand-600 focus:outline-none">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Panel -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-gray-100">
            <div class="px-4 pt-2 pb-6 space-y-2">
                <a href="#hizmetlerimiz" class="block px-3 py-2 text-base font-medium text-gray-700 hover:bg-brand-50 hover:text-brand-600 rounded-md">Hizmetlerimiz</a>
                <a href="#subelerimiz" class="block px-3 py-2 text-base font-medium text-gray-700 hover:bg-brand-50 hover:text-brand-600 rounded-md">Şubelerimiz</a>
                <a href="#iletisim" class="block px-3 py-2 text-base font-medium text-gray-700 hover:bg-brand-50 hover:text-brand-600 rounded-md">İletişim</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-pattern relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 lg:py-32 flex flex-col lg:flex-row items-center relative z-10">
            <div class="lg:w-1/2 text-center lg:text-left pr-0 lg:pr-12">
                <span class="text-brand-600 font-semibold tracking-wide uppercase text-sm mb-4 block">İzmir'in Güvenilir Terzisi</span>
                <h1 class="text-4xl sm:text-5xl md:text-6xl font-extrabold text-gray-900 leading-tight mb-6">
                    Kıyafetlerinize hak ettiği <span class="text-brand-600">özeni</span> gösterin.
                </h1>
                <p class="text-lg sm:text-xl text-gray-600 mb-8 max-w-2xl mx-auto lg:mx-0">
                    Kusursuz temizlik ve usta terzilik bir arada. İzmir'de 3 şubemizle kıyafetlerinizi ilk günkü gibi yeniliyor, size özel hale getiriyoruz.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
                    <a href="#subelerimiz" class="bg-brand-600 text-white px-8 py-4 rounded-full font-semibold text-lg hover:bg-brand-700 transition-colors shadow-lg hover:shadow-xl text-center">
                        En Yakın Şubeyi Bul
                    </a>
                    <a href="#iletisim" class="bg-white text-brand-600 border-2 border-brand-600 px-8 py-4 rounded-full font-semibold text-lg hover:bg-brand-50 transition-colors text-center">
                        Bize Ulaşın
                    </a>
                </div>
            </div>
            <div class="lg:w-1/2 mt-16 lg:mt-0 relative">
                <!-- Decorative Image -->
                <div class="relative rounded-2xl overflow-hidden shadow-2xl border-4 border-white">
                    <img src="https://images.unsplash.com/photo-1582735689369-4fe89db7114c?auto=format&fit=crop&q=80&w=1000" alt="Kuru Temizleme ve Terzi" class="w-full h-auto object-cover" onerror="this.src='https://placehold.co/1000x800/3b82f6/ffffff?text=Kuru+Temizleme+Gorseli'">
                    <div class="absolute inset-0 bg-gradient-to-t from-brand-900/40 to-transparent"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="hizmetlerimiz" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-brand-600 font-semibold tracking-wide uppercase text-sm mb-2">Uzmanlık Alanımız</h2>
                <h3 class="text-3xl sm:text-4xl font-bold text-gray-900 mb-4">Size Nasıl Yardımcı Olabiliriz?</h3>
                <p class="text-gray-600 text-lg">En hassas kumaşlardan, en zorlu tadilatlara kadar her detayı özenle ele alıyoruz.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-brand-50 rounded-2xl p-8 hover:-translate-y-2 transition-transform duration-300 shadow-sm hover:shadow-md border border-brand-100">
                    <div class="w-16 h-16 bg-white rounded-xl shadow-sm flex items-center justify-center text-brand-600 text-3xl mb-6">
                        <i class="fa-solid fa-soap"></i>
                    </div>
                    <h4 class="text-2xl font-bold text-gray-900 mb-3">Kuru Temizleme</h4>
                    <p class="text-gray-600">Takım elbiseler, ipek gömlekler ve gelinlikler... Hassas kumaşlarınız zarar görmeden, lekelerden tamamen arındırılarak temizlenir.</p>
                </div>

                <!-- Service 2 -->
                <div class="bg-brand-50 rounded-2xl p-8 hover:-translate-y-2 transition-transform duration-300 shadow-sm hover:shadow-md border border-brand-100">
                    <div class="w-16 h-16 bg-white rounded-xl shadow-sm flex items-center justify-center text-brand-600 text-3xl mb-6">
                        <i class="fa-solid fa-scissors"></i>
                    </div>
                    <h4 class="text-2xl font-bold text-gray-900 mb-3">Terzi & Tadilat</h4>
                    <p class="text-gray-600">Paça boyu, daraltma, fermuar değişimi veya özel dikim... Kıyafetlerinizin üzerinize tam oturması için profesyonel terzilik hizmeti.</p>
                </div>

                <!-- Service 3 -->
                <div class="bg-brand-50 rounded-2xl p-8 hover:-translate-y-2 transition-transform duration-300 shadow-sm hover:shadow-md border border-brand-100">
                    <div class="w-16 h-16 bg-white rounded-xl shadow-sm flex items-center justify-center text-brand-600 text-3xl mb-6">
                        <i class="fa-solid fa-temperature-arrow-up"></i>
                    </div>
                    <h4 class="text-2xl font-bold text-gray-900 mb-3">Buharlı Ütüleme</h4>
                    <p class="text-gray-600">Zamanınız size kalsın. Yüksek basınçlı buharlı sistemlerimiz ile kıyafetlerinizi jilet gibi ütülüyor, kullanıma hazır hale getiriyoruz.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Branches Section -->
    <section id="subelerimiz" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-brand-600 font-semibold tracking-wide uppercase text-sm mb-2">Yaygın Ağımız</h2>
                <h3 class="text-3xl sm:text-4xl font-bold text-gray-900 mb-4">İzmir'de 3 Farklı Noktadayız</h3>
                <p class="text-gray-600 text-lg">Size en yakın şubemizi seçerek hizmetlerimizden faydalanmaya başlayın.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Branch 1 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-100 flex flex-col hover:shadow-md transition-shadow">
                    <div class="bg-brand-600 p-8 text-center">
                        <h4 class="text-3xl font-bold text-white tracking-wide">Ataşehir</h4>
                    </div>
                    <div class="p-8 flex flex-col flex-grow">
                        <div class="space-y-4 mb-8 flex-grow">
                            <p class="flex items-start text-gray-600">
                                <i class="fa-solid fa-location-dot mt-1 w-6 text-brand-500 text-lg"></i>
                                <span class="leading-relaxed">Ataşehir Mahallesi 8010 Sokak No:38/A<br>Çiğli / İzmir, Turkey</span>
                            </p>
                            <p class="flex items-center text-gray-600">
                                <i class="fa-solid fa-phone w-6 text-brand-500 text-lg"></i>
                                <span class="font-medium">0535 456 90 78</span>
                            </p>
                        </div>
                        <a href="https://maps.google.com" target="_blank" class="block w-full py-3 px-4 bg-gray-50 hover:bg-brand-50 text-center rounded-xl text-brand-600 font-medium transition-colors border border-gray-100 hover:border-brand-200">
                            Haritada Gör
                        </a>
                    </div>
                </div>

                <!-- Branch 2 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-100 flex flex-col hover:shadow-md transition-shadow">
                    <div class="bg-brand-600 p-8 text-center">
                        <h4 class="text-3xl font-bold text-white tracking-wide">Bayraklı</h4>
                    </div>
                    <div class="p-8 flex flex-col flex-grow">
                        <div class="space-y-4 mb-8 flex-grow">
                            <p class="flex items-start text-gray-600">
                                <i class="fa-solid fa-location-dot mt-1 w-6 text-brand-500 text-lg"></i>
                                <span class="leading-relaxed">İzmir Adalet Sarayı Binası<br>Kapalı Otopark Zemin Kat</span>
                            </p>
                            <p class="flex items-center text-gray-600">
                                <i class="fa-solid fa-phone w-6 text-brand-500 text-lg"></i>
                                <span class="font-medium">0535 456 90 78</span>
                            </p>
                        </div>
                        <a href="https://maps.google.com" target="_blank" class="block w-full py-3 px-4 bg-gray-50 hover:bg-brand-50 text-center rounded-xl text-brand-600 font-medium transition-colors border border-gray-100 hover:border-brand-200">
                            Haritada Gör
                        </a>
                    </div>
                </div>

                <!-- Branch 3 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-100 flex flex-col hover:shadow-md transition-shadow">
                    <div class="bg-brand-600 p-8 text-center">
                        <h4 class="text-3xl font-bold text-white tracking-wide">Mavişehir</h4>
                    </div>
                    <div class="p-8 flex flex-col flex-grow">
                        <div class="space-y-4 mb-8 flex-grow">
                            <p class="flex items-start text-gray-600">
                                <i class="fa-solid fa-location-dot mt-1 w-6 text-brand-500 text-lg"></i>
                                <span class="leading-relaxed">Mavişehir Albayrak 2. Etap<br>İzmir</span>
                            </p>
                            <p class="flex items-center text-gray-600">
                                <i class="fa-solid fa-phone w-6 text-brand-500 text-lg"></i>
                                <span class="font-medium">0535 456 90 78</span>
                            </p>
                        </div>
                        <a href="https://maps.google.com" target="_blank" class="block w-full py-3 px-4 bg-gray-50 hover:bg-brand-50 text-center rounded-xl text-brand-600 font-medium transition-colors border border-gray-100 hover:border-brand-200">
                            Haritada Gör
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="iletisim" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-brand-900 rounded-3xl overflow-hidden shadow-2xl">
                <div class="grid grid-cols-1 lg:grid-cols-2">
                    
                    <!-- Contact Info -->
                    <div class="p-10 md:p-16 text-white flex flex-col justify-center">
                        <h3 class="text-3xl sm:text-4xl font-bold mb-4">Bize Ulaşın</h3>
                        <p class="text-brand-100 mb-10 text-lg">Sorularınız, fiyat bilgisi veya özel talepleriniz için formu doldurabilir veya iletişim bilgilerimizden bize ulaşabilirsiniz.</p>
                        
                        <div class="space-y-6">
                            <div class="flex items-center">
                                <div class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center mr-4">
                                    <i class="fa-solid fa-envelope text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-brand-200 text-sm">E-posta</p>
                                    <p class="font-medium text-lg">bilgi@dryforyou.com.tr</p>
                                </div>
                            </div>
                            <div class="flex items-center">
                                <div class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center mr-4">
                                    <i class="fa-solid fa-phone text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-brand-200 text-sm">Müşteri Hizmetleri</p>
                                    <p class="font-medium text-lg">0535 456 90 78</p>
                                </div>
                            </div>
                            <div class="flex items-center">
                                <div class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center mr-4">
                                    <i class="fa-brands fa-instagram text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-brand-200 text-sm">Instagram</p>
                                    <a href="https://www.instagram.com/dry.for.you" target="_blank" class="font-medium text-lg hover:text-brand-200 transition-colors">@dry.for.you</a>
                                </div>
                            </div>
                            <div class="flex items-center">
                                <div class="w-12 h-12 bg-white/10 rounded-full flex items-center justify-center mr-4">
                                    <i class="fa-regular fa-clock text-xl"></i>
                                </div>
                                <div>
                                    <p class="text-brand-200 text-sm">Çalışma Saatleri</p>
                                    <p class="font-medium text-lg">Pzt - Cmt: 08:30 - 19:30</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Contact Form -->
                    <div class="bg-white p-10 md:p-16">
                        <form onsubmit="event.preventDefault(); showFormSuccess();" class="space-y-6">
                            <div id="form-success-msg" class="hidden bg-green-50 text-green-700 p-4 rounded-lg mb-6 flex items-center">
                                <i class="fa-solid fa-check-circle mr-2"></i>
                                Mesajınız başarıyla alınmıştır. En kısa sürede dönüş yapacağız.
                            </div>
                            
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                                <div>
                                    <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Adınız Soyadınız</label>
                                    <input type="text" id="name" required class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-500 focus:border-brand-500 outline-none transition-all">
                                </div>
                                <div>
                                    <label for="phone" class="block text-sm font-medium text-gray-700 mb-1">Telefon Numaranız</label>
                                    <input type="tel" id="phone" required class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-500 focus:border-brand-500 outline-none transition-all">
                                </div>
                            </div>
                            
                            <div>
                                <label for="branch" class="block text-sm font-medium text-gray-700 mb-1">İlgili Şube (Opsiyonel)</label>
                                <select id="branch" class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-500 focus:border-brand-500 outline-none transition-all bg-white">
                                    <option value="">Seçiniz...</option>
                                    <option value="atasehir">Ataşehir</option>
                                    <option value="bayrakli">Bayraklı</option>
                                    <option value="mavisehir">Mavişehir</option>
                                </select>
                            </div>

                            <div>
                                <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Mesajınız</label>
                                <textarea id="message" rows="4" required class="w-full px-4 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-500 focus:border-brand-500 outline-none transition-all resize-none"></textarea>
                            </div>
                            
                            <button type="submit" class="w-full bg-brand-600 text-white font-semibold py-4 rounded-lg hover:bg-brand-700 transition-colors shadow-md">
                                Mesaj Gönder
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white pt-16 pb-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-12">
                <div>
                    <a href="#" class="text-3xl font-bold text-white tracking-tighter lowercase mb-4 block">
                        <i class="fa-solid fa-shirt mr-2 text-brand-500"></i>dry for you.
                    </a>
                    <p class="text-gray-400">
                        İzmir'de profesyonel kuru temizleme ve terzilik hizmetleri. Kıyafetleriniz bizimle güvende.
                    </p>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Hızlı Bağlantılar</h4>
                    <ul class="space-y-2">
                        <li><a href="#hizmetlerimiz" class="text-gray-400 hover:text-white transition-colors">Hizmetlerimiz</a></li>
                        <li><a href="#subelerimiz" class="text-gray-400 hover:text-white transition-colors">Şubelerimiz</a></li>
                        <li><a href="#iletisim" class="text-gray-400 hover:text-white transition-colors">İletişim</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Bizi Takip Edin</h4>
                    <div class="flex space-x-4">
                        <a href="https://www.instagram.com/dry.for.you" target="_blank" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center text-gray-400 hover:bg-brand-600 hover:text-white transition-all">
                            <i class="fa-brands fa-instagram"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center text-gray-400 hover:bg-brand-600 hover:text-white transition-all">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center text-gray-400 hover:bg-brand-600 hover:text-white transition-all">
                            <i class="fa-brands fa-whatsapp"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-800 pt-8 text-center text-gray-500 text-sm">
                <p>&copy; 2026 dry for you. Tüm hakları saklıdır. İzmir / Türkiye</p>
            </div>
        </div>
    </footer>

    <!-- Scripts -->
    <script>
        // Mobile Menu Toggle
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Close mobile menu on link click
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });

        // Simple Form Submission Simulation
        function showFormSuccess() {
            const successMsg = document.getElementById('form-success-msg');
            successMsg.classList.remove('hidden');
            
            // Clear form
            document.getElementById('name').value = '';
            document.getElementById('phone').value = '';
            document.getElementById('branch').value = '';
            document.getElementById('message').value = '';

            // Hide message after 5 seconds
            setTimeout(() => {
                successMsg.classList.add('hidden');
            }, 5000);
        }
    </script>
</body>
</html>
