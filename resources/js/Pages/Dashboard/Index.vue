<template>
  <div>
    <Head title="Dashboard" />
    <h1 class="mb-8 text-3xl font-bold">Dashboard</h1>
    <p class="mb-8 leading-normal">Hey there! Welcome to Ping CRM, a demo app designed to help illustrate how <a class="text-indigo-500 hover:text-orange-600 underline" href="https://inertiajs.com">Inertia.js</a> works.</p>
    <Link class="btn-emerald-500 mt-6" href="/crocodile-management">鳄鱼信息管理</Link>
  </div>
</template>

<script>
import { Head, Link } from '@inertiajs/vue3'
import Layout from '@/Shared/Layout.vue'

export default {
  components: {
    Head,
    Link
  },
  layout: Layout,
}
</script>
