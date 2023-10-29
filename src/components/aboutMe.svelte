<script>
    export let title;
    export let p1;
    export let p2;
</script>


<div class="flex justify-center">
    <div class="flex flex-col justify-center items-center m-10 w-full bg-transparent h-fit ssm:m-10 2xl:mx-40 md:mx-20">
        <div class="flex flex-col justify-center items-center px-36 py-10 w-3/5 ssm:w-full ssm:text-sm sm:w-full md:w-full ssm:p-5 ssm:px-6">
            <h1 class="pb-4 w-full text-3xl font-bold">{title}</h1>
            <p class="w-full text-lg">{p1}</p>
            <p class="w-full text-lg">{p2}</p>


        </div>
    </div>    
</div>

<style>
    p {
        padding-bottom: 1rem;
    }
</style>