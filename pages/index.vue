<template>
  <div class="home-page">
    <InlineDateRange />
  </div>
</template>

<script>
export default {
  components: {
    InlineDateRange: () => import('@/components/controls/InlineDateRange')
  }
}
</script>
