<template>
    <b-navbar centered=true shadow=true>
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                Outdoor Vibrations
            </b-navbar-item>
        </template>
        <template #start >
            <b-navbar-item href="#">
                Home
            </b-navbar-item>
            <b-navbar-item href="#">
                About
            </b-navbar-item>
            <b-navbar-item href="#">
                Blog
            </b-navbar-item>
        </template>

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <strong>Subscribe</strong>
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style>
nav {
    padding: 0 3.5rem;
}
</style>