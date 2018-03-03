<template>

    <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="container">
            <div class="navbar-brand">
                <div class="navbar-item">
                    <p class="title is-4">NUXT
                        <span class="has-text-primary">BLOG</span>

                    </p>
                </div>
            </div>
            <div class="navbar-end">
                <nuxt-link class="navbar-item" to="/about">About</nuxt-link>
                <nuxt-link class="navbar-item" to="/posts">Posts</nuxt-link>
                <nuxt-link class="navbar-item" to="/admin">Admin</nuxt-link>
            </div>
        </div>
    </nav>

</template>

<style>
.navbar {
}
</style>