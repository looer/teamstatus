<template>
  <Layout>
    <div class="pt-8 md:pt-16">
      <h1 class="text-center font-bold text-4xl text-ui-primary">Thanks for you email</h1>
    </div>
    <div class="flex-col text-center">
      <Logo :width="200"/>
      <p>You can download the app from the link below.</p>
      <p>I would like to have your feedback at info@availableonteams.com</p>
      
      <a class="text-xl underline" href="/AvailableOnTeamsDEMO.exe" download>Download DEMO</a>

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
