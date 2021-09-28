<template>
  <div>
    <svg-icon icon-class="question" @click="goto"/>
  </div>
</template>

<script>
export default {
  name: 'chadDoc',
  data() {
    return {
      url: 'http://doc.chad.vip/chad-vue'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>