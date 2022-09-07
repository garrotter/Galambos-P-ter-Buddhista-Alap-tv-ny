<template>
    <div class="navbar">
        <nav class="container">
            <section>
                <input type="checkbox" name="nav_checkbox" id="nav_checkbox" class="nav_checkbox">
                <div class="nav_toggle">
                    <label for="nav_checkbox">
                        <span class="menu">&#9776;</span>
                        <span class="close">&#9932;</span>
                    </label>
                </div>
                <ul class="nav_menu">
                    <li>
                        <NuxtLink to="/">Főoldal</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/peter">Galambos Péter</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/events">Események</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/actualities">Aktualitások</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/contact">Kapcsolat</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/gallery">Galéria</NuxtLink>
                    </li>
                </ul>
            </section>
        </nav>
    </div>
</template>