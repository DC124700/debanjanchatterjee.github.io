<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Portfolio website of Dr. Debanjan Chatterjee, Ph.D., Postdoctoral Research Associate at Texas A&M AgriLife Research specializing in natural products chemistry, qNMR, metabolomics, chromatography, natural product isolation, and anti-inflammatory bioactive metabolites." />
  <title>Dr. Debanjan Chatterjee | Natural Products Chemist & Postdoctoral Research Associate</title>

  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            executive: {
              ink: '#020617',
              slate: '#0f172a',
              card: '#111827',
              blue: '#2563eb',
              indigo: '#4f46e5',
              cyan: '#06b6d4',
              soft: '#e2e8f0'
            }
          },
          boxShadow: {
            glow: '0 0 45px rgba(37, 99, 235, 0.25)'
          }
        }
      }
    }
  </script>

  <style>
    body {
      background:
        radial-gradient(circle at top left, rgba(37, 99, 235, 0.20), transparent 34rem),
        radial-gradient(circle at top right, rgba(79, 70, 229, 0.18), transparent 30rem),
        #020617;
    }

    .glass {
      background: rgba(15, 23, 42, 0.72);
      backdrop-filter: blur(16px);
      border: 1px solid rgba(148, 163, 184, 0.16);
    }

    .timeline-dot::before {
      content: "";
      position: absolute;
      left: -2.15rem;
      top: 0.35rem;
      width: 1rem;
      height: 1rem;
      border-radius: 9999px;
      background: linear-gradient(135deg, #2563eb, #06b6d4);
      box-shadow: 0 0 0 0.38rem rgba(37, 99, 235, 0.16);
    }

    details summary::-webkit-details-marker {
      display: none;
    }
  </style>
</head>

<body class="text-slate-200 antialiased">
  <!-- Navigation -->
  <header class="fixed inset-x-0 top-0 z-50 border-b border-white/10 bg-slate-950/80 backdrop-blur-xl">
    <nav class="mx-auto flex max-w-7xl items-center justify-between px-5 py-4">
      <a href="#home" class="group flex items-center gap-3">
        <span class="flex h-10 w-10 items-center justify-center rounded-2xl bg-gradient-to-br from-blue-600 to-cyan-400 text-sm font-black text-white shadow-glow">DC</span>
        <span>
          <span class="block text-sm font-bold tracking-wide text-white">Debanjan Chatterjee</span>
          <span class="block text-xs text-slate-400">Ph.D. · Natural Products Chemistry</span>
        </span>
      </a>

      <div class="hidden items-center gap-6 text-sm font-medium text-slate-300 lg:flex">
        <a href="#about" class="hover:text-cyan-300">About</a>
        <a href="#experience" class="hover:text-cyan-300">Experience</a>
        <a href="#education" class="hover:text-cyan-300">Education</a>
        <a href="#skills" class="hover:text-cyan-300">Skills</a>
        <a href="#publications" class="hover:text-cyan-300">Publications</a>
        <a href="#contact" class="rounded-full bg-blue-600 px-5 py-2 font-semibold text-white shadow-glow hover:bg-blue-500">Contact</a>
      </div>
    </nav>
  </header>

  <main id="home" class="mx-auto max-w-7xl px-5 pt-28">
    <!-- Hero -->
    <section class="grid items-center gap-10 py-12 lg:grid-cols-[1.2fr_0.8fr] lg:py-20">
      <div>
        <p class="mb-4 inline-flex rounded-full border border-blue-400/30 bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200">
          Postdoctoral Research Associate · Texas A&M AgriLife Research
        </p>

        <h1 class="max-w-4xl text-4xl font-black tracking-tight text-white sm:text-5xl lg:text-7xl">
          Dr. Debanjan Chatterjee
        </h1>

        <p class="mt-5 max-w-3xl text-lg leading-8 text-slate-300 sm:text-xl">
          Natural products chemist specializing in qNMR, LC-HRMS, HPLC/UPLC, GC-MS/GC×GC-MS, metabolomics,
          phytochemical isolation, and cell-based evaluation of bioactive plant metabolites.
        </p>

        <div class="mt-8 flex flex-wrap gap-3">
          <a href="mailto:debanjanchatterjee1995@gmail.com" class="rounded-full bg-gradient-to-r from-blue-600 to-indigo-600 px-6 py-3 text-sm font-bold text-white shadow-glow transition hover:scale-[1.02]">
            Email Me
          </a>
          <a href="#publications" class="rounded-full border border-white/15 px-6 py-3 text-sm font-bold text-slate-100 transition hover:border-cyan-300 hover:text-cyan-200">
            View Publications
          </a>
          <a href="https://orcid.org/0000-0002-2621-7553" target="_blank" rel="noopener" class="rounded-full border border-white/15 px-6 py-3 text-sm font-bold text-slate-100 transition hover:border-cyan-300 hover:text-cyan-200">
            ORCID
          </a>
        </div>

        <div class="mt-8 flex flex-wrap gap-3 text-sm">
          <a class="rounded-full bg-slate-900/80 px-4 py-2 text-slate-300 ring-1 ring-white/10 hover:text-cyan-200" href="https://scholar.google.com/scholar?q=Debanjan+Chatterjee" target="_blank" rel="noopener">Google Scholar</a>
          <a class="rounded-full bg-slate-900/80 px-4 py-2 text-slate-300 ring-1 ring-white/10 hover:text-cyan-200" href="https://www.researchgate.net/search/researcher?q=Debanjan%20Chatterjee" target="_blank" rel="noopener">ResearchGate</a>
          <a class="rounded-full bg-slate-900/80 px-4 py-2 text-slate-300 ring-1 ring-white/10 hover:text-cyan-200" href="https://www.linkedin.com/search/results/all/?keywords=Debanjan%20Chatterjee" target="_blank" rel="noopener">LinkedIn</a>
        </div>
      </div>

      <aside class="glass rounded-[2rem] p-6 shadow-glow">
        <div class="rounded-[1.5rem] bg-gradient-to-br from-slate-900 to-slate-950 p-7 ring-1 ring-white/10">
          <p class="text-sm font-semibold uppercase tracking-[0.22em] text-cyan-300">Profile Snapshot</p>
          <dl class="mt-7 grid gap-5">
            <div class="rounded-2xl bg-white/5 p-5">
              <dt class="text-sm text-slate-400">Current Role</dt>
              <dd class="mt-1 text-lg font-bold text-white">Postdoctoral Research Associate</dd>
              <dd class="text-sm text-slate-400">Texas A&M AgriLife Research · College Station, Texas, USA</dd>
            </div>
            <div class="rounded-2xl bg-white/5 p-5">
              <dt class="text-sm text-slate-400">Research Focus</dt>
              <dd class="mt-1 text-lg font-bold text-white">Natural Products · Food Metabolomics · Anti-inflammatory Bioactives</dd>
            </div>
            <div class="grid grid-cols-2 gap-4">
              <div class="rounded-2xl bg-white/5 p-5">
                <dt class="text-sm text-slate-400">Degree</dt>
                <dd class="mt-1 text-2xl font-black text-white">Ph.D.</dd>
              </div>
              <div class="rounded-2xl bg-white/5 p-5">
                <dt class="text-sm text-slate-400">Languages</dt>
                <dd class="mt-1 text-sm font-semibold text-white">English, Hindi, Bengali, Spanish</dd>
              </div>
            </div>
            <div class="rounded-2xl bg-white/5 p-5">
              <dt class="text-sm text-slate-400">Contact</dt>
              <dd class="mt-1 text-sm text-white">+1 279 257 6649</dd>
              <dd class="text-sm text-cyan-200">debanjanchatterjee1995@gmail.com</dd>
              <dd class="text-sm text-cyan-200">debanjan.chatterjee@ag.tamu.edu</dd>
            </div>
          </dl>
        </div>
      </aside>
    </section>

    <!-- About -->
    <section id="about" class="py-14">
      <div class="grid gap-8 lg:grid-cols-[0.75fr_1.25fr]">
        <div>
          <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">About Me</p>
          <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Natural products scientist connecting analytical chemistry, plant metabolomics, and cellular biology.</h2>
        </div>

        <div class="glass rounded-[2rem] p-7 leading-8 text-slate-300">
          <p>
            I am a trained natural product chemist with doctoral research in the chemical basis of traditional Ayurvedic detoxification
            processes of toxic medicinal plants and current postdoctoral research at Texas A&M AgriLife Research in horticultural sciences.
            My expertise spans qNMR, LC-HRMS, GC-MS, HPLC, HPTLC, GC×GC-MS, UPLC-RI, structural characterization, metabolite profiling,
            natural product isolation, and mechanistic evaluation of plant-derived bioactive molecules.
          </p>
          <p class="mt-5">
            My current research includes tomato sugar profiling, volatile analysis of tomato fruit using optimized HS-SPME-GC-MS,
            cis/trans lycopene analysis using ¹H and DOSY NMR, and GHSR-mediated anti-inflammatory actions of bitter melon
            metabolites in LPS-stimulated macrophages.
          </p>
        </div>
      </div>
    </section>

    <!-- Highlights -->
    <section class="py-6">
      <div class="grid gap-4 sm:grid-cols-2 lg:grid-cols-4">
        <div class="glass rounded-3xl p-6">
          <p class="text-4xl font-black text-white">qNMR</p>
          <p class="mt-2 text-sm text-slate-400">Quantitative NMR profiling, validation, and plant metabolite quantification.</p>
        </div>
        <div class="glass rounded-3xl p-6">
          <p class="text-4xl font-black text-white">GC×GC-MS</p>
          <p class="mt-2 text-sm text-slate-400">Volatile organic compound analysis in tomato varieties.</p>
        </div>
        <div class="glass rounded-3xl p-6">
          <p class="text-4xl font-black text-white">LC-HRMS</p>
          <p class="mt-2 text-sm text-slate-400">High-resolution mass characterization and metabolite profiling.</p>
        </div>
        <div class="glass rounded-3xl p-6">
          <p class="text-4xl font-black text-white">Cell Models</p>
          <p class="mt-2 text-sm text-slate-400">RAW 264.7 macrophage inflammation assays, qPCR, Western blot, and viability testing.</p>
        </div>
      </div>
    </section>

    <!-- Experience -->
    <section id="experience" class="py-16">
      <div class="mb-10">
        <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Experience</p>
        <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Research & Academic Timeline</h2>
      </div>

      <div class="relative ml-8 border-l border-slate-700/70 pl-8">
        <article class="timeline-dot relative mb-10 glass rounded-3xl p-7">
          <div class="flex flex-col justify-between gap-3 md:flex-row md:items-start">
            <div>
              <h3 class="text-2xl font-black text-white">Postdoctoral Research Associate</h3>
              <p class="mt-1 text-cyan-200">Texas A&M AgriLife Research · Horticultural Sciences · College Station, Texas, USA</p>
            </div>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-bold text-cyan-200 ring-1 ring-blue-400/20">October 2024 – Present</span>
          </div>
          <ul class="mt-6 list-disc space-y-3 pl-5 text-slate-300">
            <li>Optimization and validation of UPLC-RI-based analytical methods for tomato sugar profiling, enabling separation and quantification of major mono-, di-, and oligosaccharides and sugar alcohols.</li>
            <li>Investigating GHSR-mediated anti-inflammatory actions of bitter melon <em>Momordica charantia</em> metabolites in LPS-stimulated macrophages.</li>
            <li>Studying interference of triglycerides in cis/trans lycopene analysis across tomato varieties using ¹H and DOSY NMR.</li>
            <li>Isolation and purification of cucurbitane-type triterpene glycosides from bitter melon.</li>
            <li>Enhancing detection of volatiles in tomato fruit by optimizing solid-phase microextraction coupled with GC-MS.</li>
          </ul>
        </article>

        <article class="timeline-dot relative mb-10 glass rounded-3xl p-7">
          <div class="flex flex-col justify-between gap-3 md:flex-row md:items-start">
            <div>
              <h3 class="text-2xl font-black text-white">Assistant Professor</h3>
              <p class="mt-1 text-cyan-200">GITAM School of Pharmacy · Department of Pharmacognosy · Visakhapatnam, India</p>
            </div>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-bold text-cyan-200 ring-1 ring-blue-400/20">October 2024</span>
          </div>
        </article>

        <article class="timeline-dot relative mb-10 glass rounded-3xl p-7">
          <div class="flex flex-col justify-between gap-3 md:flex-row md:items-start">
            <div>
              <h3 class="text-2xl font-black text-white">Ph.D. Research Scholar</h3>
              <p class="mt-1 text-cyan-200">National Institute of Pharmaceutical Education and Research, Mohali, Punjab</p>
            </div>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-bold text-cyan-200 ring-1 ring-blue-400/20">2019 – 2024</span>
          </div>
          <ul class="mt-6 list-disc space-y-3 pl-5 text-slate-300">
            <li>Designed and executed a project on the chemical basis of traditional Ayurvedic detoxification processes of toxic medicinal plants including <em>Acorus calamus</em>, <em>Plumbago zeylanica</em>, <em>Croton tiglium</em>, and <em>Strychnos nux-vomica</em>.</li>
            <li>Performed qNMR, LC-HRMS, GC-MS, HPLC, and HPTLC-based secondary metabolite profiling from alkaloid-rich fractions, essential oils, hydroalcoholic extracts, and butanolic plant extracts.</li>
            <li>Conducted large-scale and small-scale isolation and characterization of β-asarone, plumbagin, isoshinanolone, chebulinic acid, and koenimbine.</li>
            <li>Assisted Indian Pharmacopoeia Commission scientists in qNMR profiling of <em>Aegle marmelos</em> and quantification of imperatonin, umbelliferone, psoralen, scopoletin, aegeline, and marmesin.</li>
            <li>Performed network pharmacology, analytical method development, LC-MS/MS profiling, qNMR profiling, in silico toxicity analysis using TOPKAT, and molecular docking studies.</li>
          </ul>
        </article>

        <article class="timeline-dot relative glass rounded-3xl p-7">
          <div class="flex flex-col justify-between gap-3 md:flex-row md:items-start">
            <div>
              <h3 class="text-2xl font-black text-white">Post-Graduate Student</h3>
              <p class="mt-1 text-cyan-200">National Institute of Pharmaceutical Education and Research, Ahmedabad, Gujarat</p>
            </div>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-bold text-cyan-200 ring-1 ring-blue-400/20">2017 – 2019</span>
          </div>
          <ul class="mt-6 list-disc space-y-3 pl-5 text-slate-300">
            <li>Identified natural products with glucagon-like peptide-1 receptor agonist activity from anti-diabetic medicinal plants.</li>
            <li>Isolated and identified Pinocembrin-7-O-[4’’,6’’-(S)-Hexahydroxy Diphenoyl-β-D-Glucose] from <em>Macrosolen capitellatus</em>.</li>
            <li>Conducted large-scale isolation of α-mangostin and chebulinic acid from <em>Garcinia mangostana</em> and <em>Terminalia chebula</em>.</li>
            <li>Performed computer-aided drug design, molecular docking, molecular dynamics, and screening using Maestro, AutoDock, GROMACS, Discovery Studio, and UCSF-Chimera.</li>
            <li>Evaluated anticancer activity using Alamar Blue assay in MCF-7 breast cancer cells and insulin secretion assay in INS-1E insulinoma cells.</li>
          </ul>
        </article>
      </div>
    </section>

    <!-- Education -->
    <section id="education" class="py-16">
      <div class="mb-10">
        <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Education</p>
        <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Academic Foundation</h2>
      </div>

      <div class="grid gap-5 md:grid-cols-2">
        <article class="glass rounded-3xl p-6">
          <p class="text-sm font-bold text-cyan-300">August 2024</p>
          <h3 class="mt-2 text-xl font-black text-white">Ph.D. in Natural Products</h3>
          <p class="mt-2 text-slate-300">National Institute of Pharmaceutical Education and Research, Mohali, Punjab</p>
          <p class="mt-2 text-sm text-slate-400">Score: 80.8% · NIPER JEE Ph.D. Entrance AIR-2</p>
        </article>

        <article class="glass rounded-3xl p-6">
          <p class="text-sm font-bold text-cyan-300">May 2019</p>
          <h3 class="mt-2 text-xl font-black text-white">M.S. (Pharm) in Natural Products Specialization</h3>
          <p class="mt-2 text-slate-300">National Institute of Pharmaceutical Education and Research, Ahmedabad, Gujarat</p>
          <p class="mt-2 text-sm text-slate-400">Score: 73.8% · NIPER JEE Master’s Entrance AIR-434</p>
        </article>

        <article class="glass rounded-3xl p-6">
          <p class="text-sm font-bold text-cyan-300">June 2017</p>
          <h3 class="mt-2 text-xl font-black text-white">Bachelor of Pharmacy</h3>
          <p class="mt-2 text-slate-300">Maulana Abul Kalam Azad University of Technology, Kolkata, West Bengal</p>
          <p class="mt-2 text-sm text-slate-400">Score: 79.99% · GPAT AIR 1342</p>
        </article>

        <article class="glass rounded-3xl p-6">
          <p class="text-sm font-bold text-cyan-300">May 2013 · May 2011</p>
          <h3 class="mt-2 text-xl font-black text-white">Higher Secondary & Secondary Education</h3>
          <p class="mt-2 text-slate-300">West Bengal Council of Higher Secondary Education · West Bengal Board of Secondary Education</p>
          <p class="mt-2 text-sm text-slate-400">Class XII: 74.99% · Class X: 79.99%</p>
        </article>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="py-16">
      <div class="mb-10">
        <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Skills</p>
        <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Technical Expertise</h2>
      </div>

      <div class="grid gap-6 lg:grid-cols-2">
        <article class="glass rounded-3xl p-7">
          <h3 class="text-xl font-black text-white">Analytical & Characterization Techniques</h3>
          <div class="mt-5 flex flex-wrap gap-3">
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">JEOL 400 MHz NMR</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">¹H NMR</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">¹³C NMR</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">2D NMR</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">DOSY</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">qNMR</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">GC×GC-MS</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">UPLC-RI</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">HPLC</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">Preparative HPLC</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">LC-MS-LTQ</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">LC-HRMS-qTOF</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">HPTLC</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">GC-FID</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">GC-MS</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">HS-SPME-GCMS</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">FT-IR</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">UV-Visible Spectroscopy</span>
            <span class="rounded-full bg-blue-500/10 px-4 py-2 text-sm font-semibold text-cyan-200 ring-1 ring-blue-400/20">Elemental Analysis</span>
          </div>
        </article>

        <article class="glass rounded-3xl p-7">
          <h3 class="text-xl font-black text-white">Cell Biology, qPCR & Protein Analysis</h3>
          <div class="mt-5 flex flex-wrap gap-3">
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">RAW 264.7 Macrophages</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">BSL-2 Cell Culture</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">MTT Assay</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">Alamar Blue</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">LDH Assay</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">LPS Inflammation Model</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">RNA Extraction</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">cDNA Synthesis</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">RT-PCR</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">qPCR</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">Western Blot</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">SDS-PAGE</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">PVDF Transfer</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">Bio-Rad ChemiDoc</span>
            <span class="rounded-full bg-indigo-500/10 px-4 py-2 text-sm font-semibold text-indigo-200 ring-1 ring-indigo-400/20">Image Lab</span>
          </div>
        </article>

        <article class="glass rounded-3xl p-7">
          <h3 class="text-xl font-black text-white">Extraction, Isolation & Natural Products</h3>
          <div class="mt-5 flex flex-wrap gap-3">
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Green Extraction</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Column Chromatography</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Silica Gel</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Basic Alumina</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Diaion HP-20</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Sephadex LH-20</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Vacuum Liquid Chromatography</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Flash Chromatography</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Yamazen</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">CombiFlash Rf+ Lumen</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Semi-Preparative HPLC</span>
            <span class="rounded-full bg-cyan-500/10 px-4 py-2 text-sm font-semibold text-cyan-100 ring-1 ring-cyan-400/20">Preparative HPLC</span>
          </div>
        </article>

        <article class="glass rounded-3xl p-7">
          <h3 class="text-xl font-black text-white">Computational, Software & Platforms</h3>
          <div class="mt-5 flex flex-wrap gap-3">
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">R</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">C</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">C++</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">AutoDock 4.2.6</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">Schrödinger Maestro 11.04</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">Discovery Studio</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">TOPKAT</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">QSAR Toolbox</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">GROMACS</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">UCSF-Chimera</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">ChemDraw</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">MNova</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">TopSpin</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">Delta</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">MassHunter</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">MzMine</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">OriginPro</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">GraphPad Prism</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">Power BI</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">EndNote</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">Mendeley</span>
            <span class="rounded-full bg-slate-700/60 px-4 py-2 text-sm font-semibold text-slate-100 ring-1 ring-white/10">Zotero</span>
          </div>
        </article>
      </div>
    </section>

    <!-- Research Themes -->
    <section class="py-16">
      <div class="mb-10">
        <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Research Themes</p>
        <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Current Scientific Focus</h2>
      </div>

      <div class="grid gap-6 lg:grid-cols-3">
        <article class="glass rounded-3xl p-7">
          <h3 class="text-xl font-black text-white">Tomato Metabolomics</h3>
          <p class="mt-4 text-slate-300">UPLC-RI sugar profiling, HS-SPME-GC-MS volatile optimization, and ¹H/DOSY NMR-based lycopene analysis across tomato varieties.</p>
        </article>
        <article class="glass rounded-3xl p-7">
          <h3 class="text-xl font-black text-white">Bitter Melon Bioactives</h3>
          <p class="mt-4 text-slate-300">Isolation and purification of cucurbitane-type triterpene glycosides and evaluation of anti-inflammatory efficacy in macrophage models.</p>
        </article>
        <article class="glass rounded-3xl p-7">
          <h3 class="text-xl font-black text-white">Ayurvedic Detoxification Chemistry</h3>
          <p class="mt-4 text-slate-300">Chemical evaluation of detoxification processes for toxic medicinal plants using qNMR, LC-HRMS, GC-MS, HPLC, and HPTLC.</p>
        </article>
      </div>
    </section>

    <!-- Publications -->
    <section id="publications" class="py-16">
      <div class="mb-10">
        <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Publications</p>
        <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Research Papers, Manuscripts & Book Chapters</h2>
      </div>

      <div class="space-y-5">
        <details open class="glass rounded-3xl p-6">
          <summary class="flex cursor-pointer items-center justify-between gap-4 text-xl font-black text-white">
            Research Papers
            <span class="rounded-full bg-white/10 px-3 py-1 text-xs text-cyan-200">Open / Close</span>
          </summary>
          <ol class="mt-6 list-decimal space-y-5 pl-5 text-slate-300">
            <li>Sangeeta Balyan, Sayak Mukhopadhyay, Debanjan Chatterjee, Vikas Dadwal, Deepak Kumar Jha, Pushkar Lele, Bhimanagouda S. Patil. “Probiotic Exopolysaccharide-Mediated Encapsulation of Indole-3-Acetic Acid: A Biocompatible Approach for Delivery, Enhanced Stability, and <em>E. coli</em> Motility Disruption.” <a class="text-cyan-300 hover:text-cyan-100" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6539060" target="_blank" rel="noopener">SSRN</a></li>
            <li>Debanjan Chatterjee, Ashutosh Kumar and Inder Pal Singh. “Qualitative and Quantitative Studies on the Chemical Changes during Ayurvedic Detoxification Process of <em>Acorus calamus</em> Linn. (Indian Vacha).” <em>Phytomedicine Plus</em> (2024). <a class="text-cyan-300 hover:text-cyan-100" href="https://www.sciencedirect.com/science/article/pii/S2667031324000496" target="_blank" rel="noopener">Article</a></li>
            <li>Debanjan Chatterjee, Fahima Narzish, Prashant Borade, and Inder Pal Singh. “Simultaneous quantitation of nine carbazole alkaloids from <em>Murraya koenigii</em> (L.) Spreng by ¹H qNMR spectroscopy.” <em>Natural Product Research</em> (2023): 1-9. <a class="text-cyan-300 hover:text-cyan-100" href="https://doi.org/10.1080/14786419.2023.2219819" target="_blank" rel="noopener">DOI</a></li>
            <li>Debanjan Chatterjee, Nazmina Vhora, Ashutosh Goswami, Aishwarya Hiray, Alok Jain, and Abhijeet S. Kate. “In-silico and in-vitro hybrid approach to identify glucagon-like peptide-1 receptor agonists from anti-diabetic natural products.” <em>Natural Product Research</em> (2022): 1-5. <a class="text-cyan-300 hover:text-cyan-100" href="https://doi.org/10.1080/14786419.2022.2106567" target="_blank" rel="noopener">DOI</a></li>
            <li>Ankur Kumar Tanwar, Debanjan Chatterjee, Neha Jain, Shivam Sharma, Kulbhushan Tikoo and Inder Pal Singh. “Chemical Basis of the Traditional Ayurvedic Detoxification Process of the Toxic Medicinal Plant <em>Plumbago zeylanica</em>.” <em>Journal of Natural Products</em> (2025): 1-9. <a class="text-cyan-300 hover:text-cyan-100" href="https://pubs.acs.org/doi/10.1021/acs.jnatprod.3c00975?articleRef=control" target="_blank" rel="noopener">Article</a></li>
            <li>Mandeep Kaur, Debanjan Chatterjee, Shivani Singla, Inder Pal Singh and Gopabandhu Jena. “<em>Terminalia chebula</em> Retz. Extract Mitigates DSS induced Chronic Colitis in BALB/c mice: Involvement of AMPK, SIRT1, NF-kB and TNF-α.” <em>Tissue and Cell</em> (2024). <a class="text-cyan-300 hover:text-cyan-100" href="https://www.sciencedirect.com/science/article/abs/pii/S0040816624002933" target="_blank" rel="noopener">Article</a></li>
            <li>Inder Pal Singh, Debanjan Chatterjee and Ankur Kumar Tanwar. “qNMR of <em>Aegle marmelos</em> PPI (Phytopharmaceutical) monograph in Indian Pharmacopoeia Addendum 2024 to IP 2022.” <a class="text-cyan-300 hover:text-cyan-100" href="https://drive.google.com/file/d/1zCHIurt9NKM5gMVQeIHnsdXRoBaRmHKS/view" target="_blank" rel="noopener">Document</a></li>
            <li>Chilamula, Srija, Komal Pandey, Nilesh V. Malpure, Debanjan Chatterjee, Prashant S. Raut, Puspanjali Sirigineedi, Khemraj Bairwa, and Abhijeet S. Kate. “Isolation and Identification of Pinocembrin-7-O-[4”, 6"-(S)-Hexahydroxy Diphenoyl]-β-D-Glucose from <em>Macrosolen capitellatus</em>: In vitro and In silico Studies to Explore its Anticancer Potential.” <em>Journal of Biologically Active Products from Nature</em> 10, no. 3 (2020): 177-182. <a class="text-cyan-300 hover:text-cyan-100" href="https://doi.org/10.1080/22311866.2020.1791732" target="_blank" rel="noopener">DOI</a></li>
          </ol>
        </details>

        <details class="glass rounded-3xl p-6">
          <summary class="flex cursor-pointer items-center justify-between gap-4 text-xl font-black text-white">
            Manuscripts Submitted / Under Consideration
            <span class="rounded-full bg-white/10 px-3 py-1 text-xs text-cyan-200">Open / Close</span>
          </summary>
          <ul class="mt-6 list-disc space-y-4 pl-5 text-slate-300">
            <li>Ankur Kumar Tanwar, Vishu Pal, Debanjan Chatterjee, Amritparna Maity, Tarun Kumar Sharma, Inder Pal Singh. “Chemotypic Discrimination of <em>Cinnamomum tamala</em> (Indian Bay Leaf) Using ¹H qNMR and Chemometric Analysis with Evaluation of Antibacterial Activity Against Sepsis and Foodborne Pathogens.” <em>Phytochemical Analysis</em> — Under Review.</li>
            <li>Sangeeta Balyan, Debanjan Chatterjee, Vikas Dadwal, Deepak Kumar Jha, Bhimanagouda S. Patil. “Structure-Function Relationships and Superior Functional Properties of Underutilized Lactic Acid Bacteria Strain-Derived Exopolysaccharides: A Comparative Study.” Under Communication.</li>
            <li>Ankur Kumar Tanwar, Debanjan Chatterjee, Tanmay Kumar Varma, Prabha Garg, Inder Pal Singh. “In Silico Identification of Poisonous Plants in Herbal Origin.” <em>Toxicon</em> (2025) — Under Review.</li>
          </ul>
        </details>

        <details class="glass rounded-3xl p-6">
          <summary class="flex cursor-pointer items-center justify-between gap-4 text-xl font-black text-white">
            Review Paper & Book Chapters
            <span class="rounded-full bg-white/10 px-3 py-1 text-xs text-cyan-200">Open / Close</span>
          </summary>
          <div class="mt-6 space-y-7 text-slate-300">
            <div>
              <h3 class="font-bold text-white">Review Paper</h3>
              <p class="mt-2">Inder Pal Singh, Ankur Kumar Tanwar, Debanjan Chatterjee, Uma Ranjan Lal. “An overview of medicinal chemistry and toxicity of poisonous plants listed in Schedule E (1) of the Drugs & Cosmetics Act of India.” <em>Toxicon</em> (2025). <a class="text-cyan-300 hover:text-cyan-100" href="https://www.sciencedirect.com/science/article/pii/S0041010125000819" target="_blank" rel="noopener">Article</a></p>
            </div>
            <div>
              <h3 class="font-bold text-white">Book Chapters</h3>
              <ul class="mt-3 list-disc space-y-4 pl-5">
                <li>Aishik Banerjee, Swarnali Banerjee, Arudeepa Dash, Subhrajyoty Basu, Debanjan Chatterjee*, Amit Kundu, Sumanta Mandal, Partha Roy, Abhishek Tiwari and Varhsa Tiwari. “Total Synthesis of Resveratrol and Stilbenes” in <em>Exploring the Synthesis, Ethnopharmacology and Therapeutic Applications of Bioactive Polyphenols</em> (2026). <a class="text-cyan-300 hover:text-cyan-100" href="https://www.routledge.com/Exploring-the-Synthesis-Ethnopharmacology-and-Therapeutic-Applications-of-Bioactive-Polyphenols/Tiwari-Tiwari/p/book/9781032916361" target="_blank" rel="noopener">Book</a></li>
                <li>LalMohan Maji, Sumanta Mandal, Pujan Sasmal, Debanjan Chatterjee*. “Enhancing Understanding of Phytochemicals’ Role in Managing Metabolic Disorder.” <em>Plant Based Drug Discovery</em> (2025). <a class="text-cyan-300 hover:text-cyan-100" href="https://www.sciencedirect.com/science/article/abs/pii/B9780443316982000023" target="_blank" rel="noopener">Chapter</a></li>
                <li>Inder Pal Singh, Furkan Ahmad, Debanjan Chatterjee, Ruchi Bajpai, and Neha Sengar. “Natural products: drug discovery and development.” <em>Drug Discovery and Development: From Targets and Molecules to Medicines</em> (2021): 11-65. <a class="text-cyan-300 hover:text-cyan-100" href="https://doi.org/10.1007/978-981-15-5534-3_2" target="_blank" rel="noopener">DOI</a></li>
                <li>Inder Pal Singh, Dharmishtha Rajput, Debanjan Chatterjee. “Analytical Methods for Capsaicinoids and Other Bioactive Metabolites.” In <em>Peppers: Biological Health and Postharvest Perspectives</em>. Taylor & Francis, 2024. <a class="text-cyan-300 hover:text-cyan-100" href="https://www.taylorfrancis.com/chapters/edit/10.1201/9781003378259-5/analytical-methods-capsaicinoids-bioactive-metabolites-inder-pal-singh-dharmistha-rajput-debanjan-chatterjee?context=ubx&refId=cfc7df4f-eba3-4539-b188-33383198f0b0" target="_blank" rel="noopener">Chapter</a></li>
                <li>Das, Niranjan, Akash Dey, Sudip Kumar Mandal, Debanjan Chatterjee, Rajan Logesh, and Hari Prasad Devkota. “Secondary metabolites of clove (<em>Syzygium aromaticum</em>).” In <em>Clove</em>, pp. 175-193. Academic Press, 2022. <a class="text-cyan-300 hover:text-cyan-100" href="https://doi.org/10.1016/B978-0-323-85177-0.00020-3" target="_blank" rel="noopener">DOI</a></li>
                <li>Malik, Chandan Kumar, and Debanjan Chatterjee*. “Machine Learning and Deep Learning in IoT-Based Healthcare Support Systems.” In <em>Healthcare Systems and Health Informatics</em>, pp. 35-50. CRC Press. <a class="text-cyan-300 hover:text-cyan-100" href="https://www.taylorfrancis.com/chapters/edit/10.1201/9781003146087-5/machine-learning-deep-learning-iot-based-healthcare-support-systems-chandan-kumar-malik-debanjan-chatterjee" target="_blank" rel="noopener">Chapter</a></li>
                <li>Dey, Akash, and Debanjan Chatterjee*. “Chapter-15 A Comprehensive Overview of Nutraceuticals from MACs: Regulatory Aspects to Commercialization.” <a class="text-cyan-300 hover:text-cyan-100" href="https://www.rubiconpublications.com/books/1632381858-studies-on-medicinal-aromatic-crops" target="_blank" rel="noopener">Chapter</a></li>
              </ul>
            </div>
          </div>
        </details>
      </div>
    </section>

    <!-- Awards & Services -->
    <section class="py-16">
      <div class="grid gap-6 lg:grid-cols-2">
        <article class="glass rounded-3xl p-7">
          <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Awards</p>
          <h2 class="mt-3 text-2xl font-black text-white">Scholastic Achievements</h2>
          <ul class="mt-6 list-disc space-y-3 pl-5 text-slate-300">
            <li>Secured Postdoctoral Fellowship from Texas AgriLife Research through a USDA granted project.</li>
            <li>Recognized as “other participants” in the Indian Pharmacopoeia Addendum 2024 for assisting qNMR profiling of <em>Aegle marmelos</em> extract and enriched fraction.</li>
            <li>Received CSIR travel grant [TG/12357/23/-HRD] covering full airfare to attend ICGST-2023 in Kuala Lumpur, Malaysia.</li>
            <li>First Prize in Oral Presentation Category at National Conference on Natural Products/AYUSH System of Medicine, PGIMER Chandigarh, 2023.</li>
            <li>Second Prize in Poster Presentation Category at NIPER Pharmacon 2022.</li>
            <li>Indian Chemical Society Research Excellence Award for Oral Presentation at RTCS-2020.</li>
            <li>Best Poster Award: S.S. Bhatnagar Young Scientist Award at RACMS-2020.</li>
            <li>Qualified NIPER Ph.D. JEE with AIR 2 in 2019.</li>
            <li>Qualified NIPER-JEE with AIR 434 and percentile 98.5% in 2017.</li>
            <li>Qualified GPAT with AIR 1342 and percentile 97.64% in 2017.</li>
            <li>Qualified WBJEE-2013.</li>
          </ul>
        </article>

        <article class="glass rounded-3xl p-7">
          <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Professional Service</p>
          <h2 class="mt-3 text-2xl font-black text-white">Reviewer & Leadership Roles</h2>
          <div class="mt-6 space-y-6 text-slate-300">
            <div>
              <h3 class="font-bold text-white">Reviewer Recognition</h3>
              <ul class="mt-3 list-disc space-y-2 pl-5">
                <li>Frontiers in Endocrinology, Frontiers</li>
                <li>Current Pharmaceutical Biotechnology, Bentham Sciences</li>
                <li>Pharmacological Research - Natural Products, Elsevier</li>
                <li>Toxicon, Elsevier</li>
                <li>Phytomedicine Plus, Elsevier</li>
                <li>Turkish Journal of Theoretical Chemistry, DerGI Park Publishing House</li>
              </ul>
            </div>
            <div>
              <h3 class="font-bold text-white">Leadership</h3>
              <ul class="mt-3 list-disc space-y-2 pl-5">
                <li>Teaching Assistant & Reviewer in Undergraduate Research Scholars’ Thesis Application Program at Texas A&M University.</li>
                <li>Organizing committee member for workshop on welfare and ethical guidelines in surgical small animal model development at GITAM School of Pharmacy.</li>
                <li>Mentored five students for master’s dissertations.</li>
                <li>Elected Council of Students’ Representatives member at NIPER Mohali.</li>
                <li>Elected Departmental Placement Coordinator for M.S. (Pharm.) placement at NIPER Ahmedabad.</li>
                <li>Elected Ph.D. Placement Coordinator for Ph.D. placement at NIPER Mohali.</li>
              </ul>
            </div>
          </div>
        </article>
      </div>
    </section>

    <!-- Conferences / Training -->
    <section class="py-16">
      <div class="mb-10">
        <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Conferences & Training</p>
        <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Presentations, Courses & Industrial Exposure</h2>
      </div>

      <div class="space-y-5">
        <details class="glass rounded-3xl p-6">
          <summary class="flex cursor-pointer items-center justify-between gap-4 text-xl font-black text-white">
            International & National Presentations
            <span class="rounded-full bg-white/10 px-3 py-1 text-xs text-cyan-200">Open / Close</span>
          </summary>
          <div class="mt-6 grid gap-8 lg:grid-cols-2">
            <div>
              <h3 class="font-bold text-white">International</h3>
              <ul class="mt-4 list-disc space-y-3 pl-5 text-slate-300">
                <li>Poster Presentation on “¹H-NMR spectroscopy-based metabolomics of <em>Cinnamomum tamala</em>: Quantification and chemometrics analysis of volatiles” at ACS Fall 2025, Washington DC, USA, August 18, 2025.</li>
                <li>Oral Presentation on “Assessing the effect of Processing on Volatile Organic Compounds in Tomatoes Using Solid-Phase Microextraction and GC-MS” at ASHS-2025, New Orleans, Louisiana, August 1, 2025.</li>
                <li>Oral Presentation on “Enhancing Detection of Volatiles in Tomato Fruit by Optimizing Solid-Phase Microextraction Coupled with GC-MS” at SRASHS-2025, Texas A&M University, Irving, Dallas, February 1, 2025.</li>
                <li>Invited lecture abstract: “Chemistry of Ayurvedic Detoxification Processes for Toxic Medicinal Plants” at ICTMP-2024, CSIR-IIIM Jammu, February 17, 2024.</li>
                <li>Poster: “Chemistry of Ayurvedic detoxification process of <em>Plumbago zeylanica</em>” at ICGST-2023, Universiti Teknologi Malaysia, Kuala Lumpur.</li>
                <li>Two posters at NIPER Pharmacon 2022 on carbazole alkaloid quantification from <em>Murraya koenigii</em> and Ayurvedic detoxification chemistry.</li>
                <li>Attended ICGST-2021, Research Institute of Green Science and Technology, Shizuoka University, Japan.</li>
                <li>Poster at RACMS-2020 on GLP-1 receptor agonists from anti-diabetic natural products.</li>
                <li>Oral Presentation at RACMS-2020 on isolation and identification of Pinocembrin-7-O-[4’’,6’’-(S)-Hexahydroxy Diphenoyl-β-D-Glucose] from <em>Macrosolen capitellatus</em>.</li>
                <li>Poster at SFEC 2020 on natural products possessing GLP-1 receptor agonist activity.</li>
                <li>Poster at DDNPTM-2018 on in silico screening of natural product database for GLP-1 receptor agonists.</li>
              </ul>
            </div>

            <div>
              <h3 class="font-bold text-white">National</h3>
              <ul class="mt-4 list-disc space-y-3 pl-5 text-slate-300">
                <li>Oral Presentation abstract: “Chemical Basis of Ayurvedic Detoxification Process” at National Conference on Natural Products/AYUSH System of Medicine-2024, PGIMER Chandigarh.</li>
                <li>Attended AYURINFORMATICS Symposium at NIPER SAS Nagar, 2024.</li>
                <li>Poster: “¹H qNMR quantification of essential oil from <em>Cinnamomum tamala</em>” at NIPER Students Research Symposium, 2023.</li>
                <li>Attended Indian Pharmacopoeia Commission interactive meet at NIPER SAS Nagar, 2023.</li>
                <li>Oral Presentation: “GCMS, HPLC, LC-MS and qNMR Based Studies on the Chemical Changes During Ayurvedic Detoxification Process of <em>Acorus calamus</em>” at PGIMER Chandigarh, 2023.</li>
                <li>Attended Recent Advances in Bioorganic and Medicinal Chemistry, NIPER SAS Nagar, 2019.</li>
                <li>Attended National Conference on Convergence of Pharmaceutical Science and Biomedical Technology, NIPER Ahmedabad, 2018.</li>
              </ul>
            </div>
          </div>
        </details>

        <details class="glass rounded-3xl p-6">
          <summary class="flex cursor-pointer items-center justify-between gap-4 text-xl font-black text-white">
            Certificate Courses, Workshops & Industrial Training
            <span class="rounded-full bg-white/10 px-3 py-1 text-xs text-cyan-200">Open / Close</span>
          </summary>
          <div class="mt-6 grid gap-8 lg:grid-cols-2">
            <div>
              <h3 class="font-bold text-white">Courses & Workshops</h3>
              <ul class="mt-4 list-disc space-y-3 pl-5 text-slate-300">
                <li>Responsible Conduct of Research course, Texas A&M University, score 85%.</li>
                <li>General Safety Refresher Course, NIPER Mohali.</li>
                <li>Two-day workshop on Patent Drafting and Specification Writing, IPR Cell, NIPER-NRDC Innovation Facilitation Centre, NIPER Mohali, March 2023.</li>
                <li>Workshop on Advances in HPLC/UPLC software systems for chromatography, ACD Labs, Gurgaon, February 2023.</li>
                <li>WIPO General Courses on Intellectual Property: DL-501 and DL-301.</li>
                <li>SERB sponsored workshop on HRMS and HPLC application in Pharmaceutical Sciences, NIPER Kolkata, February 2022.</li>
                <li>International webinar: “Coming Closer to Nature for Impactful Publication,” NIPER Ahmedabad, September 2020.</li>
                <li>International Virtual Conference on Drug Discovery and Delivery, BITS Pilani, November 2020.</li>
                <li>Disso India 2020 Online International Conference by Society for Pharmaceutical Dissolution Science.</li>
                <li>FSSAI webinar series on GC/GCMS/LCMS residual analysis, LCMS/MS dereplication strategies, FTIR/NIR fundamentals, and DOE for method development.</li>
                <li>National Webinar on Basic Principles of ICP-OES and ICP-MS by PerkinElmer, May 2020.</li>
              </ul>
            </div>

            <div>
              <h3 class="font-bold text-white">Industrial / Research Training</h3>
              <ul class="mt-4 list-disc space-y-3 pl-5 text-slate-300">
                <li>One-week training on “Molecular Biology of Inflammatory Receptors towards Carcinogenesis” from MD Anderson Cancer Research Centre, Houston, Texas, USA, September 2025.</li>
                <li>One-month training at Small & Medium Pharmaceutical Industry Centre, Mohali, India, August 2019.</li>
                <li>45-day technical trainee experience at EMAMI LIMITED, Kolkata, June 1 to July 15, 2019.</li>
                <li>15-day industrial internship at Gluconet Limited, Government of West Bengal Undertaking, Kolkata, March 15 to March 30, 2016.</li>
                <li>One-month industrial internship at Dey’s Medical Manufacturing Limited, Kolkata, January to February 2016.</li>
                <li>One-month industrial internship at Albert David Limited, Kolkata, December 2015 to January 2016.</li>
              </ul>
            </div>
          </div>
        </details>
      </div>
    </section>

    <!-- Additional Details -->
    <section class="py-16">
      <div class="grid gap-6 lg:grid-cols-3">
        <article class="glass rounded-3xl p-7">
          <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Professional Details</p>
          <h2 class="mt-3 text-2xl font-black text-white">Research Identity</h2>
          <ul class="mt-6 space-y-3 text-slate-300">
            <li><span class="font-semibold text-white">ORCID:</span> <a href="https://orcid.org/0000-0002-2621-7553" target="_blank" rel="noopener" class="text-cyan-300 hover:text-cyan-100">0000-0002-2621-7553</a></li>
            <li><span class="font-semibold text-white">Google Scholar:</span> Debanjan_Google Scholar</li>
            <li><span class="font-semibold text-white">ResearchGate:</span> Debanjan_researchgate</li>
            <li><span class="font-semibold text-white">LinkedIn:</span> Debanjan_LinkedIn</li>
            <li><span class="font-semibold text-white">References:</span> Available upon request</li>
          </ul>
        </article>

        <article class="glass rounded-3xl p-7">
          <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Instruments</p>
          <h2 class="mt-3 text-2xl font-black text-white">Hands-on Platforms</h2>
          <p class="mt-6 leading-7 text-slate-300">
            Rotary evaporator, HPLC, HPTLC, GC, GC-MS, LC-MS, LC-HRMS, NMR, routine laboratory instruments,
            Agilent 1260 LC OpenLab, Shimadzu LC Solutions, Jasco ChromNAV 2.0, Camag WinCATS, Thermo-Fisher Xcalibur,
            PerkinElmer TurboMass, Agilent MassHunter, JEOL Delta, Bruker TopSpin.
          </p>
        </article>

        <article class="glass rounded-3xl p-7">
          <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Extracurricular</p>
          <h2 class="mt-3 text-2xl font-black text-white">Creative & Technical Interests</h2>
          <ul class="mt-6 list-disc space-y-3 pl-5 text-slate-300">
            <li>Member and annual exhibitor at The Photographic Society of India.</li>
            <li>Exhibited four times at International Exhibition organized by The Calcutta Journalist Club.</li>
            <li>Received Drone Pilot Licence from Directorate General of Civil Aviation, Government of India.</li>
          </ul>
        </article>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="py-16">
      <div class="grid gap-8 lg:grid-cols-[0.8fr_1.2fr]">
        <div>
          <p class="text-sm font-bold uppercase tracking-[0.22em] text-cyan-300">Contact</p>
          <h2 class="mt-3 text-3xl font-black text-white sm:text-4xl">Let’s connect for research, collaborations, and opportunities.</h2>
          <div class="mt-8 space-y-4 text-slate-300">
            <p><span class="font-bold text-white">Location:</span> College Station, Texas, USA</p>
            <p><span class="font-bold text-white">Email:</span> <a class="text-cyan-300 hover:text-cyan-100" href="mailto:debanjanchatterjee1995@gmail.com">debanjanchatterjee1995@gmail.com</a></p>
            <p><span class="font-bold text-white">Texas A&M Email:</span> <a class="text-cyan-300 hover:text-cyan-100" href="mailto:debanjan.chatterjee@ag.tamu.edu">debanjan.chatterjee@ag.tamu.edu</a></p>
            <p><span class="font-bold text-white">Phone:</span> <a class="text-cyan-300 hover:text-cyan-100" href="tel:+12792576649">+1 279 257 6649</a></p>
          </div>
        </div>

        <form action="mailto:debanjanchatterjee1995@gmail.com" method="post" enctype="text/plain" class="glass rounded-[2rem] p-7 shadow-glow">
          <div class="grid gap-5 sm:grid-cols-2">
            <label class="block">
              <span class="text-sm font-semibold text-slate-300">Name</span>
              <input type="text" name="name" required class="mt-2 w-full rounded-2xl border border-white/10 bg-slate-950/70 px-4 py-3 text-white outline-none transition placeholder:text-slate-500 focus:border-cyan-300 focus:ring-4 focus:ring-cyan-300/10" placeholder="Your name" />
            </label>

            <label class="block">
              <span class="text-sm font-semibold text-slate-300">Email</span>
              <input type="email" name="email" required class="mt-2 w-full rounded-2xl border border-white/10 bg-slate-950/70 px-4 py-3 text-white outline-none transition placeholder:text-slate-500 focus:border-cyan-300 focus:ring-4 focus:ring-cyan-300/10" placeholder="your.email@example.com" />
            </label>
          </div>

          <label class="mt-5 block">
            <span class="text-sm font-semibold text-slate-300">Subject</span>
            <input type="text" name="subject" class="mt-2 w-full rounded-2xl border border-white/10 bg-slate-950/70 px-4 py-3 text-white outline-none transition placeholder:text-slate-500 focus:border-cyan-300 focus:ring-4 focus:ring-cyan-300/10" placeholder="Research collaboration / opportunity / inquiry" />
          </label>

          <label class="mt-5 block">
            <span class="text-sm font-semibold text-slate-300">Message</span>
            <textarea name="message" rows="6" required class="mt-2 w-full resize-none rounded-2xl border border-white/10 bg-slate-950/70 px-4 py-3 text-white outline-none transition placeholder:text-slate-500 focus:border-cyan-300 focus:ring-4 focus:ring-cyan-300/10" placeholder="Write your message here..."></textarea>
          </label>

          <button type="submit" class="mt-6 w-full rounded-2xl bg-gradient-to-r from-blue-600 to-indigo-600 px-6 py-4 text-sm font-black uppercase tracking-wide text-white shadow-glow transition hover:scale-[1.01] hover:from-blue-500 hover:to-indigo-500">
            Send Message
          </button>
        </form>
      </div>
    </section>
  </main>

  <footer class="border-t border-white/10 py-8">
    <div class="mx-auto flex max-w-7xl flex-col items-center justify-between gap-4 px-5 text-center text-sm text-slate-400 md:flex-row md:text-left">
      <p>© 2026 Dr. Debanjan Chatterjee. Natural Products Chemistry · qNMR · Metabolomics · Bioactive Plant Metabolites.</p>
      <div class="flex flex-wrap justify-center gap-3">
        <a href="mailto:debanjanchatterjee1995@gmail.com" class="hover:text-cyan-300">Email</a>
        <a href="https://orcid.org/0000-0002-2621-7553" target="_blank" rel="noopener" class="hover:text-cyan-300">ORCID</a>
        <a href="#home" class="hover:text-cyan-300">Back to Top</a>
      </div>
    </div>
  </footer>
</body>
</html>
