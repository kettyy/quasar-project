<template>
  <div class="q-pa-md q-gutter-y-md">
    <div>
      <p>Basic</p>
      <div class="q-pa-md q-gutter-sm">
        <q-avatar color="red" text-color="white" icon="directions" />
        <q-avatar color="primary" text-color="white">J</q-avatar>
        <q-avatar size="100px" font-size="52px" color="teal" text-color="white" icon="directions" />
        <q-avatar size="24px" color="orange">J</q-avatar>
        <q-avatar>
          <img src="https://cdn.quasar.dev/img/avatar.png">
        </q-avatar>
      </div>
    </div>

    <div>
      <p>Square</p>
      <div class="q-pa-md q-gutter-sm">
        <q-avatar square color="red" text-color="white" icon="directions" />
        <q-avatar square color="primary" text-color="white">J</q-avatar>
        <q-avatar square size="100px" font-size="82px" color="teal" text-color="white" icon="directions" />
        <q-avatar square size="24px" color="orange">J</q-avatar>
        <q-avatar square>
          <img src="https://cdn.quasar.dev/img/avatar.png">
        </q-avatar>
      </div>
    </div>

    <div>
      <p>Rounded</p>
      <div class="q-pa-md q-gutter-sm">
        <q-avatar rounded color="red" text-color="white" icon="directions" />
        <q-avatar rounded color="primary" text-color="white">J</q-avatar>
        <q-avatar rounded size="100px" font-size="82px" color="teal" text-color="white" icon="directions" />
        <q-avatar rounded size="24px" color="orange">J</q-avatar>
        <q-avatar rounded>
          <img src="https://cdn.quasar.dev/img/avatar.png">
        </q-avatar>
      </div>
    </div>

    <div>
      <p>Sizes</p>
      <div class="q-pa-md q-gutter-sm">
        <q-avatar
          v-for="size in ['xs', 'sm', 'md', 'lg', 'xl']"
          :key="size"
          :size="size"
          color="primary"
          text-color="white"
          icon="directions" />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">

</script>
