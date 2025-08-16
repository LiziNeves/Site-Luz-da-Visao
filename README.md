# Site-Luz-da-Visao
Site organizacional ong
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luz da Visão - Transformando Vidas</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8fafc;
        }
        
        .hero-gradient {
            background: linear-gradient(120deg, #1e3a8a 0%, #0f172a 100%);
        }
        
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
        }
        
        .transition-all {
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="text-gray-800">
    <!-- Barra de Navegação -->
    <nav class="bg-blue-900 text-white shadow-lg">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <img src="https://placehold.co/50x50" alt="Logo Luz da Visão - Ícone de olho estilizado em branco sobre fundo azul" class="h-12" />
                <span class="text-xl font-bold">Luz da Visão</span>
            </div>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="hover:text-blue-200 transition-all">Início</a>
                <a href="#about" class="hover:text-blue-200 transition-all">Sobre Nós</a>
                <a href="#projects" class="hover:text-blue-200 transition-all">Projetos</a>
                <a href="#partners" class="hover:text-blue-200 transition-all">Parceiros</a>
                <a href="#contact" class="hover:text-blue-200 transition-all">Contato</a>
            </div>
            <button class="md:hidden focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>
        </div>
    </nav>

    <!-- Seção Hero -->
    <section id="home" class="hero-gradient text-white py-20">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-6">Transformando vidas através da educação e inclusão</h1>
                <p class="text-xl mb-8">Acreditamos que toda criança merece oportunidades para brilhar e desenvolver seu potencial.</p>
                <div class="flex space-x-4">
                    <a href="#donate" class="bg-white text-blue-900 px-6 py-3 rounded-lg font-bold hover:bg-blue-100 transition-all">Doe Agora</a>
                    <a href="#volunteer" class="border-2 border-white text-white px-6 py-3 rounded-lg font-bold hover:bg-white hover:text-blue-900 transition-all">Seja Voluntário</a>
                </div>
            </div>
            <div class="md:w-1/2">
                <img src="https://placehold.co/600x400" alt="Crianças sorrindo em sala de aula com materiais educacionais coloridos, professora ajudando alunos" class="rounded-lg shadow-2xl" />
            </div>
        </div>
    </section>

    <!-- Seção Sobre Nós -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-blue-900 mb-4">Nossa Missão</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
            </div>
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-10">
                    <img src="https://placehold.co/500x300" alt="Equipe da ONG em reunião de planejamento com quadros brancos cheios de post-its coloridos" class="rounded-lg shadow-lg" />
                </div>
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-bold text-blue-900 mb-6">Quem Somos</h3>
                    <p class="mb-6">A Luz da Visão é uma organização sem fins lucrativos fundada em 2020 com o propósito de promover a inclusão social e educacional de crianças e adolescentes em situação de vulnerabilidade.</p>
                    <p class="mb-6">Nossa atuação se baseia em três pilares fundamentais: educação de qualidade, desenvolvimento de habilidades socioemocionais e inclusão esportiva.</p>
                    <div class="flex items-center space-x-2 mb-4">
                        <div class="w-2 h-2 bg-blue-600 rounded-full"></div>
                        <span>+2.500 crianças impactadas</span>
                    </div>
                    <div class="flex items-center space-x-2 mb-4">
                        <div class="w-2 h-2 bg-blue-600 rounded-full"></div>
                        <span>15 comunidades atendidas</span>
                    </div>
                    <div class="flex items-center space-x-2">
                        <div class="w-2 h-2 bg-blue-600 rounded-full"></div>
                        <span>50 voluntários ativos</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Nossos Projetos -->
    <section id="projects" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-blue-900 mb-4">Nossos Projetos</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Desenvolvemos programas sociais que transformam realidades e criam oportunidades para crianças e adolescentes.</p>
                <div class="w-20 h-1 bg-blue-600 mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white rounded-xl shadow-lg overflow-hidden card-hover transition-all">
                    <img src="https://placehold.co/600x400" alt="Crianças em sala de aula com tablets, aprendendo programação em computadores" class="w-full h-48 object-cover" />
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-blue-900 mb-2">Educação Digital</h3>
                        <p class="text-gray-600 mb-4">Levar tecnologia e inovação para as comunidades, capacitando crianças e adolescentes com habilidades do século XXI.</p>
                        <a href="#" class="text-blue-600 font-semibold hover:text-blue-800 transition-all">Saiba mais →</a>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl shadow-lg overflow-hidden card-hover transition-all">
                    <img src="https://placehold.co/600x400" alt="Jogo de futebol infantil com diversas crianças de diferentes origens se divertindo" class="w-full h-48 object-cover" />
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-blue-900 mb-2">Esporte para Todos</h3>
                        <p class="text-gray-600 mb-4">Promovendo inclusão social e valores como trabalho em equipe através de atividades esportivas.</p>
                        <a href="#" class="text-blue-600 font-semibold hover:text-blue-800 transition-all">Saiba mais →</a>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl shadow-lg overflow-hidden card-hover transition-all">
                    <img src="https://placehold.co/600x400" alt="Crianças plantando mudas em horta comunitária, aprendendo sobre sustentabilidade" class="w-full h-48 object-cover" />
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-blue-900 mb-2">Crescendo Verde</h3>
                        <p class="text-gray-600 mb-4">Educação ambiental e cultivo sustentável formando cidadãos conscientes de seu papel na sociedade.</p>
                        <a href="#" class="text-blue-600 font-semibold hover:text-blue-800 transition-all">Saiba mais →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Impacto -->
    <section class="py-20 hero-gradient text-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold mb-4">Nosso Impacto</h2>
                <p class="text-xl max-w-2xl mx-auto">Acompanhe os números que refletem nossa dedicação e o poder da comunidade unida por uma causa.</p>
                <div class="w-20 h-1 bg-white mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 text-center">
                <div class="p-6 bg-blue-800 bg-opacity-30 rounded-xl">
                    <div class="text-4xl font-bold mb-2">2.5K+</div>
                    <div>Crianças beneficiadas</div>
                </div>
                <div class="p-6 bg-blue-800 bg-opacity-30 rounded-xl">
                    <div class="text-4xl font-bold mb-2">120+</div>
                    <div>Atividades realizadas</div>
                </div>
                <div class="p-6 bg-blue-800 bg-opacity-30 rounded-xl">
                    <div class="text-4xl font-bold mb-2">15</div>
                    <div>Comunidades atendidas</div>
                </div>
                <div class="p-6 bg-blue-800 bg-opacity-30 rounded-xl">
                    <div class="text-4xl font-bold mb-2">50+</div>
                    <div>Voluntários ativos</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Parceiros -->
    <section id="partners" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-blue-900 mb-4">Nossos Parceiros</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Juntos somos mais fortes! Conheça as organizações que acreditam no nosso trabalho.</p>
                <div class="w-20 h-1 bg-blue-600 mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 items-center">
                <div class="flex justify-center">
                    <img src="https://placehold.co/150x80" alt="Logo empresa parceira - Educação" class="h-16 object-contain" />
                </div>
                <div class="flex justify-center">
                    <img src="https://placehold.co/150x80" alt="Logo empresa parceira - Tecnologia" class="h-16 object-contain" />
                </div>
                <div class="flex justify-center">
                    <img src="https://placehold.co/150x80" alt="Logo empresa parceira - Esportes" class="h-16 object-contain" />
                </div>
                <div class="flex justify-center">
                    <img src="https://placehold.co/150x80" alt="Logo empresa parceira - Responsabilidade Social" class="h-16 object-contain" />
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Doe Agora -->
    <section id="donate" class="py-20 bg-blue-50">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto bg-white rounded-xl shadow-lg overflow-hidden">
                <div class="md:flex">
                    <div class="md:w-1/2 bg-blue-900 text-white p-10">
                        <h2 class="text-3xl font-bold mb-6">Sua doação faz a diferença</h2>
                        <p class="mb-6">Com apenas R$ 50 por mês, você proporciona materiais escolares para uma criança durante um ano inteiro.</p>
                        <div class="space-y-4">
                            <div class="flex items-center">
                                <div class="w-2 h-2 bg-white rounded-full mr-2"></div>
                                
