<template>
<!-- <HelloWorld msg="Welcome to Aparna" /> -->
<SearchBox />
<FilterSection />
<InvoiceSummary />
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import SearchBox from './components/SearchBox.vue'
import FilterSection from './components/FilterSection.vue'
import InvoiceSummary from './components/InvoiceSummary.vue'

export default {
    name: 'App',
    components: {
        /* HelloWorld, */
        SearchBox,
        FilterSection,
        InvoiceSummary,
    }
}
</script>

<!-- <style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style> -->
