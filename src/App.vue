<template>
  <div id="app">
    <div cellspacing=0  border=0 class="card">
      <div class="namebox">
        Name on card <br>
        <input type="text" id="name" v-model = ""> <br>
        Card number <br>
        <input type="text" id="name" v-model = "">
      </div>
      <div class="box">
        <div class="left1">
          Expiration <br>
          <input type="text" id="short1" placeholder="December(12)" v-model = "">
          <input type="text" id="short" placeholder="2016" v-model = "">
        </div>
        <div class="right">
          CVC Code<br>
          <input type="text" id="short" placeholder="334" der v-model = ""> <br>
        </div>
      </div>
      <div class="button1">
        <button type="button" class="btn btn-success">Success</button>
      </div>
    </div>
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
  color:white;
}
input {
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    color:black;
}
#name{
padding: 8px 50px;
width:90%;
}
#short{
padding: 8px 8px;
width:20%;
}
#short1{
padding: 8px 8px;
width:30%;
}
.card{
  margin-left:400px;
  margin-top:130px;
  position:absolute;
  width:550px;
  height:350px;
  border-radius:29px;
  border: 0px solid black;
  box-shadow:13px 11px 15px 7px rgba(50,50,50,.5);
  background-image:url('http://usavisacenter.ru/img/main-bg.png');
  background-repeat:no-repeat;
  background-size:cover;
}
.box{
  width: 100%;
  height: 70px;
  float:left;
  margin:5%;
}
.left1{
  float:left;
  width: 65%;
}
.right{
  float:left;
  width: 35%;
}
.namebox{
  margin:5%;
  height: 100px;
}
.button1{

  margin:1%;
  width: 100%;
  text-align: center ;
}
</style>
