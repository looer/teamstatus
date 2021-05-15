<template>
  <Layout>
    <div class="pt-8 md:pt-16">
      <h1 class="text-center font-bold text-4xl text-ui-primary">Thanks for you email</h1>
    </div>
    <div class="flex-col text-center">
      <Logo :width="200"/>
      <p>At the moment the product is in development.</p>
      <p>You will be notified once it's available!</p>
      <a href="https://gum.co/wWkny">Download from Gumroad</a>
    </div>
    <div class="mt-10 flex items-center justify-center">
      <g-link to="/" class="font-bold border-b border-ui-primary text-xl">Go back</g-link>.
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Success'
  }
}
</script>