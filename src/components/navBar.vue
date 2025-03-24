<template>
    <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
</template>
<script>
export default {
    name: 'navBar',
}
</script>
<style scoped>
nav {
    background-color: var(--cor1);

    padding-top: 15px;
    padding-bottom:5px;
    box-shadow: 0px 2px 20px #0000007e;
}

a {
    margin: 9px;
    color: #222;
}

a:hover {
    background-color: var(--cor4);
    color: var(--cor5);
    padding: 5px;
}

</style>