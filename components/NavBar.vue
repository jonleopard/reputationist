<template>
  <nav
    class="navbar is-transparent is-fixed-top is-solid"
    role="navigation"
    aria-label="main navigation"
  >
    <div class="navbar-brand">
      <a class="navbar-item" href="/">
        <img src="/logo-main.png" width="112px" />
      </a>

      <a
        role="button"
        class="navbar-burger burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start">
        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            Services
          </a>

          <div class="navbar-dropdown">
            <a class="navbar-item">
              Reputation Management
            </a>
            <a class="navbar-item">
              Enterprise SEO
            </a>
          </div>
        </div>

        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            Who we help
          </a>

          <div class="navbar-dropdown">
            <a class="navbar-item">
              C-Suites & Executives
            </a>
            <a class="navbar-item">
              Individuals
            </a>
            <a class="navbar-item">
              Small Businesses
            </a>
            <a class="navbar-item">
              Large Companies
            </a>
            <a class="navbar-item">
              Enterprise Companies
            </a>
          </div>
        </div>

        <a class="navbar-item">
          About Us
        </a>

        <a class="navbar-item">
          Case Studies
        </a>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <a class="button is-primary">
            <strong>Contact</strong>
          </a>
        </div>
      </div>
    </div>
  </nav></template
>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
