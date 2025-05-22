<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buffet Sr. Wilson - Sua Experiência Gastronômica</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .section-title {
            position: relative;
            display: inline-block;
            padding-bottom: 0.5rem;
            margin-bottom: 2rem;
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50%;
            height: 4px;
            background-color: #f59e0b; /* amber-500 */
            border-radius: 2px;
        }
        .card {
            background-color: white;
            border-radius: 0.75rem;
            padding: 1.5rem;
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
        }
        .btn-primary {
            background-color: #f59e0b; /* amber-500 */
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            font-weight: 600;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        .btn-primary:hover {
            background-color: #d97706; /* amber-600 */
            transform: translateY(-2px);
        }
        .btn-secondary {
            background-color: #e5e7eb; /* gray-200 */
            color: #4b5563; /* gray-600 */
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            font-weight: 600;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        .btn-secondary:hover {
            background-color: #d1d5db; /* gray-300 */
            transform: translateY(-2px);
        }
        /* Custom scrollbar for better aesthetics */
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9; /* slate-100 */
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1; /* slate-300 */
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8; /* slate-500 */
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body class="bg-stone-100 text-stone-800 min-h-screen flex flex-col">

    <header class="bg-amber-600 text-white shadow-lg py-6">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl font-bold mb-2">Buffet Sr. Wilson</h1>
            <p class="text-xl">Sua Experiência Gastronômica Inesquecível</p>
        </div>
    </header>

    <main class="container mx-auto px-4 py-8 flex-grow">
        <section id="hero" class="text-center mb-12">
            <h2 class="text-3xl font-semibold text-amber-700 mb-4">Transformamos seu evento em uma celebração inesquecível.</h2>
            <p class="text-lg text-stone-700 mb-6 max-w-2xl mx-auto">
                Com anos de experiência e paixão pela culinária, o Buffet Sr. Wilson oferece um serviço completo e personalizado para que cada detalhe do seu evento seja perfeito.
            </p>
            <a href="#contact" class="btn-primary inline-block">Fale Conosco Agora!</a>
        </section>

        <section id="services" class="mb-12">
            <h2 class="text-2xl font-semibold text-stone-700 section-title mx-auto text-center mb-8">Nossos Serviços</h2>
            <p class="text-lg text-stone-700 text-center mb-8 max-w-3xl mx-auto">
                Especializados em criar momentos gastronômicos únicos, adaptamos nossos cardápios e serviços para cada tipo de celebração, garantindo sabor, apresentação e um atendimento impecável.
            </p>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="card text-center">
                    <span class="text-4xl mb-4 block">🎂</span>
                    <h3 class="text-xl font-semibold text-stone-700 mb-2">Aniversários</h3>
                    <p class="text-stone-600">Cardápios festivos e personalizados para todas as idades, do infantil ao adulto, com opções que encantam a todos.</p>
                </div>
                <div class="card text-center">
                    <span class="text-4xl mb-4 block">🎓</span>
                    <h3 class="text-xl font-semibold text-stone-700 mb-2">Formaturas</h3>
                    <p class="text-stone-600">Celebre essa conquista com um buffet à altura, com pratos sofisticados e serviço impecável para formandos e convidados.</p>
                </div>
                <div class="card text-center">
                    <span class="text-4xl mb-4 block">💍</span>
                    <h3 class="text-xl font-semibold text-stone-700 mb-2">Casamentos</h3>
                    <p class="text-stone-600">O dia mais especial merece um menu dos sonhos, com elegância e sabor que marcam a memória dos noivos e seus convidados.</p>
                </div>
                <div class="card text-center">
                    <span class="text-4xl mb-4 block">🏢</span>
                    <h3 class="text-xl font-semibold text-stone-700 mb-2">Eventos Empresariais</h3>
                    <p class="text-stone-600">Serviço profissional e adaptável para coffee breaks, almoços executivos e confraternizações, com pontualidade e discrição.</p>
                </div>
                <div class="card text-center">
                    <span class="text-4xl mb-4 block">👨‍👩‍👧‍👦</span>
                    <h3 class="text-xl font-semibold text-stone-700 mb-2">Celebrações Familiares</h3>
                    <p class="text-stone-600">Reuniões, batizados e outras celebrações com a família e amigos, com a qualidade e o carinho que seu momento merece.</p>
                </div>
                <div class="card text-center">
                    <span class="text-4xl mb-4 block">🍽️</span>
                    <h3 class="text-xl font-semibold text-stone-700 mb-2">Degustação e Consultoria</h3>
                    <p class="text-stone-600">Oferecemos sessões de degustação e consultoria especializada para ajudar na escolha do cardápio perfeito para o seu evento.</p>
                </div>
            </div>
        </section>

        <section id="diferenciais" class="mb-12">
            <h2 class="text-2xl font-semibold text-stone-700 section-title mx-auto text-center mb-8">Nossos Diferenciais</h2>
            <p class="text-lg text-stone-700 text-center mb-8 max-w-3xl mx-auto">
                O que nos torna a escolha ideal para o seu evento:
            </p>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="card flex items-start space-x-4">
                    <span class="text-3xl text-amber-600">✨</span>
                    <div>
                        <h3 class="text-xl font-semibold text-stone-700 mb-1">Atenção ao Detalhe</h3>
                        <p class="text-stone-600">Cuidado minucioso em cada etapa, do planejamento à execução, para garantir a perfeição.</p>
                    </div>
                </div>
                <div class="card flex items-start space-x-4">
                    <span class="text-3xl text-amber-600">🎨</span>
                    <div>
                        <h3 class="text-xl font-semibold text-stone-700 mb-1">Apresentação Impecável</h3>
                        <p class="text-stone-600">Pratos e mesas montados com estética refinada, transformando a gastronomia em arte.</p>
                    </div>
                </div>
                <div class="card flex items-start space-x-4">
                    <span class="text-3xl text-amber-600">😋</span>
                    <div>
                        <h3 class="text-xl font-semibold text-stone-700 mb-1">Sabor Marcante</h3>
                        <p class="text-stone-600">Ingredientes frescos e receitas exclusivas que garantem uma experiência gastronômica memorável.</p>
                    </div>
                </div>
                <div class="card flex items-start space-x-4">
                    <span class="text-3xl text-amber-600">🤝</span>
                    <div>
                        <h3 class="text-xl font-semibold text-stone-700 mb-1">Equipe Profissional</h3>
                        <p class="text-stone-600">Profissionais simpáticos, ágeis e dedicados a garantir o bem-estar de seus convidados.</p>
                    </div>
                </div>
                <div class="card flex items-start space-x-4">
                    <span class="text-3xl text-amber-600">🗓️</span>
                    <div>
                        <h3 class="text-xl font-semibold text-stone-700 mb-1">Planejamento Personalizado</h3>
                        <p class="text-stone-600">Cardápios e serviços adaptados às suas preferências e necessidades específicas do evento.</p>
                    </div>
                </div>
                <div class="card flex items-start space-x-4">
                    <span class="text-3xl text-amber-600">🔄</span>
                    <div>
                        <h3 class="text-xl font-semibold text-stone-700 mb-1">Flexibilidade e Adaptação</h3>
                        <p class="text-stone-600">Nossa capacidade de nos adaptar a diferentes demandas e imprevistos, garantindo a tranquilidade do cliente.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="testimonials" class="mb-12">
            <h2 class="text-2xl font-semibold text-stone-700 section-title mx-auto text-center mb-8">O Que Dizem Nossos Clientes</h2>
            <p class="text-lg text-stone-700 text-center mb-8 max-w-3xl mx-auto">
                A satisfação dos nossos clientes é a nossa maior recompensa. Veja alguns depoimentos:
            </p>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="card">
                    <p class="italic text-stone-600 mb-4">"O Buffet Sr. Wilson superou todas as nossas expectativas! O sabor dos pratos, a apresentação e o profissionalismo da equipe tornaram nosso casamento inesquecível."</p>
                    <p class="font-semibold text-stone-700">- Ana e Pedro S.</p>
                </div>
                <div class="card">
                    <p class="italic text-stone-600 mb-4">"Contratamos para a formatura da minha filha e foi um sucesso absoluto. A flexibilidade e o cuidado com cada detalhe fizeram toda a diferença. Recomendo!"</p>
                    <p class="font-semibold text-stone-700">- Carla R.</p>
                </div>
                <div class="card">
                    <p class="italic text-stone-600 mb-4">"Cada prato era uma obra de arte! O Sr. Wilson e sua equipe são impecáveis, desde o primeiro contato até o final do evento. Fiquei muito feliz com a escolha."</p>
                    <p class="font-semibold text-stone-700">- Mariana F.</p>
                </div>
                <div class="card">
                    <p class="italic text-stone-600 mb-4">"Serviço de altíssima qualidade! A comida estava deliciosa e a equipe muito atenciosa. Meus convidados elogiaram muito. Com certeza farei outros eventos com eles."</p>
                    <p class="font-semibold text-stone-700">- João P.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="text-center mb-12">
            <h2 class="text-2xl font-semibold text-stone-700 section-title mx-auto text-center mb-8">Fale Conosco</h2>
            <p class="text-lg text-stone-700 mb-6 max-w-2xl mx-auto">
                Pronto para planejar seu próximo evento com o Buffet Sr. Wilson? Entre em contato e solicite seu orçamento personalizado!
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="https://wa.me/553496901445" target="_blank" class="btn-primary flex items-center justify-center gap-2">
                    <span class="text-xl">📞</span> WhatsApp
                </a>
                <a href="tel:+553496901445" class="btn-secondary flex items-center justify-center gap-2">
                    <span class="text-xl">📱</span> Ligar Agora
                </a>
                <a href="mailto:contato@buffetsrwilson.com.br" class="btn-secondary flex items-center justify-center gap-2">
                    <span class="text-xl">📧</span> Enviar E-mail
                </a>
            </div>
        </section>
    </main>

    <footer class="bg-stone-800 text-stone-300 text-center py-6 mt-12">
        <p class="text-sm">&copy; <span id="currentYear"></span> Buffet Sr. Wilson. Todos os direitos reservados.</p>
        <p class="text-xs mt-1">Desenvolvido com carinho para suas celebrações.</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            // Smooth scrolling for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });

            // Set current year in footer
            document.getElementById('currentYear').textContent = new Date().getFullYear();
        });
    </script>

</body>
</html>
