<template>
  <div class="container pt-4">
      <div>
        <b-navbar toggleable="lg" type="transparent" variant="">
            <b-navbar-brand id="logo" href="#"><h2>Glade</h2></b-navbar-brand>

            <b-navbar-toggle id="toggle" target="nav-collapse">
                <svg width="20px" height="20px" viewBox="0 0 20 20" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                    <!-- Generator: Sketch 3.7.2 (28276) - http://www.bohemiancoding.com/sketch -->
                    <title>menu</title>
                    <desc>Created with Sketch.</desc>
                    <defs></defs>
                    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                        <g id="menu" fill="#00afef">
                            <path d="M0,3 L20,3 L20,5 L0,5 L0,3 Z M0,9 L20,9 L20,11 L0,11 L0,9 Z M0,15 L20,15 L20,17 L0,17 L0,15 Z" id="Combined-Shape"></path>
                        </g>
                    </g>
                </svg>
            </b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav id="menu-container" class="d-flex justify-content-around">
                <b-nav-item href="#" ><span id="menu">Create New Card</span></b-nav-item>
                <b-nav-item href="#" ><span id="menu">Features</span></b-nav-item>
                <b-nav-item href="#" ><span id="menu">My Transaction</span></b-nav-item>
                <b-nav-item href="#" ><button id="login" class="btn btn-outline-info px-4">Login</button></b-nav-item>
            </b-navbar-nav>
            </b-collapse>
        </b-navbar>
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#logo {
    color: #00afef;
    font-weight: 900;
}
#menu {
    text-decoration: none;
    color: #0d3e53;
    font-weight: 700;
}

#toggle {
    background-color: transparent;
    color: white;
}

#menu:hover {
    text-decoration: none;
}

#menu-container {
    width: 60%;
    margin-left: 30%;
}

#login {
    text-decoration: none;
    color: #0d3e53;
    font-weight: 700;
    border: #00afef 2px solid;
    border-radius: 20px;
}

#login:hover {
    background-color: #00afef;
    color: white;
}
</style>