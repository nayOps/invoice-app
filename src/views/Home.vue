<template>
    <div class="home container">
        <!-- header -->
                
        <div class="header">
        <div class="left flex flex-column">
            <h1>Invoices</h1>
            <span>There are 4 total invoices</span>
        </div>
        <div class="right flex">
            <div  @click="toggleFilterMenu" class="filter flex" ref="filter" >
            </div>
        </div>
        </div>
    </div>
<template>

<script>
    export default{
        name: "Home";
        components:{
        },
    }
</script>