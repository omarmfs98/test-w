<template>
  <div class="summary-cart">
    <Icon name="mdi:cart-variant" />
    <span class="price">$0</span>
  </div>
</template>

<style lang="scss">
.summary-cart {
  display: flex;
  align-items: center;
  background-color: $primary;
  color: #2c2a29;
  padding: 3px 5px;
  .price {
    margin-left: 5px;
  }
}
</style>
