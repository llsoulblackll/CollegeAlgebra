<template>
    <div id="header">
        <div class="top">
            <!-- Logo -->
            <div id="logo">
                <span class="image avatar48"><img src="../assets/img/avatar.jpg" alt="" /></span>
                <h1 id="title">College Algebra</h1>
                <p>LM01221</p>
            </div>
            <!-- Nav -->
            <nav id="nav">
                <ul>
                    <li><router-link to="/" id="top-link" class="navbar-link"><span class="link icon fa-home">Inicio</span></router-link></li>
                    <li>
                        <router-link to="/portafolio" id="portfolio-link" class="navbar-link"><span class="link icon fa-th">Portafolio</span>
                            <ul id="portfolioList" class="drop-list">
                                <li>Ejercicio 1</li>
                                <li>Ejercicio 2</li>
                                <li>Ejercicio 3</li>
                                <li>Ejercicio 4</li>
                                <li>Ejercicio 5</li>
                            </ul>
                        </router-link>
                    </li>
                    <li><router-link to="/about" id="about-link" class="navbar-link"><span class="icon fa-user">El Equipo</span></router-link></li>
                </ul>
            </nav>
        </div>
        <div class="bottom">
            <!-- Social Icons -->
            <ul class="icons">
                <li><a href="#" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
            	<li><a href="#" class="icon fa-facebook"><span class="label">Facebook</span></a></li>
            	<li><a href="#" class="icon fa-github"><span class="label">Github</span></a></li>
            	<li><a href="#" class="icon fa-dribbble"><span class="label">Dribbble</span></a></li>
            	<li><a href="#" class="icon fa-envelope"><span class="label">Email</span></a></li>
            </ul>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Navbar',
    watch: {
        $route(to, from){
            $('.drop-list').slideUp();
            if(to.name === 'portfolio'){
                $('#portfolioList').slideDown();
            }
        }
    }
}
</script>
