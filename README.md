<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Fone Bluetooth TWS Premium - Som de Qualidade | Pague na Entrega R$65</title>
    <meta name="description" content="Fone Bluetooth TWS Premium com som de alta qualidade. Pague apenas R$ 65 quando receber. Entrega rápida em todo Brasil e garantia de 7 dias.">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap" rel="stylesheet">
    
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    
    <!-- GSAP para animações -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: '#FF6B00',
                        secondary: '#0066FF',
                        dark: '#0a0a0a',
                        'dark-gray': '#1a1a1a',
                        'accent-blue': '#5B9BD5',
                    },
                    animation: {
                        'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        'bounce-slow': 'bounce 2s infinite',
                        'float': 'float 6s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0px)' },
                            '50%': { transform: 'translateY(-20px)' },
                        }
                    }
                }
            }
        }
    </script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
            -webkit-tap-highlight-color: transparent;
            background-color: #0a0a0a;
        }
        
        .text-shadow {
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #FF6B00 0%, #FF8C00 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 50%, #0f172a 100%);
        }
        
        .cta-button {
            background: linear-gradient(135deg, #FF6B00 0%, #FF8533 100%);
            box-shadow: 0 10px 30px -5px rgba(255, 107, 0, 0.4), 0 0 60px -10px rgba(255, 107, 0, 0.3);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
        }
        
        .cta-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: left 0.5s;
        }
        
        .cta-button:hover::before {
            left: 100%;
        }
        
        .cta-button:hover {
            transform: translateY(-3px) scale(1.02);
            box-shadow: 0 20px 40px -5px rgba(255, 107, 0, 0.5), 0 0 80px -10px rgba(255, 107, 0, 0.4);
        }
        
        .cta-button:active {
            transform: translateY(-1px) scale(0.98);
        }
        
        .floating-whatsapp {
            animation: float-whatsapp 3s ease-in-out infinite;
            box-shadow: 0 10px 30px -5px rgba(37, 211, 102, 0.4);
        }
        
        @keyframes float-whatsapp {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        
        .benefit-card {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .benefit-card:hover {
            transform: translateY(-8px);
            background: rgba(255, 255, 255, 0.06);
            border-color: rgba(255, 107, 0, 0.3);
            box-shadow: 0 20px 40px rgba(0,0,0,0.4);
        }
        
        .sticky-cta {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            z-index: 50;
            transform: translateY(100%);
            transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            background: rgba(10, 10, 10, 0.95);
            backdrop-filter: blur(20px);
            border-top: 1px solid rgba(255, 107, 0, 0.3);
        }
        
        .sticky-cta.visible {
            transform: translateY(0);
        }
        
        .product-image-container {
            position: relative;
            filter: drop-shadow(0 25px 50px rgba(0,0,0,0.5));
        }
        
        .glow-effect {
            position: absolute;
            inset: -20%;
            background: radial-gradient(circle, rgba(91, 155, 213, 0.15) 0%, transparent 70%);
            z-index: -1;
            animation: pulse-glow 4s ease-in-out infinite;
        }
        
        @keyframes pulse-glow {
            0%, 100% { opacity: 0.5; transform: scale(1); }
            50% { opacity: 0.8; transform: scale(1.1); }
        }
        
        .security-banner {
            background: linear-gradient(135deg, #FF6B00 0%, #FF8533 50%, #FF6B00 100%);
            background-size: 200% 200%;
            animation: gradient-shift 3s ease infinite;
        }
        
        @keyframes gradient-shift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .countdown-box {
            background: rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
        }
        
        .feature-icon {
            background: linear-gradient(135deg, rgba(255, 107, 0, 0.2) 0%, rgba(255, 107, 0, 0.05) 100%);
            border: 1px solid rgba(255, 107, 0, 0.2);
        }
        
        .price-highlight {
            position: relative;
            display: inline-block;
        }
        
        .price-highlight::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, #FF6B00, #FFD700);
            border-radius: 2px;
        }
        
        .trust-badge {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
        }
        
        .trust-badge:hover {
            background: rgba(255, 255, 255, 0.1);
            transform: translateY(-2px);
        }
        
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0a0a0a;
        }
        ::-webkit-scrollbar-thumb {
            background: #333;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #FF6B00;
        }
    </style>
</head>
<body class="text-white overflow-x-hidden">

    <!-- Header Fixo -->
    <header class="fixed top-0 left-0 right-0 z-40 bg-dark/80 backdrop-blur-xl border-b border-white/5 transition-all duration-300" id="header">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16 sm:h-20">
                <!-- Logo -->
                <div class="flex items-center space-x-3 group cursor-pointer">
                    <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-primary to-orange-500 rounded-xl flex items-center justify-center shadow-lg shadow-orange-500/20 group-hover:scale-110 transition-transform duration-300">
                        <i data-lucide="headphones" class="w-6 h-6 sm:w-7 sm:h-7 text-white"></i>
                    </div>
                    <div class="flex flex-col">
                        <span class="text-lg sm:text-xl font-black tracking-tight">TWS<span class="text-primary">Premium</span></span>
                        <span class="text-[10px] sm:text-xs text-gray-400 -mt-1">Som de Alta Fidelidade</span>
                    </div>
                </div>
                
                <!-- WhatsApp Flutuante -->
                <a href="https://wa.me/5564993274233" target="_blank" class="floating-whatsapp flex items-center space-x-2 bg-gradient-to-r from-green-500 to-green-600 hover:from-green-400 hover:to-green-500 text-white px-4 sm:px-5 py-2.5 sm:py-3 rounded-full font-bold text-sm transition-all shadow-lg group">
                    <i data-lucide="message-circle" class="w-5 h-5 group-hover:scale-110 transition-transform"></i>
                    <span class="hidden sm:inline">Falar no WhatsApp</span>
                    <span class="sm:hidden">WhatsApp</span>
                </a>
            </div>
        </div>
    </header>

    <!-- Espaçamento do Header -->
    <div class="h-16 sm:h-20"></div>

    <!-- Seção Hero -->
    <section class="hero-gradient relative overflow-hidden min-h-[95vh] flex items-center">
        <!-- Background Elements -->
        <div class="absolute inset-0 overflow-hidden pointer-events-none">
            <div class="absolute top-20 left-10 w-96 h-96 bg-accent-blue/10 rounded-full blur-3xl animate-pulse-slow"></div>
            <div class="absolute bottom-20 right-10 w-[500px] h-[500px] bg-primary/5 rounded-full blur-3xl"></div>
            <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-[800px] h-[800px] bg-gradient-radial from-accent-blue/5 to-transparent rounded-full"></div>
        </div>

        <!-- Grid Pattern Overlay -->
        <div class="absolute inset-0 bg-[linear-gradient(rgba(255,255,255,0.03)_1px,transparent_1px),linear-gradient(90deg,rgba(255,255,255,0.03)_1px,transparent_1px)] bg-[size:60px_60px] [mask-image:radial-gradient(ellipse_at_center,black_40%,transparent_80%)]"></div>

        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8 lg:py-16">
            <div class="grid lg:grid-cols-2 gap-8 lg:gap-12 items-center">
                <!-- Conteúdo -->
                <div class="text-center lg:text-left space-y-4 sm:space-y-6 order-2 lg:order-1">
                    <!-- Badge de Entrega -->
                    <div class="inline-flex items-center space-x-2 bg-white/5 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 mb-2 hover:bg-white/10 transition-colors cursor-default">
                        <span class="flex h-2.5 w-2.5 relative">
                            <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-green-400 opacity-75"></span>
                            <span class="relative inline-flex rounded-full h-2.5 w-2.5 bg-green-500"></span>
                        </span>
                        <span class="text-xs sm:text-sm font-semibold text-gray-300">Entrega em 24-48h • Todo Brasil</span>
                    </div>

                    <h1 class="text-3xl sm:text-5xl lg:text-6xl font-black leading-[1.1] text-shadow">
                        Fone Bluetooth <br>
                        <span class="gradient-text">TWS Premium</span>
                    </h1>
                    
                    <p class="text-base sm:text-xl text-gray-300 font-medium max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                        Experimente a verdadeira liberdade sonora. Conexão instantânea, bateria de longa duração e qualidade de som profissional.
                    </p>

                    <!-- Preço -->
                    <div class="flex flex-col items-center lg:items-start space-y-2 sm:space-y-3 py-2">
                        <div class="flex items-center space-x-3 bg-white/5 px-4 py-2 rounded-full border border-white/10">
                            <span class="text-gray-400 line-through text-base sm:text-lg font-medium">De R$ 129,90</span>
                            <span class="bg-green-500 text-white px-3 py-1 rounded-full text-xs sm:text-sm font-black shadow-lg shadow-green-500/30">-50% OFF</span>
                        </div>
                        <div class="flex items-baseline space-x-2">
                            <span class="text-gray-400 text-lg">Por apenas</span>
                            <div class="price-highlight">
                                <span class="text-5xl sm:text-7xl font-black text-white tracking-tight">R$ 65</span>
                            </div>
                        </div>
                        <p class="text-green-400 font-semibold text-sm sm:text-base flex items-center">
                            <i data-lucide="shield-check" class="w-4 h-4 sm:w-5 sm:h-5 mr-2"></i>
                            Pagamento somente na entrega
                        </p>
                    </div>

                    <!-- CTA Principal -->
                    <div class="pt-2 sm:pt-4 space-y-3">
                        <a href="https://app.coinzz.com.br/checkout/1-unidade-ijxm1-0" class="cta-button inline-flex items-center justify-center w-full sm:w-auto px-6 sm:px-10 py-4 sm:py-5 rounded-2xl text-white font-black text-base sm:text-lg tracking-wide group relative">
                            <span class="relative z-10 flex items-center">
                                <i data-lucide="shopping-bag" class="w-5 h-5 sm:w-6 sm:h-6 mr-2 sm:mr-3"></i>
                                QUERO COMPRAR E PAGAR NA ENTREGA
                                <i data-lucide="arrow-right" class="w-5 h-5 sm:w-6 sm:h-6 ml-2 sm:ml-3 group-hover:translate-x-1 transition-transform"></i>
                            </span>
                        </a>
                        
                        <!-- Garantias abaixo do CTA -->
                        <div class="flex flex-wrap items-center justify-center lg:justify-start gap-3 pt-2">
                            <div class="flex items-center space-x-1.5 text-xs text-gray-400 bg-white/5 px-3 py-1.5 rounded-full border border-white/10">
                                <i data-lucide="truck" class="w-3.5 h-3.5 text-primary"></i>
                                <span>Frete Grátis</span>
                            </div>
                            <div class="flex items-center space-x-1.5 text-xs text-gray-400 bg-white/5 px-3 py-1.5 rounded-full border border-white/10">
                                <i data-lucide="refresh-cw" class="w-3.5 h-3.5 text-primary"></i>
                                <span>7 Dias Garantia</span>
                            </div>
                            <div class="flex items-center space-x-1.5 text-xs text-gray-400 bg-white/5 px-3 py-1.5 rounded-full border border-white/10">
                                <i data-lucide="lock" class="w-3.5 h-3.5 text-primary"></i>
                                <span>Compra Segura</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Imagem do Produto -->
                <div class="relative order-1 lg:order-2 flex justify-center items-center">
                    <div class="product-image-container relative w-full max-w-md lg:max-w-lg animate-float">
                        <div class="glow-effect"></div>
                        
                        <!-- Imagem real do produto -->
                        <div class="relative z-10 bg-gradient-to-b from-transparent via-transparent to-dark/50 rounded-3xl p-4">
                            <img src="/mnt/kimi/upload/1000014224.jpg" 
                                 alt="Fone Bluetooth TWS Premium - Case de carregamento com fones sem fio" 
                                 class="w-full h-auto object-contain drop-shadow-2xl rounded-2xl hover:scale-105 transition-transform duration-700">
                        </div>
                        
                        <!-- Badge flutuante de qualidade -->
                        <div class="absolute -top-2 -right-2 sm:top-4 sm:right-0 bg-gradient-to-br from-primary to-orange-500 text-white w-20 h-20 sm:w-24 sm:h-24 rounded-full flex flex-col items-center justify-center font-black text-center shadow-2xl transform rotate-12 border-4 border-dark z-20 animate-bounce-slow">
                            <span class="text-2xl sm:text-3xl">5.0</span>
                            <span class="text-[10px] sm:text-xs uppercase tracking-wider">Bluetooth</span>
                        </div>

                        <!-- Badge de bateria -->
                        <div class="absolute bottom-10 -left-4 sm:left-0 bg-dark/90 backdrop-blur-md border border-white/20 text-white px-4 py-2 rounded-full flex items-center space-x-2 shadow-xl z-20">
                            <i data-lucide="battery-charging" class="w-5 h-5 text-green-400"></i>
                            <span class="text-sm font-bold">24h de Bateria</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Scroll Indicator -->
        <div class="absolute bottom-6 left-1/2 transform -translate-x-1/2 animate-bounce hidden lg:block">
            <div class="w-8 h-12 border-2 border-white/20 rounded-full flex justify-center pt-2">
                <div class="w-1.5 h-3 bg-white/40 rounded-full animate-pulse"></div>
            </div>
        </div>
    </section>

    <!-- Banner de Segurança - Destaque Máximo -->
    <section class="security-banner py-6 sm:py-8 relative overflow-hidden border-y-4 border-orange-400/30">
        <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGNpcmNsZSBjeD0iMjAiIGN5PSIyMCIgcj0iMSIgZmlsbD0id2hpdGUiIGZpbGwtb3BhY2l0eT0iMC4yIi8+PC9zdmc+')] opacity-30"></div>
        
        <div class="max-w-6xl mx-auto px-4 text-center relative z-10">
            <div class="flex flex-col items-center space-y-3 sm:space-y-4">
                <div class="flex items-center space-x-3 text-white">
                    <div class="bg-white/20 p-2 rounded-full">
                        <i data-lucide="shield-check" class="w-8 h-8 sm:w-10 sm:h-10"></i>
                    </div>
                    <h2 class="text-2xl sm:text-4xl lg:text-5xl font-black tracking-tight uppercase text-shadow">
                        Você só paga quando receber!
                    </h2>
                    <div class="bg-white/20 p-2 rounded-full">
                        <i data-lucide="package-check" class="w-8 h-8 sm:w-10 sm:h-10"></i>
                    </div>
                </div>
                <p class="text-xl sm:text-3xl font-bold text-white/95 flex items-center flex-wrap justify-center gap-2">
                    <span class="bg-white/20 px-4 py-1 rounded-lg">R$ 65 na entrega</span>
                    <span class="hidden sm:inline">•</span>
                    <span>Zero risco para você</span>
                </p>
                <div class="flex items-center space-x-2 text-white/90 text-sm sm:text-base bg-black/20 px-4 py-2 rounded-full">
                    <i data-lucide="truck" class="w-5 h-5"></i>
                    <span class="font-bold">Entregamos em todo 
