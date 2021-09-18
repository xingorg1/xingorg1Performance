<template>
  <div class="cell">
    <div v-if="value" class="on">1</div>
    <section v-else class="off">2</section>
  </div>
</template>

<script>
export default {
  props: ['value'],
}
</script>
