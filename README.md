<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda Profesional</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-900">
  <!-- Header -->
  <header class="bg-white shadow">
    <div class="max-w-7xl mx-auto px-4 py-6 flex justify-between items-center">
      <h1 class="text-2xl font-bold">TiendaPro</h1>
      <nav class="space-x-4">
        <a href="#" class="text-gray-700 hover:text-blue-600">Inicio</a>
        <a href="#productos" class="text-gray-700 hover:text-blue-600">Productos</a>
        <a href="#contacto" class="text-gray-700 hover:text-blue-600">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-blue-100 py-20 text-center">
    <h2 class="text-4xl font-bold mb-4">Encuentra los mejores productos al mejor precio</h2>
    <p class="text-lg">Calidad, confianza y servicio al cliente garantizados</p>
  </section>

  <!-- Productos -->
  <section id="productos" class="max-w-7xl mx-auto px-4 py-12">
    <h3 class="text-3xl font-bold mb-8 text-center">Nuestros Productos</h3>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <!-- Producto 1 -->
      <div class="bg-white rounded-2xl shadow p-6 text-center">
        <img src="https://via.placeholder.com/200" alt="Producto 1" class="mx-auto mb-4">
        <h4 class="text-xl font-semibold mb-2">Producto 1</h4>
        <p class="text-gray-600 mb-2">Descripción breve del producto.</p>
        <p class="font-bold text-lg mb-4">$49.99</p>
        <button class="bg-blue-600 text-white px-4 py-2 rounded-xl hover:bg-blue-700">Comprar</button>
      </div>
      <!-- Producto 2 -->
      <div class="bg-white rounded-2xl shadow p-6 text-center">
        <img src="https://via.placeholder.com/200" alt="Producto 2" class="mx-auto mb-4">
        <h4 class="text-xl font-semibold mb-2">Producto 2</h4>
        <p class="text-gray-600 mb-2">Descripción breve del producto.</p>
        <p class="font-bold text-lg mb-4">$39.99</p>
        <button class="bg-blue-600 text-white px-4 py-2 rounded-xl hover:bg-blue-700">Comprar</button>
      </div>
      <!-- Producto 3 -->
      <div class="bg-white rounded-2xl shadow p-6 text-center">
        <img src="https://via.placeholder.com/200" alt="Producto 3" class="mx-auto mb-4">
        <h4 class="text-xl font-semibold mb-2">Producto 3</h4>
        <p class="text-gray-600 mb-2">Descripción breve del producto.</p>
        <p class="font-bold text-lg mb-4">$29.99</p>
        <button class="bg-blue-600 text-white px-4 py-2 rounded-xl hover:bg-blue-700">Comprar</button>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="bg-gray-100 py-12 px-4">
    <div class="max-w-3xl mx-auto">
      <h3 class="text-3xl font-bold mb-6 text-center">Contáctanos</h3>
      <form class="space-y-4">
        <input type="text" placeholder="Nombre" class="w-full p-3 border border-gray-300 rounded-xl">
        <input type="email" placeholder="Correo electrónico" class="w-full p-3 border border-gray-300 rounded-xl">
        <textarea placeholder="Mensaje" rows="4" class="w-full p-3 border border-gray-300 rounded-xl"></textarea>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded-xl hover:bg-blue-700 w-full">Enviar mensaje</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-white shadow mt-12">
    <div class="max-w-7xl mx-auto px-4 py-6 text-center text-gray-500">
      &copy; 2025 TiendaPro. Todos los derechos reservados.
    </div>
  </footer>
</body>
</html>
