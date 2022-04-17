<template>
  <h1>Home Page</h1>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <div class="navbar-brand">Lebancode</div>

      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="offcanvas"
        data-bs-target="#offcanvasNavbar"
        aria-controls="offcanvasNavbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <!-- content -->
      <div
        class="offcanvas offcanvas-end"
        tabindex="-1"
        id="offcanvasNavbar"
        aria-labelledby="offcanvasNavbarLabel"
      >
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Offcanvas</h5>
          <button
            type="button"
            class="btn-close text-reset"
            data-bs-dismiss="offcanvas"
            aria-label="Close"
          ></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
            <li class="nav-item">
              <a @click="test" class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">About</a>
            </li>
            <li
              class="nav-item"
              data-bs-toggle="tooltip"
              data-bs-placement="bottom"
              title="Tooltip on bottom"
            >
              <a class="nav-link active" aria-current="page" href="#"
                >Google DSC Lebanese University</a
              >
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="offcanvasNavbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Our Products
              </a>
              <ul
                class="dropdown-menu"
                aria-labelledby="offcanvasNavbarDropdown"
              >
                <li><a class="dropdown-item" href="#">WEB Standard Package</a></li>
                <li><a class="dropdown-item" href="#">WEB Extentions</a></li>
                <li>
                  <hr class="dropdown-divider" />
                </li>
                <li>
                  <a class="dropdown-item" href="#">Business Emails</a>
                </li>
              </ul>
            </li>
            
            <li class="nav-item">
              <a id="getstarted" class="nav-link btn btn-primary text-light" aria-current="page" href="#">Get Started</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>
<script>
import '../extra'
export default {
  data(){
    return{
      name :'m'
    }
  }
};
</script>
<style>
.nav-item {
  margin: 0px 0.5rem;
}

</style>
