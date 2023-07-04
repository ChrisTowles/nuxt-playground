<template>
  <div class="text-h3 q-pa-md">
    Page 3
  </div>
  <div class="q-pa-md row items-start q-gutter-md">
    <q-card class="my-card">
      <q-card-section>
        {{ lorem }}
      </q-card-section>
    </q-card>

    <q-card
      dark
      bordered
      class="bg-grey-9 my-card"
    >
      <q-card-section>
        <div class="text-h6">
          Our Changing Planet
        </div>
        <div class="text-subtitle2">
          by John Doe
        </div>
      </q-card-section>

      <q-separator
        dark
        inset
      />

      <q-card-section>
        {{ lorem }}
      </q-card-section>
    </q-card>
  </div>
</template>

<script lang="ts" setup>
const lorem = 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.';
</script>

<style>
.my-card {
  max-width: 300px;
}
</style>
