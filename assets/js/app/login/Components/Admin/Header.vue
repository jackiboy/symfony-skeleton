<template>
  <nav class="admin__header--topbar">
    <!-- eslint-disable-next-line vue/no-v-html -->
    <h2 class="admin__header--title" v-html="title"></h2>
  </nav>
</template>

<script>
export default {
  name: 'AdminHeader',
  props: ['title'],
};
</script>
