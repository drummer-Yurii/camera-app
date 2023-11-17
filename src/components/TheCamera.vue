<script setup>

</script>

<template>
    <div>
        <video ref="video" autoplay playsinline webkit-playsinline muted hidden></video>

        <canvas ref="canvas" width="800" height="420" class="bg-black rounded-3xl"></canvas>

        <div class="flex items-center justify-center py-4">
            <button class="px-6 py-4 bg-green-500 rounded text-white text-2xl uppercase font-bold hover:bg-green-600">
                Take Picture
            </button>
        </div>
    </div>
</template>