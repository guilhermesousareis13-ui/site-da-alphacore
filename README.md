<!DOCTYPE html>
<!-- O lang será atualizado dinamicamente por JS -->
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- O Título e a Descrição serão atualizados dinamicamente -->
    <title>Alpha Core Marketing | Tecnologia - Soluções Digitais</title>
    <meta name="description" content="Transformamos Tecnologia em Resultados Reais. Marketing Digital, SEO e Sites de Alta Performance para empresas no Brasil, Portugal e EUA.">
    <meta name="keywords" content="Marketing Digital, SEO, Tráfego Pago, Sites, Tecnologia, Alpha Core">
    
    <!-- Melhoria 12: Meta Theme Color -->
    <meta name="theme-color" content="#00FF88">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://alphacore.tech/">
    <meta property="og:title" content="Alpha Core Marketing | Tecnologia - Soluções Digitais">
    <meta property="og:description" content="Transformamos Tecnologia em Resultados Reais. Marketing Digital, SEO e Sites de Alta Performance.">
    <meta property="og:image" content="https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png">

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://alphacore.tech/">
    <meta property="twitter:title" content="Alpha Core Marketing | Tecnologia - Soluções Digitais">
    <meta property="twitter:description" content="Transformamos Tecnologia em Resultados Reais. Marketing Digital, SEO e Sites de Alta Performance.">
    <meta property="twitter:image" content="https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png">

    <!-- Favicon (Alteração 6 da v2) -->
    <link rel="icon" type="image/png" href="https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png">
    <link rel="apple-touch-icon" href="https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png">
    
    <!-- Google Fonts: Poppins -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Melhoria 3: Pré-carregamento de Fontes -->
    <link rel="preload" as="font" type="font/woff2" href="https://fonts.gstatic.com/s/poppins/v20/pxiByp8kv8JHgFVrLBT5Z1xlFQ.woff2" crossorigin>
    <link rel="preload" as="font" type="font/woff2" href="https://fonts.gstatic.com/s/poppins/v20/pxiByp8kv8JHgFVrLCz7Z1xlFQ.woff2" crossorigin>

    <!-- Melhoria 9: Hreflang e Canonical Dinâmicos (Atualizado para Hash) -->
    <link id="lang-canonical" rel="canonical" href="https://alphacore.tech/pt/">
    <link id="lang-alt-pt" rel="alternate" href="https://alphacore.tech/pt/" hreflang="pt-br">
    <link id="lang-alt-en" rel="alternate" href="https://alphacore.tech/en/" hreflang="en">
    <link id="lang-alt-xdefault" rel="alternate" href="https://alphacore.tech/pt/" hreflang="x-default">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Schema.org -->
    <script type="application/ld+json" id="schema-organization">{ "@context": "https://schema.org", "@type": "Organization", "name": "Alpha Core Marketing | Tecnologia", "url": "https://alphacore.tech/", "logo": "https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png", "contactPoint": { "@type": "ContactPoint", "telephone": "+55-19-99847-7323", "contactType": "customer service", "areaServed": ["BR", "PT", "US"], "availableLanguage": ["pt-BR", "en"] }, "sameAs": [ "https://instagram.com/alpha_corebr" ] }</script>
    <script type="application/ld+json" id="schema-service">{ "@context": "https://schema.org", "@type": "Service", "serviceType": "Marketing Digital", "provider": { "@type": "Organization", "name": "Alpha Core Marketing | Tecnologia" }, "areaServed": ["BR", "PT", "US"], "description": "Serviços de SEO, Tráfego Pago e Desenvolvimento Web." }</script>
    <script type="application/ld+json" id="schema-localbusiness">{ "@context": "https://schema.org", "@type": "LocalBusiness", "name": "Alpha Core Marketing | Tecnologia", "image": "https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png", "url": "https://alphacore.tech", "telephone": "+55-19-99847-7323", "address": { "@type": "PostalAddress", "addressLocality": "Artur Nogueira", "addressRegion": "SP", "addressCountry": "BR" }, "sameAs": [ "https://instagram.com/alpha_corebr" ] }</script>
    
    <!-- 
    ==============================================
    Bloco de CSS Interno
    ==============================================
    -->
    <style>
        /* --- CSS --- */
        
        :root {
            --neon-green: #00FF88;
            --bg-black: #0B0B0B;
            --bg-gray: #121212;
            --text-white: #FFFFFF;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--bg-black);
            color: var(--text-white);
            overflow-x: hidden;
            
            /* Melhoria 3: Cursor Neon */
            /* Esconde o cursor padrão */
            cursor: none; 
        }

        /* ==============================================
        MELHORIA: Cursor Neon Personalizado
        ==============================================
        */
        .cursor-dot, .cursor-outline {
            position: fixed;
            top: 0;
            left: 0;
            transform: translate(-50%, -50%);
            border-radius: 50%;
            z-index: 99999;
            pointer-events: none;
            transition: opacity 0.3s, transform 0.3s, width 0.3s, height 0.3s;
        }
        .cursor-dot {
            width: 8px;
            height: 8px;
            background-color: var(--neon-green);
            box-shadow: 0 0 5px var(--neon-green);
            transition: transform 0.1s; /* Ponto mais rápido */
        }
        .cursor-outline {
            width: 30px;
            height: 30px;
            border: 2px solid rgba(0,255,136,0.5);
            transition: width 0.2s, height 0.2s, transform 0.2s; /* Outline mais suave */
        }
        
        /* Efeito hover do cursor */
        body.cursor-hover .cursor-dot {
            opacity: 0.5;
            transform: translate(-50%, -50%) scale(0.5);
        }
        body.cursor-hover .cursor-outline {
            width: 45px;
            height: 45px;
            border-width: 3px;
            background-color: rgba(0,255,136,0.05);
            transform: translate(-50%, -50%) scale(1.1);
        }
        
        /* Esconder em mobile */
        @media (max-width: 768px) {
            .cursor-dot, .cursor-outline {
                display: none;
            }
            body {
                cursor: auto; /* Restaura cursor padrão */
            }
        }
        /* Fim do Cursor Neon */
        
        
        /* Configuração de Cores Tailwind */
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'neon-green': 'var(--neon-green)',
                        'bg-black': 'var(--bg-black)',
                        'bg-gray': 'var(--bg-gray)',
                    }
                }
            }
        }
        
        /* Efeitos de Brilho (Glow) */
        .text-neon {
            color: var(--neon-green);
            text-shadow: 0 0 5px rgba(0,255,136,0.7), 0 0 10px rgba(0,255,136,0.5);
        }
        
        .shadow-neon {
            box-shadow: 0 0 15px rgba(0,255,136,0.3), 0 0 25px rgba(0,255,136,0.2);
        }

        .shadow-neon-hover:hover {
            box-shadow: 0 0 20px rgba(0,255,136,0.4), 0 0 30px rgba(0,255,136,0.3);
        }

        .border-neon-hover:hover {
            border-color: var(--neon-green);
        }
        
        /* Botões */
        .btn-primary {
            @apply bg-neon-green text-black font-bold py-3 px-8 rounded-lg transition-all duration-300 transform;
        }
        .btn-primary:hover {
            @apply bg-white shadow-neon transform -translate-y-1;
        }
        
        .btn-secondary {
            @apply border border-neon-green text-neon-green font-bold py-3 px-8 rounded-lg transition-all duration-300;
        }
        .btn-secondary:hover {
            @apply bg-neon-green text-black shadow-neon;
        }
        
        /* Navegação */
        .nav-link.active {
            color: var(--neon-green);
            text-shadow: 0 0 5px rgba(0,255,136,0.7);
        }
        
        /* Controle das "Páginas" */
        .page-section {
            display: none;
        }
        .page-section.active {
            display: block;
            /* Animação de fade geral */
            animation: fadeInPage 0.6s ease-in-out;
        }
        @keyframes fadeInPage {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        /* Animação de entrada (Scroll) */
        /*
        ==============================================
        MELHORIA: Animações Staggered
        ==============================================
        */
        .fade-in-section, .service-card, .portfolio-card {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }
        .fade-in-section.is-visible, 
        .service-card.is-visible,
        .portfolio-card.is-visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Botão flutuante WhatsApp */
        .whatsapp-float {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(37, 211, 102, 0.7); }
            70% { transform: scale(1.1); box-shadow: 0 0 0 15px rgba(37, 211, 102, 0); }
            100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(37, 211, 102, 0); }
        }

        /* Fundo do Hero (Parallax) */
        .hero-bg {
            position: relative;
            overflow: hidden;
            background-image: url('https://images.pexels.com/photos/5716042/pexels-photo-5716042.jpeg');
            background-size: cover;
            background-position: center center;
            background-attachment: fixed; /* Efeito Parallax */
        }
        .hero-bg::before { content: ''; position: absolute; inset: 0; background-color: rgba(0, 0, 0, 0.65); z-index: 0; }
        .hero-bg::after { content: ''; position: absolute; inset: 0; background: radial-gradient(circle at 50% 50%, rgba(0,255,136,0.1), transparent 60%); animation: pulseGlow 6s ease-in-out infinite; z-index: 0; }
        .hero-content { position: relative; z-index: 1; }
        @keyframes pulseGlow { 0%, 100% { opacity: 0.5; transform: scale(0.9); } 50% { opacity: 1; transform: scale(1.1); } }

        /* Fundo do Sobre (Branco) */
        #page-sobre { background-color: var(--text-white); color: var(--bg-black); }
        
        /* Seção de autoridade */
        .autoridade .text-neon-green { color: var(--neon-green); text-shadow: 0 0 5px rgba(0,255,136,0.7); }

        /* Barra de Progresso do Scroll */
        #progress-bar { position: fixed; top: 0; left: 0; height: 4px; background: var(--neon-green); box-shadow: 0 0 10px var(--neon-green), 0 0 5px var(--neon-green); width: 0%; z-index: 9999; transition: width 0.1s linear; }
        
        /* Seletor de Idioma Visível */
        #lang-pt.active, #lang-en.active, #lang-pt-mobile.active, #lang-en-mobile.active { background-color: var(--bg-black); box-shadow: 0 0 10px rgba(0,255,136,0.3); opacity: 1; }
        #lang-pt.inactive, #lang-en.inactive, #lang-pt-mobile.inactive, #lang-en-mobile.inactive { opacity: 0.6; background-color: transparent; }
        
        /* ==============================================
        MELHORIA: Modals (Portfólio & Exit-Intent)
        ==============================================
        */
        .modal-overlay {
            position: fixed;
            inset: 0;
            background-color: rgba(0, 0, 0, 0.8);
            backdrop-filter: blur(10px);
            z-index: 9990;
            opacity: 0;
            transition: opacity 0.3s ease-in-out;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .modal-overlay.active { opacity: 1; }
        
        .modal-content {
            background-color: var(--bg-gray);
            border: 1px solid var(--neon-green);
            box-shadow: 0 0 30px rgba(0,255,136,0.3);
            border-radius: 0.75rem;
            padding: 2rem;
            width: 90%;
            max-width: 600px;
            max-height: 90vh;
            overflow-y: auto;
            position: relative;
            transform: scale(0.9) translateY(20px);
            opacity: 0;
            transition: all 0.3s ease-out 0.1s;
        }
        .modal-overlay.active .modal-content {
            transform: scale(1) translateY(0);
            opacity: 1;
        }
        
        .modal-close-btn {
            position: absolute;
            top: 1rem;
            right: 1rem;
            color: var(--text-white);
            transition: all 0.3s;
        }
        .modal-close-btn:hover {
            color: var(--neon-green);
            transform: rotate(90deg);
        }

        /* ==============================================
        MELHORIA: PWA Update Toast
        ==============================================
        */
        #update-toast {
            position: fixed;
            bottom: -100px; /* Começa escondido */
            left: 50%;
            transform: translateX(-50%);
            background-color: var(--bg-gray);
            color: var(--text-white);
            padding: 1rem 1.5rem;
            border-radius: 0.5rem;
            border: 1px solid var(--neon-green);
            box-shadow: 0 0 20px rgba(0,255,136,0.3);
            z-index: 9998;
            display: flex;
            align-items: center;
            gap: 1rem;
            transition: bottom 0.5s ease-in-out;
        }
        #update-toast.show {
            bottom: 2rem; /* Posição visível */
        }
        #update-toast-btn {
            @apply bg-neon-green text-black font-semibold py-1 px-3 rounded-md text-sm;
        }

        /* ==============================================
        MELHORIA: Acessibilidade (Reduced Motion)
        ==============================================
        */
        @media (prefers-reduced-motion: reduce) {
            html {
                scroll-behavior: auto; /* Remove scroll suave */
            }
            body {
                transition: none; /* Remove fade de página */
            }
            /* Desliga todas as transições e animações */
            *, *::before, *::after {
                animation-duration: 1ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 1ms !important;
                transition-delay: 0s !important;
            }
            
            /* Desliga animações específicas */
            .whatsapp-float, .hero-bg::after, .page-section.active, .cursor-dot, .cursor-outline {
                animation: none;
                transition: none;
            }
            
            /* Remove transformações de animação */
            .fade-in-section, .service-card, .portfolio-card {
                opacity: 1;
                transform: none;
            }
        }
        
        /* Otimização Mobile */
        @media (max-width: 400px) {
            .whatsapp-float { bottom: 80px; }
            #page-home h1 { font-size: 2.5rem; }
            .page-section h1 { font-size: 2.25rem; }
        }
    </style>
