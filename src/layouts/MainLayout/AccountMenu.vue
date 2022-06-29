<script setup>
const links = [
  {
    to: '/logout',
    label: 'Logout'
  },
  {
    to: '/account',
    label: 'Account'
  },
  {
    to: '/billing',
    label: 'Billing'
  }
]
</script>

<template>
  <q-menu>
    <q-list>
      <q-item
        v-for="link in links"
        :key="link.label"
        clickable
        :to="link.to"
      >
        <q-item-section>
          {{ link.label }}
        </q-item-section>
      </q-item>
    </q-list>
  </q-menu>
</template>
