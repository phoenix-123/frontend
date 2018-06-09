<template>
<div>
<divider class="heng">重庆润通科技</divider>
    <scroller lock-y scrollbar-x>
      <div class="box1">
        <div class="box1-item" v-for="i in 7"><span>{{' ' + i + ' '}}</span></div>
      </div>
    </scroller>
    </div>
</template>

<script>
import {Scroller,Divider} from 'vux'
export default{
    components:{
        Scroller,
        Divider
    }
}
</script>
<style lang="css">
.heng{
    margin: 0;
}
.box1 {
  height: 100px;
  position: relative;
  width: 1490px;
}
.box1-item {
  width: 200px;
  height: 100px;
  background-color: #ccc;
  display:inline-block;
  margin-left: 15px;
  float: left;
  text-align: center;
  line-height: 100px;
}
.box1-item:first-child {
  margin-left: 0;
}
</style>
