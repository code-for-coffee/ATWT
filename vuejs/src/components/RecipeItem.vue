<template>
  <li class="col s3">
    <div>
      <img :src="recipe.image" />
      <a :href="recipe.url">{{recipe.label}} </a>
    </div>
  </li>
</template>
<style lang="scss"> 
</style>
<script>
export default {
  name: 'recipe-item',
  data() {
    return {}
  },
  props:['recipe'],
  methods: {}
}
</script>
