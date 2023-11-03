<script>
    import Menu from "../components/menu.svelte";
    import Hero from "../components/hero.svelte";
    import MyTech from "../components/myTech.svelte";
    import AboutMe from "../components/aboutMe.svelte"
    import WorkItem from "../components/workItem.svelte";
</script>

<Menu />
<section id="home"></section>
<Hero />
<section id="about"></section>
<AboutMe 
    title="About me:"
    p1="I'm a second-year student at Sheffield Hallam University, actively seeking a placement to enhance my programming skills and gain hands-on experience."
    p2="I have a strong foundation in various programming languages, including PHP, C#, NodeJS, SvelteKit, PocketBase, SQL, CSS, HTML, and Tailwind. In addition to my passion for coding, I enjoy Warhammer 40K, Star Wars, and personal programming projects! (You'll see these in a minute)!"
/>
<AboutMe title="Some technology I use:" p1="This is technology that I'm very familiar with, there are other frameworks and languages I'm actively learning, and they'll hopefully make it here soon!" p2="This website was actually made with Tailwind and SvelteKit!"/>

<MyTech />
<section id="work"></section>
<WorkItem />


<style>
    :global(html) {
        scroll-behavior: smooth;
    } 
</style>
