<script>
    import './../Style/Hero.css';
    import Carousel from 'svelte-carousel';
    import Img from './Images.svelte';
</script>

<div class="banner" id="Home"> 
    <Carousel
        autoplay 
        autoplayDuration={5000}
        let:showPrevPage
        let:showNextPage        
    >
        <div slot="prev" on:click={showPrevPage} class="custom-arrow custom-arrow-prev">
            <i />
        </div>
        <Img caption = "San Francisco" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/GoldenGateBridge-001.jpg/1200px-GoldenGateBridge-001.jpg" alt="San Francisco"/>
        <Img caption = "Scotland" src="https://cdn.britannica.com/s:800x450,c:crop/35/204435-138-2F2B745A/Time-lapse-hyper-lapse-Isle-Skye-Scotland.jpg" alt="Scotland"/>
        <Img caption = "Darjeeling" src="https://static2.tripoto.com/media/filter/tst/img/735873/TripDocument/1537686560_1537686557954.jpg" alt="Darjeeling"/>
        <Img caption = "Scotland"src="https://i.natgeofe.com/n/f7732389-a045-402c-bf39-cb4eda39e786/scotland_travel_4x3.jpg" alt="Scotland"/>
        <Img caption = "San Francisco"src="https://www.omm.com/~/media/images/site/locations/san_francisco_780x520px.ashx" alt="San Francisco"/>
        <div slot="next" on:click={showNextPage} class="custom-arrow custom-arrow-next">
            <i />
        </div>
    </Carousel>
</div>
