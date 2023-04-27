<script>
    import './../Style/Hero.css';
    import Carousel from 'svelte-carousel';
    import Img from './Images.svelte';

    let images = [
        { caption: "Winston Chung Hall Photoshoot", src: "images/hero/img1.jpg"},
        { caption: "Professor LePendu teaching students about data cleaning", src: "images/hero/img2.jpg"},
        { caption: "All three Data Science Summer 2022 programs at once!", src: "images/hero/img3.jpg"},
        { caption: "Inspiration", src: "images/hero/img4.jpg"},
        { caption: "Analysis", src: "images/hero/img5.jpg"},
        { caption: "Collaboration", src: "images/hero/img6.jpg"},
        { caption: "A tour of University of California, Riverside campus", src: "images/hero/img7.jpg"},
        { caption: "Enjoying lunch among friends and peers", src: "images/hero/img8.jpg"}
    ];

    console.log(images);

</script>

<div class="banner" id="Home"> 
    <Carousel
        autoplay 
        autoplayDuration={10000}
        let:showPrevPage
        let:showNextPage        
    >
        <div slot="prev" on:click={showPrevPage} class="custom-arrow custom-arrow-prev">
            <i />
        </div>
        {#each images as image}
            <Img caption={image.caption} src={image.src} alt="No Image" />
        {/each}
        <div slot="next" on:click={showNextPage} class="custom-arrow custom-arrow-next">
            <i />
        </div>
    </Carousel>
</div>
