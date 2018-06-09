<template>
<div>
    <card class="bg">
       
      <img slot="header" src="../assets/one.jpg" style="width:100%;display:block;">

      <div slot="content" class="card-padding">
        <p style="color:#e00025;font-size:18px;text-indent:15px;font-weight:bold;font-family:'weiruanyahei';margin:5px">润通科技</p>
        <p style="color:#e00025;font-size:15px;line-height:0.1;font-style:italic;letter-spacing:8px;text-align:center">用心创造理想与感动</p>
        
      </div>
    </card>
</div>
</template>

<script>
import { Card } from "vux"
import { Divider } from 'vux'

export default {
  components: {
    Card
  }
};
</script>

<style>
.bg {
  background-image: url(../assets/bg1.png);  
  background-size: 100% 100%;  
  -moz-background-size: 100% 100%;  
  -webkit-background-size: 100% 100%;  
}
</style>