<script>
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

<button class="btn btn-primary" on:click={scrollIntoView}
  >{buttonContent}</button
>
