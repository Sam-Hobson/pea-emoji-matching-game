<div class="game">

    <div class="info">
    </div>

    <div class="grid-container">
    </div>

    <div class="info">
    </div>

</div>


<style lang="postcss">

    .game {
        @apply flex flex-col justify-center items-center h-screen;
    }

    .info {
        @apply h-32 canvas-width bg-blue-200;
    }

    .grid-container {
        @apply canvas-width canvas-height bg-red-200;
    }

    .canvas-width {
        @apply w-[45rem];
    }

    .canvas-height {
        @apply h-[45rem];
    }

</style>
