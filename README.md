<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mar y Brisa | Restaurante de Mariscos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        .hero-bg {
            background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), 
                              url('https://images.unsplash.com/photo-1551248429-42401df1ad84?auto=format&fit=crop&q=80&w=1600');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="text-2xl font-bold text-cyan-900 tracking-wider">MAR & BRISA</div>
                <div class="hidden md:flex space-x-8 font-medium text-sm uppercase tracking-widest">
                    <a href="#inicio" class="hover:text-cyan-600 transition">Inicio</a>
                    <a href="#menu" class="hover:text-cyan-600 transition">Menú</a>
                    <a href="#nosotros" class="hover:text-cyan-600 transition">Nosotros</a>
                    <a href="#reservas" class="bg-cyan-900 text-white px-5 py-2 rounded-full hover:bg-cyan-700 transition">Reservar</a>
                </div>
                <div class="md:hidden text-cyan-900">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                    </svg>
                </div>
            </div>
        </div>
    </nav>

    <header id="inicio" class="hero-bg h-screen flex items-center justify-center text-center text-white px-4">
        <div class="max-w-3xl">
            <span class="uppercase tracking-[0.3em] text-sm mb-4 block text-cyan-200">Sabor local, alma marina</span>
            <h1 class="text-5xl md:text-7xl mb-6">La Frescura del Océano en tu Mesa</h1>
            <p class="text-lg md:text-xl mb-8 font-light text-slate-200">Experiencias gastronómicas creadas con los mejores frutos del mar capturados el mismo día.</p>
            <a href="#menu" class="inline-block border-2 border-white px-8 py-3 hover:bg-white hover:text-slate-900 transition duration-300 font-semibold uppercase text-sm tracking-widest">
                Explorar Menú
            </a>
        </div>
    </header>

    <section id="menu" class="py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
            <h2 class="text-4xl text-cyan-900 mb-4">Nuestros Tesoros</h2>
            <div class="h-1 w-20 bg-orange-400 mx-auto"></div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition duration-300">
                <img src="https://images.unsplash.com/photo-1565557623262-b51c2513a641?auto=format&fit=crop&q=80&w=600" alt="Ceviche" class="w-full h-64 object-cover">
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h3 class="text-xl font-bold">Ceviche de la Casa</h3>
                        <span class="text-cyan-700 font-bold">$18.00</span>
                    </div>
                    <p class="text-slate-500 text-sm">Pescado blanco marinado en cítricos, ají limo, cebolla morada y cilantro fresco.</p>
                </div>
            </div>

            <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition duration-300">
                <img src="https://images.unsplash.com/photo-1599487488170-d11ec9c172f0?auto=format&fit=crop&q=80&w=600" alt="Langostas" class="w-full h-64 object-cover">
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h3 class="text-xl font-bold">Langosta al Grill</h3>
                        <span class="text-cyan-700 font-bold">$34.00</span>
                    </div>
                    <p class="text-slate-500 text-sm">Cola de langosta bañada en mantequilla de ajo y finas hierbas de temporada.</p>
                </div>
            </div>

            <div class="bg-white rounded-xl overflow-hidden shadow-lg hover:shadow-2xl transition duration-300">
                <img src="https://images.unsplash.com/photo-1534080564607-09625680034c?auto=format&fit=crop&q=80&w=600" alt="Pulpo" class="w-full h-64 object-cover">
                <div class="p-6">
                    <div class="flex justify-between items-center mb-2">
                        <h3 class="text-xl font-bold">Pulpo a las Brasas</h3>
                        <span class="text-cyan-700 font-bold">$26.00</span>
                    </div>
                    <p class="text-slate-500 text-sm">Tentáculos de pulpo marinados en pimentón ahumado con puré de papa rústico.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="nosotros" class="py-24 bg-cyan-900 text-white overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row items-center gap-16">
                <div class="lg:w-1/2">
                    <h2 class="text-4xl mb-8 italic">Tres generaciones frente al mar</h2>
                    <p class="text-slate-300 mb-6 leading-relaxed">
                        Lo que comenzó como una pequeña cabaña de pescadores en 1984, se ha transformado en un referente de la cocina costera. Nuestra filosofía es simple: respetar el producto y apoyar a los pescadores locales.
                    </p>
                    <p class="text-slate-300 mb-8 leading-relaxed">
                        Cada ingrediente en nuestra cocina es seleccionado bajo estrictos estándares de sostenibilidad, asegurando que el mar siga dándonos sus frutos por muchos años más.
                    </p>
                    <div class="grid grid-cols-2 gap-4 text-center">
                        <div class="border border-cyan-700 p-4 rounded">
                            <span class="block text-3xl font-bold text-orange-400">100%</span>
                            <span class="text-xs uppercase tracking-tighter">Fresco Diariamente</span>
                        </div>
                        <div class="border border-cyan-700 p-4 rounded">
                            <span class="block text-3xl font-bold text-orange-400">12+</span>
                            <span class="text-xs uppercase tracking-tighter">Vinos Premium</span>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 relative">
                    <img src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?auto=format&fit=crop&q=80&w=800" alt="Chef preparando comida" class="rounded-lg shadow-2xl relative z-10">
                    <div class="absolute -bottom-6 -right-6 w-full h-full border-2 border-orange-400 rounded-lg"></div>
                </div>
            </div>
        </div>
    </section>

    <section id="reservas" class="py-24 max-w-4xl mx-auto px-4">
        <div class="bg-white p-8 md:p-12 rounded-2xl shadow-xl border border-slate-100">
            <div class="text-center mb-12">
                <h2 class="text-3xl text-cyan-900 mb-2">Reserva tu Mesa</h2>
                <p class="text-slate-500 text-sm">Garantiza tu lugar frente al atardecer</p>
            </div>
            
            <form class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-slate-400 mb-2">Nombre Completo</label>
                    <input type="text" placeholder="Tu nombre" class="w-full bg-slate-50 border-none p-4 rounded-lg focus:ring-2 focus:ring-cyan-600 outline-none">
                </div>
                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-slate-400 mb-2">Correo Electrónico</label>
                    <input type="email" placeholder="email@ejemplo.com" class="w-full bg-slate-50 border-none p-4 rounded-lg focus:ring-2 focus:ring-cyan-600 outline-none">
                </div>
                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-slate-400 mb-2">Fecha</label>
                    <input type="date" class="w-full bg-slate-50 border-none p-4 rounded-lg focus:ring-2 focus:ring-cyan-600 outline-none">
                </div>
                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-slate-400 mb-2">Personas</label>
                    <select class="w-full bg-slate-50 border-none p-4 rounded-lg focus:ring-2 focus:ring-cyan-600 outline-none">
                        <option>2 Personas</option>
                        <option>4 Personas</option>
                        <option>6+ Personas</option>
                    </select>
                </div>
                <div class="md:col-span-2">
                    <label class="block text-xs font-bold uppercase tracking-wider text-slate-400 mb-2">Comentarios Especiales</label>
                    <textarea rows="4" placeholder="¿Alguna alergia o motivo especial?" class="w-full bg-slate-50 border-none p-4 rounded-lg focus:ring-2 focus:ring-cyan-600 outline-none"></textarea>
                </div>
                <div class="md:col-span-2">
                    <button type="submit" class="w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-4 rounded-lg shadow-lg shadow-orange-200 transition duration-300 uppercase tracking-widest text-sm">
                        Confirmar Reserva
                    </button>
                </div>
            </form>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-400 py-12 text-center border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4">
            <p class="text-white font-bold mb-4">MAR & BRISA</p>
            <p class="text-sm mb-6">Av. Costanera 123, Playa Paraíso • Abierto todos los días de 12:00 PM a 11:00 PM</p>
            <div class="flex justify-center space-x-6">
                <a href="#" class="hover:text-white transition">Instagram</a>
                <a href="#" class="hover:text-white transition">Facebook</a>
            </div>
            <p class="mt-10 text-[10px] uppercase tracking-widest">© 2024 Restaurante de Mariscos. Todos los derechos reservados.</p>
        </div>
    </footer>

</body>
</html>
