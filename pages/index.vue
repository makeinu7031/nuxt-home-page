<template>
    <div>
        <p>これはテスト</p>
        <div class="spotify">
            <iframe style="border-radius:12px"
                src="https://open.spotify.com/embed/playlist/60m28e3BJhD599Bisi3EpY?utm_source=generator" width="100%"
                height="352" frameBorder="0"
                allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
                loading="lazy"></iframe>
        </div>

        <div class="youtube">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/Q-Ec_n81iyc?si=aXIZplxGGSFeDbbo"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                allowfullscreen></iframe>
        </div>
    </div>
</template>

<style>
.youtube {
    width: 100%;
    aspect-ratio: 16 / 9;
    margin: auto;
    text-align: center;
}

.spotify {
    width: 100%;
    margin: auto;
    text-align: center;
    margin-bottom: 1rem;
}

.youtube iframe {
    width: 100%;
    height: 100%;
}
</style>