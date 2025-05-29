<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>INEMAC - Ingeniería Especializada en Medio Ambiente, Construcción y Capacitación</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#2A9D8F',secondary:'#264653'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700;800&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Montserrat', sans-serif;
}
.hero-section {
background-image: linear-gradient(to right, rgba(255, 255, 255, 0.9) 40%, rgba(255, 255, 255, 0.7) 60%, rgba(255, 255, 255, 0.4) 80%, rgba(255, 255, 255, 0) 100%), url('https://readdy.ai/api/search-image?query=futuristic%20environmental%20monitoring%20scene%20in%20dramatic%20Peruvian%20landscape%2C%20scientists%20using%20holographic%20interfaces%20and%20augmented%20reality%20for%20environmental%20analysis%2C%20advanced%20drones%20and%20monitoring%20equipment%20with%20glowing%20displays%2C%20stunning%20mountain%20backdrop%20with%20dramatic%20lighting%20and%20tech%20elements%2C%20cinematic%20professional%20photography&width=1600&height=800&seq=hero1&orientation=landscape');
background-size: cover;
background-position: center right;
}
input:focus, textarea:focus {
outline: none;
border-color: #2A9D8F;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
-webkit-appearance: none;
margin: 0;
}
.service-card:hover {
transform: translateY(-5px);
box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
}
.stats-item {
position: relative;
}
.stats-item:not(:last-child)::after {
content: "";
position: absolute;
right: 0;
top: 20%;
height: 60%;
width: 1px;
background-color: #e5e7eb;
}
</style>
</head>
<body id="inicio" class="bg-gray-50">
<!-- Header -->
<header class="bg-white shadow-sm sticky top-0 z-50">
<div class="container mx-auto px-4 py-3 flex justify-between items-center">
<a href="#" class="flex items-center hover:opacity-90 transition-opacity">
<img src="https://static.readdy.ai/image/96e5929cc978f1d5b2c6005d0965087e/453fc979e66c8b05761c20932443328b.jpeg" alt="INEMAC Logo" class="h-12 w-auto">
</a>
<nav class="hidden md:flex space-x-8">
<a href="#inicio" class="text-gray-800 font-medium hover:text-primary transition-colors">Inicio</a>
<a href="#casos-estudios" class="text-gray-800 font-medium hover:text-primary transition-colors">Casos de Estudios</a>
<a href="#catalogo" class="text-gray-800 font-medium hover:text-primary transition-colors">Catálogo</a>
<a href="#nosotros" class="text-gray-800 font-medium hover:text-primary transition-colors">Nosotros</a>
<a href="#proyectos-aprobados" class="text-gray-800 font-medium hover:text-primary transition-colors">Proyectos Aprobados</a>
<a href="#contacto" class="text-gray-800 font-medium hover:text-primary transition-colors">Contacto</a>
</nav>
<div class="flex items-center space-x-4">
<button id="quote-btn" class="hidden md:block bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">Solicitar Cotización</button>
<a href="https://wa.me/51956298271" target="_blank" class="hidden md:flex items-center bg-green-600 text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">
Contactar ahora <i class="ri-whatsapp-line ml-2"></i>
</a>
<button class="md:hidden w-10 h-10 flex items-center justify-center text-gray-700" id="mobile-menu-button">
<i class="ri-menu-line ri-lg"></i>
</button>
</div>
</div>
<!-- Mobile menu -->
<div class="md:hidden hidden bg-white absolute w-full border-b border-gray-200" id="mobile-menu">
<div class="container mx-auto px-4 py-3 flex flex-col space-y-3">
<a href="#inicio" class="text-gray-800 py-2 border-b border-gray-100">Inicio</a>
<a href="#casos-estudios" class="text-gray-800 py-2 border-b border-gray-100">Casos de Estudios</a>
<a href="#catalogo" class="text-gray-800 py-2 border-b border-gray-100">Catálogo</a>
<a href="#nosotros" class="text-gray-800 py-2 border-b border-gray-100">Nosotros</a>
<a href="#proyectos-aprobados" class="text-gray-800 py-2 border-b border-gray-100">Proyectos Aprobados</a>
<a href="#contacto" class="text-gray-800 py-2 border-b border-gray-100">Contacto</a>
<button id="quote-btn-mobile" class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap text-center w-full">Solicitar Cotización</button>
<a href="https://wa.me/51956298271" target="_blank" class="bg-green-600 text-white px-4 py-2 !rounded-button whitespace-nowrap text-center w-full flex items-center justify-center">
Contactar ahora <i class="ri-whatsapp-line ml-2"></i>
</a>
</div>
</div>
</header>
<!-- Hero Section -->
<section class="hero-section min-h-[600px] flex items-center">
<div class="container mx-auto px-4 py-16 w-full">
<div class="max-w-2xl">
<h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">INGENIERÍA ESPECIALIZADA EN MEDIO AMBIENTE, CONSTRUCCIÓN Y CAPACITACIÓN - INEMAC</h1>
<p class="text-lg text-gray-700 mb-8">Brindamos servicios especializados en ingeniería ambiental, construcción y capacitación, cumpliendo con los más altos estándares y normativas vigentes.</p>
<div class="flex flex-col sm:flex-row gap-4">
<a href="https://wa.me/51956298271" target="_blank" class="bg-primary text-white px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors text-center">Contactar Ahora <i class="ri-whatsapp-line ml-2"></i></a>
</div>
</div>
</div>
</section>
<!-- Casos de Estudios -->
<section id="casos-estudios" class="py-16 bg-white">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Casos de Estudios</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Balotario de observaciones ambientales y sociales frecuentes en instrumentos de gestión ambiental del sector transportes.</p>
</div>
<div class="grid grid-cols-1 gap-8">
<div class="bg-white p-8 rounded-lg shadow-lg">
<div class="flex items-center mb-6">
<div class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mr-4">
<i class="ri-file-list-3-line text-primary ri-xl"></i>
</div>
<h3 class="text-xl font-semibold">Observaciones Frecuentes en Instrumentos de Gestión Ambiental</h3>
</div>
<div class="space-y-8">
<!-- Observaciones Ambientales -->
<div class="bg-gray-50 p-6 rounded-lg">
<h4 class="text-lg font-semibold mb-4 flex items-center">
<i class="ri-leaf-line mr-2 text-primary"></i>
Observaciones Ambientales
</h4>
<ul class="space-y-4">
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">1</span>
</div>
<div>
<p class="font-medium text-gray-900">Línea Base Física</p>
<p class="text-gray-600 mt-1">Falta de caracterización detallada de los componentes ambientales en el área de influencia directa e indirecta del proyecto vial.</p>
</div>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">2</span>
</div>
<div>
<p class="font-medium text-gray-900">Identificación de Impactos</p>
<p class="text-gray-600 mt-1">Inadecuada valoración de impactos ambientales durante las etapas de construcción y operación de la infraestructura vial.</p>
</div>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">3</span>
</div>
<div>
<p class="font-medium text-gray-900">Plan de Manejo Ambiental</p>
<p class="text-gray-600 mt-1">Medidas de mitigación insuficientes o no específicas para los impactos identificados en el proyecto de transporte.</p>
</div>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">4</span>
</div>
<div>
<p class="font-medium text-gray-900">Programa de Monitoreo</p>
<p class="text-gray-600 mt-1">Falta de detalle en la frecuencia y ubicación de puntos de monitoreo ambiental durante la ejecución del proyecto.</p>
</div>
</li>
</ul>
</div>
<!-- Observaciones Sociales -->
<div class="bg-gray-50 p-6 rounded-lg">
<h4 class="text-lg font-semibold mb-4 flex items-center">
<i class="ri-team-line mr-2 text-primary"></i>
Observaciones Sociales
</h4>
<ul class="space-y-4">
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">1</span>
</div>
<div>
<p class="font-medium text-gray-900">Área de Influencia Social</p>
<p class="text-gray-600 mt-1">Delimitación inadecuada del área de influencia social directa e indirecta del proyecto de infraestructura vial.</p>
</div>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">2</span>
</div>
<div>
<p class="font-medium text-gray-900">Participación Ciudadana</p>
<p class="text-gray-600 mt-1">Mecanismos de participación ciudadana insuficientes o no adaptados a las características de la población local.</p>
</div>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">3</span>
</div>
<div>
<p class="font-medium text-gray-900">Plan de Relaciones Comunitarias</p>
<p class="text-gray-600 mt-1">Falta de programas específicos para la gestión de impactos sociales y relacionamiento con comunidades afectadas.</p>
</div>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex-shrink-0 flex items-center justify-center bg-primary bg-opacity-10 rounded-full mt-1 mr-3">
<span class="text-primary text-sm">4</span>
</div>
<div>
<p class="font-medium text-gray-900">Compensación e Indemnización</p>
<p class="text-gray-600 mt-1">Criterios poco claros para la valoración y compensación de predios afectados por el derecho de vía.</p>
</div>
</li>
</ul>
</div>
<!-- Recomendaciones -->
<div class="bg-primary bg-opacity-5 p-6 rounded-lg">
<h4 class="text-lg font-semibold mb-4 flex items-center">
<i class="ri-lightbulb-line mr-2 text-primary"></i>
Recomendaciones Clave
</h4>
<ul class="space-y-3">
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-700">Realizar un análisis exhaustivo de la normativa ambiental y social aplicable al sector transportes.</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-700">Implementar metodologías participativas para el levantamiento de información social.</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-700">Establecer indicadores medibles para el seguimiento de compromisos socioambientales.</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-700">Documentar adecuadamente todas las actividades de participación ciudadana y consulta.</span>
</li>
</ul>
</div>
</div>
</div>
</div>
</section>
<!-- Estadísticas -->
<section class="py-16 bg-gray-50">
<div class="container mx-auto px-4">
<div class="bg-white rounded-lg shadow-md p-8">
<div class="grid grid-cols-1 md:grid-cols-4 gap-6">
<div class="stats-item text-center">
<div class="text-4xl font-bold text-primary mb-2">+120</div>
<p class="text-gray-600">Proyectos Completados</p>
</div>
<div class="stats-item text-center">
<div class="text-4xl font-bold text-primary mb-2">98%</div>
<p class="text-gray-600">Clientes Satisfechos</p>
</div>
<div class="stats-item text-center">
<div class="text-4xl font-bold text-primary mb-2">+15</div>
<p class="text-gray-600">Años de Experiencia</p>
</div>
<div class="stats-item text-center">
<div class="text-4xl font-bold text-primary mb-2">+30</div>
<p class="text-gray-600">Especialistas</p>
</div>
</div>
</div>
</div>
</section>
<!-- Catálogo de Servicios -->
<section id="catalogo" class="py-16 bg-white">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Catálogo de Servicios</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Explore nuestra amplia gama de servicios especializados en gestión ambiental, social, arqueológica y seguridad laboral.</p>
</div>
<!-- Filtros -->
<div class="flex flex-wrap justify-center gap-4 mb-10">
<button class="filter-btn active bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap" data-filter="all">Todos</button>
<button class="filter-btn bg-white border border-gray-300 text-gray-700 px-4 py-2 !rounded-button whitespace-nowrap hover:bg-gray-50" data-filter="ambiental">Ambiental</button>
<button class="filter-btn bg-white border border-gray-300 text-gray-700 px-4 py-2 !rounded-button whitespace-nowrap hover:bg-gray-50" data-filter="social">Social</button>
<button class="filter-btn bg-white border border-gray-300 text-gray-700 px-4 py-2 !rounded-button whitespace-nowrap hover:bg-gray-50" data-filter="arqueologico">Arqueológico</button>
<button class="filter-btn bg-white border border-gray-300 text-gray-700 px-4 py-2 !rounded-button whitespace-nowrap hover:bg-gray-50" data-filter="sst">Seguridad</button>
</div>
<!-- Grid de Servicios -->
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Servicio 1 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="ambiental">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=environmental%20consultants%20actively%20engaging%20with%20advanced%20monitoring%20equipment%2C%20dynamic%20scene%20with%20holographic%20displays%20showing%20real-time%20environmental%20data%2C%20modern%20professional%20setting%20with%20cutting-edge%20technology%2C%20vibrant%20natural%20lighting%2C%20high-end%20professional%20photography&width=600&height=400&seq=serv1&orientation=landscape" alt="Supervisión Ambiental" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Supervisión Ambiental en Campo</h3>
<p class="text-gray-600 mb-4">Monitoreo y supervisión del cumplimiento de compromisos ambientales en proyectos según la normativa peruana.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio1">Ver Detalles</button>
</div>
</div>
<!-- Servicio 2 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="social ambiental">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=socio-environmental%20baseline%20study%20in%20Peru%2C%20professionals%20interviewing%20local%20communities%2C%20taking%20notes%2C%20documenting%20social%20conditions%2C%20rural%20Peruvian%20setting%2C%20professional%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv2&orientation=landscape" alt="Línea Base Socioambiental" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Elaboración de Línea Base Socioambiental</h3>
<p class="text-gray-600 mb-4">Diagnóstico integral de las condiciones ambientales y sociales previo al desarrollo de proyectos.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio2">Ver Detalles</button>
</div>
</div>
<!-- Servicio 3 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="ambiental">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=environmental%20consultants%20reviewing%20documents%20and%20addressing%20environmental%20observations%20in%20office%20setting%2C%20professional%20environment%2C%20people%20analyzing%20environmental%20reports%2C%20high%20quality%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv3&orientation=landscape" alt="Subsanación Ambiental" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Subsanación de Observaciones Ambientales</h3>
<p class="text-gray-600 mb-4">Resolución de observaciones emitidas por autoridades ambientales en estudios y documentos técnicos.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio3">Ver Detalles</button>
</div>
</div>
<!-- Servicio 4 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="ambiental social">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=professionals%20creating%20socio-environmental%20thematic%20maps%20on%20computers%2C%20GIS%20specialists%20working%20with%20mapping%20software%2C%20detailed%20maps%20of%20Peruvian%20regions%20visible%20on%20screens%2C%20professional%20office%20setting%2C%20high%20quality%20photography&width=600&height=400&seq=serv4&orientation=landscape" alt="Mapas Temáticos" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Elaboración de Mapas Temáticos Socioambientales</h3>
<p class="text-gray-600 mb-4">Desarrollo de cartografía especializada para la representación de variables ambientales y sociales.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio4">Ver Detalles</button>
</div>
</div>
<!-- Servicio 5 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="arqueologico">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=archaeological%20permit%20management%20in%20Peru%2C%20professionals%20examining%20archaeological%20artifacts%2C%20documenting%20findings%20at%20Peruvian%20archaeological%20site%2C%20people%20in%20field%20gear%20working%20near%20ancient%20ruins%2C%20professional%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv5&orientation=landscape" alt="Permisos Arqueológicos" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Gestión de Permisos Arqueológicos</h3>
<p class="text-gray-600 mb-4">Tramitación de autorizaciones ante el Ministerio de Cultura para intervenciones en áreas con potencial arqueológico.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio5">Ver Detalles</button>
</div>
</div>
<!-- Servicio 6 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="ambiental">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=environmental%20consultants%20preparing%20environmental%20impact%20studies%20in%20Peru%2C%20professionals%20analyzing%20data%20and%20creating%20reports%2C%20team%20meeting%20discussing%20environmental%20findings%2C%20professional%20office%20setting%2C%20high%20quality%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv6&orientation=landscape" alt="Estudios Ambientales" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Elaboración de Estudios Ambientales</h3>
<p class="text-gray-600 mb-4">Desarrollo de instrumentos de gestión ambiental según los requerimientos de la normativa peruana.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio6">Ver Detalles</button>
</div>
</div>
<!-- Servicio 7 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="social">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=social%20permit%20management%20in%20Peru%2C%20community%20consultation%20meeting%20with%20indigenous%20Peruvian%20communities%2C%20professionals%20facilitating%20dialogue%20between%20company%20representatives%20and%20local%20people%2C%20rural%20setting%2C%20professional%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv7&orientation=landscape" alt="Permisos Sociales" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Gestión de Permisos Sociales</h3>
<p class="text-gray-600 mb-4">Facilitación de procesos de consulta previa y obtención de licencia social para operar en comunidades.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio7">Ver Detalles</button>
</div>
</div>
<!-- Servicio 8 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="ambiental social arqueologico sst">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=professionals%20preparing%20compliance%20reports%20in%20Peru%2C%20team%20reviewing%20environmental%20and%20safety%20documentation%2C%20people%20analyzing%20data%20and%20creating%20comprehensive%20reports%2C%20professional%20office%20setting%2C%20high%20quality%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv8&orientation=landscape" alt="Informes de Cumplimiento" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Elaboración de Informes de Cumplimiento</h3>
<p class="text-gray-600 mb-4">Preparación de reportes de cumplimiento ambiental, social, arqueológico y de seguridad laboral.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio8">Ver Detalles</button>
</div>
</div>
<!-- Servicio 9 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="ambiental">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=environmental%20training%20workshop%20in%20Peru%2C%20professional%20trainer%20explaining%20environmental%20regulations%20to%20corporate%20audience%2C%20interactive%20training%20session%20with%20presentation%20slides%2C%20professional%20conference%20room%20setting%2C%20high%20quality%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv9&orientation=landscape" alt="Capacitación Ambiental" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Servicios de Capacitación Ambiental</h3>
<p class="text-gray-600 mb-4">Programas de formación en normativa ambiental peruana y buenas prácticas para empresas y organizaciones.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio9">Ver Detalles</button>
</div>
</div>
<!-- Servicio 10 -->
<div class="service-card bg-white rounded-lg shadow-md overflow-hidden transition-all duration-300" data-category="ambiental">
<div class="h-48 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=environmental%20monitoring%20in%20Peru%2C%20professionals%20taking%20water%20and%20soil%20samples%20in%20field%2C%20using%20specialized%20equipment%20to%20measure%20environmental%20parameters%2C%20people%20in%20safety%20gear%20collecting%20environmental%20data%2C%20professional%20field%20setting%2C%20high%20quality%20photography%2C%20natural%20lighting&width=600&height=400&seq=serv10&orientation=landscape" alt="Monitoreo Ambiental" class="w-full h-full object-cover object-top">
</div>
<div class="p-6">
<h3 class="text-xl font-semibold mb-3">Servicio de Monitoreo Ambiental</h3>
<p class="text-gray-600 mb-4">Medición y seguimiento de parámetros ambientales según protocolos y estándares de calidad ambiental peruanos.</p>
<button class="view-details-btn bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full" data-service="servicio10">Ver Detalles</button>
</div>
</div>
</div>
</div>
</section>
<!-- Modal de Detalles del Servicio -->
<div id="service-modal" class="fixed inset-0 bg-black bg-opacity-50 z-50 flex items-center justify-center hidden">
<div class="bg-white rounded-lg max-w-4xl w-full max-h-[90vh] overflow-y-auto">
<div class="p-6">
<div class="flex justify-between items-center mb-6">
<h3 id="modal-title" class="text-2xl font-bold text-gray-900">Detalles del Servicio</h3>
<button id="close-modal" class="w-8 h-8 flex items-center justify-center text-gray-500 hover:text-gray-700">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<div id="modal-content">
<!-- El contenido se llenará dinámicamente -->
</div>
</div>
</div>
</div>
<!-- Nosotros -->
<section id="nosotros" class="py-16 bg-gray-50">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Sobre Nosotros</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Conozca más sobre nuestra empresa y nuestro compromiso con el desarrollo sostenible en Perú.</p>
</div>
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div>
<img src="https://static.readdy.ai/image/96e5929cc978f1d5b2c6005d0965087e/2ef745fc244c90ec849783f9ca498170.jpeg" alt="Nuestro Equipo" class="rounded-lg shadow-md w-full h-auto">
</div>
<div>
<h3 class="text-2xl font-semibold mb-4">Nuestra Historia</h3>
<p class="text-gray-600 mb-6">Fundada en 2016, INEMAC nació con la misión de brindar servicios ambientales de alta calidad que contribuyan al desarrollo sostenible del Perú. A lo largo de los años, hemos crecido hasta convertirnos en una consultora integral que abarca servicios ambientales, sociales, arqueológicos, seguridad laboral e ingenieria.</p>
<h3 class="text-2xl font-semibold mb-4">Misión y Visión</h3>
<div class="mb-6">
<p class="text-gray-600 mb-3"><span class="font-semibold">Misión:</span> Proporcionar soluciones integrales y de alta calidad en gestión ambiental, social, arqueológica y de seguridad laboral que permitan a nuestros clientes cumplir con la normativa peruana y desarrollar sus proyectos de manera sostenible.</p>
<p class="text-gray-600"><span class="font-semibold">Visión:</span> Ser la consultora líder en Perú en servicios ambientales y sociales, reconocida por su excelencia técnica, compromiso ético y contribución al desarrollo sostenible del país.</p>
</div>
<h3 class="text-2xl font-semibold mb-4">Valores</h3>
<ul class="grid grid-cols-1 md:grid-cols-2 gap-3 mb-6">
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-600">Excelencia técnica</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-600">Compromiso ambiental</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-600">Responsabilidad social</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-600">Integridad y ética</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-600">Innovación constante</span>
</li>
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-600">Trabajo en equipo</span>
</li>
</ul>
</div>
</div>
</div>
</section>
<!-- Proyectos Aprobados -->
<section id="proyectos-aprobados" class="py-16 bg-white">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Proyectos Aprobados</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Fichas técnicas socioambientales aprobadas para proyectos de infraestructura en Perú.</p>
</div>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Vía Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Quebrada Tomacucho, Ruta AY 1200: EMP. AY-1199</p>
<p><span class="font-medium">Localidad:</span> Nueva Esperanza – La Merced</p>
<p><span class="font-medium">Distrito:</span> Chaviña</p>
<p><span class="font-medium">Provincia:</span> Lucanas</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2640085</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Camino Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> EMP.RO5046 (Matapuquio) - Chuymala Ancaraypampa - Laguna Isqayccocha - Matermo - Chiribamba</p>
<p><span class="font-medium">Localidad:</span> Chiribamba</p>
<p><span class="font-medium">Distrito:</span> Sancos</p>
<p><span class="font-medium">Provincia:</span> Huanca Sancos</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2611125</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Camino Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Tramo: Patibamba - Ccollpa "Puente Ccolpa"</p>
<p><span class="font-medium">Distrito:</span> Patibamba</p>
<p><span class="font-medium">Provincia:</span> La Mar</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2634375</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Camino Ruta AY-875</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Trayectoria: EMP. AY-106 - Espite - San Jacinto - Pta. Carretera, "Puente Espite"</p>
<p><span class="font-medium">Localidad:</span> Comunidad de Espite</p>
<p><span class="font-medium">Distrito:</span> Vilcanchos</p>
<p><span class="font-medium">Provincia:</span> Victor Fajardo</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2641218</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Camino Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Tramo: Pampahuasi (Puente Pampahuasi)</p>
<p><span class="font-medium">Distrito:</span> Samugari</p>
<p><span class="font-medium">Provincia:</span> La Mar</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2634291</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Camino Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Ruta R050267: Union Potrero-Patahuasi "Puente Patahuasi"</p>
<p><span class="font-medium">Distrito:</span> Chuschi</p>
<p><span class="font-medium">Provincia:</span> Cangallo</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2635260</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Camino Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Tramo: Pampa Hermosa-Michcapampa (Puente Pucachaca)</p>
<p><span class="font-medium">Localidad:</span> Centro Poblado Pampa Hermosa</p>
<p><span class="font-medium">Distrito:</span> Tambo</p>
<p><span class="font-medium">Provincia:</span> La Mar</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2634594</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Vía Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Tramo Paucamarca - Chiquinda (Puente Surumayo)</p>
<p><span class="font-medium">Localidad:</span> Chiquinda</p>
<p><span class="font-medium">Distrito:</span> Gregorio Pita</p>
<p><span class="font-medium">Provincia:</span> San Marcos</p>
<p><span class="font-medium">Departamento:</span> Cajamarca</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2635441</p>
</div>
</div>
<div class="bg-white p-6 rounded-lg shadow-md">
<div class="flex items-center text-primary mb-4">
<i class="ri-file-list-3-line ri-lg"></i>
<span class="ml-2 font-semibold">Ficha Técnica Socioambiental</span>
</div>
<h4 class="font-semibold text-lg mb-3">Renovación de Puente - Camino Vecinal</h4>
<div class="space-y-2 text-gray-600">
<p><span class="font-medium">Ubicación:</span> Ruta Quinua - Acos Vinchos "Puente Tutapa"</p>
<p><span class="font-medium">Distrito:</span> Quinua</p>
<p><span class="font-medium">Provincia:</span> Huamanga</p>
<p><span class="font-medium">Departamento:</span> Ayacucho</p>
<p class="mt-4"><span class="font-medium">CUI N°:</span> 2634281</p>
</div>
</div>
</div>
</div>
</section>
<!-- Contacto -->
<section id="contacto" class="py-16 bg-gray-50">
<div class="container mx-auto px-4">
<div class="text-center mb-12">
<h2 class="text-3xl font-bold text-gray-900 mb-4">Contáctenos</h2>
<p class="text-gray-600 max-w-3xl mx-auto">Estamos listos para ayudarle con sus necesidades en gestión ambiental, social, arqueológica y de seguridad laboral.</p>
</div>
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
<div>
<form action="https://readdy.ai/api/form/d0rrch5sc5d31noa4j00" method="POST" class="bg-white p-8 rounded-lg shadow-md" enctype="application/x-www-form-urlencoded">
<div class="mb-6">
<label for="contact-nombre" class="block text-sm font-medium text-gray-700 mb-1">Nombre Completo</label>
<input type="text" id="contact-nombre" name="nombre" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required>
</div>
<div class="mb-6">
<label for="contact-email" class="block text-sm font-medium text-gray-700 mb-1">Correo Electrónico</label>
<input type="email" id="contact-email" name="email" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required>
</div>
<div class="mb-6">
<label for="contact-telefono" class="block text-sm font-medium text-gray-700 mb-1">Teléfono</label>
<input type="tel" id="contact-telefono" name="telefono" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary">
</div>
<div class="mb-6">
<label for="contact-servicio" class="block text-sm font-medium text-gray-700 mb-1">Servicio de Interés</label>
<div class="relative">
<select id="contact-servicio" name="servicio" class="w-full px-4 py-2 border border-gray-300 rounded appearance-none focus:border-primary pr-8" required>
<option value="">Seleccione un servicio</option>
<option value="supervision">Supervisión Ambiental</option>
<option value="linea-base">Línea Base Socioambiental</option>
<option value="subsanacion">Subsanación de Observaciones</option>
<option value="mapas">Mapas Temáticos</option>
<option value="arqueologia">Permisos Arqueológicos</option>
<option value="estudios">Estudios Ambientales</option>
<option value="permisos-sociales">Permisos Sociales</option>
<option value="informes">Informes de Cumplimiento</option>
<option value="capacitacion">Capacitación Ambiental</option>
<option value="monitoreo">Monitoreo Ambiental</option>
</select>
<div class="absolute inset-y-0 right-0 flex items-center px-2 pointer-events-none text-gray-500">
<i class="ri-arrow-down-s-line"></i>
</div>
</div>
</div>
<div class="mb-6">
<label for="contact-mensaje" class="block text-sm font-medium text-gray-700 mb-1">Mensaje</label>
<textarea id="contact-mensaje" name="mensaje" rows="5" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required></textarea>
</div>
<button type="submit" class="bg-primary text-white px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full">Enviar Mensaje</button>
<div id="contact-form-message" class="hidden mt-4 p-4 rounded text-center"></div>
</form>
</div>
<div>
<div class="bg-white p-8 rounded-lg shadow-md mb-8">
<h3 class="text-xl font-semibold mb-6">Información de Contacto</h3>
<div class="space-y-4">
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4">
<i class="ri-map-pin-line"></i>
</div>
<div>
<h4 class="font-medium">Dirección</h4>
<p class="text-gray-600">PJ. Miraflores, Carmen alto, Huamanga, Ayacucho.</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4">
<i class="ri-phone-line"></i>
</div>
<div>
<h4 class="font-medium">Teléfono</h4>
<p class="text-gray-600">+51 956298271</p>
<p class="text-gray-600">956298271</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4">
<i class="ri-mail-line"></i>
</div>
<div>
<h4 class="font-medium">Correo Electrónico</h4>
<p class="text-gray-600">Walas8712@gmail.com</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4">
<i class="ri-time-line"></i>
</div>
<div>
<h4 class="font-medium">Horario de Atención</h4>
<p class="text-gray-600">Lunes a Viernes: 8:30 AM - 6:00 PM</p>
</div>
</div>
</div>
</div>
<div class="bg-white p-8 rounded-lg shadow-md">
<h3 class="text-xl font-semibold mb-6">Nuestra Ubicación</h3>
<div class="h-64 rounded overflow-hidden bg-gray-200" style="background-image: url('https://public.readdy.ai/gen_page/map_placeholder_1280x720.png'); background-size: cover; background-position: center;"></div>
</div>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="bg-gray-900 text-white pt-16 pb-8">
<div class="container mx-auto px-4">
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-12">
<div>
<a href="#" class="block mb-4 hover:opacity-90 transition-opacity">
<img src="https://static.readdy.ai/image/96e5929cc978f1d5b2c6005d0965087e/453fc979e66c8b05761c20932443328b.jpeg" alt="INEMAC Logo" class="h-12 w-auto brightness-0 invert">
</a>
<p class="text-gray-400 mb-6">INGENIERÍA ESPECIALIZADA EN MEDIO AMBIENTE, CONSTRUCCIÓN Y CAPACITACIÓN - Soluciones integrales para proyectos en Perú.</p>
<div class="flex space-x-4">
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-facebook-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-linkedin-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-instagram-line"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-800 rounded-full hover:bg-primary transition-colors">
<i class="ri-twitter-x-line"></i>
</a>
</div>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Enlaces Rápidos</h3>
<ul class="space-y-3">
<li><a href="#inicio" class="text-gray-400 hover:text-white transition-colors">Inicio</a></li>
<li><a href="#catalogo" class="text-gray-400 hover:text-white transition-colors">Catálogo de Servicios</a></li>
<li><a href="#nosotros" class="text-gray-400 hover:text-white transition-colors">Sobre Nosotros</a></li>
<li><a href="#contacto" class="text-gray-400 hover:text-white transition-colors">Contacto</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Blog</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Servicios</h3>
<ul class="space-y-3">
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Servicios Ambientales</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Servicios Sociales</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Servicios Arqueológicos</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Seguridad en el Trabajo</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Capacitaciones</a></li>
</ul>
</div>
<div>
<h3 class="text-lg font-semibold mb-4">Boletín Informativo</h3>
<p class="text-gray-400 mb-4">Suscríbase para recibir actualizaciones sobre normativa ambiental y nuestros servicios.</p>
<form class="space-y-3">
<div class="relative">
<input type="email" placeholder="Su correo electrónico" class="w-full px-4 py-2 bg-gray-800 border border-gray-700 rounded text-white placeholder-gray-500 focus:border-primary border-none">
</div>
<button type="submit" class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full">Suscribirse</button>
</form>
</div>
</div>
<div class="border-t border-gray-800 pt-8">
<div class="flex flex-col md:flex-row justify-between items-center">
<p class="text-gray-400 text-sm mb-4 md:mb-0">© 2025 INEMAC. Todos los derechos reservados.</p>
<div class="flex space-x-6">
<a href="#" class="text-gray-400 hover:text-white text-sm transition-colors">Política de Privacidad</a>
<a href="#" class="text-gray-400 hover:text-white text-sm transition-colors">Términos de Servicio</a>
<a href="#" class="text-gray-400 hover:text-white text-sm transition-colors">Mapa del Sitio</a>
</div>
</div>
</div>
</div>
</footer>
<!-- Modal de Cotización -->
<div id="quote-modal" class="fixed inset-0 bg-black bg-opacity-50 z-50 flex items-center justify-center hidden">
<div class="bg-white rounded-lg max-w-xl w-full mx-4">
<div class="p-6">
<div class="flex justify-between items-center mb-6">
<h3 class="text-2xl font-bold text-gray-900">Solicitar Cotización</h3>
<button id="close-quote-modal" class="w-8 h-8 flex items-center justify-center text-gray-500 hover:text-gray-700">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<form id="quote-form" action="https://readdy.ai/api/form/d0rrch5sc5d31noa4j00" method="POST" class="space-y-4" enctype="application/x-www-form-urlencoded">
<input type="hidden" name="email_to" value="walas8712@gmail.com">
<div class="grid grid-cols-1 md:grid-cols-2 gap-4">
<div>
<label for="quote-nombre" class="block text-sm font-medium text-gray-700 mb-1">Nombre Completo</label>
<input type="text" id="quote-nombre" name="nombre" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required>
</div>
<div>
<label for="quote-email" class="block text-sm font-medium text-gray-700 mb-1">Correo Electrónico</label>
<input type="email" id="quote-email" name="email" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required>
</div>
</div>
<div>
<label for="quote-telefono" class="block text-sm font-medium text-gray-700 mb-1">Teléfono</label>
<input type="tel" id="quote-telefono" name="telefono" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required>
</div>
<div>
<label for="quote-empresa" class="block text-sm font-medium text-gray-700 mb-1">Empresa</label>
<input type="text" id="quote-empresa" name="empresa" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required>
</div>
<div>
<label for="quote-servicio" class="block text-sm font-medium text-gray-700 mb-1">Servicio de Interés</label>
<div class="relative">
<select id="quote-servicio" name="servicio" class="w-full px-4 py-2 border border-gray-300 rounded appearance-none focus:border-primary pr-8" required>
<option value="">Seleccione un servicio</option>
<option value="supervision">Supervisión Ambiental</option>
<option value="linea-base">Línea Base Socioambiental</option>
<option value="subsanacion">Subsanación de Observaciones</option>
<option value="mapas">Mapas Temáticos</option>
<option value="arqueologia">Permisos Arqueológicos</option>
<option value="estudios">Estudios Ambientales</option>
<option value="permisos-sociales">Permisos Sociales</option>
<option value="informes">Informes de Cumplimiento</option>
<option value="capacitacion">Capacitación Ambiental</option>
<option value="monitoreo">Monitoreo Ambiental</option>
</select>
<div class="absolute inset-y-0 right-0 flex items-center px-2 pointer-events-none text-gray-500">
<i class="ri-arrow-down-s-line"></i>
</div>
</div>
</div>
<div>
<label for="quote-mensaje" class="block text-sm font-medium text-gray-700 mb-1">Detalles del Proyecto</label>
<textarea id="quote-mensaje" name="mensaje" rows="4" maxlength="500" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" required></textarea>
</div>
<button type="submit" class="bg-primary text-white px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors w-full">Enviar Solicitud</button>
</form>
</div>
</div>
</div>
<script id="quote-modal-script">
document.addEventListener('DOMContentLoaded', function() {
const quoteModal = document.getElementById('quote-modal');
const quoteBtn = document.getElementById('quote-btn');
const quoteBtnMobile = document.getElementById('quote-btn-mobile');
const closeQuoteModalBtn = document.getElementById('close-quote-modal');
const quoteForm = document.getElementById('quote-form');
const modalHandlers = {
open() {
quoteModal.classList.remove('hidden');
document.body.style.overflow = 'hidden';
},
close() {
quoteModal.classList.add('hidden');
document.body.style.overflow = 'auto';
}
};
quoteBtn.addEventListener('click', modalHandlers.open);
quoteBtnMobile.addEventListener('click', modalHandlers.open);
closeQuoteModalBtn.addEventListener('click', modalHandlers.close);
quoteModal.addEventListener('click', function(e) {
if (e.target === quoteModal) {
modalHandlers.close();
}
});
quoteForm.addEventListener('submit', function(e) {
e.preventDefault();
const formData = new FormData(this);
const confirmationDialog = document.createElement('div');
confirmationDialog.className = 'fixed inset-0 bg-black bg-opacity-50 z-50 flex items-center justify-center';
confirmationDialog.innerHTML = `
<div class="bg-white rounded-lg p-6 max-w-sm w-full mx-4 relative">
<div class="text-center">
<div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
<i class="ri-check-line ri-2x text-green-500"></i>
</div>
<h3 class="text-xl font-semibold text-gray-900 mb-2">¡Solicitud Enviada!</h3>
<p class="text-gray-600 mb-6">Gracias por su interés. Nos pondremos en contacto con usted a la brevedad para proporcionarle una cotización detallada.</p>
<button class="bg-primary text-white px-6 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">Aceptar</button>
</div>
</div>
`;
fetch(this.action, {
method: 'POST',
body: new URLSearchParams(formData),
headers: {
'Content-Type': 'application/x-www-form-urlencoded',
},
})
.then(response => {
if (!response.ok) {
throw new Error('Error en el envío');
}
modalHandlers.close();
this.reset();
document.body.appendChild(confirmationDialog);
})
.catch(error => {
console.error('Error:', error);
});
confirmationDialog.querySelector('button').addEventListener('click', function() {
document.body.removeChild(confirmationDialog);
});
});
});
</script>
<script id="mobile-menu-script">
document.addEventListener('DOMContentLoaded', function() {
const mobileMenuButton = document.getElementById('mobile-menu-button');
const mobileMenu = document.getElementById('mobile-menu');
mobileMenuButton.addEventListener('click', function() {
mobileMenu.classList.toggle('hidden');
});
// Cerrar menú al hacer clic en un enlace y scroll suave
const mobileLinks = mobileMenu.querySelectorAll('a');
mobileLinks.forEach(link => {
link.addEventListener('click', function(e) {
mobileMenu.classList.add('hidden');
if (this.getAttribute('href') !== '#') {
e.preventDefault();
const targetId = this.getAttribute('href').substring(1);
const targetElement = document.getElementById(targetId);
if (targetElement) {
targetElement.scrollIntoView({ behavior: 'smooth' });
}
}
});
});
// Scroll suave para enlaces del menú desktop
const desktopLinks = document.querySelectorAll('nav.md\\:flex a');
desktopLinks.forEach(link => {
link.addEventListener('click', function(e) {
e.preventDefault();
const href = this.getAttribute('href');
if (href === '#inicio') {
window.scrollTo({ top: 0, behavior: 'smooth' });
} else if (href !== '#') {
const targetId = href.substring(1);
const targetElement = document.getElementById(targetId);
if (targetElement) {
targetElement.scrollIntoView({ behavior: 'smooth' });
}
}
});
});
});
</script>
<script id="service-filter-script">
document.addEventListener('DOMContentLoaded', function() {
const filterButtons = document.querySelectorAll('.filter-btn');
const serviceCards = document.querySelectorAll('.service-card');
filterButtons.forEach(button => {
button.addEventListener('click', function() {
// Remover clase active de todos los botones
filterButtons.forEach(btn => {
btn.classList.remove('active', 'bg-primary', 'text-white');
btn.classList.add('bg-white', 'border', 'border-gray-300', 'text-gray-700', 'hover:bg-gray-50');
});
// Agregar clase active al botón clickeado
this.classList.add('active', 'bg-primary', 'text-white');
this.classList.remove('bg-white', 'border', 'border-gray-300', 'text-gray-700', 'hover:bg-gray-50');
const filter = this.getAttribute('data-filter');
// Filtrar tarjetas
serviceCards.forEach(card => {
if (filter === 'all' || card.getAttribute('data-category').includes(filter)) {
card.style.display = 'block';
} else {
card.style.display = 'none';
}
});
});
});
});
</script>
<script id="service-modal-script">
document.addEventListener('DOMContentLoaded', function() {
const modal = document.getElementById('service-modal');
const closeModal = document.getElementById('close-modal');
const modalTitle = document.getElementById('modal-title');
const modalContent = document.getElementById('modal-content');
const modalForm = document.getElementById('modal-form');
const viewDetailsButtons = document.querySelectorAll('.view-details-btn');
// Datos de los servicios
const serviciosData = {
servicio1: {
titulo: "Supervisión Ambiental en Campo",
descripcion: "Nuestro servicio de supervisión ambiental en campo garantiza el cumplimiento de los compromisos ambientales establecidos en los instrumentos de gestión ambiental aprobados y la normativa ambiental peruana vigente.",
beneficios: [
"Prevención de incumplimientos y sanciones ambientales",
"Documentación adecuada de las actividades de supervisión",
"Identificación temprana de riesgos ambientales",
"Asesoramiento técnico especializado en tiempo real",
"Informes detallados con evidencia fotográfica y recomendaciones"
],
proceso: [
"Planificación de la supervisión según cronograma del proyecto",
"Revisión de compromisos ambientales aplicables",
"Ejecución de la supervisión en campo",
"Documentación de hallazgos y evidencias",
"Elaboración de informes de supervisión",
"Seguimiento a la implementación de medidas correctivas"
]
},
servicio2: {
titulo: "Elaboración de Línea Base Socioambiental",
descripcion: "Desarrollamos estudios de línea base socioambiental completos que caracterizan las condiciones iniciales del entorno físico, biológico y social del área de influencia de un proyecto, cumpliendo con los requisitos establecidos en la normativa peruana.",
beneficios: [
"Base sólida para la evaluación de impactos",
"Identificación de áreas sensibles y especies protegidas",
"Caracterización adecuada de ecosistemas y comunidades",
"Información de calidad para la toma de decisiones",
"Cumplimiento de estándares técnicos y legales"
],
proceso: [
"Definición del alcance y metodología del estudio",
"Revisión de información secundaria disponible",
"Planificación y ejecución de trabajo de campo",
"Muestreo y análisis de componentes ambientales",
"Levantamiento de información social",
"Procesamiento de datos y elaboración del informe final"
]
},
servicio3: {
titulo: "Subsanación de Observaciones Ambientales",
descripcion: "Brindamos asistencia especializada para responder y subsanar observaciones emitidas por las autoridades ambientales peruanas (SENACE, OEFA, ANA, SERFOR, etc.) a los instrumentos de gestión ambiental presentados.",
beneficios: [
"Respuestas técnicamente sólidas y legalmente fundamentadas",
"Reducción de tiempos de aprobación",
"Minimización de riesgos de rechazo",
"Asesoramiento por especialistas con experiencia en evaluación",
"Acompañamiento durante todo el proceso de evaluación"
],
proceso: [
"Análisis detallado de las observaciones recibidas",
"Identificación de información complementaria requerida",
"Coordinación con el equipo técnico del cliente",
"Elaboración de respuestas y documentación de soporte",
"Revisión de calidad y consistencia",
"Presentación formal ante la autoridad competente"
]
},
servicio4: {
titulo: "Elaboración de Mapas Temáticos Socioambientales",
descripcion: "Desarrollamos cartografía especializada utilizando sistemas de información geográfica (SIG) para representar variables ambientales, sociales y arqueológicas relevantes para los proyectos y estudios ambientales.",
beneficios: [
"Visualización clara de información espacial compleja",
"Análisis territorial integrado",
"Cumplimiento de estándares cartográficos peruanos",
"Soporte para la toma de decisiones",
"Mapas de alta calidad para informes y presentaciones"
],
proceso: [
"Definición de necesidades cartográficas",
"Recopilación y validación de datos espaciales",
"Procesamiento de información georreferenciada",
"Diseño y elaboración de mapas temáticos",
"Control de calidad cartográfica",
"Entrega en formatos digitales e impresos"
]
},
servicio5: {
titulo: "Gestión de Permisos Arqueológicos",
descripcion: "Gestionamos la obtención de permisos y certificaciones arqueológicas requeridas por el Ministerio de Cultura para el desarrollo de proyectos en áreas con potencial arqueológico, conforme a la Ley General del Patrimonio Cultural de la Nación.",
beneficios: [
"Cumplimiento de la normativa arqueológica peruana",
"Prevención de paralizaciones por hallazgos fortuitos",
"Protección del patrimonio cultural",
"Reducción de riesgos legales y reputacionales",
"Acompañamiento por arqueólogos certificados"
],
proceso: [
"Evaluación arqueológica preliminar",
"Elaboración del Proyecto de Evaluación Arqueológica (PEA)",
"Gestión de autorizaciones ante el Ministerio de Cultura",
"Ejecución de trabajos arqueológicos en campo",
"Elaboración del informe final",
"Obtención del Certificado de Inexistencia de Restos Arqueológicos (CIRA)"
]
},
servicio6: {
titulo: "Elaboración de Estudios Ambientales",
descripcion: "Desarrollamos instrumentos de gestión ambiental completos (DIA, EIA-sd, EIA-d, MEIA, ITS, etc.) que cumplen con los requisitos establecidos en la normativa ambiental peruana para diferentes sectores productivos.",
beneficios: [
"Estudios técnicamente robustos y legalmente viables",
"Equipo multidisciplinario especializado",
"Conocimiento actualizado de la normativa sectorial",
"Optimización de medidas de manejo ambiental",
"Acompañamiento durante todo el proceso de evaluación"
],
proceso: [
"Análisis del proyecto y marco normativo aplicable",
"Elaboración del plan de trabajo",
"Desarrollo de la línea base ambiental y social",
"Identificación y evaluación de impactos",
"Diseño de la estrategia de manejo ambiental",
"Elaboración del estudio y presentación a la autoridad"
]
},
servicio7: {
titulo: "Gestión de Permisos Sociales",
descripcion: "Facilitamos los procesos de consulta previa, participación ciudadana y obtención de licencia social para operar, cumpliendo con la normativa peruana y los estándares internacionales de relacionamiento comunitario.",
beneficios: [
"Construcción de relaciones de confianza con comunidades",
"Prevención y gestión de conflictos sociales",
"Cumplimiento de estándares nacionales e internacionales",
"Facilitación intercultural efectiva",
"Documentación adecuada de procesos participativos"
],
proceso: [
"Mapeo de actores sociales e identificación de intereses",
"Diseño de estrategia de relacionamiento comunitario",
"Implementación de mecanismos de participación ciudadana",
"Facilitación de procesos de consulta previa",
"Negociación de acuerdos y convenios",
"Seguimiento a compromisos sociales"
]
},
servicio8: {
titulo: "Elaboración de Informes de Cumplimiento",
descripcion: "Preparamos informes de cumplimiento ambiental, social, arqueológico y de seguridad laboral requeridos por las autoridades peruanas, asegurando la documentación adecuada de las obligaciones legales y compromisos asumidos.",
beneficios: [
"Cumplimiento oportuno de obligaciones de reporte",
"Documentación sistemática de evidencias",
"Identificación de oportunidades de mejora",
"Prevención de sanciones por incumplimiento",
"Trazabilidad de la gestión socioambiental"
],
proceso: [
"Revisión de obligaciones de reporte aplicables",
"Recopilación y análisis de información",
"Verificación de cumplimiento de compromisos",
"Elaboración del informe según formato requerido",
"Control de calidad y consistencia",
"Presentación ante la autoridad competente"
]
},
servicio9: {
titulo: "Servicios de Capacitación Ambiental",
descripcion: "Ofrecemos programas de capacitación especializados en normativa ambiental peruana, buenas prácticas ambientales y sistemas de gestión, adaptados a las necesidades específicas de cada organización.",
beneficios: [
"Personal actualizado en normativa ambiental",
"Fortalecimiento de capacidades internas",
"Reducción de riesgos por desconocimiento",
"Metodologías participativas y prácticas",
"Materiales didácticos personalizados"
],
proceso: [
"Diagnóstico de necesidades de capacitación",
"Diseño del programa formativo",
"Elaboración de materiales didácticos",
"Implementación de talleres y cursos",
"Evaluación de aprendizaje",
"Seguimiento y reforzamiento"
]
},
servicio10: {
titulo: "Servicio de Monitoreo Ambiental",
descripcion: "Realizamos monitoreos ambientales de agua, aire, suelo, ruido, flora, fauna y otros componentes ambientales, siguiendo los protocolos establecidos por el MINAM y los estándares de calidad ambiental peruanos.",
beneficios: [
"Cumplimiento de programas de monitoreo aprobados",
"Equipos calibrados y métodos acreditados",
"Detección temprana de desviaciones",
"Interpretación técnica de resultados",
"Recomendaciones para la gestión ambiental"
],
proceso: [
"Planificación del monitoreo según normativa aplicable",
"Preparación de equipos y materiales",
"Ejecución del monitoreo en campo",
"Análisis de muestras en laboratorios acreditados",
"Procesamiento e interpretación de datos",
"Elaboración del informe de monitoreo"
]
}
};
// Abrir modal con detalles del servicio
viewDetailsButtons.forEach(button => {
button.addEventListener('click', function() {
const serviceId = this.getAttribute('data-service');
const serviceData = serviciosData[serviceId];
modalTitle.textContent = serviceData.titulo;
let contentHTML = `
<div class="mb-6">
<h4 class="text-lg font-semibold mb-3">Descripción</h4>
<p class="text-gray-600">${serviceData.descripcion}</p>
</div>
<div class="mb-6">
<h4 class="text-lg font-semibold mb-3">Beneficios</h4>
<ul class="space-y-2">
`;
serviceData.beneficios.forEach(beneficio => {
contentHTML += `
<li class="flex items-start">
<div class="w-6 h-6 flex items-center justify-center text-primary mr-2 mt-0.5">
<i class="ri-check-line"></i>
</div>
<span class="text-gray-600">${beneficio}</span>
</li>
`;
});
contentHTML += `
</ul>
</div>
<div>
<h4 class="text-lg font-semibold mb-3">Proceso de Trabajo</h4>
<ol class="space-y-2 list-decimal list-inside text-gray-600 pl-4">
`;
serviceData.proceso.forEach(paso => {
contentHTML += `<li>${paso}</li>`;
});
contentHTML += `
</ol>
</div>
`;
modalContent.innerHTML = contentHTML;
modal.classList.remove('hidden');
// Evitar scroll del body
document.body.style.overflow = 'hidden';
});
});
// Cerrar modal
closeModal.addEventListener('click', function() {
modal.classList.add('hidden');
document.body.style.overflow = 'auto';
});
// Cerrar modal al hacer clic fuera del contenido
modal.addEventListener('click', function(e) {
if (e.target === modal) {
modal.classList.add('hidden');
document.body.style.overflow = 'auto';
}
});
});
</script>
<script id="contact-form-script">
document.addEventListener('DOMContentLoaded', function() {
const contactForm = document.querySelector('#contacto form');
const contactFormMessage = document.getElementById('contact-form-message');
contactForm.addEventListener('submit', function(e) {
e.preventDefault();
const formData = new FormData(this);
const confirmationDialog = document.createElement('div');
confirmationDialog.className = 'fixed inset-0 bg-black bg-opacity-50 z-50 flex items-center justify-center';
confirmationDialog.innerHTML = `
<div class="bg-white rounded-lg p-6 max-w-sm w-full mx-4 relative">
<div class="text-center">
<div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
<i class="ri-check-line ri-2x text-green-500"></i>
</div>
<h3 class="text-xl font-semibold text-gray-900 mb-2">¡Mensaje Enviado!</h3>
<p class="text-gray-600 mb-6">Gracias por contactarnos. Nos pondremos en contacto con usted a la brevedad.</p>
<button class="bg-primary text-white px-6 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition-colors">Aceptar</button>
</div>
</div>
`;
document.body.appendChild(confirmationDialog);
document.body.style.overflow = 'hidden';
confirmationDialog.querySelector('button').addEventListener('click', function() {
document.body.removeChild(confirmationDialog);
document.body.style.overflow = 'auto';
});
fetch(this.action, {
method: 'POST',
body: new URLSearchParams(formData),
headers: {
'Content-Type': 'application/x-www-form-urlencoded',
},
})
.then(response => {
if (!response.ok) {
throw new Error('Error en el envío');
}
this.reset();
})
.catch(error => {
const messageElement = contactFormMessage;
messageElement.classList.remove('hidden');
messageElement.classList.add('bg-red-100', 'text-red-700', 'p-4', 'rounded');
messageElement.textContent = 'Error al enviar el mensaje. Por favor, inténtelo de nuevo.';
});
});
});
</script>
</body>
</html>
