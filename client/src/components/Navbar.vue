<template>
<nav class="navbar navbar-icon-top navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">INHANCE.</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/">
         HOME
        </router-link>
        </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/Members">
         MEMBERS
        </router-link>
          </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/News">
         NEWS
        </router-link>
          </a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder=" " aria-label="Search">
      <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">search</button>
    </form> 
  </div>
</nav>
</template>

<style>
@font-face {
  font-family: Adallyn;
  src: url('/fonts/Adallyn-bold.ttf');
}
.nav-brand {
  font-family: Adallyn;

}
.nav-item a {
  font-family: Adallyn;
  color: rgb(46, 46, 46);
  font-size: 20px; 
  margin: 0 25px;
}

.nav-item a:hover {
  text-decoration: underline;
  color: rgb(46, 46, 46);
}

.navbar-brand {
  font-family: Adallyn;
  padding-right: 200px;
  padding-left: 50px;
}

.navbar {
  margin-top: 20px;
}

</style>
