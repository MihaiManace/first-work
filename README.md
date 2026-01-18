<html lang="ro" class="scroll-smooth"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>deCarbo - Servicii Premium Auto</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://code.iconify.design/3/3.1.0/iconify.min.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #09090b; /* Zinc 950 */
        }
        .glass-panel {
            background: rgba(24, 24, 27, 0.6);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        /* Custom scrollbar for a cleaner look */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #09090b;
        }
        ::-webkit-scrollbar-thumb {
            background: #27272a;
            border-radius: 3px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #3f3f46;
        }
    </style>
</head>
<body class="text-zinc-400 antialiased selection:bg-zinc-700 selection:text-white">

    <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 border-b border-zinc-800 bg-zinc-950/80 backdrop-blur-md">
        <div class="max-w-5xl mx-auto px-6 h-14 flex items-center justify-between">
            <a href="#" class="text-white font-medium tracking-tight text-lg flex items-center gap-2">
                <span class="iconify text-white" data-icon="lucide:hexagon" data-width="20"></span>
                deCarbo
            </a>
            <div class="hidden sm:flex items-center gap-6 text-sm font-medium">
                <a href="#about" class="hover:text-white transition-colors">Despre</a>
                <a href="#schedule" class="hover:text-white transition-colors">Program</a>
                <a href="#reviews" class="hover:text-white transition-colors">Recenzii</a>
            </div>
            <a href="tel:0725180234" class="text-sm font-medium bg-white text-zinc-950 px-3 py-1.5 rounded-md hover:bg-zinc-200 transition-colors">
                Contact
            </a>
        </div>
    </nav>

    <main class="max-w-5xl mx-auto px-6 pt-24 pb-12 space-y-8">

        <!-- Hero / About Section -->
        <section id="about" class="space-y-4 py-8">
            <h1 class="text-4xl md:text-5xl font-medium text-white tracking-tight">Performanță și confort.</h1>
            <p class="text-lg md:text-xl text-zinc-400 max-w-2xl leading-relaxed font-light">
                deCarbo a fost creat pentru a vă oferi servicii premium profesionale pentru confort şi creşterea eficienţei maşinii dumneavoastră.
            </p>
            <div class="flex flex-wrap gap-2 pt-2">
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-medium bg-zinc-900 border border-zinc-800 text-zinc-300">
                    <span class="iconify" data-icon="lucide:wrench" data-width="14"></span> Mecanic
                </span>
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-medium bg-zinc-900 border border-zinc-800 text-zinc-300">
                    <span class="iconify" data-icon="lucide:battery-charging" data-width="14"></span> Baterie
                </span>
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-medium bg-zinc-900 border border-zinc-800 text-zinc-300">
                    <span class="iconify" data-icon="lucide:droplet" data-width="14"></span> Schimbă uleiul
                </span>
            </div>
        </section>

        <!-- Main Grid Layout -->
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6">

            <!-- Schedule Column -->
            <div id="schedule" class="col-span-1 md:col-span-4 glass-panel rounded-2xl p-6 flex flex-col h-full">
                <div class="flex items-center justify-between mb-6">
                    <h2 class="text-zinc-100 font-medium tracking-tight">Program de lucru</h2>
                    <span class="text-xs font-medium px-2 py-0.5 rounded bg-red-500/10 text-red-400 border border-red-500/20">Închis</span>
                </div>
                
                <ul class="space-y-3 text-sm flex-1">
                    <li class="flex justify-between">
                        <span class="text-zinc-500">luni</span>
                        <span class="text-zinc-300">09:00–18:00</span>
                    </li>
                    <li class="flex justify-between">
                        <span class="text-zinc-500">marți</span>
                        <span class="text-zinc-300">09:00–18:00</span>
                    </li>
                    <li class="flex justify-between">
                        <span class="text-zinc-500">miercuri</span>
                        <span class="text-zinc-300">09:00–18:00</span>
                    </li>
                    <li class="flex justify-between">
                        <span class="text-zinc-500">joi</span>
                        <span class="text-zinc-300">09:00–18:00</span>
                    </li>
                    <li class="flex justify-between">
                        <span class="text-zinc-500">vineri</span>
                        <span class="text-zinc-300">09:00–18:00</span>
                    </li>
                    <li class="flex justify-between">
                        <span class="text-zinc-500">sâmbătă</span>
                        <span class="text-zinc-500 italic">Închis</span>
                    </li>
                    <li class="flex justify-between">
                        <span class="text-zinc-500">duminică</span>
                        <span class="text-zinc-500 italic">Închis</span>
                    </li>
                </ul>
            </div>

            <!-- Location & Contact Column -->
            <div class="col-span-1 md:col-span-5 flex flex-col gap-6">
                <!-- Location Card -->
                <div class="glass-panel rounded-2xl p-0 overflow-hidden relative group">
                    <!-- Fake Map Background -->
                    <div class="absolute inset-0 bg-zinc-800 opacity-50 z-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI0MCIgaGVpZ2h0PSI0MCIgdmlld0JveD0iMCAwIDQwIDQwIj48ZyBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0wIDQwTDQwIDBIMHY0MHpNNDAgNDBWMHMyMCAyMCA0MCA0MHoiIGZpbGw9IiMzMzMiIGZpbGwtb3BhY2l0eT0iMC4xIi8+PC9nPjwvc3ZnPg==')]"></div>
                    <div class="relative z-10 p-6 bg-gradient-to-t from-zinc-900 via-zinc-900/80 to-transparent min-h-[200px] flex flex-col justify-end">
                        <div class="flex items-start gap-3">
                            <span class="bg-white text-zinc-950 p-2 rounded-lg shadow-lg">
                                <span class="iconify" data-icon="lucide:map-pin" data-width="20"></span>
                            </span>
                            <div>
                                <h3 class="text-white font-medium text-sm">Locație</h3>
                                <p class="text-sm text-zinc-400 mt-1 leading-snug">
                                    Strada Izvor 3, Bragadiru,<br>077025 Bragadiru, Ilfov, România
                                </p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Contact Actions -->
                <div class="glass-panel rounded-2xl p-6">
                    <h3 class="text-zinc-100 font-medium tracking-tight mb-4">Contactează-ne</h3>
                    <p class="text-2xl font-light text-white mb-6 tracking-tight">0725 180 234</p>
                    <div class="grid grid-cols-2 gap-3">
                        <a href="tel:0725180234" class="flex items-center justify-center gap-2 bg-white text-zinc-950 text-sm font-medium py-2.5 px-4 rounded-lg hover:bg-zinc-200 transition-colors">
                            <span class="iconify" data-icon="lucide:phone" data-width="16"></span> Apeleză
                        </a>
                        <button class="flex items-center justify-center gap-2 bg-zinc-800 text-white border border-zinc-700 text-sm font-medium py-2.5 px-4 rounded-lg hover:bg-zinc-700 transition-colors">
                            <span class="iconify" data-icon="lucide:navigation" data-width="16"></span> Indicații
                        </button>
                    </div>
                </div>
            </div>

            <!-- Features/Stats Column -->
            <div class="col-span-1 md:col-span-3 space-y-6">
                
                <!-- Accessibility -->
                <div class="glass-panel rounded-2xl p-5">
                    <h3 class="text-xs uppercase tracking-widest text-zinc-500 font-semibold mb-4">Accesibilitate</h3>
                    <ul class="space-y-3">
                        <li class="flex items-start gap-3">
                            <span class="iconify text-zinc-100 mt-0.5" data-icon="lucide:accessibility" data-width="16"></span>
                            <span class="text-sm text-zinc-400 leading-tight">Intrare accesibilă</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="iconify text-zinc-100 mt-0.5" data-icon="lucide:parking-circle" data-width="16"></span>
                            <span class="text-sm text-zinc-400 leading-tight">Parcare accesibilă</span>
                        </li>
                    </ul>
                </div>

                <!-- Amenities -->
                <div class="glass-panel rounded-2xl p-5">
                    <h3 class="text-xs uppercase tracking-widest text-zinc-500 font-semibold mb-4">Dotări</h3>
                    <div class="flex gap-4">
                        <div class="flex flex-col items-center gap-1">
                            <div class="bg-zinc-800/50 p-2 rounded-md">
                                <span class="iconify text-zinc-300" data-icon="lucide:wrench" data-width="18"></span>
                            </div>
                            <span class="text-[10px] text-zinc-500">Mecanic</span>
                        </div>
                        <div class="flex flex-col items-center gap-1">
                            <div class="bg-zinc-800/50 p-2 rounded-md">
                                <span class="iconify text-zinc-300" data-icon="lucide:door-open" data-width="18"></span>
                            </div>
                            <span class="text-[10px] text-zinc-500">Toaletă</span>
                        </div>
                    </div>
                </div>

                <!-- Payments -->
                <div class="glass-panel rounded-2xl p-5">
                    <h3 class="text-xs uppercase tracking-widest text-zinc-500 font-semibold mb-4">Plăți</h3>
                    <div class="flex flex-wrap gap-2">
                         <span class="inline-flex items-center gap-1 px-2 py-1 bg-zinc-900 border border-zinc-800 rounded text-xs text-zinc-400">
                            <span class="iconify" data-icon="lucide:credit-card" data-width="12"></span> Card
                        </span>
                        <span class="inline-flex items-center gap-1 px-2 py-1 bg-zinc-900 border border-zinc-800 rounded text-xs text-zinc-400">
                            <span class="iconify" data-icon="lucide:nfc" data-width="12"></span> NFC
                        </span>
                    </div>
                </div>
            </div>
        </div>

        <!-- Reviews Section -->
        <section id="reviews" class="pt-8">
            <div class="flex flex-col md:flex-row items-start md:items-end justify-between mb-8 gap-4">
                <div>
                    <h2 class="text-2xl text-white font-medium tracking-tight mb-2">Recenzii clienți</h2>
                    <div class="flex items-center gap-3">
                        <span class="text-3xl font-semibold text-white tracking-tight">4,8</span>
                        <div class="flex flex-col gap-0.5">
                            <div class="flex text-yellow-500">
                                <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="14"></span>
                                <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="14"></span>
                                <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="14"></span>
                                <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="14"></span>
                                <span class="iconify" data-icon="lucide:star-half" data-fill="currentColor" data-width="14"></span>
                            </div>
                            <span class="text-xs text-zinc-500">191 de recenzii</span>
                        </div>
                    </div>
                </div>
                
                <!-- Rating Bars (Visual Only) -->
                <div class="flex flex-col gap-1 w-full md:w-48">
                    <div class="flex items-center gap-2 text-[10px] text-zinc-500">
                        <span>5</span> <div class="h-1 flex-1 bg-zinc-800 rounded-full overflow-hidden"><div class="h-full bg-zinc-500 w-[85%]"></div></div>
                    </div>
                    <div class="flex items-center gap-2 text-[10px] text-zinc-500">
                        <span>4</span> <div class="h-1 flex-1 bg-zinc-800 rounded-full overflow-hidden"><div class="h-full bg-zinc-500 w-[10%]"></div></div>
                    </div>
                    <div class="flex items-center gap-2 text-[10px] text-zinc-500">
                        <span>3</span> <div class="h-1 flex-1 bg-zinc-800 rounded-full overflow-hidden"><div class="h-full bg-zinc-500 w-[3%]"></div></div>
                    </div>
                    <div class="flex items-center gap-2 text-[10px] text-zinc-500">
                        <span>2</span> <div class="h-1 flex-1 bg-zinc-800 rounded-full overflow-hidden"><div class="h-full bg-zinc-500 w-[1%]"></div></div>
                    </div>
                    <div class="flex items-center gap-2 text-[10px] text-zinc-500">
                        <span>1</span> <div class="h-1 flex-1 bg-zinc-800 rounded-full overflow-hidden"><div class="h-full bg-zinc-500 w-[1%]"></div></div>
                    </div>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Review 1 -->
                <div class="glass-panel p-6 rounded-2xl flex flex-col gap-4 hover:border-zinc-700 transition-colors">
                    <div class="flex items-center justify-between">
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-zinc-800 flex items-center justify-center text-xs font-medium text-zinc-300">
                                AA
                            </div>
                            <div>
                                <h4 class="text-sm font-medium text-white">aurel aurash</h4>
                                <span class="text-xs text-zinc-500">acum 9 luni</span>
                            </div>
                        </div>
                        <div class="flex text-yellow-500">
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                        </div>
                    </div>
                    <p class="text-sm text-zinc-300 leading-relaxed">
                        Am apelat la acest service pentru a rezolva problema care-mi dădea batai de cap de ceva timp la Volvo xc90 2016 D5- egr înfundat. Mi-au fost curățate admisia, egr-ul și răcitorul de gaze si intr-o zi totul a fost gata.
                        <br><br>
                        Echipa a lucrat rapid și profesionist explicandu-mi în detaliu procesul și beneficiile curățării..masina se simte mai bine, se tureaza mai bine și consuma mai puțin.. incredibil, zici ca e alta mașină.. nota 10 pentru tot ceea ce fac acești buni profesioniști. Recomand cu încredere deCarbo!
                    </p>
                </div>

                <!-- Review 2 -->
                <div class="glass-panel p-6 rounded-2xl flex flex-col gap-4 hover:border-zinc-700 transition-colors">
                    <div class="flex items-center justify-between">
                        <div class="flex items-center gap-3">
                            <div class="w-8 h-8 rounded-full bg-zinc-800 flex items-center justify-center text-xs font-medium text-zinc-300">
                                MA
                            </div>
                            <div>
                                <h4 class="text-sm font-medium text-white">Alexandru-Mihai Anghel</h4>
                                <span class="text-xs text-zinc-500">acum o lună</span>
                            </div>
                        </div>
                        <div class="flex text-yellow-500">
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                             <span class="iconify" data-icon="lucide:star" data-fill="currentColor" data-width="12"></span>
                        </div>
                    </div>
                    <p class="text-sm text-zinc-300 leading-relaxed">
                        Am realizat la ei o curatare de admisie, racitor de gaze, egr si clapeta de acceleratie. Mi-a placut ca au vorbit frumos de la primul contact pe email/telefon si in persoana. Mi-au trimis oferta de pret cu care am fost de acord iar la final, avand in vedere ca nu a mai fost nimic altceva de facut la masina, pretul a ramas la fel.
                        <br><br>
                        Am putut sa platesc cu cardul. Mi-au trimis poze cu ce au gasit si cum au remediat.
                    </p>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="pt-12 border-t border-zinc-900 flex flex-col md:flex-row justify-between items-center text-xs text-zinc-600 gap-4">
            <p>© 2024 deCarbo. Toate drepturile rezervate.</p>
            <div class="flex gap-4">
                <a href="#" class="hover:text-zinc-400">Confidențialitate</a>
                <a href="#" class="hover:text-zinc-400">Termeni și condiții</a>
            </div>
        </footer>

    </main>


</body></html>
