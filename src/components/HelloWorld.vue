<script setup lang="ts">
</script>

<template>
    <header>
        <h1>Concepteur développeur d'application</h1>
    </header>

    <section style="display: inline-flex; align-items: center;">
        <img id="img-profile" src="./../../assets/kirito.jpg" alt="Profile"/>
        <h2>Mathieu ROCANCOURT</h2>
    </section>

    <section>
        <h3>Expériences professionnelles</h3>
    </section>

    <div class="ticks"></div>

    <section id="next-steps">
        <div id="social">
            <svg class="icon" aria-hidden="true">
                <use href="/icons.svg#social-icon"></use>
            </svg>
            <h2>Connect with me</h2>
            <ul>
                <li>
                    <a href="https://github.com/MathieuROCANCOURT" target="_blank">
                        <svg class="button-icon" aria-hidden="true">
                            <use href="/icons.svg#github-icon"></use>
                        </svg>
                        GitHub
                    </a>
                </li>
                <li>
                    <a href="https://www.linkedin.com/in/mathieu-rocancourt" target="_blank">
                        <svg class="button-icon" aria-hidden="true">
                            <use href="/icons.svg#linkedin-icon"></use>
                        </svg>
                        LinkedIn
                    </a>
                </li>
            </ul>
        </div>
    </section>

    <div class="ticks"></div>
    <section id="spacer"></section>
</template>
