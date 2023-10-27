<div class="flex flex-col w-full">
    <!-- Include the "My Projects" component -->
    <div class="grid h-20 card bg-base-300 rounded-box place-items-center mb-10 mx-7">
        <h1 class="text-3xl font-bold">My Projects:</h1>
    </div>

    <!-- Include the other components (Bucketlist and A link to the project) within the same flex container -->
    <div class="flex flex-col justify-center w-full mb-10 sm:flex-row">
        <div class="w-full sm:w-2/6 card bg-base-300 rounded-box place-items-center p-10 px-16 mb-4 sm:mb-0">
            <h1 class="text-4xl mt-10 mb-5 w-full">Bucketlist</h1>
            <p class="w-full mb-2">I made this little web-app to learn SvelteKit.</p>
            <p class="w-full mb-2">I connected the very simple front-end to a PocketBase database, and interfaced them via SvelteKit and the PocketBase API, in the beginning this was a large obstacle.</p>
            <p class="w-full mb-2">This was the first web-application I made that I would consider 'full-stack' besides the deployment. I made lots of mistakes, but overcoming them was a really fun experience.</p>
        </div>
        <div class="divider divider-horizontal"></div> <!-- Remove sm:hidden class here -->
        <div class="w-full sm:w-2/6 card bg-base-300 rounded-box place-items-center p-10 px-16 mb-4 sm:mb-0">
            <h1>A link to the project will go here.</h1>
        </div>
    </div>
</div>
