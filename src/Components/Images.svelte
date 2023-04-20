<script>
    export let src, alt, caption
  </script>
<div
    class="img-container"
>
    <p class="caption">
        {caption}
    </p>
    <img src={src} alt={alt}/>
    
  </div>
  
  <style>
    .img-container {
        height: 500px;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        user-select: none;
    }
    .img-container > img {
        height: auto;
        width: 100%; 
    }
    .img-container > p {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        
    }
    .caption {
        position: absolute;
        overflow: hidden; 
        padding: 30px;
        margin-left: -1335px;
        font-size: 50px;
        font-weight: bold;
        color: white; 
        background-image: linear-gradient(to right, black, rgba(0, 0, 0, 0.869), rgba(0, 0, 0, 0.686), rgba(128, 128, 128, 0)); 
        height: 500px;
        width: 500px; 
    }
  </style>