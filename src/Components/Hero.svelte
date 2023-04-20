<script>
    import './../Style/Hero.css';
    import Carousel from 'svelte-carousel';
    import Color from './Color.svelte';
</script>

<div class="banner" id="Home"> 
    <h1 class="center" style=""> 
        DSA 2023
    </h1>
    <div
    class="color-container"
    style="background-color: {color};"
    >
    <Carousel
        autoplay 
        autoplayDuration={5000}
    >
        <Color color="#85d78b" text="#85d78b" />
        <Color color="#71d077" text="#71d077" />
        <Color color="#5dca64" text="#5dca64" />
        <Color color="#49c351" text="#49c351" />
        <Color color="#35bd3e" text="#35bd3e" />
    </Carousel>
</div>