</head>
<body class="bg-bg-black">
    
    <!-- Melhoria 7: Barra de Progresso do Scroll -->
    <div id="progress-bar"></div>

    <!-- Melhoria 3: Cursor Neon -->
    <div class="cursor-dot"></div>
    <div class="cursor-outline"></div>

    <!-- ===== HEADER ===== -->
    <header class="sticky top-0 z-50 w-full bg-bg-black/80 backdrop-blur-md border-b border-bg-gray shadow-lg">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <!-- Logo -->
            <a href="#home" class="nav-link" data-page="home">
                <img src="https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png" alt="Alpha Core Logo" class="h-10 md:h-12 w-auto transition-transform duration-300 hover:scale-105">
            </a>
            
            <!-- Links Desktop -->
            <div class="hidden md:flex items-center space-x-6">
                <a href="#home" class="nav-link text-white hover:text-neon-green transition-colors duration-300 font-medium" data-page="home" data-lang="nav.home"></a>
                <a href="#servicos" class="nav-link text-white hover:text-neon-green transition-colors duration-300 font-medium" data-page="servicos" data-lang="nav.services"></a>
                <a href="#sobre" class="nav-link text-white hover:text-neon-green transition-colors duration-300 font-medium" data-page="sobre" data-lang="nav.about"></a>
                <a href="#portfolio" class="nav-link text-white hover:text-neon-green transition-colors duration-300 font-medium" data-page="portfolio" data-lang="nav.portfolio"></a>
                <a href="#contato" class="nav-link text-white hover:text-neon-green transition-colors duration-300 font-medium" data-page="contato" data-lang="nav.contact"></a>
            </div>
            
            <!-- Seletor de Idioma e CTA Desktop -->
            <div class="hidden md:flex items-center space-x-4">
                <div class="flex items-center gap-1.5 rounded-lg bg-bg-gray p-1.5 border border-gray-700">
                    <button id="lang-pt" class="px-2 py-1 rounded-md transition-all duration-300" title="Mudar para Português" aria-label="Mudar para Português">
                        <span class="text-xl">🇧🇷</span>
                    </button>
                    <button id="lang-en" class="px-2 py-1 rounded-md transition-all duration-300" title="Switch to English" aria-label="Switch to English">
                        <span class="text-xl">🇺🇸</span>
                    </button>
                </div>
                <a href="#contato" class="btn-primary text-sm py-2 px-5 nav-link" data-page="contato" data-lang="nav.cta" data-source="header_cta"></a>
            </div>
            
            <!-- Botão Mobile Menu -->
            <div class="md:hidden flex items-center">
                <button id="mobile-menu-button" class="text-white focus:outline-none" aria-label="Abrir menu mobile">
                    <svg class="w-7 h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                    </svg>
                </button>
            </div>
        </nav>
        
        <!-- Mobile Menu (Oculto) -->
        <div id="mobile-menu" class="hidden md:hidden bg-bg-gray pb-4">
            <a href="#home" class="nav-link block text-white text-center py-2 px-4 hover:bg-bg-black" data-page="home" data-lang="nav.home"></a>
            <a href="#servicos" class="nav-link block text-white text-center py-2 px-4 hover:bg-bg-black" data-page="servicos" data-lang="nav.services"></a>
            <a href="#sobre" class="nav-link block text-white text-center py-2 px-4 hover:bg-bg-black" data-page="sobre" data-lang="nav.about"></a>
            <a href="#portfolio" class="nav-link block text-white text-center py-2 px-4 hover:bg-bg-black" data-page="portfolio" data-lang="nav.portfolio"></a>
            <a href="#contato" class="nav-link block text-white text-center py-2 px-4 hover:bg-bg-black" data-page="contato" data-lang="nav.contact"></a>
            
            <!-- Seletor de Idioma Mobile -->
            <div class="flex justify-center items-center gap-2 mt-4 rounded-lg bg-bg-black p-1.5 border border-gray-700 mx-4">
                 <button id="lang-pt-mobile" class="flex-1 px-2 py-1 rounded-md transition-all duration-300" title="Mudar para Português" aria-label="Mudar para Português">
                    <span class="text-xl font-medium">🇧🇷 PT</span>
                </button>
                <button id="lang-en-mobile" class="flex-1 px-2 py-1 rounded-md transition-all duration-300" title="Switch to English" aria-label="Switch to English">
                    <span class="text-xl font-medium">🇺🇸 EN</span>
                </button>
            </div>
            
            <div class="mt-4 px-4">
                 <a href="#contato" class="btn-primary w-full text-center nav-link" data-page="contato" data-lang="nav.cta" data-source="mobile_menu_cta"></a>
            </div>
        </div>
    </header>

    <!-- ===== MAIN CONTENT ===== -->
    <main>
        
        <!-- ===== PÁGINA: INÍCIO (HOME) ===== -->
        <section id="page-home" class="page-section">
            
            <!-- Hero Section -->
            <div class="hero-bg min-h-screen flex items-center justify-center pt-16 pb-20">
                <div class="hero-content container mx-auto px-6 text-center">
                    <h1 class="text-4xl md:text-6xl lg:text-7xl font-extrabold text-white leading-tight mb-6">
                        <span data-lang="home.headline_1"></span>
                        <span class="text-neon" data-lang="home.headline_2"></span>
                        <span data-lang="home.headline_3"></span>
                    </h1>
                    <p class="text-lg md:text-xl text-gray-200 max-w-3xl mx-auto mb-8" data-lang="home.subheadline"></p>
                    <p class="text-sm text-gray-300 max-w-2xl mx-auto mb-10" data-lang="home.authority_line"></p>

                    <div class="flex flex-col sm:flex-row justify-center gap-4">
                        <a href="https://wa.me/5519998477323?text=Olá%20Alpha%20Core!%20Quero%20uma%20análise%20gratuita" target="_blank" class="btn-primary" data-lang="home.cta_whatsapp" data-source="hero_cta_whatsapp"></a>
                        <a href="#contato" class="btn-secondary nav-link" data-page="contato" data-lang="home.cta_consult" data-source="hero_cta_form"></a>
                    </div>
                </div>
            </div>
            
            <!-- Clientes Section -->
            <div class="py-16 bg-bg-gray">
                <div class="container mx-auto px-6 text-center">
                    <h3 class="text-sm font-semibold text-gray-400 uppercase tracking-wider" data-lang="home.clients_title"></h3>
                    <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 mt-8 opacity-70">
                        <span class="text-2xl font-bold">🇧🇷 BRASIL</span>
                        <span class="text-2xl font-bold">🇵🇹 PORTUGAL</span>
                        <span class="text-2xl font-bold">🇺🇸 EUA</span>
                    </div>
                </div>
            </div>
            
            <!-- Destaque Serviços Section -->
            <div class="py-24 bg-bg-black">
                <div class="container mx-auto px-6">
                    <div class="text-center max-w-3xl mx-auto mb-16 fade-in-section">
                        <h2 class="text-3xl md:text-4xl font-bold mb-4" data-lang="home.services_title"></h2>
                        <p class="text-gray-300 text-lg" data-lang="home.services_subtitle"></p>
                    </div>
                    
                    <!-- MELHORIA: Staggered Group -->
                    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 staggered-group">
                        <!-- Card 1: Sites -->
                        <div class="service-card bg-bg-gray p-8 rounded-xl border border-transparent transition-all duration-300 border-neon-hover shadow-neon-hover transform hover:-translate-y-2">
                            <svg class="w-12 h-12 text-neon-green mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                            <h3 class="text-2xl font-bold mb-3" data-lang="services.item1_title"></h3>
                            <p class="text-gray-300 mb-5" data-lang="services.item1_desc_short"></p>
                            <a href="#servicos" class="nav-link font-semibold text-neon-green hover:underline" data-page="servicos" data-lang="common.learn_more"></a>
                        </div>
                        
                        <!-- Card 2: SEO -->
                        <div class="service-card bg-bg-gray p-8 rounded-xl border border-transparent transition-all duration-300 border-neon-hover shadow-neon-hover transform hover:-translate-y-2">
                            <svg class="w-12 h-12 text-neon-green mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                            <h3 class="text-2xl font-bold mb-3" data-lang="services.item2_title"></h3>
                            <p class="text-gray-300 mb-5" data-lang="services.item2_desc_short"></p>
                            <a href="#servicos" class="nav-link font-semibold text-neon-green hover:underline" data-page="servicos" data-lang="common.learn_more"></a>
                        </div>

                        <!-- Card 3: Tráfego Pago -->
                        <div class="service-card bg-bg-gray p-8 rounded-xl border border-transparent transition-all duration-300 border-neon-hover shadow-neon-hover transform hover:-translate-y-2">
                            <svg class="w-12 h-12 text-neon-green mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"></path></svg>
                            <h3 class="text-2xl font-bold mb-3" data-lang="services.item3_title"></h3>
                            <p class="text-gray-300 mb-5" data-lang="services.item3_desc_short"></p>
                            <a href="#servicos" class="nav-link font-semibold text-neon-green hover:underline" data-page="servicos" data-lang="common.learn_more"></a>
                        </div>

                        <!-- Card 4: Redes Sociais -->
                        <div class="service-card bg-bg-gray p-8 rounded-xl border border-transparent transition-all duration-300 border-neon-hover shadow-neon-hover transform hover:-translate-y-2">
                            <svg class="w-12 h-12 text-neon-green mb-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a2 2 0 01-2-2V4a2 2 0 012-2h8a2 2 0 012 2v4z"></path></svg>
                            <h3 class="text-2xl font-bold mb-3" data-lang="services.item4_title"></h3>
                            <p class="text-gray-300 mb-5" data-lang="services.item4_desc_short"></p>
                            <a href="#servicos" class="nav-link font-semibold text-neon-green hover:underline" data-page="servicos" data-lang="common.learn_more"></a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- ===== PÁGINA: SERVIÇOS (SERVICES) ===== -->
        <section id="page-servicos" class="page-section pt-24 pb-20">
            <div class="container mx-auto px-6">
                <div class="text-center max-w-3xl mx-auto mb-16 fade-in-section">
                    <h1 class="text-4xl md:text-5xl font-extrabold mb-4" data-lang="services.page_title"></h1>
                    <p class="text-lg text-gray-300" data-lang="services.page_subtitle"></p>
                </div>
                
                <!-- Lista de Serviços Detalhados -->
                <div class="space-y-16">
                    
                    <!-- Serviço 1: Sites -->
                    <div class="fade-in-section grid md:grid-cols-2 gap-12 items-center">
                        <div>
                            <span class="text-sm font-bold text-neon-green uppercase" data-lang="services.item1_tag"></span>
                            <h2 class="text-3xl font-bold my-3" data-lang="services.item1_title"></h2>
                            <p class="text-gray-300 mb-6" data-lang="services.item1_desc_long"></p>
                            <ul class="space-y-2 text-gray-200">
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item1_feat1"></span></li>
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item1_feat2"></span></li>
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item1_feat3"></span></li>
                            </ul>
                        </div>
                        <div>
                            <img src="https://i.postimg.cc/4KPBPv9W/unnamed.jpg" alt="Sites e Lojas Virtuais" class="w-full h-auto rounded-xl object-cover border border-gray-800 shadow-neon" loading="lazy">
                        </div>
                    </div>
                    
                    <!-- Serviço 2: SEO -->
                    <div class="fade-in-section grid md:grid-cols-2 gap-12 items-center">
                        <div class="md:order-2">
                            <span class="text-sm font-bold text-neon-green uppercase" data-lang="services.item2_tag"></span>
                            <h2 class="text-3xl font-bold my-3" data-lang="services.item2_title"></h2>
                            <p class="text-gray-300 mb-6" data-lang="services.item2_desc_long"></p>
                            <ul class="space-y-2 text-gray-200">
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item2_feat1"></span></li>
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item2_feat2"></span></li>
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item2_feat3"></span></li>
                            </ul>
                        </div>
                        <div class="md:order-1">
                             <img src="https://i.postimg.cc/hJsps8dL/unnamed-1.jpg" alt="SEO & Performance no Google" class="w-full h-auto rounded-xl object-cover border border-gray-800 shadow-neon" loading="lazy">
                        </div>
                    </div>
                    
                    <!-- Serviço 3: Tráfego Pago -->
                    <div class="fade-in-section grid md:grid-cols-2 gap-12 items-center">
                        <div>
                            <span class="text-sm font-bold text-neon-green uppercase" data-lang="services.item3_tag"></span>
                            <h2 class="text-3xl font-bold my-3" data-lang="services.item3_title"></h2>
                            <p class="text-gray-300 mb-6" data-lang="services.item3_desc_long"></p>
                            <ul class="space-y-2 text-gray-200">
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item3_feat1"></span></li>
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item3_feat2"></span></li>
                                <li class="flex items-center"><span class="text-neon-green mr-2">✓</span> <span data-lang="services.item3_feat3"></span></li>
                            </ul>
                        </div>
                        <div>
                             <img src="https://i.postimg.cc/GBKqKPy5/unnamed-2.jpg" alt="Tráfego Pago (Google & Meta Ads)" class="w-full h-auto rounded-xl object-cover border border-gray-800 shadow-neon" loading="lazy">
                        </div>
                    </div>
                    
                </div>

                <!-- CTA Section -->
                <div class="fade-in-section text-center bg-bg-gray mt-24 py-16 px-6 rounded-xl border border-neon-green shadow-neon">
                    <h2 class="text-3xl font-bold mb-4" data-lang="services.cta_title"></h2>
                    <p class="text-lg text-gray-300 max-w-2xl mx-auto mb-8" data-lang="services.cta_subtitle"></p>
                    <a href="#contato" class="btn-primary nav-link" data-page="contato" data-lang="services.cta_button" data-source="servicos_cta"></a>
                </div>
            </div>
        </section>
        
        <!-- ===== PÁGINA: SOBRE (ABOUT) ===== -->
        <section id="page-sobre" class="page-section pt-24 pb-20">
            <div class="container mx-auto px-6">
                <div class="grid lg:grid-cols-2 gap-16 items-center">
                    <!-- Conteúdo de Texto -->
                    <div class="fade-in-section">
                        <span class="text-sm font-bold text-neon-green uppercase" data-lang="about.tag"></span>
                        <h1 class="text-4xl md:text-5xl font-extrabold my-4" data-lang="about.title"></h1>
                        <p class="text-lg text-gray-700 mb-6" data-lang="about.p1"></p>
                        <p class="text-lg text-gray-700 mb-8" data-lang="about.p2"></p>
                        
                        <div class="grid grid-cols-2 gap-6">
                            <div class="border-l-4 border-neon-green pl-4">
                                <span class="text-3xl font-bold block" data-lang="about.stat1_num"></span>
                                <span class="text-gray-600" data-lang="about.stat1_desc"></span>
                            </div>
                            <div class="border-l-4 border-neon-green pl-4">
                                <span class="text-3xl font-bold block" data-lang="about.stat2_num"></span>
                                <span class="text-gray-600" data-lang="about.stat2_desc"></span>
                            </div>
                            <div class="border-l-4 border-neon-green pl-4">
                                <span class="text-3xl font-bold block" data-lang="about.stat3_num"></span>
                                <span class="text-gray-600" data-lang="about.stat3_desc"></span>
                            </div>
                            <div class="border-l-4 border-neon-green pl-4">
                                <span class="text-3xl font-bold block" data-lang="about.stat4_num"></span>
                                <span class="text-gray-600" data-lang="about.stat4_desc"></span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Imagem -->
                    <div class="fade-in-section">
                        <img src="https://placehold.co/600x700/0B0B0B/00FF88?text=Alpha+Core+Team" alt="Equipe Alpha Core" class="w-full h-auto rounded-xl object-cover shadow-2xl" loading="lazy">
                    </div>
                </div>
            </div>
        </section>
        
        <!-- ===== PÁGINA: PORTFÓLIO (PORTFOLIO) ===== -->
        <section id="page-portfolio" class="page-section pt-24 pb-20">
            <div class="container mx-auto px-6">
                <div class="text-center max-w-3xl mx-auto mb-16 fade-in-section">
                    <h1 class="text-4xl md:text-5xl font-extrabold mb-4" data-lang="portfolio.title"></h1>
                    <p class="text-lg text-gray-300" data-lang="portfolio.subtitle"></p>
                </div>

                <!-- Seção de Autoridade com Imagem -->
                <section class="autoridade bg-bg-gray text-white py-12 md:py-16 px-6 rounded-xl shadow-lg text-center md:text-left mb-16 lg:mb-20 fade-in-section">
                    <div class="grid md:grid-cols-2 gap-8 items-center max-w-5xl mx-auto">
                        <div class="flex justify-center md:justify-end">
                            <img src="https://i.postimg.cc/fb5cTvN9/unnamed-6-removebg-preview.png" alt="Mais de 500 clientes no Brasil, EUA e Portugal" class="max-w-xs md:max-w-sm w-full h-auto" loading="lazy">
                        </div>
                        <h2 class="text-2xl md:text-3xl font-bold" data-lang="portfolio.authority_text_1"></h2>
                    </div>
                </section>

                <!-- 
                ==============================================
                MELHORIA: Galeria de Projetos com Modal
                ==============================================
                -->
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 staggered-group">
                    <!-- Projeto 1: Fintech -->
                    <div class="portfolio-card group relative rounded-xl overflow-hidden bg-bg-gray border border-gray-800 shadow-neon-hover transition-all duration-300 cursor-pointer" data-project-id="p1">
                        <img src="https://i.postimg.cc/Sjbt4G62/unnamed.jpg" alt="Fintech" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" loading="lazy">
                        <div class="absolute inset-0 bg-black/70 flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div>
                                <span class="text-sm font-bold text-neon-green" data-lang="portfolio.p1_cat"></span>
                                <h3 class="text-2xl font-bold text-white" data-lang="portfolio.p1_title"></h3>
                                <p class="text-gray-200" data-lang="portfolio.p1_desc"></p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Projeto 2: E-commerce -->
                    <div class="portfolio-card group relative rounded-xl overflow-hidden bg-bg-gray border border-gray-800 shadow-neon-hover transition-all duration-300 cursor-pointer" data-project-id="p2">
                        <img src="https://i.postimg.cc/H8tM1mQ6/unnamed-1.jpg" alt="E-commerce (Sites e Lojas Virtuais)" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" loading="lazy">
                         <div class="absolute inset-0 bg-black/70 flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div>
                                <span class="text-sm font-bold text-neon-green" data-lang="portfolio.p2_cat"></span>
                                <h3 class="text-2xl font-bold text-white" data-lang="portfolio.p2_title"></h3>
                                <p class="text-gray-200" data-lang="portfolio.p2_desc"></p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Projeto 3: Tráfego Pago -->
                    <div class="portfolio-card group relative rounded-xl overflow-hidden bg-bg-gray border border-gray-800 shadow-neon-hover transition-all duration-300 cursor-pointer" data-project-id="p3">
                        <img src="https://i.postimg.cc/vxvnwyrF/unnamed-2.jpg" alt="Tráfego Pago" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" loading="lazy">
                         <div class="absolute inset-0 bg-black/70 flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div>
                                <span class="text-sm font-bold text-neon-green" data-lang="portfolio.p3_cat"></span>
                                <h3 class="text-2xl font-bold text-white" data-lang="portfolio.p3_title"></h3>
                                <p class="text-gray-200" data-lang="portfolio.p3_desc"></p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Projeto 4: Real Estate -->
                    <div class="portfolio-card group relative rounded-xl overflow-hidden bg-bg-gray border border-gray-800 shadow-neon-hover transition-all duration-300 cursor-pointer" data-project-id="p4">
                        <img src="https://i.postimg.cc/9wB9H2Gv/unnamed-3.jpg" alt="Real Estate" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" loading="lazy">
                         <div class="absolute inset-0 bg-black/70 flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div>
                                <span class="text-sm font-bold text-neon-green" data-lang="portfolio.p4_cat"></span>
                                <h3 class="text-2xl font-bold text-white" data-lang="portfolio.p4_title"></h3>
                                <p class="text-gray-200" data-lang="portfolio.p4_desc"></p>
                            </div>
                        </div>
                    </div>
                    <!-- Projeto 5: EdTech -->
                    <div class="portfolio-card group relative rounded-xl overflow-hidden bg-bg-gray border border-gray-800 shadow-neon-hover transition-all duration-300 cursor-pointer" data-project-id="p5">
                        <img src="https://i.postimg.cc/7JNzr43v/unnamed-4.jpg" alt="EdTech" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" loading="lazy">
                         <div class="absolute inset-0 bg-black/70 flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div>
                                <span class="text-sm font-bold text-neon-green" data-lang="portfolio.p5_cat"></span>
                                <h3 class="text-2xl font-bold text-white" data-lang="portfolio.p5_title"></h3>
                                <p class="text-gray-200" data-lang="portfolio.p5_desc"></p>
                            </div>
                        </div>
                    </div>
                    <!-- Projeto 6: Saúde -->
                    <div class="portfolio-card group relative rounded-xl overflow-hidden bg-bg-gray border border-gray-800 shadow-neon-hover transition-all duration-300 cursor-pointer" data-project-id="p6">
                        <img src="https://i.postimg.cc/vxvnwyrd/unnamed-5.jpg" alt="Saúde" class="w-full h-64 object-cover transition-transform duration-500 group-hover:scale-110" loading="lazy">
                         <div class="absolute inset-0 bg-black/70 flex items-end p-6 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div>
                                <span class="text-sm font-bold text-neon-green" data-lang="portfolio.p6_cat"></span>
                                <h3 class="text-2xl font-bold text-white" data-lang="portfolio.p6_title"></h3>
                                <p class="text-gray-200" data-lang="portfolio.p6_desc"></p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- CTA -->
                <div class="fade-in-section text-center mt-20">
                    <h3 class="text-3xl font-bold" data-lang="portfolio.cta_title"></h3>
                    <a href="#contato" class="btn-primary mt-6 nav-link" data-page="contato" data-lang="portfolio.cta_button" data-source="portfolio_cta"></a>
                </div>
            </div>
        </section>
        
        <!-- ===== PÁGINA: CONTATO (CONTACT) ===== -->
        <section id="page-contato" class="page-section pt-24 pb-20">
            <div class="container mx-auto px-6">
                <div class="text-center max-w-3xl mx-auto mb-16 fade-in-section">
                    <h1 class="text-4xl md:text-5xl font-extrabold mb-4" data-lang="contact.title"></h1>
                    <p class="text-lg text-gray-300" data-lang="contact.subtitle"></p>
                </div>
                
                <div class="grid lg:grid-cols-3 gap-12 bg-bg-gray p-8 md:p-12 rounded-xl border border-gray-800 shadow-neon">
                    
                    <!-- 
                    ==============================================
                    MELHORIA: Formulário Netlify com AJAX e Tracking
                    ==============================================
                    -->
                    <form name="contact" id="contact-form" class="lg:col-span-2 space-y-6 fade-in-section" netlify>
                        <!-- Campo oculto para Netlify -->
                        <input type="hidden" name="form-name" value="contact" />
                        <!-- Campo oculto para rastreio de Lead Source -->
                        <input type="hidden" name="lead_source" id="lead_source_field" value="direct">
                        
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-300" data-lang="contact.form_name"></label>
                            <input type="text" name="name" id="name" required class="mt-1 block w-full bg-bg-black border border-gray-700 rounded-md shadow-sm py-3 px-4 text-white focus:border-neon-green focus:ring-neon-green">
                        </div>
                        <div>
                            <label for="company" class="block text-sm font-medium text-gray-300" data-lang="contact.form_company"></label>
                            <input type="text" name="company" id="company" class="mt-1 block w-full bg-bg-black border border-gray-700 rounded-md shadow-sm py-3 px-4 text-white focus:border-neon-green focus:ring-neon-green">
                        </div>
                        <div class="grid sm:grid-cols-2 gap-6">
                            <div>
                                <label for="email" class="block text-sm font-medium text-gray-300" data-lang="contact.form_email"></label>
                                <input type="email" name="email" id="email" required class="mt-1 block w-full bg-bg-black border border-gray-700 rounded-md shadow-sm py-3 px-4 text-white focus:border-neon-green focus:ring-neon-green">
                            </div>
                            <div>
                                <label for="whatsapp" class="block text-sm font-medium text-gray-300" data-lang="contact.form_whatsapp"></label>
                                <input type="tel" name="whatsapp" id="whatsapp" required class="mt-1 block w-full bg-bg-black border border-gray-700 rounded-md shadow-sm py-3 px-4 text-white focus:border-neon-green focus:ring-neon-green">
                            </div>
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-300" data-lang="contact.form_message"></label>
                            <textarea id="message" name="message" rows="5" required class="mt-1 block w-full bg-bg-black border border-gray-700 rounded-md shadow-sm py-3 px-4 text-white focus:border-neon-green focus:ring-neon-green"></textarea>
                        </div>
                        <div>
                            <button type="submit" id="form-submit-btn" class="btn-primary w-full" data-lang="contact.form_submit"></button>
                        </div>
                    </form>
                    
                    <!-- Informações de Contato -->
                    <div class="fade-in-section">
                        <h3 class="text-2xl font-bold mb-6" data-lang="contact.info_title"></h3>
                        <div class="space-y-6">
                            <!-- E-mail -->
                            <div class="flex items-start space-x-4">
                                <svg class="w-6 h-6 text-neon-green mt-1 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                                <div>
                                    <h4 class="text-lg font-semibold" data-lang="contact.info_email_title"></h4>
                                    <a href="mailto:alphacoreofc@gmail.com" class="text-gray-300 hover:text-neon-green transition-colors">alphacoreofc@gmail.com</a>
                                </div>
                            </div>
                            <!-- WhatsApp -->
                            <div class="flex items-start space-x-4">
                                <svg class="w-6 h-6 text-neon-green mt-1 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M19.001 4.999c-4.418 0-8 3.582-8 8 0 1.439.385 2.785 1.057 3.965l-1.057 4.037 4.143-1.036c1.15.645 2.459 1.034 3.857 1.034 4.418 0 8-3.582 8-8s-3.582-8-8-8zm0 14.5c-1.164 0-2.268-.313-3.205-.855l-.229-.136-2.394.598.608-2.336-.148-.237c-.579-1.025-.932-2.196-.932-3.468 0-3.584 2.916-6.5 6.5-6.5s6.5 2.916 6.5 6.5-2.916 6.5-6.5 6.5zm-3.197-4.101c-.173-.086-.96-.474-1.108-.528-.148-.054-.255-.086-.363.086-.108.173-.418.528-.513.636-.095.108-.19.12-.363.042-.173-.086-.729-.266-1.388-.855-.513-.474-.86-.843-.96-.987-.108-.148-.012-.23.074-.316.074-.074.173-.19.255-.282.086-.086.108-.148.173-.255.054-.108.027-.19 0-.282-.027-.086-.363-.86-.49-1.176-.12-.316-.255-.27-.363-.27-.108 0-.229-.012-.363-.012s-.336.042-.513.229c-.173.173-.662.645-.662 1.572 0 .927.689 1.812.797 1.947.108.148 1.334 2.039 3.231 2.859.45.19.8.303 1.08.389.474.136.905.12.122.074.389-.012 1.201-.49 1.374-.951.173-.46.173-.86.12-.951-.054-.086-.173-.148-.363-.229z"></path></svg>
                                <div>
                                    <h4 class="text-lg font-semibold" data-lang="contact.info_whatsapp_title"></h4>
                                    <a href="https://wa.me/5519998477323?text=Olá%20Alpha%20Core!%20Quero%20uma%20análise%20gratuita" target="_blank" class="text-gray-300 hover:text-neon-green transition-colors">+55 (19) 99847-7323</a>
                                </div>
                            </div>
                            <!-- Instagram -->
                            <div class="flex items-start space-x-4">
                                <svg class="w-6 h-6 text-neon-green mt-1 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12.9V19a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h6.1a1 1 0 00.7-.3l1.1-1.4a1 1 0 011.4 0l1.1 1.4a1 1 0 00.7.3H19a2 2 0 012 2v.9"></path></svg>
                                <div>
                                    <h4 class="text-lg font-semibold" data-lang="contact.info_social_title"></h4>
                                    <a href="https://instagram.com/alpha_corebr" target="_blank" class="text-gray-300 hover:text-neon-green transition-colors">@alpha_corebr</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- 
        ==============================================
        MELHORIA: Página de "Obrigado" (para AJAX)
        ==============================================
        -->
        <section id="page-obrigado" class="page-section pt-32 pb-40">
            <div class="container mx-auto px-6 text-center">
                <div class="max-w-2xl mx-auto">
                    <svg class="w-20 h-20 text-neon-green mx-auto mb-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    <h1 class="text-4xl md:text-5xl font-extrabold mb-4" data-lang="obrigado.title"></h1>
                    <p class="text-lg text-gray-300 mb-8" data-lang="obrigado.subtitle"></p>
                    <a href="#home" class="btn-primary nav-link" data-page="home" data-lang="obrigado.button"></a>
                </div>
            </div>
        </section>

    </main>

    <!-- ===== FOOTER ===== -->
    <footer class="bg-bg-black border-t border-bg-gray mt-20 pt-16 pb-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-3 lg:grid-cols-4 gap-12">
                <!-- Col 1: Logo e Social -->
                <div class="md:col-span-1 lg:col-span-2">
                    <img src="https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png" alt="Alpha Core Logo" class="h-10 w-auto mb-4" loading="lazy">
                    <p class="text-gray-400 max-w-sm mb-6" data-lang="footer.desc"></p>
                    <div class="flex space-x-5">
                        <a href="https://wa.me/5519998477323?text=Olá%20Alpha%20Core!%20Quero%20uma%20análise%20gratuita" target="_blank" class="text-gray-400 hover:text-neon-green transition-colors" title="WhatsApp" aria-label="Abrir WhatsApp">
                            <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M19.001 4.999c-4.418 0-8 3.582-8 8 0 1.439.385 2.785 1.057 3.965l-1.057 4.037 4.143-1.036c1.15.645 2.459 1.034 3.857 1.034 4.418 0 8-3.582 8-8s-3.582-8-8-8zm0 14.5c-1.164 0-2.268-.313-3.205-.855l-.229-.136-2.394.598.608-2.336-.148-.237c-.579-1.025-.932-2.196-.932-3.468 0-3.584 2.916-6.5 6.5-6.5s6.5 2.916 6.5 6.5-2.916 6.5-6.5 6.5zm-3.197-4.101c-.173-.086-.96-.474-1.108-.528-.148-.054-.255-.086-.363.086-.108.173-.418.528-.513.636-.095.108-.19.12-.363.042-.173-.086-.729-.266-1.388-.855-.513-.474-.86-.843-.96-.987-.108-.148-.012-.23.074-.316.074-.074.173-.19.255-.282.086-.086.108-.148.173-.255.054-.108.027-.19 0-.282-.027-.086-.363-.86-.49-1.176-.12-.316-.255-.27-.363-.27-.108 0-.229-.012-.363-.012s-.336.042-.513.229c-.173.173-.662.645-.662 1.572 0 .927.689 1.812.797 1.947.108.148 1.334 2.039 3.231 2.859.45.19.8.303 1.08.389.474.136.905.12.122.074.389-.012 1.201-.49 1.374-.951.173-.46.173-.86.12-.951-.054-.086-.173-.148-.363-.229z"></path></svg>
                        </a>
                        <a href="https://instagram.com/alpha_corebr" target="_blank" class="text-gray-400 hover:text-neon-green transition-colors" title="Instagram" aria-label="Abrir Instagram">
                             <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12.9V19a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h6.1a1 1 0 00.7-.3l1.1-1.4a1 1 0 011.4 0l1.1 1.4a1 1 0 00.7.3H19a2 2 0 012 2v.9"></path></svg>
                        </a>
                        <a href="mailto:alphacoreofc@gmail.com" class="text-gray-400 hover:text-neon-green transition-colors" title="E-mail" aria-label="Enviar E-mail">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </a>
                    </div>
                </div>
                
                <!-- Col 2: Links Rápidos -->
                <div>
                    <h4 class="text-lg font-semibold text-white mb-4" data-lang="footer.links_title"></h4>
                    <ul class="space-y-3">
                        <li><a href="#home" class="nav-link text-gray-400 hover:text-neon-green transition-colors" data-page="home" data-lang="nav.home"></a></li>
                        <li><a href="#servicos" class="nav-link text-gray-400 hover:text-neon-green transition-colors" data-page="servicos" data-lang="nav.services"></a></li>
                        <li><a href="#sobre" class="nav-link text-gray-400 hover:text-neon-green transition-colors" data-page="sobre" data-lang="nav.about"></a></li>
                        <li><a href="#portfolio" class="nav-link text-gray-400 hover:text-neon-green transition-colors" data-page="portfolio" data-lang="nav.portfolio"></a></li>
                        <li><a href="#contato" class="nav-link text-gray-400 hover:text-neon-green transition-colors" data-page="contato" data-lang="nav.contact"></a></li>
                    </ul>
                </div>
                
                <!-- Col 3: Contato -->
                <div>
                    <h4 class="text-lg font-semibold text-white mb-4" data-lang="footer.contact_title"></h4>
                    <ul class="space-y-3 text-gray-400">
                        <li data-lang="footer.contact_loc1"></li>
                        <li data-lang="footer.contact_loc2"></li>
                        <li data-lang="footer.contact_loc3"></li>
                        <li class="pt-2"><a href="mailto:alphacoreofc@gmail.com" class="hover:text-neon-green">alphacoreofc@gmail.com</a></li>
                    </ul>
                </div>
            </div>
            
            <!-- Linha Copyright -->
            <div class="mt-12 pt-8 border-t border-gray-800 text-center text-gray-500">
                <p data-lang="footer.copyright"></p>
            </div>
        </div>
    </footer>
    
    <!-- ===== Botão Flutuante WhatsApp ===== -->
    <a href="https://wa.me/5519998477323?text=Olá%20Alpha%20Core!%20Quero%20uma%20análise%20gratuita" 
       target="_blank" 
       class="whatsapp-float fixed bottom-6 right-6 bg-green-500 rounded-full p-4 text-white shadow-lg z-40 transition-transform hover:scale-110"
       title="Falar com um especialista no WhatsApp"
       data-source="whatsapp_float_cta">
        <svg class="w-8 h-8" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"><path d="M19.001 4.999c-4.418 0-8 3.582-8 8 0 1.439.385 2.785 1.057 3.965l-1.057 4.037 4.143-1.036c1.15.645 2.459 1.034 3.857 1.034 4.418 0 8-3.582 8-8s-3.582-8-8-8zm0 14.5c-1.164 0-2.268-.313-3.205-.855l-.229-.136-2.394.598.608-2.336-.148-.237c-.579-1.025-.932-2.196-.932-3.468 0-3.584 2.916-6.5 6.5-6.5s6.5 2.916 6.5 6.5-2.916 6.5-6.5 6.5zm-3.197-4.101c-.173-.086-.96-.474-1.108-.528-.148-.054-.255-.086-.363.086-.108.173-.418.528-.513.636-.095.108-.19.12-.363.042-.173-.086-.729-.266-1.388-.855-.513-.474-.86-.843-.96-.987-.108-.148-.012-.23.074-.316.074-.074.173-.19.255-.282.086-.086.108-.148.173-.255.054-.108.027-.19 0-.282-.027-.086-.363-.86-.49-1.176-.12-.316-.255-.27-.363-.27-.108 0-.229-.012-.363-.012s-.336.042-.513.229c-.173.173-.662.645-.662 1.572 0 .927.689 1.812.797 1.947.108.148 1.334 2.039 3.231 2.859.45.19.8.303 1.08.389.474.136.905.12.122.074.389-.012 1.201-.49 1.374-.951.173-.46.173-.86.12-.951-.054-.086-.173-.148-.363-.229z"></path></svg>
    </a>

    <!-- 
    ==============================================
    MELHORIA: Templates de Modal
    ==============================================
    -->
    
    <!-- Modal: Portfólio Case Study -->
    <div id="portfolio-modal" class="modal-overlay hidden" aria-modal="true" role="dialog">
        <div class="modal-content">
            <!-- Conteúdo injetado por JS -->
            <img id="modal-img" src="" alt="Case Study" class="w-full h-48 object-cover rounded-lg mb-6" loading="lazy">
            <h2 id="modal-title" class="text-3xl font-bold mb-4"></h2>
            
            <h3 class="text-xl font-semibold text-neon-green mb-2" data-lang="modals.portfolio.challenge"></h3>
            <p id="modal-challenge" class="text-gray-300 mb-4"></p>
            
            <h3 class="text-xl font-semibold text-neon-green mb-2" data-lang="modals.portfolio.solution"></h3>
            <p id="modal-solution" class="text-gray-300 mb-4"></p>
            
            <h3 class="text-xl font-semibold text-neon-green mb-2" data-lang="modals.portfolio.results"></h3>
            <p id="modal-results" class="text-gray-300 mb-6"></p>

            <a href="#contato" id="modal-cta" class="btn-primary w-full text-center nav-link" data-page="contato" data-lang="portfolio.cta_button"></a>
            
            <button id="modal-close-btn" class="modal-close-btn" aria-label="Fechar modal">
                <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            </button>
        </div>
    </div>
    
    <!-- Modal: Exit-Intent -->
    <div id="exit-intent-modal" class="modal-overlay hidden" aria-modal="true" role="dialog">
         <div class="modal-content text-center max-w-lg">
            <h2 class="text-3xl font-bold mb-4" data-lang="modals.exit.title"></h2>
            <p class="text-lg text-gray-300 mb-8" data-lang="modals.exit.subtitle"></p>
            <a href="#contato" id="exit-modal-cta" class="btn-primary w-full text-center nav-link" data-page="contato" data-lang="modals.exit.button"></a>
            
            <button id="exit-modal-close-btn" class="modal-close-btn" aria-label="Fechar modal">
                <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            </button>
        </div>
    </div>
    
    <!-- 
    ==============================================
    MELHORIA: PWA Update Toast Template
    ==============================================
    -->
    <div id="update-toast">
        <span data-lang="modals.update.title"></span>
        <button id="update-toast-btn" data-lang="modals.update.button"></button>
    </div>


    <!-- 
    ==============================================
    Bloco de JAVASCRIPT Interno
    ==============================================
    -->
    <script>
        // --- JAVASCRIPT ---
        
        // Objeto de dados para internacionalização (i18n)
        const textData = {
            
            // --- PT VERSION ---
            'pt': {
                meta: {
                    title: 'Alpha Core Marketing | Tecnologia - Soluções Digitais',
                    description: 'Transformamos Tecnologia em Resultados Reais. Marketing Digital, SEO e Sites de Alta Performance para empresas no Brasil, Portugal e EUA.'
                },
                nav: {
                    home: 'Início',
                    services: 'Serviços',
                    about: 'Sobre',
                    portfolio: 'Portfólio',
                    contact: 'Contato',
                    cta: 'Agendar Consultoria'
                },
                home: {
                    headline_1: 'Transformamos',
                    headline_2: 'Tecnologia',
                    headline_3: 'em Resultados Reais.',
                    subheadline: 'Marketing Digital, SEO e Sites de Alta Performance. A Alpha Core é sua parceira estratégica para crescer no Brasil, Portugal e EUA.',
                    cta_whatsapp: 'Falar com um Especialista',
                    cta_consult: 'Quero minha análise gratuita',
                    authority_line: 'Mais de 500 empresas impulsionadas em 3 países com performance digital comprovada.',
                    clients_title: '+500 CLIENTES SATISFEITOS NO',
                    services_title: 'Nossas Soluções Core',
                    services_subtitle: 'Do design ao código, do clique à conversão. Entregamos performance digital ponta a ponta.'
                },
                common: {
                    learn_more: 'Saber Mais'
                },
                services: {
                    page_title: 'Nossos Serviços de Performance',
                    page_subtitle: 'Soluções integradas de tecnologia e marketing para escalar seu negócio digitalmente.',
                    item1_tag: 'Desenvolvimento Web',
                    item1_title: 'Sites e Lojas Virtuais',
                    item1_desc_short: 'Criamos plataformas web ultra-rápidas, responsivas e focadas em conversão.',
                    item1_desc_long: 'Do institucional ao e-commerce complexo, projetamos e codificamos experiências digitais que não são apenas bonitas, mas funcionam. Focamos em performance (Core Web Vitals), responsividade total e jornadas de usuário que convertem visitantes em clientes.',
                    item1_feat1: 'Plataformas WordPress & Shopify',
                    item1_feat2: 'Otimização de Velocidade (LCP/FID)',
                    item1_feat3: 'Design UX/UI Focado em Conversão',
                    item2_tag: 'Google',
                    item2_title: 'SEO & Performance no Google',
                    item2_desc_short: 'Posicionamos sua marca no topo do Google com estratégias de SEO técnico e de conteúdo.',
                    item2_desc_long: 'Ser encontrado é o primeiro passo. Nosso time de SEO técnico e de conteúdo trabalha para colocar sua empresa na primeira página do Google para as palavras-chave que importam. Realizamos auditorias completas, otimização on-page e estratégias de link building.',
                    item2_feat1: 'Auditoria Técnica e de Concorrentes',
                    item2_feat2: 'Pesquisa de Palavras-Chave Estratégicas',
                    item2_feat3: 'SEO Internacional (Brasil, PT, EUA)',
                    item3_tag: 'Mídia Paga',
                    item3_title: 'Tráfego Pago (Google & Meta Ads)',
                    item3_desc_short: 'Gerenciamos campanhas em Google Ads e Meta Ads para maximizar seu ROI.',
                    item3_desc_long: 'Atraia o público certo, no momento certo. Nossos gestores de tráfego são especialistas em criar e otimizar campanhas no Google Ads, Meta Ads (Facebook/Instagram) e LinkedIn Ads. Foco total em Custo por Aquisição (CPA) e Retorno sobre Investimento (ROI).',
                    item3_feat1: 'Gestão de Campanhas de Performance',
                    item3_feat2: 'Testes A/B de Criativos e Landing Pages',
                    item3_feat3: 'Dashboards de Resultados em Tempo Real',
                    item4_title: 'Gestão de Redes Sociais',
                    item4_desc_short: 'Construímos comunidades engajadas e fortalecemos sua presença de marca online.',
                    cta_title: 'Pronto para Analisar sua Performance?',
                    cta_subtitle: 'Solicite uma análise gratuita do seu site e descubra pontos de melhoria em SEO e performance que podemos otimizar.',
                    cta_button: 'Receber diagnóstico do meu site'
                },
                about: {
                    tag: 'Nossa Missão',
                    title: 'Mais que uma Agência, um Ecossistema de Tecnologia.',
                    p1: 'A Alpha Core nasceu da união entre engenharia de software e estratégia de marketing. Não apenas criamos campanhas; construímos os sistemas que as tornam possíveis e mensuráveis.',
                    p2: 'Com uma equipe sênior e atuação internacional, entendemos as nuances dos mercados do Brasil, Portugal e Estados Unidos. Nossa abordagem é data-driven, nossa execução é ágil e nosso foco é absoluto: gerar crescimento sustentável para nossos clientes através da tecnologia.',
                    stat1_num: '10+', stat1_desc: 'Anos de Experiência',
                    stat2_num: '3', stat2_desc: 'Mercados Internacionais',
                    stat3_num: '500+', stat3_desc: 'Clientes Atendidos',
                    stat4_num: '100%', stat4_desc: 'Foco em Performance'
                },
                portfolio: {
                    title: 'Nossos Casos de Sucesso',
                    subtitle: 'Projetos que combinam design impactante e tecnologia de ponta para gerar resultados reais.',
                    authority_text_1: "A Alpha Core é parceira estratégica de mais de <span class='text-neon-green'>500 empresas</span> no Brasil, Portugal e EUA.",
                    cta_title: 'Quer ver sua marca aqui?',
                    cta_button: 'Vamos Iniciar seu Projeto',
                    // Data dos Modais (PT)
                    p1_cat: 'Fintech',
                    p1_title: 'Plataforma TechFin',
                    p1_desc: 'Soluções digitais para fintechs e startups financeiras.',
                    p1_challenge: 'Cliente precisava de uma plataforma segura para processamento de pagamentos e validação de identidade, com alta disponibilidade e UX intuitiva.',
                    p1_solution: 'Desenvolvemos um portal em React.js com integração a APIs de pagamento (Stripe) e serviços de KYC (Know Your Customer), focado em segurança e performance.',
                    p1_results: '📈 +35% em captação de leads B2B; 🚀 Lançamento da plataforma em 3 meses; 🛡️ 100% de compliance com normas do Banco Central.',
                    
                    p2_cat: 'E-commerce',
                    p2_title: 'Sites e Lojas Virtuais',
                    p2_desc: 'Design, performance e conversão em alto nível.',
                    p2_challenge: 'Varejista de moda com baixa conversão mobile e site lento, perdendo vendas para concorrentes mais ágeis.',
                    p2_solution: 'Migração completa para Shopify 2.0, com tema customizado focado em mobile-first, otimização de imagens (WebP) e checkout transparente.',
                    p2_results: '🛒 +60% na taxa de conversão mobile; ⚡ Redução de 50% no tempo de carregamento; 💰 +40% no faturamento mensal.',

                    p3_cat: 'Mídia Paga',
                    p3_title: 'Tráfego Pago',
                    p3_desc: 'Campanhas otimizadas com foco em ROI.',
                    p3_challenge: 'Empresa de SaaS B2B com Custo por Lead (CPL) muito alto no Google Ads e baixa qualificação dos leads gerados.',
                    p3_solution: 'Reestruturação total das campanhas (SKAGs), negativação de palavras-chave, implementação de scripts de lance e criação de landing pages dinâmicas.',
                    p3_results: '💸 -45% no Custo por Lead; ✅ +70% na taxa de qualificação de leads (MQLs); 📈 Aumento de 25% no número de demos agendadas.',

                    p4_cat: 'Real Estate',
                    p4_title: 'Construtora de Luxo',
                    p4_desc: 'Captação de leads premium para alto padrão.',
                    p4_challenge: 'Lançamento de empreendimento de alto padrão com dificuldade em atrair o público correto (investidores e compradores de luxo).',
                    p4_solution: 'Campanhas segmentadas no Meta Ads (Facebook/Instagram) e LinkedIn Ads, usando criativos de alto impacto e segmentação por patrimônio e interesse.',
                    p4_results: '📊 +200 leads qualificados no primeiro mês; 🤝 15 unidades vendidas diretamente das campanhas; 💰 ROI de 12x sobre o investimento em mídia.',
                    
                    p5_cat: 'EdTech',
                    p5_title: 'Plataforma de Cursos',
                    p5_desc: 'Marketing digital para plataformas educacionais.',
                    p5_challenge: 'Plataforma de cursos online precisava escalar suas vendas de lançamentos (fórmula) e funis perpétuos.',
                    p5_solution: 'Criação de funis de e-mail marketing automatizados, gestão de tráfego para captação (lançamento) e remarketing (perpétuo) no Google e Meta Ads.',
                    p5_results: '🚀 +3000 alunos em um único lançamento; 🔄 Aumento de 50% nas vendas do funil perpétuo; 🎓 Custo por Aluno (CPA) 20% abaixo da meta.',

                    p6_cat: 'Saúde',
                    p6_title: 'Clínica Premium',
                    p6_desc: 'Branding e performance para setor de saúde.',
                    p6_challenge: 'Clínica de estética precisava de mais agendamentos de avaliações, respeitando as normas de publicidade do CFM.',
                    p6_solution: 'SEO Local (Google Meu Negócio) para ranquear a clínica na região e campanhas de Google Ads focadas em "agendamento de consulta" e procedimentos.',
                    p6_results: '🗓️ +80% em agendamentos de avaliação via site; 📍 Top 1 no Google Maps para "clínica de estética [cidade]"; 📱 Redução de 30% no custo por agendamento.',
                },
                contact: {
                    title: 'Inicie seu Projeto',
                    subtitle: 'Agende uma consultoria gratuita ou envie sua mensagem. Nosso time de especialistas está pronto para analisar seu desafio.',
                    form_name: 'Nome',
                    form_company: 'Empresa (Opcional)',
                    form_email: 'E-mail',
                    form_whatsapp: 'WhatsApp',
                    form_message: 'Mensagem',
                    form_submit: 'Enviar Mensagem',
                    info_title: 'Canais de Contato',
                    info_email_title: 'E-mail',
                    info_whatsapp_title: 'WhatsApp',
                    info_social_title: 'Redes Sociais'
                },
                footer: {
                    desc: 'Excelência em Soluções Digitais. Levando sua empresa para o próximo nível com tecnologia e marketing.',
                    links_title: 'Links Rápidos',
                    contact_title: 'Contato',
                    contact_loc1: 'Brasil',
                    contact_loc2: 'Portugal',
                    contact_loc3: 'EUA',
                    copyright: '© 2025 Alpha Core Marketing | Tecnologia — Excelência em Soluções Digitais.'
                },
                // Textos dos Modais (PT)
                modals: {
                    portfolio: {
                        challenge: 'O Desafio',
                        solution: 'A Solução Alpha Core',
                        results: 'Resultados'
                    },
                    exit: {
                        title: 'Espere, não vá ainda!',
                        subtitle: 'Vimos que você tem interesse em performance. Que tal uma análise de SEO gratuita para o seu site? Sem compromisso.',
                        button: 'Quero Minha Análise Gratuita'
                    },
                    update: {
                        title: 'Site atualizado!',
                        button: 'Recarregar'
                    }
                },
                // Página de Obrigado (PT)
                obrigado: {
                    title: 'Mensagem Recebida!',
                    subtitle: 'Obrigado por entrar em contato. Nosso time de especialistas analisará sua mensagem e retornará em breve.',
                    button: 'Voltar ao Início'
                }
            },
            
            // --- EN VERSION ---
            'en': {
                meta: {
                    title: 'Alpha Core Marketing | Technology - Digital Solutions',
                    description: 'We Turn Technology into Real Results. Digital Marketing, SEO, and High-Performance Websites for companies in the USA, Brazil, and Portugal.'
                },
                nav: {
                    home: 'Home',
                    services: 'Services',
                    about: 'About',
                    portfolio: 'Portfolio',
                    contact: 'Contact',
                    cta: 'Schedule Consultation'
                },
                home: {
                    headline_1: 'We Turn',
                    headline_2: 'Technology',
                    headline_3: 'into Real Results.',
                    subheadline: 'Digital Marketing, SEO, and High-Performance Websites. Alpha Core is your strategic partner for growth in the USA, Brazil, and Portugal.',
                    cta_whatsapp: 'Talk to an Expert',
                    cta_consult: 'Get My Free Analysis',
                    authority_line: 'Over 500 companies boosted in 3 countries with proven digital performance.',
                    clients_title: '+500 SATISFIED CLIENTS IN',
                    services_title: 'Our Core Solutions',
                    services_subtitle: 'From design to code, from click to conversion. We deliver end-to-end digital performance.'
                },
                common: {
                    learn_more: 'Learn More'
                },
                services: {
                    page_title: 'Our Performance Services',
                    page_subtitle: 'Integrated technology and marketing solutions to scale your business digitally.',
                    item1_tag: 'Web Development',
                    item1_title: 'Websites & E-commerce',
                    item1_desc_short: 'We build ultra-fast, responsive, and conversion-focused web platforms.',
                    item1_desc_long: 'From institutional sites to complex e-commerce, we design and code digital experiences that aren\'t just beautiful—they work. We focus on performance (Core Web Vitals), full responsiveness, and user journeys that convert visitors into customers.',
                    item1_feat1: 'WordPress & Shopify Platforms',
                    item1_feat2: 'Speed Optimization (LCP/FID)',
                    item1_feat3: 'Conversion-Focused UX/UI Design',
                    item2_tag: 'Google',
                    item2_title: 'SEO & Google Performance',
                    item2_desc_short: 'We position your brand at the top of Google with technical and content SEO strategies.',
                    item2_desc_long: 'Getting found is the first step. Our technical and content SEO team works to put your company on the first page of Google for the keywords that matter. We conduct full audits, on-page optimization, and link-building strategies.',
                    item2_feat1: 'Technical & Competitor Audits',
                    item2_feat2: 'Strategic Keyword Research',
                    item2_feat3: 'International SEO (USA, BR, PT)',
                    item3_tag: 'Paid Media',
                    item3_title: 'Paid Traffic (Google & Meta Ads)',
                    item3_desc_short: 'We manage Google Ads and Meta Ads campaigns to maximize your ROI.',
                    item3_desc_long: 'Attract the right audience at the right time. Our traffic managers are experts in creating and optimizing campaigns on Google Ads, Meta Ads (Facebook/Instagram), and LinkedIn Ads. Total focus on Cost Per Acquisition (CPA) and Return on Investment (ROI).',
                    item3_feat1: 'Performance Campaign Management',
                    item3_feat2: 'Creative & Landing Page A/B Testing',
                    item3_feat3: 'Real-Time Results Dashboards',
                    item4_title: 'Social Media Management',
                    item4_desc_short: 'We build engaged communities and strengthen your online brand presence.',
                    cta_title: 'Ready to Analyze Your Performance?',
                    cta_subtitle: 'Request a free analysis of your website and discover SEO and performance improvement points we can optimize.',
                    cta_button: 'Receive My Site Diagnosis'
                },
                about: {
                    tag: 'Our Mission',
                    title: 'More than an Agency, a Technology Ecosystem.',
                    p1: 'Alpha Core was born from the union of software engineering and marketing strategy. We don\'t just create campaigns; we build the systems that make them possible and measurable.',
                    p2: 'With a senior team and international operations, we understand the nuances of the US, Brazil, and Portugal markets. Our approach is data-driven, our execution is agile, and our focus is absolute: to generate sustainable growth for our clients through technology.',
                    stat1_num: '10+', stat1_desc: 'Years of Experience',
                    stat2_num: '3', stat2_desc: 'International Markets',
                    stat3_num: '500+', stat3_desc: 'Clients Served',
                    stat4_num: '100%', stat4_desc: 'Focus on Performance'
                },
                portfolio: {
                    title: 'Our Success Cases',
                    subtitle: 'Projects that combine impactful design and cutting-edge technology to generate real results.',
                    authority_text_1: "Alpha Core is a strategic partner to over <span class='text-neon-green'>500 companies</span> in the USA, Brazil, and Portugal.",
                    cta_title: 'Want to see your brand here?',
                    cta_button: 'Let\'s Start Your Project',
                    // Data dos Modais (EN)
                    p1_cat: 'Fintech',
                    p1_title: 'TechFin Platform',
                    p1_desc: 'Digital solutions for fintechs and financial startups.',
                    p1_challenge: 'Client needed a secure platform for payment processing and identity validation, with high availability and an intuitive UX.',
                    p1_solution: 'We developed a React.js portal with payment API (Stripe) and KYC (Know Your Customer) service integrations, focusing on security and performance.',
                    p1_results: '📈 +35% in B2B lead generation; 🚀 Platform launch in 3 months; 🛡️ 100% compliance with Central Bank regulations.',
                    
                    p2_cat: 'E-commerce',
                    p2_title: 'Websites & E-commerce',
                    p2_desc: 'High-level design, performance, and conversion.',
                    p2_challenge: 'Fashion retailer with low mobile conversion and a slow site, losing sales to more agile competitors.',
                    p2_solution: 'Full migration to Shopify 2.0, with a custom mobile-first theme, WebP image optimization, and a seamless checkout process.',
                    p2_results: '🛒 +60% in mobile conversion rate; ⚡ 50% reduction in load time; 💰 +40% in monthly revenue.',
                    
                    p3_cat: 'Paid Media',
                    p3_title: 'Paid Traffic',
                    p3_desc: 'Optimized campaigns focused on ROI.',
                    p3_challenge: 'B2B SaaS company with a very high Cost Per Lead (CPL) on Google Ads and low-quality leads.',
                    p3_solution: 'Complete campaign restructure (SKAGs), negative keyword implementation, bid scripts, and creation of dynamic landing pages.',
                    p3_results: '💸 -45% in Cost Per Lead; ✅ +70% in lead qualification rate (MQLs); 📈 25% increase in scheduled demos.',
                    
                    p4_cat: 'Real Estate',
                    p4_title: 'Luxury Developer',
                    p4_desc: 'Premium lead generation for high-end properties.',
                    p4_challenge: 'Launching a high-end development with difficulty attracting the right audience (investors and luxury buyers).',
                    p4_solution: 'Targeted campaigns on Meta Ads (Facebook/Instagram) and LinkedIn Ads, using high-impact creatives and segmentation by wealth and interest.',
                    p4_results: '📊 +200 qualified leads in the first month; 🤝 15 units sold directly from campaigns; 💰 12x ROI on media spend.',
                    
                    p5_cat: 'EdTech',
                    p5_title: 'Course Platform',
                    p5_desc: 'Digital marketing for educational platforms.',
                    p5_challenge: 'Online course platform needed to scale its sales for launches (formula) and evergreen funnels.',
                    p5_solution: 'Creation of automated email marketing funnels, traffic management for capture (launch) and remarketing (evergreen) on Google and Meta Ads.',
                    p5_results: '🚀 +3000 students in a single launch; 🔄 50% increase in evergreen funnel sales; 🎓 Cost Per Student (CPA) 20% below target.',
                    
                    p6_cat: 'Healthcare',
                    p6_title: 'Premium Clinic',
                    p6_desc: 'Branding and performance for the health sector.',
                    p6_challenge: 'Aesthetic clinic needed more evaluation bookings while adhering to medical advertising regulations.',
                    p6_solution: 'Local SEO (Google Business Profile) to rank the clinic regionally and Google Ads campaigns focused on "book appointment" and specific procedures.',
                    p6_results: '🗓️ +80% in evaluation bookings via site; 📍 Top 1 on Google Maps for "aesthetic clinic [city]"; 📱 30% reduction in cost per booking.',
                },
                contact: {
                    title: 'Start Your Project',
                    subtitle: 'Schedule a free consultation or send us your message. Our team of experts is ready to analyze your challenge.',
                    form_name: 'Name',
                    form_company: 'Company (Optional)',
                    form_email: 'E-mail',
                    form_whatsapp: 'WhatsApp',
                    form_message: 'Message',
                    form_submit: 'Send Message',
                    info_title: 'Contact Channels',
                    info_email_title: 'E-mail',
                    info_whatsapp_title: 'WhatsApp',
                    info_social_title: 'Social Media'
                },
                footer: {
                    desc: 'Excellence in Digital Solutions. Taking your company to the next level with technology and marketing.',
                    links_title: 'Quick Links',
                    contact_title: 'Contact',
                    contact_loc1: 'USA',
                    contact_loc2: 'Portugal',
                    contact_loc3: 'Brazil',
                    copyright: '© 2025 Alpha Core Marketing | Technology — Excellence in Digital Solutions.'
                },
                // Textos dos Modais (EN)
                modals: {
                    portfolio: {
                        challenge: 'The Challenge',
                        solution: 'The Alpha Core Solution',
                        results: 'Results'
                    },
                    exit: {
                        title: "Wait, don't go yet!",
                        subtitle: 'We saw you\'re interested in performance. How about a free, no-obligation SEO analysis for your website?',
                        button: 'Get My Free Analysis'
                    },
                    update: {
                        title: 'Site updated!',
                        button: 'Reload'
                    }
                },
                // Página de Obrigado (EN)
                obrigado: {
                    title: 'Message Received!',
                    subtitle: 'Thank you for getting in touch. Our team of experts will analyze your message and get back to you shortly.',
                    button: 'Back to Home'
                }
            }
        };

        // --- LÓGICA DA APLICAÇÃO ---

        // Estado da Aplicação
        let appState = {
            currentLang: 'pt',
            currentPage: 'home'
        };

        // --- Seletores do DOM ---
        const dom = {
            html: document.documentElement,
            body: document.body,
            langButtons: document.querySelectorAll('#lang-pt, #lang-en, #lang-pt-mobile, #lang-en-mobile'),
            navLinks: document.querySelectorAll('.nav-link'),
            pageSections: document.querySelectorAll('.page-section'),
            textElements: document.querySelectorAll('[data-lang]'),
            mobileMenu: document.getElementById('mobile-menu'),
            mobileMenuButton: document.getElementById('mobile-menu-button'),
            progressBar: document.getElementById('progress-bar'),
            // Hreflang
            canonicalLink: document.getElementById('lang-canonical'),
            altPtLink: document.getElementById('lang-alt-pt'),
            altEnLink: document.getElementById('lang-alt-en'),
            altXDefaultLink: document.getElementById('lang-alt-xdefault'),
            // Cursor
            cursorDot: document.querySelector('.cursor-dot'),
            cursorOutline: document.querySelector('.cursor-outline'),
            // Modals
            portfolioModal: document.getElementById('portfolio-modal'),
            portfolioModalClose: document.getElementById('modal-close-btn'),
            portfolioCards: document.querySelectorAll('.portfolio-card'),
            exitIntentModal: document.getElementById('exit-intent-modal'),
            exitIntentModalClose: document.getElementById('exit-modal-close-btn'),
            modalOverlays: document.querySelectorAll('.modal-overlay'),
            // Formulário
            contactForm: document.getElementById('contact-form'),
            formSubmitBtn: document.getElementById('form-submit-btn'),
            leadSourceField: document.getElementById('lead_source_field'),
            // PWA Update
            updateToast: document.getElementById('update-toast'),
            updateToastBtn: document.getElementById('update-toast-btn')
        };
        
        let newSW; // Para guardar o novo Service Worker

        // --- Funções Principais ---

        /**
         * Atualiza todo o conteúdo de texto da página com base no idioma
         * @param {string} lang - 'pt' ou 'en'
         */
        function updateTextContent(lang) {
            dom.html.lang = lang === 'pt' ? 'pt-BR' : 'en';
            dom.canonicalLink.href = `https://alphacore.tech/${lang}/`;
            dom.altPtLink.href = 'https://alphacore.tech/pt/';
            dom.altEnLink.href = 'https://alphacore.tech/en/';
            
            document.title = textData[lang].meta.title;
            document.querySelector('meta[name="description"]').setAttribute('content', textData[lang].meta.description);
            
            dom.textElements.forEach(el => {
                const key = el.dataset.lang;
                const [section, ...itemParts] = key.split('.');
                const item = itemParts.join('.');
                
                try {
                    const text = itemParts.reduce((obj, key) => obj[key], textData[lang][section]);
                    if (text) {
                        el.innerHTML = text;
                    }
                } catch (e) {
                    console.warn(`Chave i18n não encontrada: ${key}`);
                }
            });
        }

        /**
         * Atualiza o estado visual dos botões de idioma
         * @param {string} lang - 'pt' ou 'en'
         */
        function updateLangButtons(lang) {
            dom.langButtons.forEach(btn => {
                const btnLang = btn.id.includes('pt') ? 'pt' : 'en';
                btn.classList.toggle('active', btnLang === lang);
                btn.classList.toggle('inactive', btnLang !== lang);
            });
        }

        /**
         * Altera o idioma global (com fade)
         * @param {string} lang - 'pt' ou 'en'
         */
        function changeLanguage(lang) {
            if (lang === appState.currentLang) return; 

            dom.body.style.opacity = 0;
            setTimeout(() => {
                appState.currentLang = lang;
                updateTextContent(lang);
                updateLangButtons(lang);
                dom.body.style.opacity = 1;
            }, 400);
        }

        /**
         * MELHORIA: Navegador (Router)
         * Lê o hash da URL e mostra a página correta
         */
        function handleHashChange() {
            let hash = window.location.hash.substring(1);
            
            // Mapeia hashs antigos ou vazios
            if (!hash || !document.getElementById(`page-${hash}`)) {
                hash = 'home';
            }
            
            // Se a página já for a ativa, não faz nada
            if (hash === appState.currentPage) return;
            
            appState.currentPage = hash;
            
            // Fade out
            dom.body.style.opacity = 0;
            
            setTimeout(() => {
                // Ativa a seção correta
                dom.pageSections.forEach(section => {
                    section.classList.toggle('active', section.id === `page-${hash}`);
                });
                
                // Atualiza links do header
                dom.navLinks.forEach(link => {
                    link.classList.toggle('active', link.dataset.page === hash);
                });
                
                // Fecha o menu mobile se estiver aberto
                if (!dom.mobileMenu.classList.contains('hidden')) {
                    dom.mobileMenu.classList.add('hidden');
                }
                
                window.scrollTo(0, 0); // Sobe para o topo
                dom.body.style.opacity = 1; // Fade in
            }, 400); // Mesmo tempo da transição no CSS
        }
        
        /**
         * MELHORIA: Modal de Portfólio
         * Abre o modal com os dados do projeto
         * @param {string} projectId - ex: "p1", "p2"
         */
        function openModal(projectId) {
            const lang = appState.currentLang;
            const data = textData[lang].portfolio[projectId];
            
            if (!data) return;
            
            // Popula o modal
            document.getElementById('modal-img').src = document.querySelector(`.portfolio-card[data-project-id="${projectId}"] img`).src;
            document.getElementById('modal-img').alt = data.title;
            document.getElementById('modal-title').innerHTML = data.title;
            document.getElementById('modal-challenge').innerHTML = data.challenge;
            document.getElementById('modal-solution').innerHTML = data.solution;
            document.getElementById('modal-results').innerHTML = data.results;
            
            // Atualiza o CTA do modal para rastrear a origem
            const modalCta = document.getElementById('modal-cta');
            modalCta.dataset.source = `portfolio_modal_${projectId}`;
            
            dom.portfolioModal.classList.remove('hidden');
            setTimeout(() => dom.portfolioModal.classList.add('active'), 10); // Ativa transição
        }
        
        /**
         * Fecha todos os modais ativos
         */
        function closeModal() {
            dom.modalOverlays.forEach(modal => {
                modal.classList.remove('active');
                setTimeout(() => modal.classList.add('hidden'), 300); // Espera transição
            });
        }
        
        /**
         * MELHORIA: Modal de Exit-Intent
         * Mostra o modal de saída se as condições forem atendidas
         */
        function showExitIntent(e) {
            // Condições para mostrar: mouse saindo pelo topo E não foi mostrado nesta sessão
            if (e.clientY <= 0 && !sessionStorage.getItem('exitIntentShown')) {
                dom.exitIntentModal.classList.remove('hidden');
                setTimeout(() => dom.exitIntentModal.classList.add('active'), 10);
                sessionStorage.setItem('exitIntentShown', 'true'); // Marca como visto
                
                // Atualiza o CTA para rastreio
                document.getElementById('exit-modal-cta').dataset.source = 'exit_intent_modal_cta';
            }
        }
        
        /**
         * MELHORIA: PWA Update Toast
         * Mostra o toast de atualização
         */
        function showUpdateToast() {
            dom.updateToast.classList.add('show');
        }

        /**
         * MELHORIA: Formulário AJAX Netlify
         * Envia o formulário sem recarregar a página
         */
        async function handleFormSubmit(e) {
            e.preventDefault();
            
            const form = e.target;
            const formData = new FormData(form);
            const submitBtn = dom.formSubmitBtn;
            const originalBtnText = submitBtn.innerHTML;
            
            submitBtn.disabled = true;
            submitBtn.innerHTML = 'Enviando...';
            
            try {
                const response = await fetch('/', {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/x-www-form-urlencoded' },
                    body: new URLSearchParams(formData).toString()
                });
                
                if (response.ok) {
                    // Sucesso! Limpa o formulário e vai para a página de obrigado
                    form.reset();
                    window.location.hash = '#obrigado';
                } else {
                    // Erro
                    alert('Houve um erro ao enviar sua mensagem. Tente novamente.');
                }
            } catch (error) {
                console.error('Erro no envio do formulário:', error);
                alert('Houve um erro de rede. Tente novamente.');
            } finally {
                submitBtn.disabled = false;
                submitBtn.innerHTML = originalBtnText;
            }
        }

        // --- Event Listeners ---
        
        document.addEventListener('DOMContentLoaded', () => {
            
            // --- 1. Configuração Inicial ---
            // Define o idioma e a página com base na URL
            const initialLang = appState.currentLang; // (Pode adicionar lógica para ler do navegador)
            appState.currentLang = initialLang;
            updateTextContent(initialLang);
            updateLangButtons(initialLang);
            handleHashChange(); // Navega para a página correta no load
            
            // Fade-in inicial do corpo
            dom.body.style.opacity = 0;
            setTimeout(() => { dom.body.style.opacity = 1; }, 50);

            // --- 2. Roteamento e Navegação ---
            window.addEventListener('hashchange', handleHashChange);
            
            dom.navLinks.forEach(link => {
                link.addEventListener('click', (e) => {
                    // Atualiza o campo de lead source se o link tiver
                    const source = e.currentTarget.dataset.source;
                    if (source) {
                        dom.leadSourceField.value = source;
                    }
                });
            });

            // --- 3. Troca de Idioma ---
            dom.langButtons.forEach(button => {
                button.addEventListener('click', (e) => {
                    e.preventDefault();
                    const lang = button.id.includes('pt') ? 'pt' : 'en';
                    changeLanguage(lang);
                });
            });
            
            // --- 4. Menu Mobile ---
            dom.mobileMenuButton.addEventListener('click', () => {
                dom.mobileMenu.classList.toggle('hidden');
            });
            
            // --- 5. Cursor Neon ---
            if (window.matchMedia('(min-width: 769px)').matches) {
                window.addEventListener('mousemove', (e) => {
                    dom.cursorDot.style.left = e.clientX + 'px';
                    dom.cursorDot.style.top = e.clientY + 'px';
                    dom.cursorOutline.style.left = e.clientX + 'px';
                    dom.cursorOutline.style.top = e.clientY + 'px';
                });
                
                document.querySelectorAll('a, button, .portfolio-card, input, textarea, label').forEach(el => {
                    el.addEventListener('mouseenter', () => dom.body.classList.add('cursor-hover'));
                    el.addEventListener('mouseleave', () => dom.body.classList.remove('cursor-hover'));
                });
            }

            // --- 6. Animações "Staggered" (Scroll) ---
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        if (entry.target.classList.contains('staggered-group')) {
                            // É um grupo de cards
                            const items = entry.target.querySelectorAll('.service-card, .portfolio-card');
                            items.forEach((item, index) => {
                                item.style.transitionDelay = `${index * 100}ms`;
                                item.classList.add('is-visible');
                            });
                        } else {
                            // É uma seção normal
                            entry.target.classList.add('is-visible');
                        }
                        observer.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.1 });

            document.querySelectorAll('.fade-in-section, .staggered-group').forEach(el => {
                observer.observe(el);
            });
            
            // --- 7. Modals (Portfólio & Exit-Intent) ---
            dom.portfolioCards.forEach(card => {
                card.addEventListener('click', (e) => {
                    const projectId = e.currentTarget.dataset.projectId;
                    openModal(projectId);
                });
            });
            
            // Listeners para fechar modais
            dom.portfolioModalClose.addEventListener('click', closeModal);
            dom.exitIntentModalClose.addEventListener('click', closeModal);
            dom.modalOverlays.forEach(overlay => {
                overlay.addEventListener('click', (e) => {
                    if (e.target === overlay) closeModal(); // Fecha só se clicar no fundo
                });
            });
            
            // Listener do Exit-Intent
            document.body.addEventListener('mouseleave', showExitIntent);
            
            // --- 8. Formulário AJAX Netlify ---
            dom.contactForm.addEventListener('submit', handleFormSubmit);
            
            // --- 9. Barra de Progresso (Scroll) ---
            window.addEventListener('scroll', () => {
              const scrollTop = window.scrollY;
              const docHeight = dom.html.scrollHeight - window.innerHeight;
              const progress = (scrollTop / docHeight) * 100;
              dom.progressBar.style.width = progress + '%';
            });
            
            // --- 10. Service Worker (PWA) ---
            if ('serviceWorker' in navigator) {
                // Cria o SW a partir de um Blob
                const swContent = `
                    const CACHE_NAME = 'alphacore-cache-v1';
                    const urlsToCache = [
                        '#home', '#servicos', '#sobre', '#portfolio', '#contato', '#obrigado',
                        'https://i.postimg.cc/RhzycscF/1000362303-removebg-preview.png',
                        'https://images.pexels.com/photos/5716042/pexels-photo-5716042.jpeg',
                        'https://i.postimg.cc/Sjbt4G62/unnamed.jpg',
                        'https://i.postimg.cc/H8tM1mQ6/unnamed-1.jpg',
                        'https://i.postimg.cc/vxvnwyrF/unnamed-2.jpg',
                        'https://i.postimg.cc/9wB9H2Gv/unnamed-3.jpg',
                        'https://i.postimg.cc/7JNzr43v/unnamed-4.jpg',
                        'https://i.postimg.cc/vxvnwyrd/unnamed-5.jpg',
                        'https://i.postimg.cc/fb5cTvN9/unnamed-6-removebg-preview.png',
                        'https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap'
                    ];

                    self.addEventListener('install', event => {
                        event.waitUntil(
                            caches.open(CACHE_NAME).then(cache => {
                                // console.log('Alpha Core SW: Cache aberto, adicionando URLs');
                                // Não bloqueia a instalação se alguma falhar
                                cache.addAll(urlsToCache).catch(err => console.warn('SW: Falha ao cachear alguns assets', err));
                            }).then(() => self.skipWaiting()) // Ativa o SW imediatamente
                        );
                    });
                    
                    self.addEventListener('activate', event => {
                        event.waitUntil(clients.claim()); // Controla a página imediatamente
                    });

                    self.addEventListener('fetch', event => {
                        // Estratégia Network-First (para conteúdo dinâmico)
                        event.respondWith(
                            fetch(event.request).catch(() => {
                                return caches.match(event.request).then(response => {
                                    return response || new Response("Offline");
                                });
                            })
                        );
                    });
                    
                    // Listener para o botão 'Atualizar' do toast
                    self.addEventListener('message', event => {
                        if (event.data && event.data.type === 'SKIP_WAITING') {
                            self.skipWaiting();
                        }
                    });
                `;
                
                const swBlob = new Blob([swContent], { type: 'application/javascript' });
                const swUrl = URL.createObjectURL(swBlob);
                
                window.addEventListener('load', () => {
                    navigator.serviceWorker.register(swUrl)
                        .then(reg => {
                            console.log('Alpha Core: ServiceWorker registrado.');
                            
                            // Lógica de atualização
                            reg.addEventListener('updatefound', () => {
                                newSW = reg.installing;
                                newSW.addEventListener('statechange', () => {
                                    if (newSW.state === 'installed' && navigator.serviceWorker.controller) {
                                        // Nova versão pronta! Mostra o toast.
                                        showUpdateToast();
                                    }
                                });
                            });
                        })
                        .catch(err => {
                            console.log('Alpha Core: Falha no registro do ServiceWorker.', err);
                        });
                });
                
                // Listener para o botão no toast
                dom.updateToastBtn.addEventListener('click', () => {
                    if (newSW) {
                        newSW.postMessage({ type: 'SKIP_WAITING' });
                        // Recarrega a página após o SW ser ativado
                        navigator.serviceWorker.addEventListener('controllerchange', () => {
                            window.location.reload();
                        });
                    }
                });
            }
            
        });
        
    </script>
    
</body>
</html>




