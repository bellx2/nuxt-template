<template lang="pug">
  b-navbar(toggleable="md" type="dark" variant="danger")
    b-navbar-brand Site Template
    b-collapse(is-nav id="nav")
      b-navbar-nav
        b-nav-item Item1
        b-nav-item(disabled) Item2
      b-navbar-nav.ml-auto
        b-nav-form
          b-form-input(size="sm")
          b-button(size="sm") Search
        b-nav-item-dropdown(text="Lang")
          b-dropdown-item JP
          b-dropdown-item EN
        b-nav-item-dropdown(text="User" right)
          b-dropdown-item Profile
          b-dropdown-item Logout
</template>

<style>
</style>

