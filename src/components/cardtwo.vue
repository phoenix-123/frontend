<template>
    <div>
        <cardtwo>
            <div slot="content" class="card-demo-flex card-demo-content01">
                <div class="vux-1px-r">
                    <span>15</span>
                    <br />
                    <span>15</span>
                </div>
                <div class="vux-1px-r">
                    <span>15</span>
                    <br />
                    <span>15</span>
                </div>        
                <div class="vux-1px-r">
                    <span>15</span>
                    <br />
                    <span>15</span>
                </div>
            </div>
        </cardtwo>
    </div>
</template>
<script>
import {Card} from 'vux'
export default {
    components:{
        Card
    }
}
</script>
<style scoped lang="less">
@import '~vux/src/styles/1px.less';

.card-demo-flex {
  display: flex;
}
.card-demo-content01 {
  padding: 10px 0;
}
.card-padding {
  padding: 15px;
}
.card-demo-flex > div {
  flex: 1;
  text-align: center;
  font-size: 12px;
}
.card-demo-flex span {
  color: #f74c31;
}
</style>

