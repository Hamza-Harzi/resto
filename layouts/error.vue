<template>
  <div>
    <slot name="header" />
    <div>
      <img
        src="https://previews.123rf.com/images/alvincadiz/alvincadiz1604/alvincadiz160400358/56426319-vector-illustration-of-smiley-emoticon-sad-face.jpg"
        alt=""
      />
    </div>
    <slot name="redirectEl" />
  </div>
</template>

<style scoped>
img {
  width: 10rem;
}
</style>
