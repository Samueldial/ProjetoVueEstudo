<template>
    <div id="header">
        <header class="header">
            <div class="img-header">
                <img src="" alt="">
            </div>
            <div class="nav-header">
                <nav class="nav">
                    <router-link to="/">Página Inicial</router-link>
                    <router-link to="/about">Sobre</router-link>
                    <router-link to="/contact">Contato</router-link>
                </nav>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    name:"header"
}
</script>
<style lang="stylus" scoped>
    .header{
        width: 100vw;
        height: 80px;

    }
</style>