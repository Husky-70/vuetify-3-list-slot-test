<template>
  <v-app>
    <v-main>
      <v-list nav>
        <v-list-item title="Item 1" />
        <v-list-item title="Item 2" />
        <template #append>
          <v-list-item title="Append" />
        </template>
      </v-list>
    </v-main>

    <AppFooter />
  </v-app>
</template>

<script setup>
  //
</script>
