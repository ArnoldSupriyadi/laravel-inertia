<template>
    <Layout>
        <Head title="inertia laravel" />
        <h1>Welcome gaannteng</h1>
        <p>Hello {{ title }}, welcome to your first Inertia app!</p>
    </Layout>
</template>

<script>
import Layout from "../Shared/Layout";
import { Head } from "@inertiajs/inertia-vue3";

export default {
    components: {
        Head,
        Layout,
    },
    props: {
        user: ["title"],
    },
};
</script>
