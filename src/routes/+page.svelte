<script>
    import AboutMe from "$lib/components/AboutMe.svelte";
    import Intro from "$lib/components/Intro.svelte";
    import Skills from "$lib/components/Skills.svelte";
    import Header from "$lib/components/Header.svelte";
    import Stack from "$lib/components/Stack.svelte";
    import Education from "$lib/components/Education.svelte";
    import Portfolio from "$lib/components/Portfolio.svelte";
    import Contacts from "$lib/components/Contacts.svelte";
</script>

<div id="page">
    <Header/>

    <main>
        <Intro/>
        <AboutMe/>
        <Skills/>
        <Stack/>
        <Education/>
        <Portfolio/>
        <Contacts/>
    </main>
</div>