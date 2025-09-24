<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Drive Latam – Sostenible | Comunidades sostenibles</title>
  <meta name="description" content="Aceleramos el desarrollo de comunidades sostenibles en Perú mediante transporte limpio e iniciativas de desarrollo con impacto social, ambiental y económico." />
  <meta name="theme-color" content="#0ea5e9"/>
  <meta property="og:type" content="website"/>
  <meta property="og:title" content="Drive Latam – Sostenible"/>
  <meta property="og:description" content="Comunidades sostenibles: transporte limpio + iniciativas de desarrollo"/>
  <meta property="og:image" content="/assets/og-banner.jpg"/>
  <meta property="og:url" content="https://tu-dominio.github.io/DriveLatamSostenible/"/>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>tailwind.config={theme:{extend:{colors:{primary:{DEFAULT:'#0ea5e9',dark:'#0284c7'},accent:'#22c55e'},fontFamily:{sans:['Inter','ui-sans-serif','system-ui','Segoe UI','Roboto','Helvetica Neue','Arial']}}}};</script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    .bg-grid{background-size:22px 22px;background-image:linear-gradient(to right,rgba(14,165,233,.06) 1px,transparent 1px),linear-gradient(to bottom,rgba(14,165,233,.06) 1px,transparent 1px)}
    .glass{backdrop-filter:blur(10px);background:rgba(255,255,255,.6)}
  </style>
