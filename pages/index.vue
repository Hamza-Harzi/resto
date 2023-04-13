<template>
  <div>
    <HTml :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
      <Head>
        <Title>Restaurantly</Title>
        <Meta name="description" content="My page is cool" />
        <Link
          rel="preload"
          href="https://previews.123rf.com/images/alvincadiz/alvincadiz1604/alvincadiz160400358/56426319-vector-illustration-of-smiley-emoticon-sad-face.jpg"
          as="script"
        />
      </Head>
    </HTml>
    <div class="container">
      <h1>Welcome to Restaurantly</h1>
      <NuxtLink href="/restaurants">Go to restaurants</NuxtLink>
    </div>
  </div>
</template>

<style scoped>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>
