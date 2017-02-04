<script>
  $( document ).ready(function(){
    $(".button-collapse").sideNav();
  });
</script>

<div class="navbar-fixed">
<nav>
  <div class="nav-wrapper grey darken-4" style="font-family: 'Oswald', sans;">
    <a href="/" class="brand-logo" style="font-family: 'Sanchez', sans; padding-left: 5px"><b>JuzJaunt</b></a>
    <a href="#" data-activates="mobile-nav" class="button-collapse"><i class="material-icons">menu</i></a>
    <ul class="right hide-on-med-and-down">
      <li><a href="#">Services</a></li>
      <li class="active grey"><a class="black-text" href="/order">Order</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </div>
</nav>
</div>
<div>
<ul class="side-nav grey darken-2" id="mobile-nav" style="font-family: 'Oswald', sans;">
  <li><a href="#" class="cards waves-effect waves-black white-text">Services</a></li>
  <li class="active grey"><a class="black-text" href="/order" class="cards waves-effect waves-black white-text">Order</a></li>
  <li><a href="#" class="cards waves-effect waves-black white-text">About</a></li>
  <li><a href="#" class="cards waves-effect waves-black white-text">Contact</a></li>
</ul>
</div>