<script></script>

<template>
    <div id="title">
        <h1 id="text">La mia prima app con Vite!</h1>
    </div>
</template>

<style>
#title {
    padding: 1rem;
    border-radius: 20px;
    background: linear-gradient(120deg, #540d6e, #ee4266, #ffd23f, #3bceac, #0ead69);
    transition: all 0.3s;
}

#title:hover {
    filter: drop-shadow(0 0 1.5rem rgb(61, 60, 60));
}

#text {
    background: linear-gradient(160deg, #0ead69, #3bceac, #1781b6, #ee4266, #540d6e);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

}
</style>
