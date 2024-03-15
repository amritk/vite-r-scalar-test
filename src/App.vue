<script setup lang="ts">
import { ApiReference } from "@scalar/api-reference";
</script>
<template>
  <ApiReference
    :configuration="{
      spec: {
        url: 'https://petstore.swagger.io/v2/swagger.json',
      },
    }"
  />
</template>
