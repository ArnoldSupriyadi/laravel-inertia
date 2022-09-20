<script setup>
import { Link } from "@inertiajs/inertia-vue3";
import Layout from "../Shared/Layout";

defineProps({
    title: String,
    likes: Number,
});
</script>
<template>
    <Layout>
        <Head title="about" />
        <h1>Welcome gaannteng</h1>
        <p>Halamman about</p>
    </Layout>
</template>
