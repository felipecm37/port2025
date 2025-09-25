<template>
    <!-- Services section start -->
    <section id="services-section" class="px-12 lg:px-32 py-10 relative overflow-hidden">
        <!-- Text wrapper start -->
        <div class="flex gap-8 flex-col md:flex-row">
            <!-- Main text start -->
            <!-- Social links start -->
            <div class="flex mt-3 gap-5 keyboard">
                <i class="fa-brands fa-html5 socialIcon2 key"></i>
                <i class="fa-brands fa-css3 socialIcon2 key"></i>
                <i class="fa-brands fa-js socialIcon2 key"></i>
                <i class="fa-brands fa-bootstrap socialIcon2 key"></i>
                <i class="fa-brands fa-vuejs socialIcon2 key"></i>
                <i class="fa-brands fa-wordpress socialIcon2 key"></i>
                <i class="fa-brands fa-magento socialIcon2 key"></i>
                <i class="fa-brands fa-shopify socialIcon2 key"></i>
            </div>
            <!-- Social links end -->
            <!-- Main text end -->
        </div>
        <!-- Text wrapper end -->

    </section>
    <!-- Services section end -->
</template>

<script>
export default {

}
</script>

<style>
.mt-3 {
    margin-top: 0;
}

.key {
    font-size: 7vw;
    display: inline-block;
    letter-spacing: -1vw;
    transition: transform 0.2s;
}



@keyframes pressDown1 {

    30%,
    40%,
    100% {
        transform: translateY(0);
    }

    35% {
        transform: translateY(10px);
    }
}

@keyframes pressDown2 {

    70%,
    80%,
    100% {
        transform: translateY(0);
    }

    75% {
        transform: translateY(10px);
    }
}

@keyframes pressDown3 {

    30%,
    40%,
    100% {
        transform: translateY(0);
    }

    35% {
        transform: translateY(10px);
    }
}

@keyframes pressDown4 {

    40%,
    50%,
    100% {
        transform: translateY(0);
    }

    45% {
        transform: translateY(10px);
    }
}

@keyframes pressDown5 {

    20%,
    30%,
    100% {
        transform: translateY(0);
    }

    25% {
        transform: translateY(10px);
    }
}

@keyframes pressDown6 {

    60%,
    70%,
    100% {
        transform: translateY(0);
    }

    65% {
        transform: translateY(10px);
    }
}

@keyframes pressDown7 {

    10%,
    20%,
    100% {
        transform: translateY(0);
    }

    15% {
        transform: translateY(10px);
    }
}

@keyframes pressDown8 {

    35%,
    45%,
    100% {
        transform: translateY(0);
    }

    40% {
        transform: translateY(10px);
    }
}



.key:nth-child(1) {
    animation: pressDown1 2s infinite;
}

.key:nth-child(2) {
    animation: pressDown2 3s infinite;
}

.key:nth-child(3) {
    animation: pressDown3 4s infinite;
}

.key:nth-child(4) {
    animation: pressDown4 2.5s infinite;
}

.key:nth-child(5) {
    animation: pressDown5 2.5s infinite;
}

.key:nth-child(6) {
    animation: pressDown6 3.5s infinite;
}

.key:nth-child(7) {
    animation: pressDown7 2.2s infinite;
}

.key:nth-child(8) {
    animation: pressDown8 3.2s infinite;
}
</style>