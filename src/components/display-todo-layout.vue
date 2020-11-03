<template>
    <div>
        <div class="header-page">
            <header-block></header-block>
        </div>
        <div class="page-container1">
            <search-box-container></search-box-container>
        </div>
    </div>
</template>
<script>
import HeaderBlock from './header-block';
import SearchBoxContainer from './search-box-container';

export default {
    data() {
        return {
            
        }
    },
    methods: {
        
    },
    computed: {
        
    },
    components: {
        HeaderBlock,
        SearchBoxContainer
    },
}
</script>
<style>
.page-container {
    width: 100%;
}
*{
    box-sizing: border-box;
}
</style>