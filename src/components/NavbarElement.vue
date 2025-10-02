<template>
	<!-- Navbar start -->
	<nav class="w-screen fixed bg-opacity-90 bg-white dark:bg-gray-900 dark:bg-opacity-90 p-4 lg:px-20 flex justify-between z-50 transition-colors duration-300">
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
			<i class="fa-solid fa-bars text-2xl dark:text-white"></i>
		</button>
		<!-- Toggler end -->

		<!-- Menu content start -->
		<div class="absolute left-0 right-0 translate-y-16 bg-opacity-90 bg-white dark:bg-gray-900 dark:bg-opacity-90 md:bg-none md:bg-opacity-0 shadow dark:shadow-gray-700 hidden md:flex flex-col gap-4 items-center p-4 md:flex-row md:static md:shadow-none md:translate-y-0 transition-colors duration-300"
			role="menu" aria-expanded="false">
			<!-- Links start -->
			<a href="#" role="menuitem">
				<p class="mx-4 dark:text-white hover:text-blue-500 dark:hover:text-blue-400 transition-colors">Home</p>
			</a>

			<a href="#about-section" role="menuitem">
				<p class="mx-4 dark:text-white hover:text-blue-500 dark:hover:text-blue-400 transition-colors">Apresentação</p>
			</a>

			<a href="#pelife-section" role="menuitem">
				<p class="mx-4 dark:text-white hover:text-blue-500 dark:hover:text-blue-400 transition-colors">Experiência</p>
			</a>

			<a href="#portfolio-section" role="menuitem">
				<p class="mx-4 dark:text-white hover:text-blue-500 dark:hover:text-blue-400 transition-colors">Portfolio</p>
			</a>

			<a href="#cursos-section" role="menuitem">
				<p class="mx-4 dark:text-white hover:text-blue-500 dark:hover:text-blue-400 transition-colors">Formação</p>
			</a>

			<a href="#contact-section">
				<button class="btn dark:bg-blue-600 dark:hover:bg-blue-700" role="menuitem">
					Contato
				</button>
			</a>

			<!-- Theme Toggle start -->
			<button @click="toggleTheme" class="p-2 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors duration-300">
				<i :class="isDark ? 'fa-solid fa-sun text-yellow-500' : 'fa-solid fa-moon text-gray-600 dark:text-gray-300'" class="text-xl"></i>
			</button>
			<!-- Theme Toggle end -->
			<!-- Links end -->
		</div>
		<!-- Menu content end -->
	</nav>
	<!-- Navbar end -->
</template>

<script>

export default {
	data() {
		return {
			isDark: false
		}
	},
	mounted() {
		// Check for saved theme preference or default to light mode
		const savedTheme = localStorage.getItem('theme');
		if (savedTheme) {
			this.isDark = savedTheme === 'dark';
		} else {
			// Check system preference
			this.isDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
		}
		this.applyTheme();
	},
	methods: {
		// Toggle navbar mode 
		navToggle() {
			let menu = document.querySelector("[role='menu']");
			let isExpanded = menu.getAttribute('aria-expanded');
			menu.setAttribute('aria-expanded', !isExpanded);
			menu.classList.toggle('hidden');
			menu.classList.toggle('flex');
		},
		// Toggle theme
		toggleTheme() {
			this.isDark = !this.isDark;
			this.applyTheme();
			localStorage.setItem('theme', this.isDark ? 'dark' : 'light');
		},
		// Apply theme to document
		applyTheme() {
			if (this.isDark) {
				document.documentElement.classList.add('dark');
			} else {
				document.documentElement.classList.remove('dark');
			}
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

/* Dark theme styles */
:root.dark .sub_pelife {
	color: #ffffff;
}
</style>