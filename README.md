<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>mipromo-coingate.github.io – Compra tarjetas de regalo con cripto, tarjeta y más</title>
  <meta name="description" content="Descubre en mipromo-coingate.github.io cómo comprar tarjetas de regalo digitales a través de CoinGate usando criptomonedas, Crypto.com Pay, Lightning, KuCoin Pay, SEPA, Visa/Mastercard/AmEx/Discover, Apple Pay y Google Pay." />
  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  <style>
    html { scroll-behavior: smooth; }
  </style>
</head>
<body class="bg-slate-950 text-slate-50 font-sans">
  <!-- Navegación -->
  <header class="sticky top-0 z-40 border-b border-slate-800 bg-slate-950/90 backdrop-blur">
    <nav class="max-w-6xl mx-auto flex items-center justify-between px-4 py-3">
      <a href="#hero" class="flex items-center gap-2">
        <div class="h-9 w-9 rounded-xl bg-gradient-to-tr from-emerald-400 to-cyan-400 flex items-center justify-center text-slate-950 font-black text-xl">CG</div>
        <div class="leading-tight">
          <p class="font-semibold tracking-tight">CoinGate Gift Cards</p>
          <p class="text-xs text-slate-400">Cripto • Tarjeta • Wallets</p>
        </div>
      </a>
      <div class="hidden md:flex items-center gap-6 text-sm">
        <a href="#como-funciona" class="text-slate-200 hover:text-emerald-400 transition">Cómo funciona</a>
        <a href="#metodos" class="text-slate-200 hover:text-emerald-400 transition">Métodos de pago</a>
        <a href="#categorias" class="text-slate-200 hover:text-emerald-400 transition">Categorías</a>
        <a href="#simulador" class="text-slate-200 hover:text-emerald-400 transition">Simulador</a>
        <a href="#faq" class="text-slate-200 hover:text-emerald-400 transition">FAQ</a>
      </div>
      <div class="hidden md:flex items-center gap-3 text-sm">
        <button id="cta-secundario" class="border border-slate-700 hover:border-emerald-400/60 text-slate-100 hover:text-emerald-300 rounded-full px-4 py-1.5 transition">Explorar marcas</button>
        <button id="cta-principal" class="bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-semibold rounded-full px-4 py-1.5 transition shadow-lg shadow-emerald-500/30">Comprar con CoinGate</button>
      </div>
      <button id="menu-toggle" class="md:hidden inline-flex items-center justify-center h-9 w-9 rounded-full border border-slate-700 text-slate-200 hover:border-emerald-400/60 hover:text-emerald-300 transition" aria-label="Abrir menú">
        <span class="sr-only">Menú</span>
        <svg id="icon-open" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
        <svg id="icon-close" xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 hidden" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </nav>
    <div id="mobile-menu" class="md:hidden max-h-0 overflow-hidden border-t border-slate-800 bg-slate-950/95 transition-[max-height] duration-300 ease-out">
      <div class="max-w-6xl mx-auto px-4 py-3 flex flex-col gap-3 text-sm">
        <a href="#como-funciona" class="text-slate-100 hover:text-emerald-400 transition">Cómo funciona</a>
        <a href="#metodos" class="text-slate-100 hover:text-emerald-400 transition">Métodos de pago</a>
        <a href="#categorias" class="text-slate-100 hover:text-emerald-400 transition">Categorías</a>
        <a href="#simulador" class="text-slate-100 hover:text-emerald-400 transition">Simulador</a>
        <a href="#faq" class="text-slate-100 hover:text-emerald-400 transition">FAQ</a>
        <div class="pt-2 flex flex-col gap-2">
          <button id="cta-secundario-mobile" class="border border-slate-700 hover:border-emerald-400/60 text-slate-100 hover:text-emerald-300 rounded-full px-4 py-2 transition text-left">Explorar marcas</button>
          <button id="cta-principal-mobile" class="bg-emerald-400 hover:bg-emerald-300 text-slate-950 font-semibold rounded-full px-4 py-2 transition text-left">Comprar con CoinGate</button>
        </div>
      </div>
    </div>
  </header>

  <main>
    <!-- Hero -->
    <section id="hero" class="relative overflow-hidden">
      <div class="absolute inset-0 bg-[radial-gradient(circle_at_top,_#22c55e22,_transparent_55%),radial-gradient(circle_at_bottom,_#06b6d422,_transparent_55%)] pointer-events-none"></div>
      <div class="max-w-6xl mx-auto px-4 py-16 md:py-24 relative">
        <div class="grid gap-12 md:grid-cols-[minmax(0,1.2fr)_minmax(0,1fr)] items-center">
          <div class="space-y-6">
            <span class="inline-flex items-center gap-2 rounded-full border border-emerald-400/40 bg-emerald-400/10 px-3 py-1 text-xs font-medium text-emerald-200">
              <span class="h-1.5 w-1.5 rounded-full bg-emerald-400"></span>
              Paga con cripto, tarjeta bancaria, SEPA y wallets móviles
            </span>
            <h1 class="text-3xl sm:text-4xl lg:text-5xl font-black tracking-tight text-slate-50">
              Convierte tu dinero digital y bancario en <span class="text-transparent bg-clip-text bg-gradient-to-r from-emerald-400 to-cyan-400">tarjetas de regalo digitales</span> al instante
            </h1>
            <p class="text-base sm:text-lg text-slate-300 max-w-xl">
              CoinGate Gift Cards te permite comprar tarjetas de regalo de tus marcas favoritas pagando con criptomonedas, Crypto.com Pay, Lightning/gateways cripto, KuCoin Pay, tarjetas Visa/Mastercard/AmEx/Discover, transferencia SEPA y wallets como Apple Pay y Google Pay.
            </p>
            <div class="flex flex-col sm:flex-row gap-3 pt-2">
              <button id="hero-comprar" class="inline-flex items-center justify-center gap-2 rounded-full bg-emerald-400 px-6 py-2.5 text-sm sm:text-base font-semibold text-slate-950 shadow-lg shadow-emerald-500/30 hover:bg-emerald-300 transition">
                Comprar gift card en CoinGate
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M5 12h14M13 6l6 6-6 6" />
                </svg>
              </button>
              <button id="hero-calcular" class="inline-flex items-center justify-center gap-2 rounded-full border border-slate-700 px-6 py-2.5 text-sm sm:text-base font-medium text-slate-100 hover:border-emerald-400/60 hover:text-emerald-300 transition">
                Calcular ejemplo de compra
              </button>
              <button id="hero-ver-marcas" class="inline-flex items-center justify-center gap-2 rounded-full border border-slate-700 px-6 py-2.5 text-sm sm:text-base font-medium text-slate-100 hover:border-emerald-400/60 hover:text-emerald-300 transition">
                Ver marcas disponibles
              </button>
            </div>
            <dl class="grid grid-cols-3 gap-4 pt-6 max-w-md text-xs sm:text-sm">
              <div>
                <dt class="text-slate-400">Tiempo promedio de entrega</dt>
                <dd class="font-semibold text-slate-50">Minutos</dd>
              </div>
              <div>
                <dt class="text-slate-400">Métodos de pago</dt>
                <dd class="font-semibold text-slate-50">Cripto, tarjeta, SEPA, wallets</dd>
              </div>
              <div>
                <dt class="text-slate-400">Países soportados</dt>
                <dd class="font-semibold text-slate-50">+70 mercados</dd>
              </div>
            </dl>
          </div>

          <!-- Tarjeta visual de modos de pago -->
          <div class="relative">
            <div class="absolute -top-10 -right-4 h-40 w-40 rounded-full bg-emerald-400/10 blur-3xl"></div>
            <div class="absolute -bottom-10 -left-6 h-40 w-40 rounded-full bg-cyan-400/10 blur-3xl"></div>

            <div class="relative mx-auto max-w-sm">
              <div class="rounded-3xl border border-slate-800 bg-gradient-to-br from-slate-900/90 via-slate-950 to-slate-950/90 p-5 shadow-2xl shadow-emerald-500/15">
                <div class="flex items-center justify-between mb-4">
                  <div class="flex items-center gap-2">
                    <div class="h-9 w-9 rounded-2xl bg-gradient-to-tr from-emerald-400 to-cyan-400 flex items-center justify-center text-slate-950 font-black text-xl">CG</div>
                    <div class="leading-tight">
                      <p class="text-xs text-slate-400">Pagando con</p>
                      <p id="modo-pago-hero" class="text-sm font-semibold">Criptomonedas</p>
                    </div>
                  </div>
                  <span class="inline-flex items-center rounded-full bg-slate-900/70 px-2.5 py-1 text-[10px] uppercase tracking-wide text-emerald-300 border border-emerald-400/40">Entrega inmediata</span>
                </div>

                <div class="mb-3 flex gap-2 text-[10px]">
                  <button id="btn-modo-cripto" class="px-2.5 py-1 rounded-full border border-emerald-400/70 bg-emerald-400/10 text-emerald-200 font-medium">Pagando con cripto</button>
                  <button id="btn-modo-tarjeta" class="px-2.5 py-1 rounded-full border border-slate-700 bg-slate-900/60 text-slate-300 font-medium hover:border-emerald-400/60 hover:text-emerald-200 transition">Pagando con tarjeta / SEPA</button>
                </div>

                <div class="grid grid-cols-3 gap-2 mb-4 text-[10px] text-slate-200">
                  <div class="rounded-2xl bg-slate-900/70 border border-slate-800 p-2 flex flex-col gap-2">
                    <span class="text-[9px] text-slate-400">Entretenimiento</span>
                    <div class="flex flex-wrap gap-1">
                      <span class="rounded-full bg-slate-800/80 px-1.5 py-0.5">Netflix</span>
                      <span class="rounded-full bg-slate-800/80 px-1.5 py-0.5">Spotify</span>
                    </div>
                  </div>
                  <div class="rounded-2xl bg-slate-900/70 border border-slate-800 p-2 flex flex-col gap-2">
                    <span class="text-[9px] text-slate-400">Gaming</span>
                    <div class="flex flex-wrap gap-1">
                      <span class="rounded-full bg-slate-800/80 px-1.5 py-0.5">PlayStation</span>
                      <span class="rounded-full bg-slate-800/80 px-1.5 py-0.5">Xbox</span>
                    </div>
                  </div>
                  <div class="rounded-2xl bg-slate-900/70 border border-slate-800 p-2 flex flex-col gap-2">
                    <span class="text-[9px] text-slate-400">Compras online</span>
                    <div class="flex flex-wrap gap-1">
                      <span class="rounded-full bg-slate-800/80 px-1.5 py-0.5">Amazon</span>
                      <span class="rounded-full bg-slate-800/80 px-1.5 py-0.5">Airbnb</span>
                    </div>
                  </div>
                </div>

                <div class="rounded-2xl border border-slate-800 bg-slate-900/70 p-3 mb-3 flex flex-col gap-2 text-[11px] text-slate-200" id="hero-opciones-pago">
                  <div class="flex items-center justify-between">
                    <div>
                      <p class="text-[10px] text-slate-400">Opciones de pago en CoinGate</p>
                      <p class="font-semibold" id="hero-opciones-titulo">Cripto • Crypto.com Pay • KuCoin Pay</p>
                    </div>
                    <div class="flex -space-x-1.5 text-[10px] font-semibold" id="hero-opciones-iconos">
                      <span class="h-7 w-7 rounded-full bg-gradient-to-br from-yellow-300 to-amber-500 border border-slate-900 flex items-center justify-center">₿</span>
                      <span class="h-7 w-7 rounded-full bg-gradient-to-br from-indigo-400 to-purple-500 border border-slate-900 flex items-center justify-center">Ξ</span>
                      <span class="h-7 w-7 rounded-full bg-gradient-to-br from-green-400 to-emerald-500 border border-slate-900 flex items-center justify-center">₮</span>
                    </div>
                  </div>
                  <div class="grid grid-cols-2 gap-2 text-[10px]">
                    <div class="rounded-xl bg-slate-950/70 border border-slate-800 p-2 flex flex-col gap-1">
                      <span class="text-slate-400">Tarjetas y banca</span>
                      <span>Visa, Mastercard, AmEx, Discover, SEPA</span>
                    </div>
                    <div class="rounded-xl bg-slate-950/70 border border-slate-800 p-2 flex flex-col gap-1">
                      <span class="text-slate-400">Wallets móviles</span>
                      <span>Apple Pay · Google Pay</span>
                    </div>
                  </div>
                </div>

                <div class="flex items-center justify-between text-[11px] text-slate-400">
                  <div class="flex items-center gap-2">
                    <span class="inline-flex h-5 w-5 items-center justify-center rounded-full bg-emerald-400/15 text-emerald-300 border border-emerald-400/40">
                      <svg xmlns="http://www.w3.org/2000/svg" class="h-3 w-3" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M5 13l4 4L19 7" />
                      </svg>
                    </span>
                    <span>Pagos protegidos y monitoreados en tiempo real</span>
                  </div>
                  <span class="text-[10px] text-slate-500">CoinGate.com</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Cómo funciona -->
    <section id="como-funciona" class="border-t border-slate-900 bg-slate-950/60">
      <div class="max-w-6xl mx-auto px-4 py-14 md:py-20">
        <div class="flex flex-col md:flex-row md:items-end md:justify-between gap-6 mb-10">
          <div>
            <h2 class="text-2xl md:text-3xl font-bold tracking-tight mb-2">Cómo funciona CoinGate Gift Cards</h2>
            <p class="text-slate-300 max-w-2xl text-sm md:text-base">
              En pocos pasos, puedes transformar tus criptomonedas o el saldo de tus tarjetas y cuentas bancarias en tarjetas de regalo digitales canjeables al instante.
            </p>
          </div>
          <p class="text-xs md:text-sm text-slate-400 max-w-sm">
            CoinGate actúa como procesador de pagos: no es tu banco ni tu exchange, sino la pasarela que conecta tus métodos de pago con las gift cards de cientos de marcas.
          </p>
        </div>

        <div class="grid gap-6 md:grid-cols-3">
          <div class="relative rounded-2xl border border-slate-800 bg-slate-900/40 p-5">
            <div class="absolute -top-3 left-4 h-6 w-6 rounded-full bg-emerald-400 text-slate-950 text-xs font-bold flex items-center justify-center shadow-md shadow-emerald-500/40">1</div>
            <h3 class="mt-3 mb-2 font-semibold text-slate-50">Elige tu tarjeta y país</h3>
            <p class="text-sm text-slate-300 mb-3">Explora el catálogo de CoinGate y selecciona la marca, el país y el monto aproximado de tu gift card.</p>
            <ul class="text-xs text-slate-400 list-disc list-inside space-y-1">
              <li>Marcas globales y locales</li>
              <li>Diferentes valores y monedas</li>
              <li>Compatibilidad por región</li>
            </ul>
          </div>
          <div class="relative rounded-2xl border border-slate-800 bg-slate-900/40 p-5">
            <div class="absolute -top-3 left-4 h-6 w-6 rounded-full bg-emerald-400 text-slate-950 text-xs font-bold flex items-center justify-center shadow-md shadow-emerald-500/40">2</div>
            <h3 class="mt-3 mb-2 font-semibold text-slate-50">Elige cómo quieres pagar</h3>
            <p class="text-sm text-slate-300 mb-3">Selecciona si quieres pagar con criptomonedas, gateways cripto o métodos tradicionales como tarjeta, SEPA o wallets móviles.</p>
            <ul class="text-xs text-slate-400 list-disc list-inside space-y-1">
              <li>Criptomonedas compatibles</li>
              <li>Crypto.com Pay, Lightning / gateway cripto, KuCoin Pay</li>
              <li>Tarjetas Visa/Mastercard/AmEx/Discover, SEPA, Apple Pay, Google Pay</li>
            </ul>
          </div>
          <div class="relative rounded-2xl border border-slate-800 bg-slate-900/40 p-5">
            <div class="absolute -top-3 left-4 h-6 w-6 rounded-full bg-emerald-400 text-slate-950 text-xs font-bold flex items-center justify-center shadow-md shadow-emerald-500/40">3</div>
            <h3 class="mt-3 mb-2 font-semibold text-slate-50">Recibe y canjea tu gift card</h3>
            <p class="text-sm text-slate-300 mb-3">Tras la confirmación del pago, CoinGate genera el código de tu tarjeta de regalo y te lo entrega casi al instante.</p>
            <ul class="text-xs text-slate-400 list-disc list-inside space-y-1">
              <li>Código y detalles enviados en minutos</li>
              <li>Instrucciones claras de canje</li>
              <li>Soporte disponible si tienes dudas</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Métodos de pago -->
    <section id="metodos" class="border-t border-slate-900 bg-slate-950">
      <div class="max-w-6xl mx-auto px-4 py-14 md:py-20">
        <div class="flex flex-col md:flex-row md:items-end md:justify-between gap-6 mb-10">
          <div>
            <h2 class="text-2xl md:text-3xl font-bold tracking-tight mb-2">Métodos de pago que puedes usar con CoinGate</h2>
            <p class="text-slate-300 max-w-2xl text-sm md:text-base">
              CoinGate no se limita a las criptomonedas. También puedes completar tu compra con gateways cripto, transferencia bancaria SEPA, tarjetas de crédito y débito, y wallets móviles populares.
            </p>
          </div>
          <p class="text-xs md:text-sm text-slate-400 max-w-sm">
            La disponibilidad exacta de cada método depende del país, la moneda y la tarjeta de regalo elegida. Verás las opciones actualizadas en el checkout de CoinGate.
          </p>
        </div>

        <div class="grid gap-6 md:grid-cols-3 text-sm">
          <div class="rounded-2xl border border-slate-800 bg-slate-900/40 p-5 flex flex-col gap-3">
            <h3 class="font-semibold flex items-center gap-2">
              <span class="inline-flex h-7 w-7 items-center justify-center rounded-full bg-emerald-400/20 text-emerald-300 border border-emerald-400/40 text-xs">1</span>
              Pagos con criptomonedas
            </h3>
            <p class="text-slate-300 text-xs md:text-sm">Envía pagos directamente desde tu wallet cripto compatible.</p>
            <ul class="text-xs text-slate-400 space-y-1 list-disc list-inside">
              <li>Bitcoin (BTC), Ethereum (ETH), Litecoin (LTC)</li>
              <li>Stablecoins como USDT, USDC, DAI</li>
              <li>Otros activos compatibles según la región</li>
            </ul>
          </div>

          <div class="rounded-2xl border border-slate-800 bg-slate-900/40 p-5 flex flex-col gap-3">
            <h3 class="font-semibold flex items-center gap-2">
              <span class="inline-flex h-7 w-7 items-center justify-center rounded-full bg-cyan-400/20 text-cyan-300 border border-cyan-400/40 text-xs">2</span>
              Gateways cripto y cuentas
            </h3>
            <p class="text-slate-300 text-xs md:text-sm">Paga usando servicios que conectan tu cuenta con CoinGate sin mover fondos on-chain en algunos casos.</p>
            <ul class="text-xs text-slate-400 space-y-1 list-disc list-inside">
              <li>Crypto.com Pay</li>
              <li>Lightning / gateway cripto compatible ⚡</li>
              <li>KuCoin Pay (pagos desde tu cuenta de KuCoin)</li>
            </ul>
          </div>

          <div class="rounded-2xl border border-slate-800 bg-slate-900/40 p-5 flex flex-col gap-3">
            <h3 class="font-semibold flex items-center gap-2">
              <span class="inline-flex h-7 w-7 items-center justify-center rounded-full bg-amber-400/20 text-amber-200 border border-amber-400/40 text-xs">3</span>
              Tarjetas, banca y wallets móviles
            </h3>
            <p class="text-slate-300 text-xs md:text-sm">Completa la compra con tus tarjetas habituales o con tu banco, incluso si no usas criptomonedas.</p>
            <ul class="text-xs text-slate-400 space-y-1 list-disc list-inside">
              <li>Tarjetas Visa y Mastercard (débito o crédito)</li>
              <li>American Express (AmEx) y Discover</li>
              <li>Transferencias SEPA en euros</li>
              <li>Apple Pay (🍎) y Google Pay (🤖)</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Categorías destacadas -->
    <section id="categorias" class="border-t border-slate-900 bg-slate-950">
      <div class="max-w-6xl mx-auto px-4 py-14 md:py-20">
        <div class="flex flex-col md:flex-row md:items-end md:justify-between gap-6 mb-10">
          <div>
            <h2 class="text-2xl md:text-3xl font-bold tracking-tight mb-2">Gift cards para cada momento</h2>
            <p class="text-slate-300 max-w-2xl text-sm md:text-base">
              Desde entretenimiento y gaming hasta compras online, viajes y servicios digitales. CoinGate ofrece una amplia variedad de tarjetas de regalo que se adaptan a cómo pagas: cripto, tarjeta, SEPA o wallets móviles.
            </p>
          </div>
          <button id="cta-coingate-categorias" class="inline-flex items-center gap-2 rounded-full border border-slate-700 px-4 py-2 text-xs md:text-sm font-medium text-slate-100 hover:border-emerald-400/60 hover:text-emerald-300 transition">
            Ver catálogo completo en CoinGate
            <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M5 12h14M13 6l6 6-6 6" />
            </svg>
          </button>
        </div>

        <div class="grid gap-6 md:grid-cols-4">
          <div class="rounded-2xl border border-slate-800 bg-slate-900/40 p-4 flex flex-col justify-between">
            <div>
              <h3 class="font-semibold mb-1">Entretenimiento</h3>
              <p class="text-xs text-slate-300 mb-3">Suscripciones y contenido para tus plataformas favoritas.</p>
              <ul class="text-xs text-slate-200 space-y-1">
                <li>• Netflix</li>
                <li>• Spotify</li>
                <li>• Apple Services</li>
                <li>• Google Play</li>
              </ul>
            </div>
            <span class="mt-4 inline-flex w-fit rounded-full bg-slate-800/80 px-3 py-1 text-[10px] text-slate-300">Perfecto para regalar entretenimiento</span>
          </div>
          <div class="rounded-2xl border border-slate-800 bg-slate-900/40 p-4 flex flex-col justify-between">
            <div>
              <h3 class="font-semibold mb-1">Gaming</h3>
              <p class="text-xs text-slate-300 mb-3">Carga saldo en tus juegos y plataformas favoritas.</p>
              <ul class="text-xs text-slate-200 space-y-1">
                <li>• PlayStation Store</li>
                <li>• Xbox Live</li>
                <li>• Steam</li>
                <li>• Nintendo eShop</li>
              </ul>
            </div>
            <span class="mt-4 inline-flex w-fit rounded-full bg-slate-800/80 px-3 py-1 text-[10px] text-slate-300">Para gamers y streamers</span>
          </div>
          <div class="rounded-2xl border border-slate-800 bg-slate-900/40 p-4 flex flex-col justify-between">
            <div>
              <h3 class="font-semibold mb-1">Compras online</h3>
              <p class="text-xs text-slate-300 mb-3">Compra productos y servicios en marketplaces globales.</p>
              <ul class="text-xs text-slate-200 space-y-1">
                <li>• Amazon</li>
                <li>• eBay</li>
                <li>• AliExpress</li>
                <li>• Walmart (según región)</li>
              </ul>
            </div>
            <span class="mt-4 inline-flex w-fit rounded-full bg-slate-800/80 px-3 py-1 text-[10px] text-slate-300">Convierte tu saldo en compras reales</span>
          </div>
          <div class="rounded-2xl border border-slate-800 bg-slate-900/40 p-4 flex flex-col justify-between">
            <div>
              <h3 class="font-semibold mb-1">Viajes y servicios</h3>
              <p class="text-xs text-slate-300 mb-3">Reserva alojamientos, transporte y otros servicios.</p>
              <ul class="text-xs text-slate-200 space-y-1">
                <li>• Airbnb</li>
                <li>• Uber</li>
                <li>• Booking.com</li>
                <li>• Servicios digitales varios</li>
              </ul>
            </div>
            <span class="mt-4 inline-flex w-fit rounded-full bg-slate-800/80 px-3 py-1 text-[10px] text-slate-300">Ideal para tus viajes</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Simulador -->
    <section id="simulador" class="border-t border-slate-900 bg-slate-950">
      <div class="max-w-6xl mx-auto px-4 py-14 md:py-20 grid gap-10 md:grid-cols-[minmax(0,1.1fr)_minmax(0,1fr)] items-start">
        <div>
          <h2 class="text-2xl md:text-3xl font-bold tracking-tight mb-2">Simula tu compra con CoinGate</h2>
          <p class="text-slate-300 text-sm md:text-base mb-6 max-w-xl">
            Elige una categoría, un monto estimado y cómo te gustaría pagar. Este simulador es orientativo: el cálculo real de precios y tipos de cambio se hace en tiempo real en CoinGate.
          </p>

          <form id="simulador-form" class="space-y-4 max-w-md">
            <div>
              <span class="block text-xs font-medium text-slate-300 mb-1">Tipo de pago</span>
              <div class="inline-flex rounded-full border border-slate-700 bg-slate-900/80 p-1 text-[11px] mb-2">
                <button type="button" id="pago-cripto" class="px-3 py-1 rounded-full bg-emerald-500/20 text-emerald-200 font-medium border border-emerald-400/60">Criptomonedas / Gateways cripto</button>
                <button type="button" id="pago-tarjeta" class="px-3 py-1 rounded-full text-slate-300 hover:text-emerald-200 hover:border-emerald-400/60 border border-transparent">Tarjeta / SEPA / Wallet móvil</button>
              </div>
            </div>

            <div>
              <label for="categoria" class="block text-xs font-medium text-slate-300 mb-1">Categoría</label>
              <select id="categoria" class="w-full rounded-xl border border-slate-700 bg-slate-900/80 px-3 py-2 text-sm text-slate-100 focus:outline-none focus:border-emerald-400">
                <option value="entretenimiento">Entretenimiento</option>
                <option value="gaming">Gaming</option>
                <option value="compras">Compras online</option>
                <option value="viajes">Viajes y servicios</option>
              </select>
            </div>

            <div>
              <label for="marca" class="block text-xs font-medium text-slate-300 mb-1">Marca / Tarjeta (ejemplo)</label>
              <select id="marca" class="w-full rounded-xl border border-slate-700 bg-slate-900/80 px-3 py-2 text-sm text-slate-100 focus:outline-none focus:border-emerald-400"></select>
              <p class="mt-1 text-[11px] text-slate-500">Las marcas mostradas son una referencia de las gift cards que puedes encontrar en CoinGate Gift Cards.</p>
            </div>

            <div>
              <label for="monto" class="block text-xs font-medium text-slate-300 mb-1">Monto aproximado de la tarjeta</label>
              <div class="flex gap-2">
                <select id="moneda-fiat" class="w-28 rounded-xl border border-slate-700 bg-slate-900/80 px-2 py-2 text-xs text-slate-100 focus:outline-none focus:border-emerald-400">
                  <option value="USD">USD $</option>
                  <option value="EUR">EUR €</option>
                  <option value="GBP">GBP £</option>
                </select>
                <input type="number" id="monto" min="5" max="1000" value="50" class="flex-1 rounded-xl border border-slate-700 bg-slate-900/80 px-3 py-2 text-sm text-slate-100 focus:outline-none focus:border-emerald-400" />
              </div>
              <p class="mt-1 text-[11px] text-slate-500">El valor final se calcula en tiempo real en CoinGate según el producto, la región, el método de pago y los tipos de cambio del momento.</p>
            </div>

            <div id="bloque-cripto">
              <label for="cripto" class="block text-xs font-medium text-slate-300 mb-1">Criptomoneda
                <span class="text-[10px] text-slate-500 font-normal">(ejemplo de activos soportados; revisa CoinGate para la lista actualizada)</span>
              </label>
              <select id="cripto" class="w-full rounded-xl border border-slate-700 bg-slate-900/80 px-3 py-2 text-sm text-slate-100 focus:outline-none focus:border-emerald-400">
                <option value="BTC">Bitcoin (BTC)</option>
                <option value="ETH">Ethereum (ETH)</option>
                <option value="LTC">Litecoin (LTC)</option>
                <option value="USDT">Tether (USDT)</option>
                <option value="USDC">USD Coin (USDC)</option>
                <option value="DAI">Dai (DAI)</option>
                <option value="BNB">BNB (BNB)</option>
                <option value="TRX">Tron (TRX)</option>
                <option value="DOGE">Dogecoin (DOGE)</option>
                <option value="MATIC">Polygon (MATIC)</option>
                <option value="XRP">XRP (XRP)</option>
                <option value="BCH">Bitcoin Cash (BCH)</option>
              </select>
              <p class="mt-1 text-[11px] text-slate-500">La disponibilidad real de criptomonedas depende de CoinGate y puede variar según la tarjeta, la red y la región.</p>
            </div>


            <div class="flex flex-wrap gap-3 items-center">
              <button type="button" id="simular" class="inline-flex items-center gap-2 rounded-full bg-emerald-400 px-5 py-2 text-sm font-semibold text-slate-950 shadow-md shadow-emerald-500/30 hover:bg-emerald-300 transition">
                Calcular pago estimado
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </button>
              <button type="button" id="simulador-ir-coingate" class="inline-flex items-center gap-2 rounded-full border border-emerald-400/70 px-4 py-2 text-xs font-medium text-emerald-200 hover:border-emerald-300 hover:text-emerald-100 transition">
                Ver cálculo real en CoinGate
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M5 12h14M13 6l6 6-6 6" />
                </svg>
              </button>
            </div>
          </form>
        </div>

        <div class="rounded-2xl border border-slate-800 bg-slate-900/60 p-5 md:p-6">
          <h3 class="font-semibold mb-1">Resumen estimado</h3>
          <p class="text-xs text-slate-400 mb-4">Los valores son solo de referencia. CoinGate siempre calcula el tipo de cambio, las comisiones y los métodos disponibles en tiempo real.</p>

          <dl class="space-y-2 text-sm">
            <div class="flex justify-between">
              <dt class="text-slate-400">Categoría seleccionada</dt>
              <dd id="res-categoria" class="font-medium text-slate-100">Entretenimiento</dd>
            </div>
            <div class="flex justify-between">
              <dt class="text-slate-400">Tarjeta / Marca</dt>
              <dd id="res-marca" class="font-medium text-slate-100">Netflix</dd>
            </div>
            <div class="flex justify-between">
              <dt class="text-slate-400">Monto de la gift card</dt>
              <dd class="font-medium text-slate-100"><span id="res-monto">50.00</span> <span id="res-moneda">USD</span></dd>
            </div>
            <div class="flex justify-between">
              <dt class="text-slate-400">Modo de pago</dt>
              <dd id="res-modo" class="font-medium text-slate-100">Criptomonedas / Gateways cripto</dd>
            </div>
            <div class="flex justify-between">
              <dt class="text-slate-400">Criptomoneda (si aplica)</dt>
              <dd id="res-cripto" class="font-medium text-slate-100">BTC</dd>
            </div>
            <div class="flex justify-between">
              <dt class="text-slate-400">Pago estimado en cripto</dt>
              <dd class="font-semibold text-emerald-300"><span id="res-cantidad">0.0012</span> <span id="res-simbolo">BTC</span></dd>
            </div>
          </dl>

          <div class="mt-5 rounded-xl border border-slate-800 bg-slate-950/60 p-3 text-[11px] text-slate-400 space-y-2">
            <p>Este simulador utiliza tasas aproximadas basadas en supuestos estáticos y no representa una cotización real ni datos oficiales de CoinGate.</p>
            <p>Al usar CoinGate, el importe exacto se calcula al momento de generar el pago, según el tipo de cambio del mercado, las tarifas del método elegido y la disponibilidad por país y marca.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="border-t border-slate-900 bg-slate-950/60">
      <div class="max-w-6xl mx-auto px-4 py-14 md:py-20">
        <div class="max-w-3xl mb-8">
          <h2 class="text-2xl md:text-3xl font-bold tracking-tight mb-2">Preguntas frecuentes</h2>
          <p class="text-slate-300 text-sm md:text-base">
            Resolvemos las dudas más comunes sobre cómo funcionan las gift cards y los distintos métodos de pago al usar CoinGate.
          </p>
        </div>

        <div class="space-y-3" id="faq-list">
          <details class="group rounded-2xl border border-slate-800 bg-slate-900/40 p-4">
            <summary class="flex cursor-pointer items-center justify-between gap-4 list-none">
              <span class="text-sm font-medium text-slate-100">¿Solo puedo pagar con criptomonedas?</span>
              <span class="ml-4 flex h-6 w-6 items-center justify-center rounded-full border border-slate-700 text-slate-400 group-open:border-emerald-400/60 group-open:text-emerald-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 group-open:hidden" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M12 4v16m8-8H4" />
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 hidden group-open:block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M20 12H4" />
                </svg>
              </span>
            </summary>
            <div class="mt-3 text-xs md:text-sm text-slate-300">
              No. CoinGate permite pagar con criptomonedas, pero también con Crypto.com Pay, Lightning/gateways cripto, KuCoin Pay, transferencias SEPA, tarjetas Visa/Mastercard/AmEx/Discover y wallets móviles como Apple Pay y Google Pay, según tu país y la tarjeta de regalo elegida.
            </div>
          </details>

          <details class="group rounded-2xl border border-slate-800 bg-slate-900/40 p-4">
            <summary class="flex cursor-pointer items-center justify-between gap-4 list-none">
              <span class="text-sm font-medium text-slate-100">¿Necesito una cuenta verificada para usar CoinGate Gift Cards?</span>
              <span class="ml-4 flex h-6 w-6 items-center justify-center rounded-full border border-slate-700 text-slate-400 group-open:border-emerald-400/60 group-open:text-emerald-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 group-open:hidden" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M12 4v16m8-8H4" />
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 hidden group-open:block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M20 12H4" />
                </svg>
              </span>
            </summary>
            <div class="mt-3 text-xs md:text-sm text-slate-300">
              En muchos casos puedes comprar gift cards directamente, aunque ciertos montos o regiones pueden requerir pasos adicionales de verificación por regulación. La experiencia está pensada para que comprar una tarjeta de regalo sea lo más sencillo posible.
            </div>
          </details>

          <details class="group rounded-2xl border border-slate-800 bg-slate-900/40 p-4">
            <summary class="flex cursor-pointer items-center justify-between gap-4 list-none">
              <span class="text-sm font-medium text-slate-100">¿Cuánto tarda en llegar mi tarjeta de regalo?</span>
              <span class="ml-4 flex h-6 w-6 items-center justify-center rounded-full border border-slate-700 text-slate-400 group-open:border-emerald-400/60 group-open:text-emerald-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 group-open:hidden" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M12 4v16m8-8H4" />
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 hidden group-open:block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M20 12H4" />
                </svg>
              </span>
            </summary>
            <div class="mt-3 text-xs md:text-sm text-slate-300">
              Normalmente la entrega es casi inmediata tras la confirmación del pago. En la mayoría de los casos, recibirás tu código en cuestión de minutos junto con las instrucciones para canjearlo en la plataforma de la marca.
            </div>
          </details>

          <details class="group rounded-2xl border border-slate-800 bg-slate-900/40 p-4">
            <summary class="flex cursor-pointer items-center justify-between gap-4 list-none">
              <span class="text-sm font-medium text-slate-100">¿Qué pasa si tengo un problema con mi gift card?</span>
              <span class="ml-4 flex h-6 w-6 items-center justify-center rounded-full border border-slate-700 text-slate-400 group-open:border-emerald-400/60 group-open:text-emerald-300">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 group-open:hidden" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M12 4v16m8-8H4" />
                </svg>
                <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 hidden group-open:block" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M20 12H4" />
                </svg>
              </span>
            </summary>
            <div class="mt-3 text-xs md:text-sm text-slate-300">
              CoinGate cuenta con soporte para ayudarte si algo no funciona como esperabas. Conserva los correos y comprobantes del pago y contacta con el equipo de asistencia indicando el identificador de tu operación.
            </div>
          </details>
        </div>
      </div>
    </section>

    <!-- CTA final -->
    <section class="border-t border-slate-900 bg-gradient-to-br from-slate-950 via-slate-950 to-slate-900">
      <div class="max-w-6xl mx-auto px-4 py-14 md:py-20">
        <div class="relative overflow-hidden rounded-3xl border border-emerald-500/40 bg-gradient-to-r from-emerald-500/15 via-slate-950 to-cyan-500/10 p-6 md:p-10">
          <div class="absolute inset-y-0 right-0 w-40 bg-[radial-gradient(circle_at_center,_#22c55e33,_transparent_60%)] pointer-events-none"></div>
          <div class="relative max-w-2xl space-y-4">
            <h2 class="text-2xl md:text-3xl font-bold tracking-tight text-slate-50">Empieza a usar tus métodos de pago favoritos para comprar gift cards</h2>
            <p class="text-sm md:text-base text-emerald-50/90">
              Entra a CoinGate, explora las CoinGate Gift Cards disponibles para tu país y realiza tu primera compra pagando con criptomonedas, Crypto.com Pay, Lightning/gateways cripto, KuCoin Pay, SEPA, tarjeta bancaria o wallets como Apple Pay y Google Pay.
            </p>
            <div class="flex flex-col sm:flex-row gap-3 pt-2">
              <button id="cta-coingate-final" class="inline-flex items-center gap-2 rounded-full bg-emerald-400 px-6 py-2.5 text-sm font-semibold text-slate-950 shadow-lg shadow-emerald-500/40 hover:bg-emerald-300 transition">
                Ir a CoinGate Gift Cards
                <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M5 12h14M13 6l6 6-6 6" />
                </svg>
              </button>
              <button id="cta-coingate-final-sec" class="inline-flex items-center gap-2 rounded-full border border-emerald-300/60 px-6 py-2.5 text-sm font-medium text-emerald-50 hover:border-emerald-100 hover:text-emerald-100 transition">
                Ver métodos de pago soportados
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="border-t border-slate-900 bg-slate-950">
    <div class="max-w-6xl mx-auto px-4 py-8 text-[11px] md:text-xs text-slate-500 flex flex-col md:flex-row md:items-center md:justify-between gap-3">
      <p>
        Esta es una página informativa creada para explicar cómo comprar tarjetas de regalo digitales a través de CoinGate utilizando criptomonedas, gateways cripto, métodos de pago tradicionales y wallets móviles.
      </p>
      <p class="text-slate-600">
        Revisa siempre la información oficial, las comisiones y los términos de uso directamente en CoinGate.com.
      </p>
    </div>
  </footer>

  <script>
    // Menú móvil
    (function () {
      const toggle = document.getElementById('menu-toggle');
      const menu = document.getElementById('mobile-menu');
      const iconOpen = document.getElementById('icon-open');
      const iconClose = document.getElementById('icon-close');

      if (!toggle || !menu) return;

      toggle.addEventListener('click', () => {
        const isOpen = menu.style.maxHeight && menu.style.maxHeight !== '0px';
        if (isOpen) {
          menu.style.maxHeight = '0px';
          iconOpen.classList.remove('hidden');
          iconClose.classList.add('hidden');
        } else {
          menu.style.maxHeight = menu.scrollHeight + 'px';
          iconOpen.classList.add('hidden');
          iconClose.classList.remove('hidden');
        }
      });
    })();

    // Cambio visual del modo de pago en la tarjeta del hero
    (function () {
      const modoPagoHero = document.getElementById('modo-pago-hero');
      const btnModoCripto = document.getElementById('btn-modo-cripto');
      const btnModoTarjeta = document.getElementById('btn-modo-tarjeta');
      const heroOpcionesTitulo = document.getElementById('hero-opciones-titulo');
      const heroOpcionesIconos = document.getElementById('hero-opciones-iconos');

      if (!modoPagoHero || !btnModoCripto || !btnModoTarjeta || !heroOpcionesTitulo || !heroOpcionesIconos) return;

      btnModoCripto.addEventListener('click', () => {
        modoPagoHero.textContent = 'Criptomonedas';
        heroOpcionesTitulo.textContent = 'Cripto • Crypto.com Pay • KuCoin Pay';
        heroOpcionesIconos.innerHTML = `
          <span class="h-7 w-7 rounded-full bg-gradient-to-br from-yellow-300 to-amber-500 border border-slate-900 flex items-center justify-center">₿</span>
          <span class="h-7 w-7 rounded-full bg-gradient-to-br from-indigo-400 to-purple-500 border border-slate-900 flex items-center justify-center">Ξ</span>
          <span class="h-7 w-7 rounded-full bg-gradient-to-br from-green-400 to-emerald-500 border border-slate-900 flex items-center justify-center">₮</span>
        `;
        btnModoCripto.classList.add('border-emerald-400/70', 'bg-emerald-400/10', 'text-emerald-200');
        btnModoTarjeta.classList.remove('border-emerald-400/70', 'bg-emerald-400/10', 'text-emerald-200');
      });

      btnModoTarjeta.addEventListener('click', () => {
        modoPagoHero.textContent = 'Tarjeta bancaria / SEPA';
        heroOpcionesTitulo.textContent = 'Pagando con USD / EUR';
        heroOpcionesIconos.innerHTML = `
          <span class="h-7 w-7 rounded-full bg-slate-900 border border-slate-800 flex items-center justify-center text-xs">🇺🇸</span>
          <span class="h-7 w-7 rounded-full bg-slate-900 border border-slate-800 flex items-center justify-center text-xs">🇪🇺</span>
        `;
        btnModoTarjeta.classList.add('border-emerald-400/70', 'bg-emerald-400/10', 'text-emerald-200');
        btnModoCripto.classList.remove('border-emerald-400/70', 'bg-emerald-400/10', 'text-emerald-200');
      });
    })();

    // Scroll suave y CTAs
    (function () {
      const scrollToId = (id) => {
        const el = document.getElementById(id);
        if (el) el.scrollIntoView({ behavior: 'smooth', block: 'start' });
      };

      const heroComprar = document.getElementById('hero-comprar');
      const heroCalcular = document.getElementById('hero-calcular');
      const heroVerMarcas = document.getElementById('hero-ver-marcas');
      const ctaPrincipal = document.getElementById('cta-principal');
      const ctaSecundario = document.getElementById('cta-secundario');
      const ctaPrincipalMobile = document.getElementById('cta-principal-mobile');
      const ctaSecundarioMobile = document.getElementById('cta-secundario-mobile');
      const ctaCoingateFinalSec = document.getElementById('cta-coingate-final-sec');

      if (heroCalcular) heroCalcular.addEventListener('click', () => scrollToId('simulador'));
      if (heroVerMarcas) heroVerMarcas.addEventListener('click', () => scrollToId('categorias'));

      if (ctaSecundario) ctaSecundario.addEventListener('click', () => scrollToId('categorias'));
      if (ctaSecundarioMobile) ctaSecundarioMobile.addEventListener('click', () => scrollToId('categorias'));
      if (ctaCoingateFinalSec) ctaCoingateFinalSec.addEventListener('click', () => scrollToId('metodos'));
    })();

    // Simulador de pago (estimación educativa)
    (function () {
      const categoria = document.getElementById('categoria');
      const marca = document.getElementById('marca');
      const monto = document.getElementById('monto');
      const monedaFiat = document.getElementById('moneda-fiat');
      const cripto = document.getElementById('cripto');
      const btn = document.getElementById('simular');
      const pagoCriptoBtn = document.getElementById('pago-cripto');
      const pagoTarjetaBtn = document.getElementById('pago-tarjeta');
      const bloqueCripto = document.getElementById('bloque-cripto');

      const resCategoria = document.getElementById('res-categoria');
      const resMarca = document.getElementById('res-marca');
      const resMonto = document.getElementById('res-monto');
      const resMoneda = document.getElementById('res-moneda');
      const resModo = document.getElementById('res-modo');
      const resCripto = document.getElementById('res-cripto');
      const resCantidad = document.getElementById('res-cantidad');
      const resSimbolo = document.getElementById('res-simbolo');

      if (!btn || !categoria || !marca || !monto || !cripto || !monedaFiat || !pagoCriptoBtn || !pagoTarjetaBtn || !bloqueCripto) return;

      let modoPago = 'CRIPTO'; // o 'TARJETA'

      const marcasPorCategoria = {
        entretenimiento: ['Netflix', 'Spotify', 'Apple Services', 'Google Play', 'Disney+', 'Deezer'],
        gaming: ['PlayStation Store', 'Xbox Live', 'Steam', 'Nintendo eShop', 'Razer Gold', 'Roblox'],
        compras: ['Amazon', 'eBay', 'AliExpress', 'Walmart', 'Target', 'Best Buy'],
        viajes: ['Airbnb', 'Uber', 'Booking.com', 'Hotels.com', 'FlixBus', 'Bolt']
      };

      const tasas = {
        BTC: 60000,
        ETH: 3000,
        LTC: 80,
        USDT: 1,
        USDC: 1,
        DAI: 1,
        BNB: 400,
        TRX: 0.12,
        DOGE: 0.15,
        MATIC: 1,
        XRP: 0.6,
        BCH: 250
      };

      const nombreCategoria = {
        entretenimiento: 'Entretenimiento',
        gaming: 'Gaming',
        compras: 'Compras online',
        viajes: 'Viajes y servicios'
      };

      function poblarMarcas() {
        const cat = categoria.value || 'entretenimiento';
        const lista = marcasPorCategoria[cat] || marcasPorCategoria.entretenimiento;
        marca.innerHTML = '';
        lista.forEach((m, idx) => {
          const opt = document.createElement('option');
          opt.value = m;
          opt.textContent = m;
          if (idx === 0) opt.selected = true;
          marca.appendChild(opt);
        });
      }

      function actualizar() {
        const cat = categoria.value;
        const valor = parseFloat(monto.value) || 0;
        const coin = cripto.value;
        const marcaSeleccionada = marca.value;
        const fiat = monedaFiat.value || 'USD';

        resCategoria.textContent = nombreCategoria[cat] || cat;
        resMarca.textContent = marcaSeleccionada || '-';
        resMonto.textContent = valor ? valor.toFixed(2) : '0.00';
        resMoneda.textContent = fiat;

        if (modoPago === 'TARJETA') {
          resModo.textContent = 'Tarjeta / SEPA / Wallet móvil';
          resCripto.textContent = '-';
          resSimbolo.textContent = '';
          resCantidad.textContent = '-';
          return;
        }

        // Modo CRIPTO
        resModo.textContent = 'Criptomonedas / Gateways cripto';
        resCripto.textContent = coin;
        resSimbolo.textContent = coin;

        const tasa = tasas[coin];
        if (!valor || valor <= 0 || !tasa) {
          resCantidad.textContent = '0.0000';
          return;
        }
        const cantidad = valor / tasa;
        const decimales = ['USDT', 'USDC', 'DAI'].includes(coin) ? 2 : 6;
        resCantidad.textContent = cantidad.toFixed(decimales);
      }

      function activarModoCripto() {
        modoPago = 'CRIPTO';
        bloqueCripto.style.display = '';
        pagoCriptoBtn.classList.add('bg-emerald-500/20', 'text-emerald-200', 'border', 'border-emerald-400/60');
        pagoTarjetaBtn.classList.remove('bg-emerald-500/20', 'text-emerald-200', 'border', 'border-emerald-400/60');
        actualizar();
      }

      function activarModoTarjeta() {
        modoPago = 'TARJETA';
        bloqueCripto.style.display = 'none';
        pagoTarjetaBtn.classList.add('bg-emerald-500/20', 'text-emerald-200', 'border', 'border-emerald-400/60');
        pagoCriptoBtn.classList.remove('bg-emerald-500/20', 'text-emerald-200', 'border', 'border-emerald-400/60');
        actualizar();
      }

      poblarMarcas();
      activarModoCripto();

      btn.addEventListener('click', actualizar);
      categoria.addEventListener('change', () => {
        poblarMarcas();
        actualizar();
      });
      monto.addEventListener('input', actualizar);
      cripto.addEventListener('change', actualizar);
      monedaFiat.addEventListener('change', actualizar);
      pagoCriptoBtn.addEventListener('click', activarModoCripto);
      pagoTarjetaBtn.addEventListener('click', activarModoTarjeta);
    })();

    // Manejo de enlaces de referido hacia CoinGate
    (function () {
      const params = new URLSearchParams(window.location.search);
      const rawRef = params.get('ref') || params.get('referral') || '';
      const ref = rawRef ? rawRef.trim() : '';

      const baseUrl = 'https://coingate.com/gift-cards';

      function buildReferralUrl() {
        if (!ref) return baseUrl;
        const url = new URL(baseUrl);
        url.searchParams.set('ref', ref);
        return url.toString();
      }

      function attachClickRedirect(id) {
        const el = document.getElementById(id);
        if (!el) return;
        el.addEventListener('click', (e) => {
          // Solo abrimos CoinGate en una nueva pestaña; esta página no navega a ningún lado
          e.preventDefault();
          const url = buildReferralUrl();
          window.open(url, '_blank', 'noopener,noreferrer');
        });
      }

      attachClickRedirect('cta-coingate-final');
      attachClickRedirect('cta-coingate-categorias');
      attachClickRedirect('simulador-ir-coingate');
      attachClickRedirect('hero-comprar');
      attachClickRedirect('cta-principal');
      attachClickRedirect('cta-principal-mobile');
    })();
  </script>
</body>
</html>
