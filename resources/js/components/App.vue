<template>
    <div class="content">
        <AppNav :title="title" />
        <main class="container mt-3">
            <PostList />
        </main>
    </div>
</template>

<script>
import AppNav from "./AppNav.vue";
import PostList from "./posts/PostList.vue";
export default {
    name: "App",
    data() {
        return {
            title: "Boolpress",
        };
    },
    components: { AppNav, PostList }
};
</script>
