<template>
    <div>
        <x-header></x-header>
        <card></card>
        <scroller></scroller>
        <cardtwo></cardtwo>
        <tabbar></tabbar>
    </div>
</template>

<script>
import XHeader from '../components/xheader'
import Tabbar from '../components/tabbar'
import Card from '../components/card'
import Scroller from '../components/scroller'
import Cardtwo from '../components/cardtwo'
export default{
    components: {
        XHeader,
        Tabbar,
        Card,
        Scroller,
        Cardtwo
    }
}
</script>
<style>

</style>