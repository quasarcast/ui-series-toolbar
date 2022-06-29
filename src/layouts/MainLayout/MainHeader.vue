<script setup>
import AccountMenu from './AccountMenu.vue'
import RightToolbarLinks from './RightToolbarLinks.vue'
</script>

<template>
  <q-header
    class="q-py-sm bg-grey-4"
  >
    <q-toolbar>
      <q-img
        width="48px"
        src="~/assets/logo.svg"
      />

      <q-space />

      <div class="q-gutter-sm">
        <RightToolbarLinks />

        <q-btn
          round
          color="grey"
        >
          <q-avatar>
            <q-img src="https://picsum.photos/100/100" />
          </q-avatar>

          <AccountMenu auto-close />
        </q-btn>
      </div>
    </q-toolbar>
  </q-header>
</template>
