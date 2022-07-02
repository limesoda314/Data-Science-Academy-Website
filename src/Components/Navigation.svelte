<script>
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
                <!-- <li class = nav_link><a href="/">ShowCase</a></li> -->
                <li class = nav_link><a href="/">Show Case</a></li>
                <li class = nav_link><a href="/">Meet the Team</a></li>
                <li class = nav_link><a href="/">Contact Us</a></li>
            </div>
    </ul>
</nav>




<style>

* {
    margin: 0;
    padding: 0;
    /* box-sizing: border-box; */
}

.nav_link a {
    text-decoration: none;  
    color: rgba(30, 0, 255);
}
.nav_link {
    list-style: none;
}

.navbar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    background-color: rgb(255, 255, 255);
    color: #fff;
}

.nav_logo
{
    width: 150px;
}

.menu
{
    display: flex;
    gap: 1em;
    font-size: 18px;

}
.menu .nav_link a:hover
{
    color: rgb(64, 0, 255);
    text-decoration: underline;
}
.menu .nav_link
{
    padding: 5px 14px;
}
input[type=checkbox]
{
    display: none;
}
.hamburger_menu
{
    display: none;
    font-size: 24px;
    user-select: none;
    color: rgba(30, 0, 255);
}

@media (max-width: 768px)
{
    .menu {
        display: none;
        position: absolute;
        right: 0;
        left: 0;
        text-align: center;
        padding: 16px 0;
    }
    .menu .nav_link a:hover {
        font-weight: bolder;

    }
    input[type=checkbox]:checked ~ .menu
    {
        display: block;
        /* background-color: rgb(170, 204, 204); */
    }
    .hamburger_menu
    {
        position: absolute;
        text-align: center;
        padding: 5px;
        font-size: 30px;
        width: 30px;
        display: block;
        right: 55px;
        top:25px;
        /* background-color: red; */
    }
    .hamburger_menu:hover
    {
        font-weight: bold;
        text-shadow: 1px 1px 10px rgb(137, 220, 255);
    }
    .menu .nav_link a
    {
        position: relative;
        border-top:1px solid black;
        border-left: 1px solid black;
        background-color: rgb(255, 255, 248);
        width: 100%;
        margin-bottom: -10px;
        margin-left: -14px;
        font-weight: 15px;
        display: inline-block;
        font-size: 25px;
        padding:20px
    }
    .menu:last-child
    {
        border-bottom: 1px solid rgb(0, 0, 0);
    }
    .menu
    {
        /* background-color: red; */
        padding:10px 0px 5px 0px;
    }
}
</style>