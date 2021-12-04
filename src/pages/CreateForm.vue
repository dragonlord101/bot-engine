<template>
  <q-page class="flex flex-center">
    <label>This is the page</label>
    <FormBuilder v-model="configuration"></FormBuilder>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import { FormBuilder } from 'v-form-builder'

export default defineComponent({
  name: 'PageIndex',
  components: { FormBuilder },
  data: () => ({
    configuration: {}
  })
})
</script>
