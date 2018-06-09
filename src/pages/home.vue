<template>
    <div>
        <x-header></x-header>
        <card></card>
        <scroller></scroller>
        <tabbar></tabbar>
    </div>
</template>

<script>
import XHeader from '../components/xheader'
import Tabbar from '../components/tabbar'
import Card from '../components/card'
import Scroller from '../components/scroller'
export default{
    components: {
        XHeader,
        Tabbar,
        Card,
        Scroller
    }
}
</script>
<style>

</style>