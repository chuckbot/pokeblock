<template>
  <section class="container mx-auto">
    <header class="text-center mb-[3rem] mt-[3rem]">
      <h1>List of Pokemon</h1>
    </header>
    <div
      class="grid lg:grid-cols-4 md:grid-cols-3 gap-[3rem] mb-[8rem] max-h-[50rem] overflow-auto p-8 bg-[var(--tertiary-color)] border-4 border-[var(--secondary-color)] rounded-lg"
    >
      <div v-for="i in 12">
        <Card />
      </div>
    </div>
  </section>
</template>
