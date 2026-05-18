<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dias Tidar | Logo & Brand Designer</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: #0f172a;
      color: white;
      overflow-x: hidden;
    }

    .glow {
      box-shadow: 0 0 40px rgba(255,255,255,0.08);
    }

    .grid-bg {
      background-image:
        linear-gradient(rgba(255,255,255,0.04) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.04) 1px, transparent 1px);
      background-size: 40px 40px;
    }
  </style>
</head>
<body class="grid-bg">

  <section class="min-h-screen flex items-center justify-center px-6 py-20">
    <div class="max-w-6xl w-full grid md:grid-cols-2 gap-12 items-center">

      <div>
        <p class="uppercase tracking-[0.3em] text-slate-400 text-sm mb-4">
          Freelance Designer
        </p>

        <h1 class="text-5xl md:text-7xl font-extrabold leading-tight mb-6">
          Dias <span class="text-cyan-400">Tidar</span>
        </h1>

        <p class="text-slate-300 text-lg leading-relaxed mb-8">
          I create modern, minimal, and memorable logo identities with a strong visual foundation. 
          Focused on clean branding systems, monogram design, abstract marks, and vector-based identity exploration.
        </p>

        <div class="flex flex-wrap gap-4 mb-10">
          <a href="#portfolio" class="bg-cyan-400 text-slate-900 font-semibold px-6 py-3 rounded-2xl hover:scale-105 transition duration-300">
            View Portfolio
          </a>

          <a href="https://99designs.com/profiles/diastidar" target="_blank" class="border border-slate-600 px-6 py-3 rounded-2xl hover:bg-white hover:text-slate-900 transition duration-300">
            99designs
          </a>
        </div>

        <div class="flex gap-8 text-sm text-slate-400">
          <div>
            <h3 class="text-white text-2xl font-bold">5+</h3>
            <p>Years Experience</p>
          </div>

          <div>
            <h3 class="text-white text-2xl font-bold">100+</h3>
            <p>Design Concepts</p>
          </div>

          <div>
            <h3 class="text-white text-2xl font-bold">Worldwide</h3>
            <p>Clients</p>
          </div>
        </div>
      </div>

      <div class="relative">
        <div class="absolute inset-0 bg-cyan-400 blur-[120px] opacity-20 rounded-full"></div>

        <div class="relative bg-slate-900/70 border border-slate-700 rounded-[32px] p-8 glow backdrop-blur-xl">
          <div class="grid grid-cols-2 gap-4">

            <div class="bg-slate-800 rounded-3xl p-6 h-40 flex items-center justify-center text-4xl font-black tracking-widest">
              DT
            </div>

            <div class="bg-cyan-400 text-slate-900 rounded-3xl p-6 h-40 flex items-center justify-center text-3xl font-bold">
              MONO
            </div>

            <div class="bg-slate-800 rounded-3xl p-6 h-40 flex items-center justify-center text-2xl font-bold border border-slate-700">
              VECTOR
            </div>

            <div class="bg-white text-slate-900 rounded-3xl p-6 h-40 flex items-center justify-center text-3xl font-extrabold">
              GRID
            </div>

          </div>
        </div>
      </div>

    </div>
  </section>


  <section id="portfolio" class="px-6 py-24">
    <div class="max-w-6xl mx-auto">

      <div class="mb-16 text-center">
        <p class="uppercase tracking-[0.3em] text-cyan-400 text-sm mb-4">
          Selected Works
        </p>

        <h2 class="text-4xl md:text-5xl font-extrabold mb-6">
          Logo Exploration Collection
        </h2>

        <p class="text-slate-400 max-w-2xl mx-auto leading-relaxed">
          A collection of identity concepts combining geometric structure, negative space, modern symbolism, and clean typography.
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">

        <div class="bg-slate-900 border border-slate-800 rounded-[28px] overflow-hidden hover:-translate-y-2 transition duration-300 glow">
          <div class="h-60 bg-gradient-to-br from-slate-800 to-slate-700 flex items-center justify-center text-5xl font-black">
            AX
          </div>

          <div class="p-6">
            <h3 class="text-2xl font-bold mb-3">Monogram Identity</h3>
            <p class="text-slate-400 leading-relaxed">
              Clean vector monogram system focused on structure, symmetry, and strong brand memorability.
            </p>
          </div>
        </div>

        <div class="bg-slate-900 border border-slate-800 rounded-[28px] overflow-hidden hover:-translate-y-2 transition duration-300 glow">
          <div class="h-60 bg-gradient-to-br from-cyan-400 to-blue-500 flex items-center justify-center text-5xl font-black text-slate-900">
            NX
          </div>

          <div class="p-6">
            <h3 class="text-2xl font-bold mb-3">Abstract Brand Mark</h3>
            <p class="text-slate-400 leading-relaxed">
              Modern abstract logo exploration using balance, rhythm, and futuristic visual language.
            </p>
          </div>
        </div>

        <div class="bg-slate-900 border border-slate-800 rounded-[28px] overflow-hidden hover:-translate-y-2 transition duration-300 glow">
          <div class="h-60 bg-gradient-to-br from-white to-slate-300 flex items-center justify-center text-5xl font-black text-slate-900">
            ORB
          </div>

          <div class="p-6">
            <h3 class="text-2xl font-bold mb-3">Minimal Symbol</h3>
            <p class="text-slate-400 leading-relaxed">
              Simplified symbolic identity inspired by modern digital brands and premium aesthetics.
            </p>
          </div>
        </div>

      </div>
    </div>
  </section>


  <section class="px-6 py-24">
    <div class="max-w-4xl mx-auto text-center bg-slate-900 border border-slate-800 rounded-[36px] p-12 glow">

      <p class="uppercase tracking-[0.3em] text-cyan-400 text-sm mb-4">
        Available for Projects
      </p>

      <h2 class="text-4xl md:text-5xl font-extrabold leading-tight mb-6">
        Building visual identities that feel sharp, timeless, and unforgettable.
      </h2>

      <p class="text-slate-400 leading-relaxed mb-10 max-w-2xl mx-auto">
        Open for logo design, brand identity systems, minimalist concepts, monogram exploration, and vector illustration projects.
      </p>

      <div class="flex flex-wrap justify-center gap-4">
        <a href="mailto:dias.tidar9@gmail.com" class="bg-cyan-400 text-slate-900 font-semibold px-6 py-3 rounded-2xl hover:scale-105 transition duration-300">
          Contact Me
        </a>

        <a href="https://www.behance.net/" target="_blank" class="border border-slate-700 px-6 py-3 rounded-2xl hover:bg-white hover:text-slate-900 transition duration-300">
          Behance
        </a>
      </div>

    </div>
  </section>


  <footer class="px-6 py-10 border-t border-slate-800 text-center text-slate-500 text-sm">
    © 2026 Dias Tidar. Crafted with clean grids, vectors, and caffeine.
  </footer>

</body>
</html>
