<template>
  <div class="layout-container">
    <AppHeader />
    <div class="layout-container__content">
      <section></section>
      <section>
        <slot />
      </section>
    </div>
  </div>
</template>

<style lang="scss">
.layout-container {
  max-width: 800px;
  margin: auto;
  &__content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    section {
      border-bottom: 1px solid #000;
    }
  }
}
</style>