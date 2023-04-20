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
                <li class = nav_link><Link to="/home">Home</Link></li>
                <li class = nav_link><Link to="/about">About DSA</Link></li>
                <li class = nav_link><Link to="/showcase">Show Case</Link></li>
                <li class = nav_link><Link to="/people">Meet the Team</Link></li>
                <li class = nav_link><Link to="/contact">Contact Us</Link></li>
            </div>
    </ul>
</nav>





