<template>
  <h1>WeatherApp</h1>
  <input type="text" placeholder="wpisz lokalizacje" v-model="localeInfo" />
</template>

<script>
export default {
  // domysle dane deklarowane na poczatku
  data() {
    return {
      localeInfo: 'San Escobar',
    };
  },
  // mounted - funkcja wywołująca się po " zamontowaniu komponentu"
  mounted() {
    console.log('hello');
    console.log('this');
    this.localeInfo = 'San Escobar';
  },
};
</script>

<style>
h1 {
  color: red;
}
</style>
