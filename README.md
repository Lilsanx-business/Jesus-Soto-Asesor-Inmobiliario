<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Nombre | Asesor Inmobiliario</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-2xl font-bold text-blue-900 uppercase tracking-wider">Tu Logo/Nombre</h1>
            <div class="hidden md:flex space-x-8 font-medium">
                <a href="#inicio" class="hover:text-blue-600 transition">Inicio</a>
                <a href="#catalogo" class="hover:text-blue-600 transition">Propiedades</a>
                <a href="#contacto" class="hover:text-blue-600 transition">Contacto</a>
            </div>
        </div>
    </nav>

    <header id="inicio" class="relative h-[500px] flex items-center justify-center text-white">
        <img src="https://images.unsplash.com/photo-1560518883-ce09059eeffa?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" 
             class="absolute inset-0 w-full h-full object-cover brightness-50" alt="Casa de lujo">
        <div class="relative text-center px-4">
            <h2 class="text-4xl md:text-5xl font-extrabold mb-4">Encuentra el hogar de tus sueños</h2>
            <p class="text-xl mb-8 text-gray-200">Asesoría inmobiliaria profesional y personalizada.</p>
            <a href="#catalogo" class="bg-blue-700 hover:bg-blue-800 text-white px-8 py-3 rounded-full font-bold transition">Ver Catálogo</a>
        </div>
    </header>

    <section id="catalogo" class="container mx-auto px-6 py-16">
        <h3 class="text-3xl font-bold text-center mb-12 text-blue-900 underline decoration-blue-500">Desarrollos Disponibles</h3>
        
        <div class="grid md:grid-cols-3 gap-8">
            <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=500&q=60" alt="Departamento" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-blue-600 text-xs font-bold uppercase">Preventa</span>
                    <h4 class="text-xl font-bold my-2">Banyana Residencial</h4>
                    <p class="text-gray-600 mb-4">3 Recámaras | 2 Baños | Zona Exclusiva</p>
                    <button class="w-full border-2 border-blue-900 text-blue-900 py-2 rounded font-bold hover:bg-blue-900 hover:text-white transition">Más Información</button>
                </div>
            </div>

            <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=500&q=60" alt="Casa" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-green-600 text-xs font-bold uppercase">Disponible</span>
                    <h4 class="text-xl font-bold my-2">Loft Industrial Centro</h4>
                    <p class="text-gray-600 mb-4">1 Recámara | Diseño Moderno | Amueblado</p>
                    <button class="w-full border-2 border-blue-900 text-blue-900 py-2 rounded font-bold hover:bg-blue-900 hover:text-white transition">Más Información</button>
                </div>
            </div>

            <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:scale-105 transition duration-300">
                <img src="https://images.unsplash.com/photo-1564013799919-ab600027ffc6?auto=format&fit=crop&w=500&q=60" alt="Residencia" class="w-full h-48 object-cover">
                <div class="p-6">
                    <span class="text-blue-600 text-xs font-bold uppercase">Preventa</span>
                    <h4 class="text-xl font-bold my-2">Villas del Sol</h4>
                    <p class="text-gray-600 mb-4">Alberca privada | 4 Recámaras | Seguridad 24/7</p>
                    <button class="w-full border-2 border-blue-900 text-blue-900 py-2 rounded font-bold hover:bg-blue-900 hover:text-white transition">Más Información</button>
                </div>
            </div>
        </div>
    </section>

    <a href="https://wa.me/5211234567890?text=Hola,%20vi%20tu%20catálogo%20web%20y%20me%20gustaría%20recibir%20asesoría." 
       target="_blank"
       class="fixed bottom-6 right-6 bg-[#25D366] text-white w-16 h-16 rounded-full flex items-center justify-center shadow-2xl hover:bg-[#128C7E] transition-all transform hover:scale-110 z-[100]">
        <i class="fab fa-whatsapp text-3xl"></i>
    </a>

    <footer class="bg-blue-950 text-white py-10 text-center">
        <p>&copy; 2024 Tu Marca Personal - Todos los derechos reservados.</p>
    </footer>

</body>
</html>
