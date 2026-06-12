<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shafira Pramatya - Digital Business & IS Consulting Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter, Playfair Display, and Space Grotesk -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,500;0,600;0,700;1,400;1,600&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                        display: ['Space Grotesk', 'sans-serif'],
                    },
                    colors: {
                        dustgrey: '#CFDBD5',    // Subtle stone grey
                        ivory: '#E8EDDF',       // Luxurious creamy white
                        tuscansun: '#F5CB5C',   // Radiant golden accent
                        shadowgrey: '#242423',  // Misty dark twilight
                        graphite: '#333533',    // Balanced neutral dark graphite
                        purewhite: '#FFFFFF',   // Clean base background
                    }
                }
            }
        }
    </script>
    <style>
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #FFFFFF;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #CFDBD5;
            border-radius: 4px;
        }
        .custom-shadow {
            box-shadow: 0 10px 30px -10px rgba(36, 36, 35, 0.08);
        }
        .retro-border {
            border: 1px solid #CFDBD5;
        }
    </style>
</head>
<body class="bg-purewhite text-shadowgrey font-sans antialiased selection:bg-tuscansun selection:text-shadowgrey">

    <header class="sticky top-0 z-50 bg-purewhite/95 backdrop-blur-md border-b border-dustgrey/40">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="font-display text-lg md:text-xl font-bold tracking-tight text-shadowgrey">
                S<span class="text-tuscansun">.</span>Pramatya
            </a>
            <nav class="hidden md:flex space-x-8 text-xs font-bold uppercase tracking-wider text-graphite">
                <a href="#about" class="hover:text-tuscansun transition-colors">About</a>
                <a href="#startup" class="hover:text-tuscansun transition-colors">Arthayana</a>
                <a href="#projects" class="hover:text-tuscansun transition-colors">Deliverables</a>
                <a href="#experience" class="hover:text-tuscansun transition-colors">Experience</a>
                <a href="#credentials" class="hover:text-tuscansun transition-colors">Credentials</a>
            </nav>
            <a href="#contact" class="bg-shadowgrey hover:bg-graphite text-ivory text-[11px] font-bold uppercase tracking-wider px-5 py-2.5 rounded shadow-sm hover:shadow transition-all duration-300">
                Let's Connect
            </a>
        </div>
    </header>

    <section id="about" class="py-12 md:py-20 max-w-6xl mx-auto px-6 border-b border-dustgrey/40">
        <div class="grid md:grid-cols-12 gap-12 items-center">
            <!-- Left Info Block -->
            <div class="md:col-span-7 space-y-6">
                <!-- Highlighting Arthayana award win directly instead of general focus tag -->
                <div class="inline-flex items-center gap-2 bg-ivory border border-dustgrey text-graphite text-xs font-semibold px-3.5 py-1.5 rounded-full">
                    <span class="w-2 h-2 rounded-full bg-tuscansun animate-pulse"></span>
                    Award Winner: 3rd Place International Start-Up (Arthayana)
                </div>
                <span class="block text-xs uppercase tracking-widest text-graphite font-bold">International Program Undergraduate</span>
                <h1 class="font-serif text-4xl md:text-5xl lg:text-6xl font-bold tracking-tight text-shadowgrey leading-tight">
                    Optimizing <span class="text-graphite italic">Digital Business</span> & Financial Ecosystem
                </h1>
                <p class="text-graphite/90 text-sm md:text-base leading-relaxed max-w-xl">
                    An International Program student at Universitas Negeri Surabaya deeply passionate about global learning, digital systems, and financial analysis. Currently driving academic and capital market synergy as the <strong>Vice President Director</strong> of the Capital Market Community.
                </p>

                <!-- Dynamic Academic Metrics Grid with Tuscan Sun highlights -->
                <div class="grid grid-cols-3 gap-4 pt-4 border-t border-dustgrey/60 max-w-lg">
                    <div class="border-l-2 border-tuscansun pl-3">
                        <span class="block text-2xl font-display font-bold text-shadowgrey">3.88</span>
                        <span class="text-[10px] text-graphite font-bold uppercase tracking-wider">Current GPA</span>
                    </div>
                    <div class="border-l-2 border-tuscansun pl-3">
                        <span class="block text-2xl font-display font-bold text-shadowgrey">580</span>
                        <span class="text-[10px] text-graphite font-bold uppercase tracking-wider">TOEFL Predict</span>
                    </div>
                    <div class="border-l-2 border-tuscansun pl-3">
                        <span class="block text-2xl font-display font-bold text-shadowgrey">2</span>
                        <span class="text-[10px] text-graphite font-bold uppercase tracking-wider">Research Papers</span>
                    </div>
                </div>

                <!-- Action CTAs -->
                <div class="pt-2 flex flex-wrap gap-4">
                    <a href="#startup" class="bg-shadowgrey hover:bg-graphite text-purewhite text-xs font-bold uppercase tracking-wider px-6 py-3 rounded shadow-md hover:translate-y-[-1px] transition-all">
                        Explore Arthayana Startup <i class="fa-solid fa-rocket ml-1.5 text-[10px] text-tuscansun"></i>
                    </a>
                    <a href="#projects" class="border border-dustgrey bg-purewhite hover:bg-ivory/20 text-graphite text-xs font-bold uppercase tracking-wider px-6 py-3 rounded transition-all">
                        View Technical Deliverables
                    </a>
                </div>
            </div>

            <div class="md:col-span-5 flex justify-center">
                <div class="relative group max-w-sm w-full">
                    <!-- Retro Framed Shadow using Tuscan Sun -->
                    <div class="absolute -inset-2 bg-dustgrey/30 rounded-2xl blur-lg group-hover:bg-tuscansun/20 transition-all"></div>
                    <div class="relative bg-purewhite p-4 rounded-2xl border border-dustgrey shadow-sm">
                        <!-- Img with warm tint and fallback handler -->
                        <div class="aspect-[3/4] w-full bg-purewhite rounded-xl overflow-hidden relative border border-dustgrey/60">
                            <img src="https://lh3.googleusercontent.com/d/1ZjX3NSLo2D_6H2DQK2baeg8XMhcB-YW1" 
                                 onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&q=80&w=600'" 
                                 alt="Shafira Pramatya" 
                                 class="w-full h-full object-cover transition-all duration-700">
                            <!-- Card overlay info using custom warm charcoal backdrop -->
                            <div class="absolute bottom-0 inset-x-0 p-4 bg-gradient-to-t from-shadowgrey to-transparent text-purewhite">
                                <h3 class="font-serif text-lg font-bold">Shafira Pramatya</h3>
                                <p class="text-[11px] text-ivory">UNESA Digital Business Undergraduate</p>
                            </div>
                        </div>
                        <!-- Toolset Snippets on Card Bottom -->
                        <div class="mt-3 flex flex-wrap gap-1">
                            <span class="text-[9px] bg-ivory text-graphite border border-dustgrey px-2 py-0.5 rounded font-medium">Python (Pandas)</span>
                            <span class="text-[9px] bg-ivory text-graphite border border-dustgrey px-2 py-0.5 rounded font-medium">SPSS / SmartPLS</span>
                            <span class="text-[9px] bg-ivory text-graphite border border-dustgrey px-2 py-0.5 rounded font-medium">Figma UI/UX</span>
                            <span class="text-[9px] bg-ivory text-graphite border border-dustgrey px-2 py-0.5 rounded font-medium">WordPress CMS</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="bg-ivory/20 py-16 border-b border-dustgrey/60">
        <div class="max-w-6xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto space-y-2 mb-12">
                <span class="text-xs font-bold uppercase tracking-widest text-graphite">The Consultant's Toolkit</span>
                <h2 class="font-serif text-2xl md:text-3xl font-bold text-shadowgrey">Core Areas of Competence</h2>
                <p class="text-xs md:text-sm text-graphite">Integrating quantitative research methodologies with system design frameworks to construct enterprise-grade digital business models.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Competency 1 -->
                <div class="p-6 rounded-lg border border-dustgrey bg-purewhite space-y-3 hover:border-tuscansun transition-all duration-300 custom-shadow">
                    <div class="w-10 h-10 rounded-lg bg-ivory/60 flex items-center justify-center text-graphite"><i class="fa-solid fa-code-fork text-lg"></i></div>
                    <h3 class="font-bold text-sm uppercase tracking-wider text-shadowgrey">Information Systems & Design</h3>
                    <p class="text-xs text-graphite leading-relaxed">Designing database relations (ERDs), drafting full-scope Product Requirement Documents (PRDs), and configuring functional systems.</p>
                    <span class="text-[10px] text-graphite font-bold uppercase block">Methods: ERD Modeling, Figma Prototyping</span>
                </div>
                <!-- Competency 2 -->
                <div class="p-6 rounded-lg border border-dustgrey bg-purewhite space-y-3 hover:border-tuscansun transition-all duration-300 custom-shadow">
                    <div class="w-10 h-10 rounded-lg bg-ivory/60 flex items-center justify-center text-graphite"><i class="fa-solid fa-chart-line text-lg"></i></div>
                    <h3 class="font-bold text-sm uppercase tracking-wider text-shadowgrey">Advanced Analytics & Data Science</h3>
                    <p class="text-xs text-graphite leading-relaxed">Processing multi-variable quantitative models, performing statistical analysis, and generating predictive outputs.</p>
                    <span class="text-[10px] text-graphite font-bold uppercase block">Tools: Python (Pandas/NumPy), SPSS, SmartPLS</span>
                </div>
                <!-- Competency 3 -->
                <div class="p-6 rounded-lg border border-dustgrey bg-purewhite space-y-3 hover:border-tuscansun transition-all duration-300 custom-shadow">
                    <div class="w-10 h-10 rounded-lg bg-ivory/60 flex items-center justify-center text-graphite"><i class="fa-solid fa-building-columns text-lg"></i></div>
                    <h3 class="font-bold text-sm uppercase tracking-wider text-shadowgrey">Corporate Operations & Finance</h3>
                    <p class="text-xs text-graphite leading-relaxed">Coordinating cross-functional business strategies, managing capital market projects, and structuring corporate protocols.</p>
                    <span class="text-[10px] text-graphite font-bold uppercase block">Network: Sucor Sekuritas, IDX, OJK</span>
                </div>
            </div>
        </div>
    </section>

    <section id="startup" class="py-20 bg-shadowgrey text-purewhite relative overflow-hidden">
        <!-- Background Grid Pattern -->
        <div class="absolute inset-0 opacity-5" style="background-size: 20px 20px; background-image: linear-gradient(to right, #CFDBD5 1px, transparent 1px), linear-gradient(to bottom, #CFDBD5 1px, transparent 1px);"></div>
        
        <div class="max-w-6xl mx-auto px-6 relative z-10">
            <div class="grid md:grid-cols-12 gap-12 items-center">
                <!-- Left: Double Interactive product mock frame & Image Gallery -->
                <div class="md:col-span-5 space-y-6 order-2 md:order-1">
                    <!-- Startup App & Award Ceremony Photos -->
                    <div class="bg-graphite border border-dustgrey/30 rounded-xl overflow-hidden shadow-2xl">
                        <!-- Browser Bar -->
                        <div class="bg-purewhite/10 px-3 py-2 border-b border-dustgrey/20 flex justify-between items-center text-[10px] font-mono">
                            <span class="text-ivory">Arthayana</span>
                            <div class="flex space-x-1">
                                <span class="w-2.5 h-2.5 rounded-full bg-dustgrey"></span>
                                <span class="w-2.5 h-2.5 rounded-full bg-ivory"></span>
                                <span class="w-2.5 h-2.5 rounded-full bg-tuscansun"></span>
                            </div>
                        </div>
                        <!-- Award Documentation Slideshow Gallery -->
                        <div class="relative bg-purewhite p-4 text-shadowgrey space-y-4">
                            <div class="flex justify-between items-center border-b border-dustgrey pb-3">
                                <span class="font-serif font-bold text-lg text-shadowgrey">Arthayana</span>
                                <span class="bg-tuscansun/20 text-graphite text-[9px] font-bold px-2 py-0.5 rounded border border-tuscansun">Culture & Local SMEs</span>
                            </div>
                            
                            <!-- Visual Gallery Tabs for Google Drive Photos -->
                            <div class="space-y-3">
                                <div class="relative aspect-video w-full rounded-lg overflow-hidden border border-dustgrey/40">
                                    <img id="arthayana-img-1" src="https://lh3.googleusercontent.com/d/18HSTLsZS-YO8l2efxQribn3cBVbko1uM" 
                                         onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1542744094-3a31f103e35f?auto=format&fit=crop&q=80&w=600'" 
                                         class="w-full h-full object-cover transition-opacity duration-500" alt="Arthayana Pitching Session">
                                    <img id="arthayana-img-2" src="https://lh3.googleusercontent.com/d/1vXVb3TBuDUatfeC6zpopJNCq3qBuIDFx" 
                                         onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1517245386807-bb43f82c33c4?auto=format&fit=crop&q=80&w=600'" 
                                         class="w-full h-full object-cover absolute inset-0 opacity-0 transition-opacity duration-500" alt="DIGCOFEST Award Ceremony">
                                </div>
                                <div class="flex justify-center gap-2">
                                    <button onclick="toggleArthayanaPic(1)" id="btn-pic-1" class="w-3 h-3 rounded-full bg-tuscansun border border-tuscansun transition-colors"></button>
                                    <button onclick="toggleArthayanaPic(2)" id="btn-pic-2" class="w-3 h-3 rounded-full bg-dustgrey border border-dustgrey hover:bg-tuscansun/50 transition-colors"></button>
                                </div>
                                <span class="block text-center text-[10px] text-graphite font-semibold italic">Interactive Gallery: Toggle award ceremony & pitching photos</span>
                            </div>

                            <div class="space-y-2">
                                <span class="block text-[11px] uppercase tracking-wider font-bold text-graphite">The Platform Value Engine:</span>
                                <p class="text-[11px] text-graphite/90 leading-relaxed bg-purewhite p-3 rounded border border-dustgrey">
                                    "A comprehensive digital ecosystem that integrates cultural heritage needs directly with scalable e-commerce capabilities, empowering local SMEs to expand modern commercial reach."
                                </p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- CANVA PITCH DECK & FIGMA LINK -->
                    <div class="p-4 bg-purewhite/5 border border-dustgrey/10 rounded-lg space-y-3">
                        <p class="text-xs text-ivory/80 text-center md:text-left">Inspect high-fidelity screens and strategic commercial pitch layouts for the award-winning venture:</p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <a href="https://canva.link/bxy94rqh9mw3ne9" target="_blank" class="inline-flex items-center justify-center gap-1.5 bg-tuscansun hover:bg-tuscansun/90 text-shadowgrey text-xs font-bold uppercase tracking-wider px-3 py-3 rounded transition-all duration-300">
                                <i class="fa-solid fa-file-powerpoint text-sm"></i> Canva Pitch Deck <i class="fa-solid fa-arrow-up-right-from-square text-[8px]"></i>
                            </a>
                            <a href="https://www.figma.com/proto/qGH6awQQqIO4sXDjGMwkGC/Arthayana-Indonesia?node-id=271-693&p=f&t=R1dnTzeM8jacfiuE-0&scaling=min-zoom&content-scaling=fixed&page-id=61%3A82&starting-point-node-id=271%3A693" target="_blank" class="inline-flex items-center justify-center gap-1.5 border border-dustgrey/40 hover:bg-purewhite/10 text-ivory text-xs font-bold uppercase tracking-wider px-3 py-3 rounded transition-all duration-300">
                                <i class="fa-brands fa-figma text-sm text-tuscansun"></i> Figma Prototype <i class="fa-solid fa-arrow-up-right-from-square text-[8px]"></i>
                            </a>
                        </div>
                    </div>
                </div>

                <div class="md:col-span-7 space-y-6 order-1 md:order-2">
                    <span class="text-xs font-bold uppercase tracking-widest text-tuscansun">Award-Winning Cultural E-Commerce Innovation</span>
                    <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl font-bold tracking-tight text-purewhite leading-none">
                        Arthayana: Bridging Heritage & Local SME Commerce
                    </h2>
                    <p class="text-ivory/80 text-sm md:text-base leading-relaxed">
                        Developed and successfully pitched <strong>Arthayana</strong>, a digital cultural-commerce model designed to bridge localized business ecosystems. The conceptualized platform was recognized with the <strong>3rd Place Winner</strong> position at the <strong>DIGCOFEST International Start-Up Competition</strong> organized by Universitas Negeri Surabaya.
                    </p>
                    
                    <div class="space-y-3 pt-2">
                        <h4 class="text-xs font-bold uppercase tracking-widest text-tuscansun">Core Project Pillars Pitch:</h4>
                        <ul class="text-xs text-ivory/90 space-y-2">
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-square-poll-vertical"></i></span>
                                <span><strong>SME Integration Engine:</strong> Allows localized artisans and cultural businesses to quickly showcase regional crafts with low overhead.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-square-poll-vertical"></i></span>
                                <span><strong>Cultural Heritage Alignment:</strong> Maps specialized buyer requirements with certified local products, enhancing cultural preservation.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-square-poll-vertical"></i></span>
                                <span><strong>Sustainable Business Model Canvas (BMC):</strong> Extensively validated during the Telkom Impactify Competition for local economic empowerment.</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="py-16 bg-purewhite border-b border-dustgrey/60">
        <div class="max-w-6xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto space-y-2 mb-12">
                <span class="text-xs font-bold uppercase tracking-widest text-graphite">Interactive Modules</span>
                <h2 class="font-serif text-2xl md:text-3xl font-bold text-shadowgrey">Technical Deliverables & Analysis</h2>
                <p class="text-xs md:text-sm text-graphite">Directly explore database schemas, inspect structured product requirements, and analyze visual data analytics outputs below.</p>
            </div>

            <!-- Category Selector Tabs -->
            <div class="flex justify-center gap-3 mb-8 text-xs font-bold uppercase tracking-wider">
                <button onclick="switchProjTab('proj-data')" id="tab-btn-proj-data" class="proj-tab-btn px-4 py-2 bg-tuscansun text-shadowgrey rounded shadow-sm transition-all">Data Analysis Reports</button>
                <button onclick="switchProjTab('proj-sys')" id="tab-btn-proj-sys" class="proj-tab-btn px-4 py-2 border border-dustgrey bg-purewhite text-graphite hover:bg-ivory/30 rounded transition-all">ERD & PRD Projects</button>
            </div>

            <!-- Interactive Project Contents Box -->
            <div class="bg-purewhite rounded-xl border border-dustgrey custom-shadow overflow-hidden min-h-[500px]">
                
                <!-- CONTENT 1: Data Analysis Dashboard -->
                <div id="content-proj-data" class="proj-content p-6 md:p-8 space-y-8">
                    <div class="flex justify-between items-start flex-wrap gap-4 border-b border-dustgrey/60 pb-4">
                        <div>
                            <span class="bg-ivory text-shadowgrey text-[10px] font-bold uppercase px-2.5 py-1 rounded border border-dustgrey">Data Analytics Engine</span>
                            <h3 class="font-bold text-xl text-shadowgrey mt-1.5">Analytical Report Dashboard (Python & SPSS Outputs)</h3>
                            <p class="text-xs text-graphite font-medium">Interact with generated visualization models reflecting research metrics processed for doctoral program assessments.</p>
                        </div>
                        <span class="text-xs font-mono bg-ivory px-3 py-1 rounded text-shadowgrey border border-dustgrey">Technology: Python (Pandas), SPSS</span>
                    </div>

                    <!-- Interactive Graphs -->
                    <div class="grid md:grid-cols-12 gap-8 items-center">
                        <div class="md:col-span-7 bg-purewhite p-4 rounded-lg border border-dustgrey space-y-4 shadow-sm">
                            <span class="text-[10px] font-mono uppercase font-bold text-graphite">Visualization Platform: Matplotlib & Pandas Outputs</span>
                            
                            <!-- Graph Container 1: SVG Bar Chart -->
                            <div class="space-y-2">
                                <div class="flex justify-between text-[10px] text-graphite font-medium">
                                    <span>MSME Competitiveness Boost (Sidoarjo MSME Research)</span>
                                    <span class="text-graphite font-bold"><span class="text-tuscansun">★</span> +28.4% Efficiency Gain</span>
                                </div>
                                <div class="h-44 bg-purewhite rounded border border-dustgrey p-3 flex flex-col justify-between">
                                    <div class="flex-1 flex items-end justify-around space-x-2">
                                        <div class="w-1/4 bg-graphite/20 h-16 rounded-t relative group">
                                            <span class="absolute -top-6 left-1/2 -translate-x-1/2 bg-shadowgrey text-[9px] text-purewhite px-1 py-0.5 rounded opacity-0 group-hover:opacity-100 transition-opacity">16%</span>
                                        </div>
                                        <div class="w-1/4 bg-graphite/30 h-28 rounded-t relative group">
                                            <span class="absolute -top-6 left-1/2 -translate-x-1/2 bg-shadowgrey text-[9px] text-purewhite px-1 py-0.5 rounded opacity-0 group-hover:opacity-100 transition-opacity">42%</span>
                                        </div>
                                        <div class="w-1/4 bg-dustgrey h-32 rounded-t relative group">
                                            <span class="absolute -top-6 left-1/2 -translate-x-1/2 bg-shadowgrey text-[9px] text-purewhite px-1 py-0.5 rounded opacity-0 group-hover:opacity-100 transition-opacity">64%</span>
                                        </div>
                                        <div class="w-1/4 bg-tuscansun h-40 rounded-t relative group">
                                            <span class="absolute -top-6 left-1/2 -translate-x-1/2 bg-shadowgrey text-[9px] text-purewhite px-1 py-0.5 rounded opacity-0 group-hover:opacity-100 transition-opacity">92%</span>
                                        </div>
                                    </div>
                                    <div class="flex justify-around text-[9px] text-graphite font-mono pt-2 border-t border-dustgrey/60">
                                        <span>Before</span>
                                        <span>Stage 1</span>
                                        <span>Stage 2</span>
                                        <span>Final (SmartPLS)</span>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Right side: Analytical insights summary -->
                        <div class="md:col-span-5 space-y-4">
                            <h4 class="text-xs font-bold uppercase tracking-widest text-graphite">Key Analytics Contributions:</h4>
                            
                            <div class="space-y-4 text-xs">
                                <div class="p-3.5 bg-purewhite border border-dustgrey rounded shadow-sm">
                                    <h5 class="font-bold text-shadowgrey mb-1">MSME HR Resource Analytics</h5>
                                    <p class="text-graphite leading-relaxed">Processed multi-variable quantitative models using <strong>SPSS</strong> and structural equation modeling (SEM) with <strong>SmartPLS</strong> for Sidoarjo MSMEs, aiding published research pieces.</p>
                                </div>
                                <div class="p-3.5 bg-purewhite border border-dustgrey rounded shadow-sm">
                                    <h5 class="font-bold text-shadowgrey mb-1">BMT Sharia Risk Management Model</h5>
                                    <p class="text-graphite leading-relaxed">Developed validation matrices for operational risk assessment across localized Islamic cooperatives to boost productivity.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- CONTENT 2: ERD & PRD Explorer Module -->
                <div id="content-proj-sys" class="proj-content hidden p-6 md:p-8 space-y-8">
                    <div class="flex justify-between items-start flex-wrap gap-4 border-b border-dustgrey/60 pb-4">
                        <div>
                            <span class="bg-ivory text-shadowgrey text-[10px] font-bold uppercase px-2.5 py-1 rounded border border-dustgrey">Systems Architecture</span>
                            <h3 class="font-bold text-xl text-shadowgrey mt-1.5">Interactive ERD Diagram & PRD Specifications</h3>
                            <p class="text-xs text-graphite">Investigate the system design schemas and structured requirements designed for enterprise-level applications.</p>
                        </div>
                        <div class="flex gap-1.5 text-xs">
                            <button onclick="switchSysModule('mod-erd')" id="sys-btn-erd" class="px-3 py-1 bg-shadowgrey text-purewhite rounded">Entity Relationship (ERD)</button>
                            <button onclick="switchSysModule('mod-prd')" id="sys-btn-prd" class="px-3 py-1 bg-purewhite border border-dustgrey text-graphite hover:bg-ivory/30 rounded">Product Spec (PRD)</button>
                        </div>
                    </div>

                    <div class="min-h-[300px]">
                        <!-- Interactive ERD Viewer -->
                        <div id="sys-mod-erd" class="sys-module grid md:grid-cols-3 gap-6">
                            <!-- Left: Interactive Entity List -->
                            <div class="space-y-2">
                                <span class="text-[10px] font-bold uppercase tracking-wider text-graphite block">Click Entities to Inspect Attributes:</span>
                                <button onclick="inspectErdEntity('ent-users')" id="erd-ent-users" class="erd-ent-btn w-full p-3 bg-ivory text-shadowgrey border border-dustgrey rounded text-left font-medium text-xs flex justify-between items-center">
                                    <span>User Schema</span>
                                    <i class="fa-solid fa-angle-right text-[10px]"></i>
                                </button>
                                <button onclick="inspectErdEntity('ent-trans')" id="erd-ent-trans" class="erd-ent-btn w-full p-3 bg-purewhite hover:bg-ivory/20 border border-dustgrey text-graphite rounded text-left font-medium text-xs flex justify-between items-center">
                                    <span>Transaction Ledger Schema</span>
                                    <i class="fa-solid fa-angle-right text-[10px]"></i>
                                </button>
                                <button onclick="inspectErdEntity('ent-prod')" id="erd-ent-prod" class="erd-ent-btn w-full p-3 bg-purewhite hover:bg-ivory/20 border border-dustgrey text-graphite rounded text-left font-medium text-xs flex justify-between items-center">
                                    <span>Product Catalog Schema</span>
                                    <i class="fa-solid fa-angle-right text-[10px]"></i>
                                </button>
                            </div>

                            <!-- Right: The Database Attribute Map Display -->
                            <div class="md:col-span-2 bg-purewhite p-5 rounded-lg border border-dustgrey space-y-4">
                                <div id="erd-details-ent-users" class="erd-detail-box space-y-3">
                                    <div class="flex justify-between items-center border-b border-dustgrey pb-2">
                                        <span class="text-xs font-mono font-bold text-graphite">Table: USERS_DB (Primary Key: User_ID)</span>
                                        <span class="text-[9px] bg-tuscansun/20 text-graphite font-bold uppercase px-1.5 py-0.5 rounded border border-tuscansun">Primary Node</span>
                                    </div>
                                    <ul class="text-[11px] space-y-2 font-mono text-graphite">
                                        <li class="flex justify-between"><strong>User_ID (PK)</strong> <span class="text-shadowgrey font-semibold">VARCHAR (32)</span></li>
                                        <li class="flex justify-between"><strong>Full_Name</strong> <span class="text-graphite">VARCHAR (128)</span></li>
                                        <li class="flex justify-between"><strong>Email_Address</strong> <span class="text-graphite">VARCHAR (64)</span></li>
                                        <li class="flex justify-between"><strong>Account_Status</strong> <span class="text-graphite">ENUM ('Active', 'Suspended')</span></li>
                                        <li class="flex justify-between"><strong>Registration_Date</strong> <span class="text-graphite">TIMESTAMP</span></li>
                                    </ul>
                                </div>

                                <div id="erd-details-ent-trans" class="erd-detail-box hidden space-y-3">
                                    <div class="flex justify-between items-center border-b border-dustgrey pb-2">
                                        <span class="text-xs font-mono font-bold text-graphite">Table: TRANSACTION_LEDGER (PK: Ledger_ID, FK: User_ID)</span>
                                        <span class="text-[9px] bg-tuscansun/20 text-graphite font-bold uppercase px-1.5 py-0.5 rounded border border-tuscansun">Relational Node</span>
                                    </div>
                                    <ul class="text-[11px] space-y-2 font-mono text-graphite">
                                        <li class="flex justify-between"><strong>Ledger_ID (PK)</strong> <span class="text-shadowgrey font-semibold">VARCHAR (32)</span></li>
                                        <li class="flex justify-between"><strong>User_ID (FK)</strong> <span class="text-graphite">VARCHAR (32) (References USERS_DB)</span></li>
                                        <li class="flex justify-between"><strong>Transaction_Type</strong> <span class="text-graphite">ENUM ('Deposit', 'Trade', 'Withdrawal')</span></li>
                                        <li class="flex justify-between"><strong>Asset_Amount</strong> <span class="text-graphite">DECIMAL (18, 8)</span></li>
                                        <li class="flex justify-between"><strong>Ledger_Timestamp</strong> <span class="text-graphite">TIMESTAMP</span></li>
                                    </ul>
                                </div>

                                <div id="erd-details-ent-prod" class="erd-detail-box hidden space-y-3">
                                    <div class="flex justify-between items-center border-b border-dustgrey pb-2">
                                        <span class="text-xs font-mono font-bold text-graphite">Table: PRODUCT_CATALOG (PK: Product_ID)</span>
                                        <span class="text-[9px] bg-tuscansun/20 text-graphite font-bold uppercase px-1.5 py-0.5 rounded border border-tuscansun">Asset Node</span>
                                    </div>
                                    <ul class="text-[11px] space-y-2 font-mono text-graphite">
                                        <li class="flex justify-between"><strong>Product_ID (PK)</strong> <span class="text-shadowgrey font-semibold">VARCHAR (32)</span></li>
                                        <li class="flex justify-between"><strong>Product_Name</strong> <span class="text-graphite">VARCHAR (128)</span></li>
                                        <li class="flex justify-between"><strong>Associated_Risk_Tier</strong> <span class="text-graphite">ENUM ('Low', 'Moderate', 'High')</span></li>
                                        <li class="flex justify-between"><strong>Minimum_Subscription</strong> <span class="text-graphite">DECIMAL (12, 2)</span></li>
                                        <li class="flex justify-between"><strong>Catalog_Update_Date</strong> <span class="text-graphite">TIMESTAMP</span></li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <div id="sys-mod-prd" class="sys-module hidden space-y-4">
                            <div class="p-5 bg-purewhite rounded-lg border border-dustgrey space-y-4 text-xs leading-relaxed text-graphite shadow-sm">
                                <div class="flex justify-between items-center border-b border-dustgrey pb-2">
                                    <h4 class="font-serif font-bold text-sm text-shadowgrey">PRODUCT REQUIREMENT DOCUMENT (PRD) — ARTHAYANA PORTAL</h4>
                                    <span class="text-[9px] bg-ivory text-graphite font-bold px-2 py-0.5 rounded border border-dustgrey">Core Spec v1.4</span>
                                </div>
                                <div class="space-y-3">
                                    <div>
                                        <h5 class="font-bold text-shadowgrey uppercase text-[10px] tracking-wider mb-1">1. Product Objectives & Target Goals</h5>
                                        <p class="text-graphite font-medium">To construct an intuitive portal matching user needs for digital investment. Key metrics: 99.9% uptime, investor onboarding completing within 5 minutes, and robust data synchronization.</p>
                                    </div>
                                    <div>
                                        <h5 class="font-bold text-shadowgrey uppercase text-[10px] tracking-wider mb-1">2. Core Functional Requirements</h5>
                                        <ul class="list-disc pl-5 space-y-1 text-graphite font-medium">
                                            <li><strong>System Module onboarding:</strong> Automated investor assessment parsing through basic questionnaire algorithms.</li>
                                            <li><strong>Transaction interface:</strong> Clear feedback loops connecting API transaction calls with real-time portfolio dashboards.</li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section id="experience" class="py-20 max-w-6xl mx-auto px-6 border-b border-dustgrey/60">
        <div class="text-center max-w-2xl mx-auto space-y-2 mb-12">
            <span class="text-xs font-bold uppercase tracking-widest text-graphite">My Journey</span>
            <h2 class="font-serif text-2xl md:text-3xl font-bold text-shadowgrey">Professional & Leadership Path</h2>
            <p class="text-xs md:text-sm text-graphite">An active timeline representing academic excellence, digital consulting engagements, and organization direction.</p>
        </div>

        <div class="grid md:grid-cols-12 gap-8 items-start">
            <!-- Sidebar experience timeline selectors -->
            <div class="md:col-span-4 flex flex-col gap-2">
                <button onclick="switchExpTab('exp-cmc')" id="tab-btn-exp-cmc" class="exp-tab-btn flex items-center gap-3 p-4 rounded-xl text-left font-medium transition-all duration-300 bg-ivory text-shadowgrey border border-dustgrey">
                    <div class="w-2 h-2 rounded-full bg-tuscansun"></div>
                    <div>
                        <span class="block text-xs uppercase tracking-wider text-graphite font-bold">Executive Office</span>
                        Capital Market Community
                    </div>
                </button>
                <button onclick="switchExpTab('exp-liaison')" id="tab-btn-exp-liaison" class="exp-tab-btn flex items-center gap-3 p-4 rounded-xl text-left font-medium transition-all duration-300 hover:bg-ivory/50 text-graphite border border-transparent">
                    <div class="w-2 h-2 rounded-full bg-dustgrey"></div>
                    <div>
                        <span class="block text-xs uppercase tracking-wider text-graphite font-bold">International Exposure</span>
                        Summer Course & Exchange
                    </div>
                </button>
                <button onclick="switchExpTab('exp-acad')" id="tab-btn-exp-acad" class="exp-tab-btn flex items-center gap-3 p-4 rounded-xl text-left font-medium transition-all duration-300 hover:bg-ivory/50 text-graphite border border-transparent">
                    <div class="w-2 h-2 rounded-full bg-dustgrey"></div>
                    <div>
                        <span class="block text-xs uppercase tracking-wider text-graphite font-bold">Academic Support</span>
                        Lecturer & S3 Research
                    </div>
                </button>
            </div>

            <!-- Experience detailed content blocks -->
            <div class="md:col-span-8 bg-purewhite p-6 md:p-8 rounded-xl border border-dustgrey custom-shadow min-h-[420px]">
                
                <!-- Timeline 1: CMC -->
                <div id="content-exp-cmc" class="exp-content space-y-6">
                    <div class="flex justify-between items-start flex-wrap gap-4">
                        <div>
                            <span class="bg-ivory text-graphite text-[10px] font-bold tracking-widest uppercase px-2 py-1 rounded border border-dustgrey">Executive Leadership</span>
                            <h3 class="font-bold text-xl text-shadowgrey mt-1">Vice President Director</h3>
                            <p class="text-xs text-graphite font-semibold">Capital Market Community FEB UNESA</p>
                        </div>
                        <span class="text-xs text-graphite font-semibold bg-ivory border border-dustgrey px-3 py-1 rounded-full">Dec 2025 - Present</span>
                    </div>
                    <p class="text-xs text-graphite leading-relaxed font-medium">
                        Led strategic and operational initiatives for a <strong>200+ member</strong> capital market organization, implementing KPI tracking and data-driven decision frameworks.
                    </p>
                    <div class="space-y-3">
                        <h4 class="text-[10px] font-bold text-shadowgrey uppercase tracking-widest border-b border-dustgrey/60 pb-1">Historical Engagements:</h4>
                        <ul class="text-xs text-graphite font-medium space-y-2.5">
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-circle-check"></i></span>
                                <div><strong>Secretary I (Jan - Nov 2025):</strong> Managed operations for 9 national-scale events engaging <strong>2,000+ participants</strong>. Improved administrative efficiency through document digitization and standardization.</div>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-circle-check"></i></span>
                                <div><strong>Liaisons & Collaborations:</strong> Worked directly with regulatory and institutional partners, including the <strong>Indonesia Stock Exchange (IDX)</strong>, <strong>OJK (Otoritas Jasa Keuangan)</strong>, and brokerage corporations like <strong>Sucor Sekuritas</strong>.</div>
                            </li>
                        </ul>
                    </div>
                </div>

                <!-- Timeline 2: Liaison -->
                <div id="content-exp-liaison" class="exp-content hidden space-y-6">
                    <div class="flex justify-between items-start flex-wrap gap-4">
                        <div>
                            <span class="bg-ivory text-graphite text-[10px] font-bold tracking-widest uppercase px-2 py-1 rounded border border-dustgrey">International Exposure</span>
                            <h3 class="font-bold text-xl text-shadowgrey mt-1">Liaison Officer</h3>
                            <p class="text-xs text-graphite font-semibold">UNESA Summer Course 2026</p>
                        </div>
                        <span class="text-xs text-graphite font-semibold bg-ivory border border-dustgrey px-3 py-1 rounded-full">Feb 2026</span>
                    </div>
                    <p class="text-xs text-graphite leading-relaxed font-medium">
                        Coordinated communications, participant support pipelines, and critical on-site logistical arrangements during an offline academic exchange program for <strong>54 international participants</strong>.
                    </p>
                    <div class="space-y-3">
                        <h4 class="text-[10px] font-bold text-shadowgrey uppercase tracking-widest border-b border-dustgrey/60 pb-1">Strategic Cross-Border Initiatives:</h4>
                        <ul class="text-xs text-graphite font-medium space-y-2.5">
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-circle-check"></i></span>
                                <div><strong>ICONBIT Student Coordinator (2025):</strong> Oversaw coordination of 148 global paper presenters across 12 countries (including Japan, Spain, and India), linking with over 500+ attendees.</div>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-circle-check"></i></span>
                                <div><strong>Customer Service Internship (August 2025):</strong> Assisted clients with portfolio inquiries at Sucor Sekuritas, managing onboarding flows for 150+ client accounts with zero system errors.</div>
                            </li>
                        </ul>
                    </div>
                </div>

                <!-- Timeline 3: Academic & Research -->
                <div id="content-exp-acad" class="exp-content hidden space-y-6">
                    <div class="flex justify-between items-start flex-wrap gap-4">
                        <div>
                            <span class="bg-ivory text-graphite text-[10px] font-bold tracking-widest uppercase px-2 py-1 rounded border border-dustgrey">Academic Support</span>
                            <h3 class="font-bold text-xl text-shadowgrey mt-1">Assistant Lecturer & Research Analyst</h3>
                            <p class="text-xs text-graphite font-semibold">Undergraduate Digital Business Program, UNESA</p>
                        </div>
                        <span class="text-xs text-graphite font-semibold bg-ivory border border-dustgrey px-3 py-1 rounded-full">Oct 2024 - Present</span>
                    </div>
                    <p class="text-xs text-graphite leading-relaxed font-medium">
                        Currently assisting in lecture setups while actively involved in the <strong>LAMEMBA Re-Accreditation process</strong> of the Digital Business program and contributing to <strong>2 published research papers</strong>.
                    </p>
                    <div class="space-y-3">
                        <h4 class="text-[10px] font-bold text-shadowgrey uppercase tracking-widest border-b border-dustgrey/60 pb-1">Quantitative Contributions:</h4>
                        <ul class="text-xs text-graphite font-medium space-y-2.5">
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-circle-check"></i></span>
                                <div><strong>Doctoral (S3) Research Assistance:</strong> Executed advanced statistical models (SPSS, SmartPLS) to support doctoral articles on MSME resource competitiveness and sharia business risk structures in Sidoarjo.</div>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-tuscansun mt-0.5"><i class="fa-solid fa-circle-check"></i></span>
                                <div><strong>Global summer cohort (UGM):</strong> Selected as 1 of 9 UNESA delegates to study innovative sustainable models alongside global peers during the UGM Global Summer Week 2025, winning the *Best Group Presentation* award.</div>
                            </li>
                        </ul>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <section id="credentials" class="py-16 max-w-6xl mx-auto px-6">
        <div class="grid md:grid-cols-12 gap-12">
            
            <!-- Left Grid: Formal Accolades & Awards -->
            <div class="md:col-span-6 space-y-8">
                <div>
                    <span class="text-xs font-bold uppercase tracking-widest text-graphite">Honorable Honors</span>
                    <h2 class="font-serif text-2xl font-bold text-shadowgrey">Selected Achievements</h2>
                    <p class="text-xs text-graphite mt-1">Academically verified awards and national contest milestones.</p>
                </div>

                <div class="space-y-4">
                    <!-- Accolade 1 -->
                    <div class="flex items-start gap-4 p-4 rounded-lg border border-dustgrey bg-purewhite custom-shadow">
                        <div class="w-10 h-10 rounded bg-ivory flex items-center justify-center text-tuscansun text-lg">
                            <i class="fa-solid fa-trophy"></i>
                        </div>
                        <div>
                            <span class="text-[9px] uppercase font-bold text-graphite tracking-widest">International Start-Up</span>
                            <h4 class="font-bold text-xs text-shadowgrey mt-0.5">3rd Place Winner - DIGCOFEST</h4>
                            <p class="text-[11px] text-graphite mt-1">Universitas Negeri Surabaya (2025) — Awarded for the <strong>Arthayana</strong> Startup concept.</p>
                        </div>
                    </div>

                    <!-- Accolade 2 -->
                    <div class="flex items-start gap-4 p-4 rounded-lg border border-dustgrey bg-purewhite custom-shadow">
                        <div class="w-10 h-10 rounded bg-ivory flex items-center justify-center text-tuscansun text-lg">
                            <i class="fa-solid fa-medal"></i>
                        </div>
                        <div>
                            <span class="text-[9px] uppercase font-bold text-graphite tracking-widest">Global Academic Program</span>
                            <h4 class="font-bold text-xs text-shadowgrey mt-0.5">Best Group Presentation Award</h4>
                            <p class="text-[11px] text-graphite mt-1">UGM Global Summer Week (2025) — Study on sustainable business frameworks.</p>
                        </div>
                    </div>

                    <!-- Accolade 3 -->
                    <div class="flex items-start gap-4 p-4 rounded-lg border border-dustgrey bg-purewhite custom-shadow">
                        <div class="w-10 h-10 rounded bg-ivory flex items-center justify-center text-tuscansun text-lg">
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <div>
                            <span class="text-[9px] uppercase font-bold text-graphite tracking-widest">National Case Contest</span>
                            <h4 class="font-bold text-xs text-shadowgrey mt-0.5">Finalist - Impactify BMC Competition</h4>
                            <p class="text-[11px] text-graphite mt-1">Telkom University (2026) — Validated strategic Business Model Canvas framework.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="md:col-span-6 space-y-8">
                <div>
                    <span class="text-xs font-bold uppercase tracking-widest text-graphite">Training Wall</span>
                    <h2 class="font-serif text-2xl font-bold text-shadowgrey">Certifications & Training</h2>
                    <p class="text-xs text-graphite mt-1">Micro-credentials and specialized analytical bootcamps completed.</p>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <!-- Certification 1 -->
                    <div class="p-4 rounded-lg border border-dustgrey bg-purewhite custom-shadow flex flex-col justify-between h-32 hover:border-tuscansun transition-colors">
                        <span class="text-[9px] text-graphite font-bold uppercase tracking-widest">Western Sydney University</span>
                        <div>
                            <h4 class="font-bold text-xs text-shadowgrey">AI & Innovation Side Hustle</h4>
                            <span class="text-[10px] text-graphite mt-1 block font-mono">Credential • 2025</span>
                        </div>
                    </div>

                    <!-- Certification 2 -->
                    <div class="p-4 rounded-lg border border-dustgrey bg-purewhite custom-shadow flex flex-col justify-between h-32 hover:border-tuscansun transition-colors">
                        <span class="text-[9px] text-graphite font-bold uppercase tracking-widest">Litera Chamber Academia</span>
                        <div>
                            <h4 class="font-bold text-xs text-shadowgrey">SmartPLS SEM-PLS Training</h4>
                            <span class="text-[10px] text-graphite mt-1 block font-mono">Credential • 2025</span>
                        </div>
                    </div>

                    <!-- Certification 3 -->
                    <div class="p-4 rounded-lg border border-dustgrey bg-purewhite custom-shadow flex flex-col justify-between h-32 hover:border-tuscansun transition-colors">
                        <span class="text-[9px] text-graphite font-bold uppercase tracking-widest">PT Educativa Cipta</span>
                        <div>
                            <h4 class="font-bold text-xs text-shadowgrey">Data Analysis (SPSS)</h4>
                            <span class="text-[10px] text-graphite mt-1 block font-mono">Credential • 2025</span>
                        </div>
                    </div>

                    <!-- Certification 4 -->
                    <div class="p-4 rounded-lg border border-dustgrey bg-purewhite custom-shadow flex flex-col justify-between h-32 hover:border-tuscansun transition-colors">
                        <span class="text-[9px] text-graphite font-bold uppercase tracking-widest">PT Pegadaian (Persero)</span>
                        <div>
                            <h4 class="font-bold text-xs text-shadowgrey">Corporate Financial Literacy</h4>
                            <span class="text-[10px] text-graphite mt-1 block font-mono">Credential • 2024</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="bg-shadowgrey text-purewhite py-16 border-t border-dustgrey/40">
        <div class="max-w-4xl mx-auto px-6 text-center space-y-8">
            <div class="space-y-2">
                <span class="text-xs font-bold uppercase tracking-widest text-tuscansun">Direct Contact</span>
                <h2 class="font-serif text-3xl font-bold tracking-tight text-purewhite">Let's Construct Something Impactful</h2>
                <p class="text-xs text-ivory/80 max-w-md mx-auto leading-relaxed">
                    I am open for information systems consulting opportunities, research partnerships, and cross-functional corporate collaborations.
                </p>
            </div>

            <!-- Operational channels -->
            <div class="flex flex-wrap justify-center gap-4 text-xs font-bold uppercase tracking-widest">
                <a href="mailto:shafira.pramatya05@gmail.com" class="bg-tuscansun hover:bg-tuscansun/90 text-shadowgrey px-5 py-3 rounded transition-colors duration-300">
                    <i class="fa-solid fa-envelope mr-1.5"></i> Email Me
                </a>
                <a href="tel:+6285228833779" class="border border-dustgrey hover:bg-purewhite/10 text-purewhite px-5 py-3 rounded transition-colors duration-300">
                    <i class="fa-solid fa-phone mr-1.5"></i> Call Direct
                </a>
                <a href="https://linkedin.com" target="_blank" class="border border-dustgrey hover:bg-purewhite/10 text-purewhite px-5 py-3 rounded transition-colors duration-300">
                    <i class="fa-brands fa-linkedin mr-1.5"></i> LinkedIn
                </a>
            </div>

            <!-- Color Palette Swatch Tribute -->
            <div class="pt-8 border-t border-purewhite/10 flex flex-wrap justify-center items-center gap-4 text-[10px] text-ivory uppercase tracking-widest">
                <span>Palette Swatches:</span>
                <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded bg-dustgrey inline-block border border-purewhite/20"></span> ~Dust Grey</span>
                <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded bg-ivory inline-block border border-purewhite/20"></span> ~Ivory</span>
                <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded bg-tuscansun inline-block border border-purewhite/20"></span> ~Tuscan Sun</span>
                <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded bg-shadowgrey inline-block border border-purewhite/20"></span> ~Shadow Grey</span>
                <span class="flex items-center gap-1"><span class="w-2.5 h-2.5 rounded bg-graphite inline-block border border-purewhite/20"></span> ~Graphite</span>
            </div>

            <p class="text-[10px] text-ivory/60 uppercase tracking-widest pt-4">
                &copy; 2026 Shafira Pramatya. Elegant Warm Portfolio. All rights reserved.
            </p>
        </div>
    </footer>

    <script>
        // Toggle photos in the Arthayana Documentation Gallery
        function toggleArthayanaPic(picIndex) {
            const pic1 = document.getElementById('arthayana-img-1');
            const pic2 = document.getElementById('arthayana-img-2');
            const btn1 = document.getElementById('btn-pic-1');
            const btn2 = document.getElementById('btn-pic-2');

            if (picIndex === 1) {
                pic1.classList.remove('opacity-0');
                pic2.classList.add('opacity-0');
                btn1.className = "w-3 h-3 rounded-full bg-tuscansun border border-tuscansun transition-colors";
                btn2.className = "w-3 h-3 rounded-full bg-dustgrey border border-dustgrey hover:bg-tuscansun/50 transition-colors";
            } else {
                pic1.classList.add('opacity-0');
                pic2.classList.remove('opacity-0');
                btn1.className = "w-3 h-3 rounded-full bg-dustgrey border border-dustgrey hover:bg-tuscansun/50 transition-colors";
                btn2.className = "w-3 h-3 rounded-full bg-tuscansun border border-tuscansun transition-colors";
            }
        }

        // Switch tabs inside Project Deliverables Hub
        function switchProjTab(tabId) {
            // Hide all project content boxes
            document.querySelectorAll('.proj-content').forEach(content => {
                content.classList.add('hidden');
            });
            // Show selected content box
            document.getElementById('content-' + tabId).classList.remove('hidden');

            // Reset tab button styles using the custom dustgrey and tuscansun scheme
            document.querySelectorAll('.proj-tab-btn').forEach(btn => {
                btn.className = "proj-tab-btn px-4 py-2 border border-dustgrey bg-purewhite text-graphite hover:bg-ivory/30 rounded-md transition-all";
            });
            // Apply active button style configurations
            document.getElementById('tab-btn-' + tabId).className = "proj-tab-btn px-4 py-2 bg-tuscansun text-shadowgrey rounded shadow-sm transition-all font-semibold";
        }

        // Switch modules inside ERD/PRD sub-explorer
        function switchSysModule(modId) {
            // Hide all sub-modules
            document.querySelectorAll('.sys-module').forEach(module => {
                module.classList.add('hidden');
            });
            // Show selected sub-module
            document.getElementById('sys-' + modId).classList.remove('hidden');

            // Reset tab selectors
            document.getElementById('sys-btn-erd').className = "px-3 py-1 bg-purewhite border border-dustgrey text-graphite hover:bg-ivory/30 rounded";
            document.getElementById('sys-btn-prd').className = "px-3 py-1 bg-purewhite border border-dustgrey text-graphite hover:bg-ivory/30 rounded";

            // Apply style configuration to active module trigger
            if (modId === 'mod-erd') {
                document.getElementById('sys-btn-erd').className = "px-3 py-1 bg-shadowgrey text-purewhite rounded";
            } else {
                document.getElementById('sys-btn-prd').className = "px-3 py-1 bg-shadowgrey text-purewhite rounded";
            }
        }

        // Inspect specific table entity inside ERD schema viewer
        function inspectErdEntity(entityId) {
            // Hide all detail sheets
            document.querySelectorAll('.erd-detail-box').forEach(box => {
                box.classList.add('hidden');
            });
            // Show target table details
            document.getElementById('erd-details-' + entityId).classList.remove('hidden');

            // Reset button active styles
            document.querySelectorAll('.erd-ent-btn').forEach(btn => {
                btn.className = "erd-ent-btn w-full p-3 bg-purewhite hover:bg-ivory/20 border border-dustgrey text-graphite rounded text-left font-medium text-xs flex justify-between items-center";
            });
            // Apply style to active entity button
            document.getElementById('erd-' + entityId).className = "erd-ent-btn w-full p-3 bg-ivory text-shadowgrey border border-dustgrey rounded text-left font-medium text-xs flex justify-between items-center";
        }

        // Switch experience timeline tabs
        function switchExpTab(tabId) {
            // Hide all experience content details
            document.querySelectorAll('.exp-content').forEach(content => {
                content.classList.add('hidden');
            });
            // Show selected experience detail
            document.getElementById('content-' + tabId).classList.remove('hidden');

            // Reset tab list selection styles
            document.querySelectorAll('.exp-tab-btn').forEach(btn => {
                btn.className = "exp-tab-btn flex items-center gap-3 p-4 rounded-xl text-left font-medium transition-all duration-300 hover:bg-ivory/50 text-graphite border border-transparent";
                const dot = btn.querySelector('div');
                if (dot) {
                    dot.className = "w-2 h-2 rounded-full bg-dustgrey";
                }
            });

            // Set active timeline selector style
            const activeBtn = document.getElementById('tab-btn-' + tabId);
            activeBtn.className = "exp-tab-btn flex items-center gap-3 p-4 rounded-xl text-left font-medium transition-all duration-300 bg-ivory text-shadowgrey border border-dustgrey";
            const activeDot = activeBtn.querySelector('div');
            if (activeDot) {
                activeDot.className = "w-2 h-2 rounded-full bg-tuscansun";
            }
        }
    </script>
</body>
</html>
