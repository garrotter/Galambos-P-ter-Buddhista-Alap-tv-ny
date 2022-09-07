<template>
    <div class="container content">
        <section>
            <h2>Galambos Péter Buddhista Alapítvány</h2>
            <p>
                A céget bejegyző hatóság: Fővárosi Törvényszék<br>
                A szervezet nyilvántartási száma: 01-01-0013288<br>
                A szervezet adószáma: 19328445-1-41<br>
                A szervezet statisztikai számjele: 19328445-9499-569-01<br>
                A szervezet székhelye: 1025 Budapest, Verecke út 15821/4. hrsz.<br>
                A szervezet e-mail címe: <br>
                A szervezet telefonszáma: <br>
                Számlavezető bank: OTP Bank Nyrt.<br>
                Számlaszám: 11702012-21452684<br>
                A szervezet képviselője: Glatz Péter János
            </p>
            <p>
                Kuratóriumi tagok:
                <ul>
                    <li>Glatz Péter János<br>a kuratórium elnöke</li>
                    <li>Dakos Andrea</li>
                    <li>Magyar Gergely</li>
                    <li>Szabados Levente</li>
                    <li>Venczel Ferenc </li>
                </ul>
            </p>
            <h3>Tárhelyszolgáltató adatai</h3>
            <p>
                Neve: Rackhost Zrt.<br>
                Székhelye: 6722 Szeged, Tisza&nbsp;Lajos&nbsp;körút&nbsp;41.<br>
                E-mail címe: <a :href="`mailto:` + info">{{ info }}</a><br>
                Ügyfélszolgálati telefonszáma: +36-1-445-1200
            </p>
        </section>
    </div>
</template>

<script setup>
    const title = 'Impresszum - Galambos Péter Buddhista Alapítvány'

    useHead({
        title: title ,
        meta: [
            { name: 'description', content: title }
        ]
    })

    let info = 'rackhost.hu'
    info = 'info' + '@' + info
</script>