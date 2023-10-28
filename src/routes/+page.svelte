<script>
    import Menu from "../components/menu.svelte";
    import Hero from "../components/hero.svelte";
    import Project from "../components/project.svelte";
    import WorkDivider from "../components/work-divider.svelte";
    import Section from "../components/section.svelte";
    import MyTech from "../components/myTech.svelte";
</script>

<Menu />
<section id="home"></section>
<Hero />
<section id="work"></section>
<WorkDivider  />
<Project 
    title="Another Project"
    desc1="Some explanation"
    desc2="Some more explanation"
    desc3="Even more explanation"
    imageLink="ImageLink Here"
/>
<Section title="My Technology" />
<MyTech />




<style>
    :global(html) {
        scroll-behavior: smooth;
    } 
</style>
