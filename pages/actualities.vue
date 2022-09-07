<template>
    <div class="container content">
        <section class="flex">
            <div class="right">
                <img src="~/public/img/tea.svg" alt="tea">
            </div>
            <div class="text">
                <h3>Teázás</h3>
                <p>
                    Minden hónap első keddjén 18 órától
                </p>
            </div>
        </section>
        <section class="flex">
            <div class="left">
                <img src="~/public/img/film.svg" alt="film">
            </div>
            <div class="text">
                <h3>Filmvetítés a Mester kedvenceiből</h3>
                <p>
                    Minden hónap utolsó keddjén 18 órától
                </p>
            </div>
        </section>
        <section class="flex">
            <div class="right">
                <img src="~/public/img/kiallitas.svg" alt="kiállítás">
            </div>
            <div class="text">
                <h3>Ereklye kiállítás</h3>
                <p>
                    Előkészületben
                </p>
            </div>
        </section>
        <section class="flex">
            <div class="left">
                <img src="~/public/img/tanitasok.svg" alt="tanítások">
            </div>
            <div class="text">
                <h3>Tanítások</h3>
                <p>
                    Minden hónap második keddjén 18 órától 
                </p>
            </div>
        </section>
    </div>
</template>

<script setup>
    const title = 'Aktualitások - Galambos Péter Buddhista Alapítvány'
    
    useHead({
        title: title ,
        meta: [
            { name: 'description', content: title }
        ]
    })
</script>