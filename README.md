<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Xixuñas - Pedicura y Manicura</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="icon" href="logo.png" type="image/png">
</head>
<body class="bg-white text-gray-800 font-sans">
  <!-- Encabezado -->
  <header class="text-center py-10 border-b">
    <img src="Captura de pantalla 2025-05-16 a las 14.26.10.png" alt="Logo Xixuñas" class="mx-auto w-32">
    <h1 class="text-3xl font-bold mt-4">Xixuñas</h1>
    <p class="text-gray-500">Especialistas en pedicura y manicura en Sanlúcar de Barrameda</p>
  </header>

  <!-- Servicios -->
  <section class="py-10 px-6 text-center">
    <h2 class="text-2xl font-semibold mb-6">Nuestros servicios</h2>
    <div class="flex flex-col md:flex-row justify-center gap-6">
      <div class="bg-orange-100 p-6 rounded-2xl shadow w-full max-w-sm">
        <h3 class="text-xl font-bold mb-2">Manicura</h3>
        <p>Embellece tus manos con nuestros servicios de manicura profesional.</p>
      </div>
      <div class="bg-orange-100 p-6 rounded-2xl shadow w-full max-w-sm">
        <h3 class="text-xl font-bold mb-2">Pedicura</h3>
        <p>Relaja tus pies y luce unas uñas perfectas con nuestra pedicura.</p>
      </div>
    </div>
  </section>

  <!-- Formulario de cita -->
  <section class="py-10 px-6 bg-gray-100">
    <h2 class="text-2xl font-semibold text-center mb-6">Solicita tu cita</h2>
    <form class="max-w-xl mx-auto bg-white p-6 rounded-2xl shadow space-y-4" action="mailto:tucorreo@ejemplo.com" method="POST">
      <input type="text" name="nombre" placeholder="Tu nombre" required class="w-full border border-gray-300 rounded px-4 py-2">
      <input type="email" name="email" placeholder="Tu correo electrónico" required class="w-full border border-gray-300 rounded px-4 py-2">
      <input type="tel" name="telefono" placeholder="Tu número de teléfono" required class="w-full border border-gray-300 rounded px-4 py-2">
      <select name="servicio" required class="w-full border border-gray-300 rounded px-4 py-2">
        <option value="">Selecciona un servicio</option>
        <option value="manicura">Manicura</option>
        <option value="pedicura">Pedicura</option>
      </select>
      <input type="date" name="fecha" required class="w-full border border-gray-300 rounded px-4 py-2">
      <input type="time" name="hora" required class="w-full border border-gray-300 rounded px-4 py-2">
      <textarea name="mensaje" placeholder="Mensaje adicional (opcional)" class="w-full border border-gray-300 rounded px-4 py-2"></textarea>
      <button type="submit" class="bg-orange-500 text-white px-6 py-2 rounded hover:bg-orange-600 transition">Enviar solicitud</button>
    </form>
  </section>

  <!-- Ubicación -->
  <section class="py-10 px-6 text-center">
    <h2 class="text-2xl font-semibold mb-2">¿Dónde estamos?</h2>
    <p class="mb-4">Calle Juan XXIII, 10<br>Sanlúcar de Barrameda</p>
    <iframe class="mx-auto w-full max-w-md h-64 rounded-2xl" src="https://www.google.com/maps?q=Calle+Juan+XXIII+10,+Sanl%C3%BAcar+de+Barrameda&output=embed"></iframe>
  </section>

  <!-- WhatsApp -->
  <a href="https://wa.me/34600000000" class="fixed bottom-4 right-4 bg-green-500 hover:bg-green-600 text-white p-4 rounded-full shadow-lg" target="_blank" aria-label="WhatsApp">
    <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path stroke-linecap="round" stroke-linejoin="round" d="M16.72 12.46c-.2-.1-1.2-.6-1.4-.7-.2-.1-.4-.1-.5.1-.2.2-.5.7-.6.9-.1.2-.3.2-.6.1-.3-.2-1.2-.4-2.2-1.3-.8-.7-1.4-1.5-1.6-1.9-.2-.3 0-.5.1-.6.1-.1.2-.3.3-.4.1-.1.1-.2.2-.3.1-.2.1-.3 0-.5-.1-.1-.5-1.1-.7-1.5-.2-.4-.4-.3-.5-.3-.1 0-.2 0-.3 0-.1 0-.3.1-.4.2-.1.1-.5.5-.5 1.2 0 .7.5 1.3.6 1.4.1.2 1.1 1.8 2.7 2.6 1.7.9 2 .8 2.3.7.4-.1 1.2-.5 1.3-1.1.1-.6.1-1 .1-1.1-.1-.1-.2-.1-.4-.2z"></path>
    </svg>
  </a>

  <!-- Footer -->
  <footer class="text-center text-sm text-gray-400 py-6 border-t">
    &copy; 2025 Xixuñas. Todos los derechos reservados.
  </footer>
</body>
</html>
