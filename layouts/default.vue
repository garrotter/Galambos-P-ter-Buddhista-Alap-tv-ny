<template>
    <div id="body">
        <Header />
        <Navbar />
        <Hero />
        <main>
            <slot />
        </main>
        <Footer />
    </div>
</template>

<script setup>
    const title = 'Galambos Péter Buddhista Alapítvány'

    useHead({
        title: title,
        viewport: 'width=device-width, initial-scale=1, maximum-scale=1',
        charset: 'utf-8',
        meta: [
            { name: 'description', content: title }
        ],
        htmlAttrs: {
            lang: 'hu'
        }
    })
</script>