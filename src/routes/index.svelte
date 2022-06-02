<script>
    import '../main.scss'
    import image1 from '$lib/images/image1.jpg';
    import image2 from '$lib/images/image2.jpg';
    import image3 from '$lib/images/image3.jpg';
    import image4 from '$lib/images/image4.jpg';
    import image5 from '$lib/images/image5.jpg';
</script>

<body>

    <div class="container">
        <div class="feature">
            <img src={image2} alt="Terrain" class="feature-img">
            <div class="content">
                <h3>About Me</h3>
                <a href="#" class="cta">Learn more</a>
            </div>
        </div>
        <div class="feature">
            <img src={image3} alt="Terrain" class="feature-img">
            <div class="content">
                <h3>Portfolio</h3>
                <a href="#" class="cta">Learn more</a>
            </div>
        </div>
        <div class="feature">
            <img src={image4} alt="Terrain" class="feature-img">
            <div class="content">
                <h3>Blog</h3>
                <a href="#" class="cta">Learn more</a>
            </div>
        </div>
        <div class="feature">
            <img src={image5} alt="Terrain" class="feature-img">
            <div class="content">
                <h3>Contact</h3>
                <a href="#" class="cta">Learn more</a>
            </div>
        </div>
    </div>

</body>