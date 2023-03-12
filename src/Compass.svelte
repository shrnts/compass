<script>
    let heading = 0.0;

    const sensor = new AbsoluteOrientationSensor();
</script>

<main class="h-screen w-screen flex items-center justify-center">
    <div class="h-64 w-64 relative rounded-full border-4 border-gray-200"
         style={'transform: rotate(' + heading + 'deg)'}>
        <div class="absolute -top-10 left-1/2 color-gray-200 -translate-x-1/2 font-bold text-error">N</div>
        <div class="absolute -bottom-10 left-1/2 color-gray-200 -translate-x-1/2 font-bold">S</div>
        <div class="absolute top-1/2 -left-8 color-gray-200 -translate-y-1/2 font-bold">W</div>
        <div class="absolute top-1/2 -right-8 color-gray-200 -translate-y-1/2 font-bold">E</div>
    </div>
</main>
