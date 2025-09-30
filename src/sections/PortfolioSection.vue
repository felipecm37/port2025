<template>
    <!-- Portfolio section start -->
    <section id="portfolio-section" class="backmain px-4 lg:px-8 py-16  relative">
        <!-- Text wrapper start -->
        <div class="flex gap-8 flex-col md:flex-row">
            <!-- Main text start -->
            <h3 class="uppercase text-3xl mb-4 font-semibold ">
                PORTFOLIO
            </h3>
            <p class="capitalize xl:w-1/2 text-stone-500 mb-8">
                Projetos 2025.
            </p>
            <!-- Main text end -->
        </div>
        <!-- Text wrapper end -->

        <!-- Images grid start -->
        <div class="portfolio-grid">
            <!-- Mobile view - Grid layout -->
            <div class="grid grid-cols-2 gap-4 md:hidden">
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio1.jpg" alt="Búzios Website" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Búzios Website</b><br>Landing page turística</span>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio2.jpg" alt="Ipanema Papéis" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Ipanema Papéis</b><br>E-commerce Prestashop</span>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio3.jpg" alt="Room Design" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Room Design</b><br>Portfolio de design</span>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio7.jpg" alt="B-Store" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>B-Store</b><br>Template e-commerce</span>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio8.jpg" alt="Landing Bike" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Landing Bike</b><br>Site de bicicletas</span>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio9.jpg" alt="Landing Page" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Landing Page</b><br>Design moderno</span>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio11.jpg" alt="Portfolio 11" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Sunset Grande Rio</b><br>Event landing page</span>
                    </div>
                </div>
                <div class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio12.jpg" alt="Portfolio 12" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Novo Projeto</b><br>Descrição do projeto</span>
                    </div>
                </div>
            </div>

            <!-- Desktop view - Grid layout -->
            <div class="hidden md:grid md:grid-cols-4 lg:grid-cols-4 xl:grid-cols-4 gap-6">
                <a href="https://felipecm37.github.io/buzios.github.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio1.jpg" alt="Búzios Website" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Búzios Website</b>
                            <br>
                            Criação de uma landing page.
                            HTML - Bootstrap - CSS - JavaScript
                        </span>
                    </div>
                </a>
                <a href="https://felipecm37.github.io/ipanemapapeis.git.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio2.jpg" alt="Ipanema Papéis" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Ipanema Papéis</b>
                            <br>
                            E-commerce completo desenvolvido em Prestashop
                            <br>
                            <small>Prestashop • PHP • MySQL</small>
                        </span>
                    </div>
                </a>
                <a href="https://felipecm37.github.io/room.github.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio3.jpg" alt="Room Design" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Room Design</b>
                            <br>
                            Portfolio de design de interiores moderno
                            <br>
                            <small>HTML5 • CSS3 • JavaScript</small>
                        </span>
                    </div>
                </a>
                <a href="https://felipecm37.github.io/bstore.git.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio7.jpg" alt="B-Store" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>B-Store</b>
                            <br>
                            Template completo para e-commerce
                            <br>
                            <small>HTML5 • CSS3 • JavaScript • Bootstrap</small>
                        </span>
                    </div>
                </a>
                <a href="https://felipecm37.github.io/landingbike.git.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio8.jpg" alt="Landing Bike" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Landing Bike</b>
                            <br>
                            Landing page para loja de bicicletas
                            <br>
                            <small>Bootstrap • CSS3 • HTML5</small>
                        </span>
                    </div>
                </a>
                <a href="https://felipecm37.github.io/villasagencia.git.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio9.jpg" alt="Landing Page" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Landing Page</b>
                            <br>
                            Projeto para agência de viagens.
                            <br>
                            <small>HTML5 • CSS3 • JavaScript</small>
                        </span>
                    </div>
                </a>
                <a href="https://felipecm37.github.io/sunset_granderio.git.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio11.jpg" alt="Sunset Grande Rio" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>Sunset Grande Rio</b>
                            <br>
                            Landing page para evento musical
                            <br>
                            <small>HTML5 • CSS3 • Bootstrap • JavaScript</small>
                        </span>
                    </div>
                </a>
                <a href="https://felipecm37.github.io/ccca_projeto.git.io/" target="_blank" class="portfolio-item">
                    <img src="@/assets/portfolio/portfolio12.jpg" alt="Novo Projeto" class="rounded-xl">
                    <div class="portfolio-caption">
                        <span><b>CCAA</b>
                            <br>
                            Este projeto demonstra a implementação de um website educacional completo
                            <br>
                            <small>HTML5 • CSS3 • JavaScript</small>
                        </span>
                    </div>
                </a>
            </div>
        </div>
        <!-- Images grid end -->

        <!-- Circle start -->
        <div class="bg-neutral-300 h-64 w-64 rounded-full absolute top-0 left-0 mt-16 -z-20"></div>
        <!-- Circle end -->
    </section>
    <!-- Portfolio section end -->
</template>

<script>
export default {

}
</script>

<style>
.backmain {
    background: linear-gradient(132deg, #000000, #00ff00, #36bfff, #f9fd0c, #2e800d, #ffffff);
    background-size: 400% 400%;
    animation: BackgroundGradient 20s ease infinite;
}

@keyframes BackgroundGradient {
    0% {
        background-position: 0% 50%;
    }

    50% {
        background-position: 100% 50%;
    }

    100% {
        background-position: 0% 50%;
    }
}

.portfolio-item {
    position: relative;
    overflow: hidden;
    border-radius: 0.75rem;
    display: block;
    transition: transform 0.3s ease;
    height: 280px;
    /* Fixed height for consistent alignment */
}

.portfolio-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
    /* Align images to top to show headers */
    transition: all 0.3s ease;
}

/* Ensure mobile items don't have fixed height */
@media (max-width: 767px) {
    .portfolio-item {
        height: auto;
    }
}

.portfolio-item:hover {
    transform: scale(1.05);
}

.portfolio-caption {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(0, 0, 0, 0.9);
    backdrop-filter: blur(10px);
    color: #ffffff;
    padding: 12px 16px;
    transform: translateY(100%);
    transition: transform 0.3s ease;
    border-radius: 0 0 0.75rem 0.75rem;
}

.portfolio-caption span {
    font-weight: 600;
    font-size: 0.875rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    color: #ffffff;
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.8);
}

.portfolio-caption small {
    color: #e0e0e0;
    font-weight: 400;
    text-transform: none;
    letter-spacing: 0.25px;
    text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.8);
}

.portfolio-item:hover .portfolio-caption {
    transform: translateY(0);
}

.portfolio-item:hover img {
    filter: brightness(0.8);
}
</style>