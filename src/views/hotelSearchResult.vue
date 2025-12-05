<template>
    <el-row>
        <sideAndTopBarSearch />
        <searchResultCards />
    </el-row>
</template>
<script>
import sideAndTopBarSearch from '../components/hotelSearchResult/sideAndTopBarSearch.vue';
import searchResultCards from '../components/hotelSearchResult/searchResultCards.vue';
export default {
    components: {
        sideAndTopBarSearch,
        searchResultCards
    }
}
</script>
<style >

</style>