</head>
<body class="font-sans text-slate-800">
  <header class="sticky top-0 z-50 bg-white/80 backdrop-blur border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <a href="#home" class="flex items-center gap-3">
          <svg width="32" height="32" viewBox="0 0 64 64" fill="none" aria-hidden="true">
            <path d="M6 44c8-8 16-8 24 0 8 8 15 8 22 0" stroke="#0ea5e9" stroke-width="4" stroke-linecap="round"/>
            <path d="M18 40l10-14 10 14" stroke="#22c55e" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M46 28v12M52 24v16M58 30v10" stroke="#0f172a" stroke-width="3" stroke-linecap="round"/>
          </svg>
          <span class="text-lg font-semibold">Drive Latam – <span class="text-primary">Sostenible</span></span>
        </a>
        <nav class="hidden md:flex items-center gap-6 text-sm font-medium">
          <a href="#vision" class="hover:text-primary">Visión</a>
          <a href="#servicios" class="hover:text-primary">Servicios</a>
          <a href="#diferencial" class="hover:text-primary">Diferencial</a>
          <a href="#roadmap" class="hover:text-primary">Roadmap</a>
          <a href="#casos" class="hover:text-primary">Casos</a>
          <a href="#contacto" class="inline-flex items-center px-3 py-2 rounded-xl bg-primary text-white hover:bg-primary-dark">Contáctanos</a>
        </nav>
        <button id="menuBtn" class="md:hidden inline-flex items-center px-3 py-2 rounded-lg border border-slate-300">Menú</button>
      </div>
    </div>
    <div id="mobileMenu" class="md:hidden hidden border-t border-slate-200 bg-white">
      <nav class="max-w-7xl mx-auto px-4 py-3 flex flex-col gap-3 text-sm">
        <a href="#vision" class="hover:text-primary">Visión</a>
        <a href="#servicios" class="hover:text-primary">Servicios</a>
        <a href="#diferencial" class="hover:text-primary">Diferencial</a>
        <a href="#roadmap" class="hover:text-primary">Roadmap</a>
        <a href="#casos" class="hover:text-primary">Casos</a>
        <a href="#contacto" class="inline-flex items-center justify-center px-3 py-2 rounded-xl bg-primary text-white hover:bg-primary-dark">Contáctanos</a>
      </nav>
    </div>
  </header>

  <section id="home" class="relative overflow-hidden bg-grid">
    <div class="absolute inset-0 bg-gradient-to-b from-white/0 via-white/60 to-white"></div>
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-16 pb-20">
      <div class="grid lg:grid-cols-2 items-center gap-10">
        <div>
          <h1 class="text-3xl sm:text-4xl lg:text-5xl font-bold leading-tight text-slate-900">Comunidades sostenibles que <span class="text-primary">mejoran la vida</span></h1>
          <p class="mt-5 text-lg text-slate-700 max-w-prose">Impulsamos proyectos de <strong>transporte limpio</strong> e <strong>iniciativas de desarrollo</strong> con impacto ambiental, social y económico. Empezamos en Perú con visión de expansión regional.</p>
          <div class="mt-6 flex flex-wrap gap-3">
            <a href="#contacto" class="inline-flex items-center px-5 py-3 rounded-xl bg-primary text-white hover:bg-primary-dark">Agendar reunión</a>
            <a href="#servicios" class="inline-flex items-center px-5 py-3 rounded-xl border border-slate-300 hover:border-primary hover:text-primary">Ver servicios</a>
          </div>
          <div class="mt-6 text-sm text-slate-500">Más de 6 años impulsando electromovilidad y sostenibilidad en LATAM</div>
        </div>
        <div class="relative">
          <div class="glass rounded-3xl shadow-xl p-6">
            <div class="grid grid-cols-3 gap-4 text-center">
              <div class="p-4 rounded-2xl bg-white shadow border border-slate-100"><div class="text-3xl font-bold">CO₂↓</div><div class="text-xs text-slate-500 mt-1">Descarbonización</div></div>
              <div class="p-4 rounded-2xl bg-white shadow border border-slate-100"><div class="text-3xl font-bold">EV</div><div class="text-xs text-slate-500 mt-1">Transporte limpio</div></div>
              <div class="p-4 rounded-2xl bg-white shadow border border-slate-100"><div class="text-3xl font-bold">ODS</div><div class="text-xs text-slate-500 mt-1">Impacto social</div></div>
            </div>
            <p class="text-sm text-slate-600 mt-4">Modelo replicable y financiable con métricas de impacto.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="vision" class="py-16">
    <div class="max-w-6xl mx-auto px-4">
      <div class="grid lg:grid-cols-3 gap-8">
        <div class="lg:col-span-2">
          <h2 class="text-2xl sm:text-3xl font-semibold">Nuestra visión</h2>
          <p class="mt-4 text-slate-700 leading-relaxed">Construir <strong>comunidades sostenibles</strong> en Latinoamérica, donde las personas vivan mejor gracias a un <strong>transporte limpio</strong> e <strong>iniciativas de desarrollo</strong> que impacten su día a día.</p>
        </div>
        <div class="bg-slate-50 border border-slate-200 rounded-2xl p-5">
          <h3 class="font-semibold">Elevator pitch (30s)</h3>
          <p class="mt-2 text-sm text-slate-700">Somos Drive Latam – Sostenible. Aceleramos proyectos que construyen comunidades sostenibles mediante transporte limpio e iniciativas de desarrollo. Validamos en Perú y escalamos con indicadores de impacto y retorno.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="servicios" class="py-16 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-2xl sm:text-3xl font-semibold">Qué hacemos</h2>
      <p class="mt-2 text-slate-600">Dos verticales que habilitan la visión.</p>
      <div class="mt-8 grid md:grid-cols-2 gap-6">
        <div class="bg-white rounded-2xl p-6 border border-slate-200 shadow-sm">
          <div class="flex items-start gap-3">
            <span class="inline-flex h-10 w-10 items-center justify-center rounded-xl bg-sky-100 text-primary">🚚</span>
            <div>
              <h3 class="text-lg font-semibold">Transporte sostenible</h3>
              <p class="mt-1 text-slate-600 text-sm">Electromovilidad para minería, logística y urbano: diseño, instalación y operación de infraestructura de carga, TCO y capacitación.</p>
              <ul class="mt-3 space-y-2 text-sm list-disc list-inside text-slate-700">
                <li>Proyectos EV-Ready (diseño + EPC + O&M)</li>
                <li>Gestión de carga (AC/DC), software y data</li>
                <li>Pilotos con KPIs y escalamiento</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="bg-white rounded-2xl p-6 border border-slate-200 shadow-sm">
          <div class="flex items-start gap-3">
            <span class="inline-flex h-10 w-10 items-center justify-center rounded-xl bg-green-100 text-accent">🌱</span>
            <div>
              <h3 class="text-lg font-semibold">Iniciativas de desarrollo</h3>
              <p class="mt-1 text-slate-600 text-sm">Programas de energía, deporte, educación y gestión ambiental con impacto social y económico.</p>
              <ul class="mt-3 space-y-2 text-sm list-disc list-inside text-slate-700">
                <li>Deporte sostenible y academias</li>
                <li>Gestión de residuos y economía circular</li>
                <li>Educación y certificaciones</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="diferencial" class="py-16">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-2xl sm:text-3xl font-semibold">Por qué nosotros</h2>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="rounded-2xl border border-slate-200 p-6"><h3 class="font-semibold">Experiencia comprobada</h3><p class="mt-2 text-sm text-slate-700">6+ años en electromovilidad en Perú: minería, logística y urbano. Casos reales y redes de aliados.</p></div>
        <div class="rounded-2xl border border-slate-200 p-6"><h3 class="font-semibold">Modelo replicable</h3><p class="mt-2 text-sm text-slate-700">Metodologías y productos estandarizados (EV-Ready, KPIs, MOUs) para escalar por territorios.</p></div>
        <div class="rounded-2xl border border-slate-200 p-6"><h3 class="font-semibold">Impacto medible</h3><p class="mt-2 text-sm text-slate-700">KPIs ambientales (CO₂), sociales (empleo, salud) y económicos (TCO, ROI) listos para inversionistas.</p></div>
      </div>
    </div>
  </section>

  <section id="roadmap" class="py-16 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-2xl sm:text-3xl font-semibold">Roadmap de crecimiento</h2>
      <div class="mt-8 grid lg:grid-cols-3 gap-6">
        <div class="rounded-2xl border border-slate-200 bg-white p-6">
          <span class="text-xs font-semibold text-slate-500">Fase 1 · 0–12 meses</span>
          <h3 class="mt-1 font-semibold">Perú (validación)</h3>
          <ul class="mt-3 text-sm space-y-2 list-disc list-inside text-slate-700">
            <li>3–5 pilotos EV-Ready (minería/logística/urbano)</li>
            <li>2 programas de deporte/educación sostenible</li>
            <li>Primeras alianzas público-privadas</li>
          </ul>
        </div>
        <div class="rounded-2xl border border-slate-200 bg-white p-6">
          <span class="text-xs font-semibold text-slate-500">Fase 2 · 12–24 meses</span>
          <h3 class="mt-1 font-semibold">Consolidación</h3>
          <ul class="mt-3 text-sm space-y-2 list-disc list-inside text-slate-700">
            <li>Producto estandarizado (kits EV-Ready + O&M)</li>
            <li>Marketplace de aliados y financiamiento</li>
            <li>Contratos multianuales (SLA)</li>
          </ul>
        </div>
        <div class="rounded-2xl border border-slate-200 bg-white p-6">
          <span class="text-xs font-semibold text-slate-500">Fase 3 · 24–36 meses</span>
          <h3 class="mt-1 font-semibold">Internacionalización</h3>
          <ul class="mt-3 text-sm space-y-2 list-disc list-inside text-slate-700">
            <li>Entrada a 2–3 países (Andino/Cono Sur)</li>
            <li>Escalamiento de portafolio y certificaciones</li>
            <li>Fondo de proyectos de impacto</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <section id="casos" class="py-16">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-2xl sm:text-3xl font-semibold">Casos & aliados</h2>
      <p class="mt-2 text-slate-600">Agrega logos y 2–3 casos con resultados.</p>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="rounded-2xl border border-slate-200 p-6"><h3 class="font-semibold">Minería – Cargadores EV</h3><p class="mt-2 text-sm text-slate-700">Diseño e instalación AC/DC + KPIs de eficiencia y seguridad.</p></div>
        <div class="rounded-2xl border border-slate-200 p-6"><h3 class="font-semibold">Logística urbana EV</h3><p class="mt-2 text-sm text-slate-700">Pilotos de última milla con TCO competitivo y cero emisiones locales.</p></div>
        <div class="rounded-2xl border border-slate-200 p-6"><h3 class="font-semibold">Deporte sostenible</h3><p class="mt-2 text-sm text-slate-700">Certificación de academias y eventos con gestión de huella.</p></div>
      </div>
    </div>
  </section>

  <section id="contacto" class="py-20 bg-gradient-to-br from-sky-50 to-emerald-50 border-t border-slate-200">
    <div class="max-w-3xl mx-auto px-4 text-center">
      <h2 class="text-2xl sm:text-3xl font-semibold">Construyamos tu proyecto sostenible</h2>
      <p class="mt-3 text-slate-700">Cuéntanos tu reto. Diseñamos el piloto, medimos impacto y lo escalamos con aliados y financiamiento.</p>
      <div class="mt-6 grid sm:grid-cols-2 gap-3">
        <a href="mailto:hola@drivelatam.com" class="inline-flex items-center justify-center px-5 py-3 rounded-xl bg-primary text-white hover:bg-primary-dark">Escríbenos</a>
        <a href="https://wa.me/51999999999" class="inline-flex items-center justify-center px-5 py-3 rounded-xl border border-slate-300 hover:border-primary hover:text-primary" target="_blank" rel="noopener">WhatsApp</a>
      </div>
      <p class="mt-3 text-xs text-slate-500">Reemplaza el correo/WhatsApp por tus datos reales.</p>
    </div>
  </section>

  <footer class="py-8 text-center text-sm text-slate-500">
    <div class="max-w-7xl mx-auto px-4">
      <p>© <span id="y"></span> Drive Latam – Sostenible. Todos los derechos reservados.</p>
      <p class="mt-1">Hecho con ❤️ en Perú · GitHub Pages</p>
    </div>
  </footer>

  <script>
    document.getElementById('y').textContent=new Date().getFullYear();
    const btn=document.getElementById('menuBtn');
    const menu=document.getElementById('mobileMenu');
    btn&&btn.addEventListener('click',()=>menu.classList.toggle('hidden'));
  </script>
</body>
</html>
