<template>
  <div class="header">
    <div class="header__logo">
      <img src="https://wompi.com/assets/img/home/logo-wompi.svg" alt="Logo" />
    </div>
    <SummaryCart />
  </div>
</template>

<style lang="scss">
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px;
  &__logo {
    display: flex;
    flex-direction: column;
    img {
      height: 40px;
    }
    span {
      color: $primary;
    }
  }
}
</style>