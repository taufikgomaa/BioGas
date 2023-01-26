<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <router-link to="/" class="navbar-brand">Biogas</router-link>
            <ul class="navbar-nav">
                <li class="nav-item ">
                    <router-link to="/" class="nav-link">Home</router-link>
                </li>
                <li class="nav-item">
                <router-link to="/monitor" class="nav-link">Monitoring</router-link>
            </li>
                <li class="nav-item">
                    <router-link to="/about" class="nav-link">About the project</router-link>
                </li>
            </ul>
        </div>
    </nav>
</template>