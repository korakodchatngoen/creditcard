<template>
  <div id="app">
    Name on card <br>
    <input type="text" v-model = ""> <br>
    Card number <br>
    <input type="text" v-model = ""> <br>
    Expiry date Security code <br>
    <input v-model = ""><input placeholder="CVV" der v-model = ""> <br>

    <button>Pay</button>

  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  components: {
    Hello
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Lora|Roboto+Slab');
html {
  height: 100%;
}

body {
  font-family: 'Lora', serif;
}
input[type=text], select {
    padding: 8px 50px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
}
</style>
