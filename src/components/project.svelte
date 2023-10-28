<script>
    export let title;
    export let desc1;
    export let desc2;
    export let desc3;
    export let imageLink;
</script>

<div class="flex flex-col justify-center mb-10 w-full sm:flex-row">
    <div class="place-items-center p-10 px-20 mb-4 w-full sm:px-16 sm:w-2/6 card bg-base-300 rounded-box sm:mb-0">
        <h1 class="m-10 w-full text-4xl">{title}</h1>
        <p class="mb-2 w-full">{desc1}</p>
        <p class="mb-2 w-full">{desc2}</p>
        <p class="mb-2 w-full">{desc3}</p>
    </div>
    <div class="divider divider-horizontal"></div> <!-- Remove sm:hidden class here -->
    <div class="place-items-center p-10 px-16 mb-4 w-full sm:w-2/6 card bg-base-300 rounded-box sm:mb-0">
        <h1>{imageLink}</h1>
    </div>
</div>