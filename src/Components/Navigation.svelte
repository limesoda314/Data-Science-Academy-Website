<script>
    import './../Style/Navigation.css';

    import { Link } from "svelte-routing";

    let logo = "./images/DSA@UCR_Logo.png";
</script>

<nav class="navbar">
    <ul class="nav_items">
        <img class="nav_logo" alt="" src={logo}/>
        <input type="checkbox" id="hamburger_menu_toggle"/>
        <label for="hamburger_menu_toggle" class="hamburger_menu">&#9776;</label>
             <div class="menu">
                <li class = nav_link><a href="/home">Home</a></li>
                <li class = nav_link><a href="/about">About DSA</a></li>
                <li class = nav_link><a href="/showcase">Show Case</a></li>
                <li class = nav_link><a href="/people">Meet the Team</a></li>
                <li class = nav_link><a href="/contact">Contact Us</a></li>
            </div>
    </ul>
</nav>





