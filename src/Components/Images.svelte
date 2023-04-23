<script>
    import './../Style/Images.css';
    export let src, alt, caption
</script>


<div class="img-container">
    <p class="caption">
        {caption}
    </p>
    <img src={src} alt={alt}/>
</div>
