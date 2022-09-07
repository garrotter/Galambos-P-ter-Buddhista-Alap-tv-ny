<template>
    <div class="container content">
        <section class="flex">
            <div class="right">
                <img src="~/public/img/meditation.svg" alt="meditáció">
            </div>
            <div class="text">
                <h4>Meditáció</h4>
                <p>
                    Minden hétfőn 18 órától
                </p>
            </div>
        </section>
        <section class="flex">
            <div class="left">
                <img src="~/public/img/yoga.svg" alt="jóga">
            </div>
            <div class="text">
                <h4>Jóga</h4>
                <p>
                    Minden pénteken 18 órától<br>
                    <em>Átadáshoz kötött gyakorlás!</em>
                </p>
            </div>
        </section>
    </div>
</template>

<script setup>
    const title = 'Események - Galambos Péter Buddhista Alapítvány'
    
    useHead({
        title: title ,
        meta: [
            { name: 'description', content: title }
        ]
    })
</script>