<template>
    <div class="flex flex-col min-h-screen text-slate-300">
        <header class="px-3 py-6 text-center">
            <h1 class="text-3xl font-black text-white/80 drop-shadow-md">gpt-3.5-turbo</h1>
        </header>
        <main class="flex flex-grow px-3 py-2">
            <Chat/>
        </main>
        <footer class="px-3 py-6 text-center">
            <span class="text-xs font-light text-slate-400">powered by <a href="https://github.com/waylaidwanderer/node-chatgpt-api" target="_blank">https://github.com/waylaidwanderer/node-chatgpt-api</a></span>
        </footer>
    </div>
</template>

<style>
:root {
    --background: hsl(240, 80%, 10%);
}

body {
background-color: #292f4a;
}

footer a {
    @apply opacity-75 hover:opacity-100 transition duration-300 ease-in-out;
    background: linear-gradient(to right, #37feff 0%, #bd7bff 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
</style>
