<template>
  <q-page class="flex flex-center">
   <q-card class="card-post" flat bordered>
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://cdn.quasar.dev/img/boy-avatar.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label class="text-bold">hyperYuri</q-item-label>
          <q-item-label caption>
            Brazil
          </q-item-label>
        </q-item-section>
      </q-item>

      <q-separator />
      
      <q-img
        src="https://cdn.quasar.dev/img/parallax2.jpg"
      />

    </q-card>
  </q-page>
</template>

<script>
export default {
  name: 'PageCamera'
}
</script>

<style lang="sass">
  .card-post
    .q-image
      min-height: 200px
</style>