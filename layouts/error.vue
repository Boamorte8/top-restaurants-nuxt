<template>
  <div class="wrapper">
    <slot name="header"></slot>
    <div>
      <img
        class="img"
        src="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
        alt="Error"
      />
    </div>
    <slot name="redirectEl" />
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.img {
  width: 10rem;
}
</style>