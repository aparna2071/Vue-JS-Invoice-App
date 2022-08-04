<template>
<ul>
    <li><input placeholder="Start Date" class="textbox-n" type="dropdown" onfocus="(this.type='date')" id="date" value="Start Date" />
    </li>
    <li><input placeholder="End Date" class="textbox-n" type="dropdown" onfocus="(this.type='date')" id="date" value="End Date"></li>
    <li>
        <select name="invoices" id="invoice">
            <option value="baker">Baker McKenzie</option>
            <option value="invoice1">Invoice 1</option>
            <option value="invoice2">Invoice 2</option>
            <option value="invoice3">Invoice 3</option>
            <option value="invoice4">Invoice 4</option>
        </select>
    </li>
    <li></li>
    <li>

        <button><i class="fa fa-plus"></i> <a href="https://invoicehome.com/invoices/81024429/edit?goal=guest_invoiceCreate"> Create New Invoice</a> </button>
    </li>
</ul>
</template>

<script>
export default {
    name: 'FilterSection',

}
</script>

<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

li {
    float: left;
    display: block;
    padding: 8px;
    color: #097969;
}

#invoice {
    height: 22px;
    width: 180px;
}

button {
    background-color: white;
    color: black;
    border-color: white;
}
</style>
