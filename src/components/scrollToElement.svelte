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

<button class="btn btn-primary" in:fade={{ delay: 250, duration: 300 }}  on:click={scrollIntoView}
  >{buttonContent}</button
>
