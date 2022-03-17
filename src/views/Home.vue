<template>
    <div class="home container">
        <!-- header -->
                
        <div class="header">
        <div class="left flex flex-column">
            <h1>Invoices</h1>
            <span>There are 4 total invoices</span>
        </div>
        <div class="right flex">
            <div @click="toggleFilterMenu" class="filter flex" ref="filter" >
                <span>Filter by status</span>
                <img src="@/assets/icon-arrow-down.svg" alt="" srcset="">
                <ul v-show="filterMenu" class="filter-menu">
                    <li>Draft</li>
                    <li>Pending</li>
                    <li>Paid</li>
                    <li>Clear Filter</li>
                </ul>
            </div>
            <div @click="newInvoice" class="button flex">
                <div class="inner-button flex">
                    <img src="@/assets/icon-arrow-up.svg" alt="" srcset="">
                </div>
                <span> New Invoice </span>
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