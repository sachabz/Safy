<template>
  <div class="section border-bottom border-dark mt-4 pb-5">
    <div class="content container px-4">
      <Articles />
      <Destinations />
      <Flags />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Articles from '@/components/Articles.vue'
import Destinations from '@/components/Destinations.vue'
import Flags from '@/components/Flags.vue'

export default {
  name: 'Section2',
  components: {
    Articles,
    Destinations,
    Flags,
  }
}
</script>

<style scoped lang="scss">
</style>

