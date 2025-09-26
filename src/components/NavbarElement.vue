<template>
	<!-- Navbar start -->
	<nav class="w-screen fixed bg-opacity-90 bg-white p-4 lg:px-20 flex justify-between z-50">
		<!-- Logo start -->
		<div id="top" class="h-full w-full flex flex-col justify-center">
			<p class="pelife animate__animated animate__flipInY animate__delay-1s tracking-widest font-semibold">Felipe
				Caldas</p>
			<p class="sub_pelife animate__animated animate__fadeInUp Bigtracking-widest font-light">Desenvolvedor
				front-end UI/UX
			</p>
		</div>
		<!-- Logo end -->

		<!-- Toggler start -->
		<button role="menubar" class="md:hidden" @click="navToggle()">
			<i class="fa-solid fa-bars text-2xl"></i>
		</button>
		<!-- Toggler end -->

		<!-- Menu content start -->
		<div class="absolute left-0 right-0 translate-y-16 bg-opacity-90 bg-white md:bg-none md:bg-opacity-0 shadow hidden md:flex flex-col gap-4 items-center p-4 md:flex-row md:static md:shadow-none md:translate-y-0"
			role="menu" aria-expanded="false">
			<!-- Links start -->
			<a href="#" role="menuitem">
				<p class="mx-4">Home</p>
			</a>

			<a href="#about-section" role="menuitem">
				<p class="mx-4">Apresentação</p>
			</a>

			<a href="#pelife-section" role="menuitem">
				<p class="mx-4">Currículo</p>
			</a>

			<a href="#portfolio-section" role="menuitem">
				<p class="mx-4">Portfolio</p>
			</a>

			<a href="#cursos-section" role="menuitem">
				<p class="mx-4">Formação</p>
			</a>

			<a href="#contact-section">
				<button class="btn" role="menuitem">
					Contato
				</button>
			</a>
			<!-- Links end -->
		</div>
		<!-- Menu content end -->
	</nav>
	<!-- Navbar end -->
</template>

<script>

export default {
	methods: {
		// Toogle navbar mode 
		navToggle() {
			let menu = document.querySelector("[role='menu']");
			let isExpanded = menu.getAttribute('aria-expanded');
			menu.setAttribute('aria-expanded', !isExpanded);
			menu.classList.toggle('hidden');
			menu.classList.toggle('flex');
		}
	}
}
</script>

<style>
.pelife {
	color: #36bfff;
	font-size: 22px;
}

.sub_pelife {
	color: #000000;
	font-size: 18px;
}
</style>