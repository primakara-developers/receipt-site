<script>
export default {
  name: "Footer",
};
</script>

<template>
  <footer class="footer py-3 text-center mt-5 mb-4">
    <p class="m-0 text-secondary">Create with ❤️‍🔥 and 🖐 in Denpasar</p>
    <small
      ><a
        href="https://github.com/primakara-developers"
        target="blank"
        class="text-success"
        >Primakara Developers {{ new Date().getFullYear() }}</a
      ></small
    >
  </footer>
</template>
