<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emagreça Online | O Seu Guia Definitivo de Transformação</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Plus Jakarta Sans"', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#ecfdf5',
                            100: '#d1fae5',
                            500: '#10b981',
                            600: '#059669',
                            700: '#047857',
                            900: '#064e3b'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.4);
        }
        .gradient-bg {
            background: radial-gradient(circle at 50% 0%, rgba(16, 185, 129, 0.15) 0%, rgba(255, 255, 255, 0) 65%);
        }
    </style>
</head>
<body class="bg-[#fafafc] text-slate-800 antialiased font-sans">

    <!-- BARRA DE AVISO SUPERIOR -->
    <div class="bg-gradient-to-r from-emerald-600 to-teal-700 text-white text-xs sm:text-sm font-medium py-2.5 px-4 text-center">
        <div class="max-w-5xl mx-auto flex items-center justify-center gap-2">
            <span class="inline-block w-2 h-2 rounded-full bg-emerald-300 animate-pulse"></span>
            <span>Oferta Promocional Exclusiva de Lançamento: Vagas com desconto especial encerram hoje!</span>
        </div>
    </div>

    <!-- CABEÇALHO -->
    <header class="sticky top-0 z-50 glass-card border-b border-slate-200/60 transition-all duration-300">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 h-16 flex items-center justify-between">
            <div class="flex items-center gap-2.5">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-600 to-teal-400 flex items-center justify-center text-white shadow-md shadow-brand-500/20">
                    <i class="fa-solid fa-leaf text-lg"></i>
                </div>
                <span class="text-xl font-bold tracking-tight text-slate-900">Emagreça<span class="text-brand-600">Online</span></span>
            </div>
            <a href="#oferta" class="bg-slate-900 hover:bg-slate-800 text-white text-sm font-semibold px-5 py-2.5 rounded-full transition-all duration-200 shadow-sm hover:shadow">
                Quero o Meu Acesso
            </a>
        </div>
    </header>

    <!-- 1. HERO SECTION -->
    <section class="gradient-bg pt-12 pb-20 px-4 sm:px-6 relative overflow-hidden">
        <div class="max-w-5xl mx-auto text-center">
            
            <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-emerald-100/80 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-semibold mb-6">
                <i class="fa-solid fa-sparkles text-brand-600"></i> Método Prático e 100% Sustentável
            </div>

            <h1 class="text-3xl sm:text-5xl lg:text-6xl font-extrabold text-slate-950 tracking-tight leading-tight sm:leading-tight mb-6">
                Emagreça de forma definitiva <br class="hidden sm:inline">
                <span class="bg-clip-text text-transparent bg-gradient-to-r from-brand-600 via-teal-600 to-emerald-500">
                    sem dietas radicais e sem efeito sanfona
                </span>
            </h1>

            <p class="text-base sm:text-lg text-slate-600 max-w-2xl mx-auto mb-8 font-normal leading-relaxed">
                Descubra o aplicativo e guia digital que ensina você a queimar gordura de maneira natural, mantendo sua rotina leve e sem abrir mão de comer o que gosta.
            </p>

            <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-10">
                <a href="#oferta" class="w-full sm:w-auto inline-flex items-center justify-center gap-3 bg-brand-600 hover:bg-brand-700 text-white text-base font-bold px-8 py-4 rounded-full shadow-lg shadow-brand-600/30 transition-all duration-200 hover:-translate-y-0.5">
                    <span>COMEÇAR MINHA TRANSFORMAÇÃO</span>
                    <i class="fa-solid fa-arrow-right"></i>
                </a>
            </div>

            <div class="flex items-center justify-center gap-6 text-xs text-slate-500">
                <div class="flex items-center gap-1.5">
                    <i class="fa-solid fa-shield-halved text-brand-600"></i> 7 Dias de Garantia
                </div>
                <div class="flex items-center gap-1.5">
                    <i class="fa-solid fa-bolt text-brand-600"></i> Acesso Imediato
                </div>
                <div class="flex items-center gap-1.5">
                    <i class="fa-solid fa-circle-check text-brand-600"></i> Plataforma Segura
                </div>
            </div>

            <!-- MOCKUP VISUAL DO APLICATIVO -->
            <div class="mt-14 max-w-3xl mx-auto relative">
                <div class="bg-gradient-to-b from-slate-900 to-slate-950 p-4 sm:p-6 rounded-3xl shadow-2xl border border-slate-800 text-left">
                    <div class="flex items-center justify-between border-b border-slate-800 pb-4 mb-5">
                        <div class="flex items-center gap-3">
                            <div class="w-3 h-3 rounded-full bg-rose-500"></div>
                            <div class="w-3 h-3 rounded-full bg-amber-500"></div>
                            <div class="w-3 h-3 rounded-full bg-emerald-500"></div>
                        </div>
                        <span class="text-xs text-slate-400 font-mono">app.emagrecaonline.com</span>
                        <div class="w-10"></div>
                    </div>
                    
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <div class="bg-slate-800/60 rounded-xl p-4 border border-slate-700/50">
                            <span class="text-xs text-slate-400 uppercase font-semibold">Meta Diária</span>
                            <p class="text-xl font-bold text-white mt-1">-500 kcal</p>
                            <div class="w-full bg-slate-700 h-2 rounded-full mt-3 overflow-hidden">
                                <div class="bg-brand-500 h-full w-4/5 rounded-full"></div>
                            </div>
                        </div>
                        <div class="bg-slate-800/60 rounded-xl p-4 border border-slate-700/50">
                            <span class="text-xs text-slate-400 uppercase font-semibold">Cardápio do Dia</span>
                            <p class="text-lg font-bold text-white mt-1">Prático & Saboroso</p>
                            <span class="text-xs text-emerald-400 font-medium">100% descomplicado</span>
                        </div>
                        <div class="bg-slate-800/60 rounded-xl p-4 border border-slate-700/50">
                            <span class="text-xs text-slate-400 uppercase font-semibold">Progresso</span>
                            <p class="text-lg font-bold text-white mt-1">Constante</p>
                            <span class="text-xs text-emerald-400 font-medium">+4.200 transformações</span>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- 2. IDENTIFICAÇÃO DAS DORES -->
    <section class="py-16 bg-white border-y border-slate-200/80 px-4 sm:px-6">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 mb-3">
                    Você já se sentiu preso em algum desses ciclos?
                </h2>
                <p class="text-slate-600 text-sm sm:text-base">
                    Emagrecer não precisa ser sinônimo de passar fome ou viver frustrado.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                <div class="p-5 rounded-2xl bg-rose-50/50 border border-rose-100 flex items-start gap-4">
                    <div class="w-10 h-10 rounded-xl bg-rose-100 text-rose-600 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-arrows-rotate"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Efeito Sanfona Contínuo</h3>
                        <p class="text-sm text-slate-600">Perde peso rápido cortando tudo, mas recupera o dobro assim que volta à rotina normal.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl bg-rose-50/50 border border-rose-100 flex items-start gap-4">
                    <div class="w-10 h-10 rounded-xl bg-rose-100 text-rose-600 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-clock"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Falta de Tempo para Cozinhar</h3>
                        <p class="text-sm text-slate-600">Dietas com ingredientes caros e preparos complexos que não cabem no dia a dia corrido.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl bg-rose-50/50 border border-rose-100 flex items-start gap-4">
                    <div class="w-10 h-10 rounded-xl bg-rose-100 text-rose-600 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-battery-quarter"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Cansaço e Falta de Energia</h3>
                        <p class="text-sm text-slate-600">Sensação constante de fraqueza, irritabilidade e desânimo provocados por restrições extremas.</p>
                    </div>
                </div>

                <div class="p-5 rounded-2xl bg-rose-50/50 border border-rose-100 flex items-start gap-4">
                    <div class="w-10 h-10 rounded-xl bg-rose-100 text-rose-600 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-circle-xmark"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Desistir na Segunda Semana</h3>
                        <p class="text-sm text-slate-600">Falta de clareza e de um método passo a passo que se adapte à sua vida real.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. A SOLUÇÃO & BENEFÍCIOS -->
    <section class="py-20 px-4 sm:px-6">
        <div class="max-w-5xl mx-auto">
            <div class="text-center max-w-2xl mx-auto mb-14">
                <span class="text-xs uppercase font-bold text-brand-600 tracking-wider">A Solução Prática</span>
                <h2 class="text-3xl font-extrabold text-slate-950 mt-1">Como o Emagreça Online Funciona</h2>
                <p class="text-slate-600 mt-2 text-sm sm:text-base">Um ecossistema planejado para gerar resultados reais sem complicações.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="p-6 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 rounded-xl bg-emerald-50 text-brand-600 flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-utensils"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900 mb-2">Cardápios Acessíveis</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Refeições elaboradas com comida de verdade, práticas e com ingredientes simples que você já tem em casa.
                    </p>
                </div>

                <div class="p-6 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 rounded-xl bg-emerald-50 text-brand-600 flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-person-walking"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900 mb-2">Treinos Rápidos</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Rotinas de 15 a 20 minutos que podem ser feitas na sala de casa, sem exigir nenhum tipo de aparelho caro.
                    </p>
                </div>

                <div class="p-6 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-md transition-shadow">
                    <div class="w-12 h-12 rounded-xl bg-emerald-50 text-brand-600 flex items-center justify-center text-xl mb-4">
                        <i class="fa-solid fa-mobile-screen"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900 mb-2">Acesso Direto no Celular</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Consulte seu planejamento, metas e receitas onde e quando quiser, de maneira limpa, intuitiva e direta.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. PROVA SOCIAL / DEPOIMENTOS -->
    <section class="py-16 bg-slate-900 text-white px-4 sm:px-6">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-12">
                <span class="text-xs uppercase font-bold text-brand-400 tracking-wider">Histórias Reais</span>
                <h2 class="text-2xl sm:text-3xl font-extrabold mt-1">Quem experimentou, transformou a rotina</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-slate-800/70 p-6 rounded-2xl border border-slate-700">
                    <div class="flex text-amber-400 text-xs mb-3">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-slate-300 text-sm italic mb-4">
                        "O melhor do aplicativo é não ter que passar fome. Consegui eliminar 7kg em 6 semanas apenas organizando as refeições certas."
                    </p>
                    <div class="font-bold text-sm text-white">Juliana M.</div>
                    <div class="text-xs text-brand-400">-7 kg eliminados</div>
                </div>

                <div class="bg-slate-800/70 p-6 rounded-2xl border border-slate-700">
                    <div class="flex text-amber-400 text-xs mb-3">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-slate-300 text-sm italic mb-4">
                        "Prático demais. Não tenho tempo para preparar pratos difíceis, e as sugestões de refeições rápidas salvaram meus dias."
                    </p>
                    <div class="font-bold text-sm text-white">Ricardo S.</div>
                    <div class="text-xs text-brand-400">-5,5 kg eliminados</div>
                </div>

                <div class="bg-slate-800/70 p-6 rounded-2xl border border-slate-700">
                    <div class="flex text-amber-400 text-xs mb-3">
                        <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                    </div>
                    <p class="text-slate-300 text-sm italic mb-4">
                        "Já tentei vários métodos antes, mas a clareza e facilidade desse guia foi o que realmente manteve minha constância."
                    </p>
                    <div class="font-bold text-sm text-white">Carla T.</div>
                    <div class="text-xs text-brand-400">-9 kg eliminados</div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. OFERTA ESPECIAL + BÔNUS -->
    <section id="oferta" class="py-20 px-4 sm:px-6">
        <div class="max-w-3xl mx-auto">
            
            <div class="text-center mb-8">
                <span class="text-xs font-bold uppercase text-brand-600 tracking-wider">Acesso Imediato</span>
                <h2 class="text-3xl font-extrabold text-slate-900 mt-1">Garanta o Seu Acesso Promocional</h2>
                <p class="text-slate-600 text-sm">Preço promocional válido apenas nesta página de lançamento.</p>
            </div>

            <div class="bg-white rounded-3xl border-2 border-brand-500 shadow-xl overflow-hidden relative">
                
                <div class="bg-gradient-to-r from-brand-600 to-teal-600 text-white text-center py-2 text-xs font-bold uppercase tracking-wider">
                    Oferta Mais Recomendada
                </div>

                <div class="p-6 sm:p-10">
                    <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center pb-6 border-b border-slate-100 gap-4">
                        <div>
                            <h3 class="text-2xl font-bold text-slate-950">Plano Vitalício Completo</h3>
                            <p class="text-xs text-slate-500 mt-1">Acesso irrestrito a todo o conteúdo e atualizações</p>
                        </div>
                        <div class="text-left sm:text-right">
                            <span class="text-xs text-slate-400 line-through">De R$ 197,00</span>
                            <div class="text-3xl sm:text-4xl font-extrabold text-brand-600">R$ 97,00</div>
                            <span class="text-xs text-slate-500 font-medium">ou em até 12x no cartão</span>
                        </div>
                    </div>

                    <!-- ITENS INCLUSOS -->
                    <div class="py-6 space-y-3.5">
                        <div class="flex items-center gap-3 text-sm text-slate-700">
                            <i class="fa-solid fa-circle-check text-brand-600 text-base"></i>
                            <span>Acesso completo ao Guia & Aplicativo Emagreça Online</span>
                        </div>
                        <div class="flex items-center gap-3 text-sm text-slate-700">
                            <i class="fa-solid fa-circle-check text-brand-600 text-base"></i>
                            <span>Cardápios práticos semanais para café, almoço e jantar</span>
                        </div>
                        <div class="flex items-center gap-3 text-sm text-slate-700">
                            <i class="fa-solid fa-circle-check text-brand-600 text-base"></i>
                            <span>Rotinas de exercícios guiados em casa (15 min/dia)</span>
                        </div>
                        <div class="flex items-center gap-3 text-sm font-semibold text-brand-700 bg-brand-50/60 p-2.5 rounded-xl">
                            <i class="fa-solid fa-gift text-brand-600 text-base"></i>
                            <span>BÔNUS 1: Guia de Doces & Sobremesas Fit Sem Culpa</span>
                        </div>
                        <div class="flex items-center gap-3 text-sm font-semibold text-brand-700 bg-brand-50/60 p-2.5 rounded-xl">
                            <i class="fa-solid fa-gift text-brand-600 text-base"></i>
                            <span>BÔNUS 2: Lista Prática de Compras no Supermercado</span>
                        </div>
                    </div>

                    <!-- BOTÃO DE CHECKOUT -->
                    <!-- Substitua o link 'https://pay.kiwify.com.br/exemplo' pelo seu link oficial gerado na plataforma de pagamento -->
                    <a href="https://pay.kiwify.com.br/exemplo" target="_blank" class="w-full mt-4 flex items-center justify-center gap-2 bg-brand-600 hover:bg-brand-700 text-white font-bold text-base sm:text-lg py-4 px-6 rounded-2xl shadow-lg shadow-brand-600/30 transition-all hover:scale-[1.01]">
                        <span>QUERO EMAGRECER AGORA</span>
                        <i class="fa-solid fa-lock text-sm"></i>
                    </a>

                    <div class="mt-4 flex items-center justify-center gap-4 text-xs text-slate-400">
                        <span><i class="fa-solid fa-lock"></i> Compra 100% Criptografada</span>
                        <span>•</span>
                        <span>Pagamento via PIX ou Cartão</span>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- 6. GARANTIA INCONDICIONAL -->
    <section class="pb-16 px-4 sm:px-6">
        <div class="max-w-2xl mx-auto p-6 sm:p-8 rounded-2xl bg-white border border-slate-200 text-center flex flex-col items-center">
            <div class="w-16 h-16 rounded-full bg-emerald-100 text-brand-700 flex items-center justify-center text-2xl mb-4">
                <i class="fa-solid fa-award"></i>
            </div>
            <h3 class="text-xl font-bold text-slate-900 mb-2">Garantia Blindada de 7 Dias</h3>
            <p class="text-sm text-slate-600 leading-relaxed">
                Você tem 7 dias completos para testar todo o conteúdo. Se dentro desse período você achar que o método não é para você, basta pedir o reembolso com um único clique na plataforma e 100% do seu dinheiro será devolvido, sem burocracia.
            </p>
        </div>
    </section>

    <!-- RODAPÉ COMPATÍVEL COM EXIGÊNCIAS DE PLATAFORMAS -->
    <footer class="bg-slate-950 text-slate-500 py-12 px-4 sm:px-6 text-xs border-t border-slate-800">
        <div class="max-w-5xl mx-auto flex flex-col items-center text-center gap-4">
            <div class="text-slate-300 font-bold text-base">Emagreça Online</div>
            <p class="max-w-2xl">
                Aviso Legal: Os resultados podem variar de pessoa para pessoa. Este produto não substitui o acompanhamento e diagnóstico médico profissional. Consulte sempre seu médico ou nutricionista antes de iniciar qualquer mudança em sua rotina física ou alimentar.
            </p>
            <div class="flex gap-4 text-slate-400 mt-2">
                <a href="#" class="hover:underline">Termos de Uso</a>
                <span>•</span>
                <a href="#" class="hover:underline">Políticas de Privacidade</a>
            </div>
            <p class="mt-2 text-slate-600">© 2026 Emagreça Online. Todos os direitos reservados.</p>
        </div>
    </footer>

</body>
</html>
