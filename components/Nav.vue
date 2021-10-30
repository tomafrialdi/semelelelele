<template>
  <nav id="nav">
    <div class="container">
      <div class="flex items-center justify-between py-5 md:py-6 px-9 md:px-0">
        <div class="w-6/12 md:w-3/12 flex items-center">
          <nuxt-link to="/">
            <img
              src="~/assets/images/website/logo.png"
              alt="Logo"
              class="logo__nav"
            />
          </nuxt-link>
        </div>
        <div class="hidden md:block w-6/12 flex items-center justify-center">
          <nuxt-link to="/" class="relative font-medium text-sm text-color-757575 px-4"
            >Home</nuxt-link
          >
          <nuxt-link to="/" class="relative font-medium text-sm text-color-757575 px-4"
            >About</nuxt-link
          >
          <nuxt-link to="/" class="relative font-medium text-sm text-color-757575 px-4"
            >
            <span class="h-19px w-36px bg-color-E7462D absolute -top-4 right-1 font-bold text-8px text-white rounded-full text-center pt-px">HOT</span>
            Promotions
            </nuxt-link
          >
          <nuxt-link to="/" class="relative font-medium text-sm text-color-757575 px-4"
            >Blogs</nuxt-link
          >
          <nuxt-link to="/" class="relative font-medium text-sm text-color-757575 px-4"
            >Contact Us</nuxt-link
          >
        </div>
        <div class="w-6/12 md:w-3/12 flex items-center justify-end">
            <nuxt-link to="/" class="hidden md:block font-medium text-sm text-color-333333 mr-6">Masuk</nuxt-link>
            <nuxt-link to="/" class="h-10 md:h-11 inline-flex items-center justify-center bg-color-8BAC3E font-medium text-sm text-color-FFFFFF rounded-full px-5">Daftar Sekarang</nuxt-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style scoped>
.logo__nav {
    height: 50px;
    width: 207px;
}
@media(max-width: 500px) {
  .logo__nav {
    height: 36px;
    width: 150px;
}
}
</style>