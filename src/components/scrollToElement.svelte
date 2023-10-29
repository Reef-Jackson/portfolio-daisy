<script>
  import { fade } from "svelte/transition";


  export let targetId;
  export let buttonContent;

  function scrollIntoView() {
    const el = document.querySelector(`#${targetId}`);
    if (!el) return;
    el.scrollIntoView({
      behavior: "smooth",
    });
  }
</script>

<button class="text-white btn bg-info" on:click={scrollIntoView}
  >{buttonContent}</button
>
