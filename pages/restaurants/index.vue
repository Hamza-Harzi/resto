<template>
  <div>
    <HTml :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
      <Head>
        <Title>Top 50 restaurants in the world</Title>
        <Meta name="description" content="My page is cool" />
        <Link
          rel="preload"
          href="https://previews.123rf.com/images/alvincadiz/alvincadiz1604/alvincadiz160400358/56426319-vector-illustration-of-smiley-emoticon-sad-face.jpg"
          as="script"
        />
      </Head>
    </HTml>
    <NuxtLayout name="custom">
      <div class="container">
        <RestaurantTable />
      </div>
    </NuxtLayout>
  </div>
</template>
