<div id="realhomes-website" style="font-family: 'Inter', sans-serif; color: #333; line-height: 1.6;">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        .gold-accent { color: #D4AF37; }
        .bg-gold { background-color: #D4AF37; }
        .bg-navy { background-color: #0A192F; }
        .hero-gradient { background: linear-gradient(rgba(10, 25, 47, 0.85), rgba(10, 25, 47, 0.65)); }
        .card-hover:hover { transform: translateY(-10px); transition: all 0.3s ease; }
    </style>

    <nav class="fixed w-full z-50 bg-white/95 backdrop-blur-md shadow-sm">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold text-navy uppercase">REAL<span class="gold-accent">HOMES</span></div>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#home" class="hover:text-yellow-600 transition">Home</a>
                <a href="#about" class="hover:text-yellow-600 transition">About</a>
                <a href="#properties" class="hover:text-yellow-600 transition">Properties</a>
                <a href="#services" class="hover:text-yellow-600 transition">Services</a>
                <a href="#contact" class="bg-navy text-white px-5 py-2 rounded hover:bg-gray-800 transition">Contact</a>
            </div>
        </div>
    </nav>

    <section id="home" class="relative h-screen flex items-center justify-center text-white">
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=2070" class="w-full h-full object-cover" alt="Abuja Skyline">
            <div class="absolute inset-0 hero-gradient"></div>
        </div>
        <div class="relative z-10 text-center px-6 max-w-4xl pt-20">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">Your Trusted Partner in <span class="gold-accent">Commercial Real Estate</span></h1>
            <p class="text-lg md:text-xl mb-10 text-gray-200">Helping you find the perfect property for your business and investment needs.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#properties" class="bg-gold hover:bg-yellow-600 text-white px-10 py-4 rounded-lg font-bold transition shadow-lg">Explore Properties</a>
                <a href="#contact" class="bg-white/10 backdrop-blur-md border border-white/30 hover:bg-white hover:text-navy px-10 py-4 rounded-lg font-bold transition">Contact Us</a>
            </div>
        </div>
    </section>

    <section id="about" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-16 items-center">
            <div>
                <h2 class="text-3xl font-bold text-navy mb-6">About RealHomes and Property</h2>
                <p class="text-gray-600 mb-6">RealHomes and Property is a reliable commercial real estate agency based in Lugbe, Federal Capital Territory. We are dedicated to providing the most professional and trusted property solutions in the region.</p>
                <p class="text-gray-600">Our team focuses on delivering high-value commercial assets that meet the specific needs of modern businesses and savvy investors.</p>
            </div>
            <div class="grid grid-cols-2 gap-4">
                <div class="p-6 bg-gray-50 rounded-xl text-center shadow-sm">
                    <i data-lucide="shield-check" class="mx-auto mb-3 gold-accent"></i>
                    <h4 class="font-bold">Trusted Agency</h4>
                </div>
                <div class="p-6 bg-navy text-white rounded-xl text-center shadow-sm">
                    <i data-lucide="check-circle" class="mx-auto mb-3 gold-accent"></i>
                    <h4 class="font-bold">Verified Listings</h4>
                </div>
                <div class="p-6 bg-navy text-white rounded-xl text-center shadow-sm">
                    <i data-lucide="headphones" class="mx-auto mb-3 gold-accent"></i>
                    <h4 class="font-bold">Professional Support</h4>
                </div>
                <div class="p-6 bg-gray-50 rounded-xl text-center shadow-sm">
                    <i data-lucide="zap" class="mx-auto mb-3 gold-accent"></i>
                    <h4 class="font-bold">Seamless Process</h4>
                </div>
            </div>
        </div>
    </section>

    <section id="properties" class="py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl font-bold text-navy mb-12 text-center">Featured Commercial Properties</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white rounded-xl overflow-hidden shadow-md card-hover transition-all">
                    <img src="https://images.unsplash.com/photo-1497366216548-37526070297c?q=80&w=600" class="w-full h-56 object-cover" alt="Property">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Corporate Office Plaza</h3>
                        <p class="text-gray-500 text-sm mb-4"><i data-lucide="map-pin" class="inline w-3 h-3"></i> Central District, Abuja</p>
                        <div class="flex justify-between items-center border-t pt-4">
                            <span class="text-xl font-bold text-navy">₦15,000,000</span>
                            <button class="bg-navy text-white px-4 py-2 rounded text-sm">View Details</button>
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl overflow-hidden shadow-md card-hover transition-all">
                    <img src="https://images.unsplash.com/photo-1541888946425-d81bb19480c5?q=80&w=600" class="w-full h-56 object-cover" alt="Property">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Industrial Hub</h3>
                        <p class="text-gray-500 text-sm mb-4"><i data-lucide="map-pin" class="inline w-3 h-3"></i> Idu Industrial, Abuja</p>
                        <div class="flex justify-between items-center border-t pt-4">
                            <span class="text-xl font-bold text-navy">₦45,000,000</span>
                            <button class="bg-navy text-white px-4 py-2 rounded text-sm">View Details</button>
                        </div>
                    </div>
                </div>
                <div class="bg-white rounded-xl overflow-hidden shadow-md card-hover transition-all">
                    <img src="https://images.unsplash.com/photo-1556761175-b413da4baf72?q=80&w=600" class="w-full h-56 object-cover" alt="Property">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Retail Storefront</h3>
                        <p class="text-gray-500 text-sm mb-4"><i data-lucide="map-pin" class="inline w-3 h-3"></i> Lugbe, Abuja</p>
                        <div class="flex justify-between items-center border-t pt-4">
                            <span class="text-xl font-bold text-navy">₦5,500,000</span>
                            <button class="bg-navy text-white px-4 py-2 rounded text-sm">View Details</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-24 bg-navy text-white text-center">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl font-bold mb-16">Our Services</h2>
            <div class="grid md:grid-cols-4 gap-8">
                <div><i data-lucide="key" class="mx-auto mb-4 gold-accent"></i><h4 class="font-bold">Property Sales</h4></div>
                <div><i data-lucide="building" class="mx-auto mb-4 gold-accent"></i><h4 class="font-bold">Property Leasing</h4></div>
                <div><i data-lucide="briefcase" class="mx-auto mb-4 gold-accent"></i><h4 class="font-bold">Consultation</h4></div>
                <div><i data-lucide="trending-up" class="mx-auto mb-4 gold-accent"></i><h4 class="font-bold">Investment Advisory</h4></div>
            </div>
        </div>
    </section>

    <section class="py-24 bg-white">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold text-navy mb-12">Client Testimonials</h2>
            <div class="bg-gray-50 p-10 rounded-3xl italic text-gray-600 shadow-inner">
                "The most seamless property acquisition process I've ever experienced in Abuja. Professional and highly recommended!"
                <p class="mt-6 font-bold text-navy not-italic">— Michael O., Tech Hub CEO</p>
            </div>
        </div>
    </section>

    <section id="contact" class="py-24 border-t">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-16">
            <div>
                <h2 class="text-3xl font-bold text-navy mb-6">Get In Touch Today</h2>
                <p class="mb-8 text-gray-600">Schedule a consultation or visit our office in Lugbe.</p>
                <div class="space-y-4">
                    <p><strong>Address:</strong> Federal Housing, Total Road, Lugbe 980001, FCT</p>
                    <p><strong>Phone:</strong> 09136177347</p>
                </div>
            </div>
            <form class="space-y-4">
                <input type="text" placeholder="Your Name" class="w-full p-3 border rounded">
                <input type="email" placeholder="Email Address" class="w-full p-3 border rounded">
                <textarea placeholder="Message" rows="4" class="w-full p-3 border rounded"></textarea>
                <button class="w-full bg-gold text-white font-bold py-3 rounded hover:bg-yellow-600 transition">Send Message</button>
            </form>
        </div>
    </section>

    <footer class="py-10 bg-navy text-center text-gray-500 text-sm">
        &copy; 2026 RealHomes and Property. All rights reserved.
    </footer>

    <script>
        lucide.createIcons();
    </script>
</div>
