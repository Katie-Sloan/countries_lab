<template lang="html">
  <div id="favourite_countries">
    <h2>Favourite Countries</h2>
      <ul>
        <li v-for="(country, index) in favouriteCountries" :key="index" country="country">
          <span>{{country.name}}</span>
        </li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'favourite-countries',
  props: ['favouriteCountries']
}
</script>

<style lang="css" scoped>
</style>
