<template>
    <header>
        <h1>RPG Planner</h1>
        <nav>
            <a href=#>Import Settings</a>
            <a href="#">Export Settings</a>
        </nav>
    </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style lang="scss">
@import '../assets/styles/variables.scss';

header {
  width: 100%;
  padding: 1em;
  font-size: 140%;
  text-align: center;
  box-shadow: 0 3px 5px rgba(57, 63, 72, 0.3);
  h1 {
    font-weight: 600;
    display: inline;
    font-size: inherit;
    text-transform: uppercase;
    letter-spacing: -2px;
    line-height: $lh;
    color: $primary;
  }
}
nav a {
  display: inline-block;
  outline: none;
  text-decoration: none;
  opacity: 0.7;
  padding: 0 0.5em;
  color: $secondary;
  transition: color 0.5s ease-out;
  line-height: $lh;
  &:hover, &:focus {
    transition: color 0.5s ease-in;
    color: $primary;
  }
}

@media (min-width: 500px) {
  header {
    text-align: left;
  }
  nav {
    float: right;
  }
}
</style>

