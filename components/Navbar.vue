<template>
    <b-navbar :centered="centered" :shadow="shadow">
        <template #brand>
            <b-navbar-item class="brand" tag="router-link" :to="{ path: '/' }">
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
                    <a class="button">
                        <strong>Subscribe</strong>
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
</template>

<script>
export default {
    name: 'Navbar',
    data() {
        return {
            centered: true,
            shadow: true
        }
    }
}
</script>

<style>
nav {
    padding: 0 3.5rem;
}

.brand {
    font-size: 36px;
    font-weight: bold;
}

a {
    font-size: 18px;
    font-weight: 600;
}

.button {
    background-color: #58B727;
    color: #fff;
}
</style>