<script setup lang="ts">
const dateNow = computed(() => {
  return new Date().getFullYear();
});

function openLinkedIn() {
  window.open("https://www.linkedin.com/in/carlosgarciafern/");
}
</script>
<template>
  <footer
    class="min-h-[130px] border-t-2 border-t-[var(--secondary-color)] bg-[var(--tertiary-color)] text-center"
  >
    <div class="mt-6 flex justify-center"></div>

    <div class="mt-6">
      <h3 class="cursor-pointer text-base" @click="openLinkedIn">
        © Carlos Garcia {{ dateNow }}
      </h3>
    </div>
  </footer>
</template>
