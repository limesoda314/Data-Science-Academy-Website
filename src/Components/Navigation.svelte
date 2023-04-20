<script>
    import './../Style/Navigation.css';
    let logo = "./images/DSA@UCR_Logo.png";
</script>

<nav class="navbar">
    <ul class="nav_items">
        <img class="nav_logo" alt="" src={logo}/>
        <input type="checkbox" id="hamburger_menu_toggle"/>
        <label for="hamburger_menu_toggle" class="hamburger_menu">&#9776;</label>
             <div class="menu">
                <li class = nav_link><a href="/">Home</a></li>
                <li class = nav_link><a href="/">About DSA</a></li>
                <li class = nav_link><a href="/">Show Case</a></li>
                <li class = nav_link><a href="/">Meet the Team</a></li>
                <li class = nav_link><a href="/">Contact Us</a></li>
            </div>
    </ul>
</nav>





