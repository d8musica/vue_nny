<template>
  <div >
    <button @click='subt' type="button" name="minus">-</button>
    {{contador}}
    <button @click='add' type="button" name="plus">+</button>
  </div>
</template>
<script>
export default {
  data: () => ({
    contador: 0
  }),
  methods: {
    add() {
      this.contador++
    },
    subt() {
      this.contador--
    }
  }
}
</script>
<style lang="scss" scoped>
</style>
