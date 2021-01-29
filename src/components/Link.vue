<template>
  <a :href="href" class="btn btn-dark btn-block mb-2 w-100 p-3" role="button" target="_blank">
    <i :class="icon"></i>
    {{text}}
  </a>
</template>

<script>
export default {
  props: {
    text: String,
    title: String,
    icon: String,
    href: URL,
  },
  methods: {
    open() {
      window.open(this.href);
    },
  },
};
</script>
