<template>
<div id="top">
    Users / Invoices
    <!-- <i class="fa fa-search"></i> -->
    <input type="textarea" placeholder="Search invoices..." id="search"/>
</div><br>
<div id="file">
    <i class="fa fa-file"></i> Invoices
</div>
</template>

<script>
export default {
    name: 'SearchBox'
}

</script>

<style>
#top {
    color: #097969
}

#search {
    height: 30px;
    width: 700px;
}

#file {
    background-color: #097969;
    color: white;
    width: 150px;
    height: 30px;
    padding-left: 50px;
    padding-top: 10px;
    border-radius: 25px;

}
</style>
