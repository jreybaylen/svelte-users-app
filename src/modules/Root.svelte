<script lang="ts">
    import Header from '@components/Header.svelte'
    import Footer from '@components/Footer.svelte'
    import Content from '@components/Content.svelte'
    import HomePage from '@modules/pages/Home/index.svelte'
</script>

<Header />
<Content className="container">
    <HomePage />
</Content>
<Footer />