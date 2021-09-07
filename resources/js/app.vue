<template>
    <div>
        <nav class="navbar navbar-expand-sm bg-primary navbar-dark">
            <div class="container">
                <a class="navbar-brand" href="#">Laravel-Vue-crud</a>
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a href="" class="nav-item nav-link">Home</a>
                    </li>
                    <li class="nav-item">
                        <router-link
                            :to="{ name: 'ProductIndex' }"
                            class="nav-item nav-link"
                            >Products</router-link
                        >
                    </li>
                </ul>
            </div>
        </nav>
        <router-view> </router-view>
    </div>
</template>

<script>
export default {};
</script>
