<template>
    <div class="gift">
       <div class="gift-tie-1"></div>
       <div class="gift-tie-2"></div>
       <div class="gift-top"></div>
        <div class="gift-body"></div>
    </div>
    
    </template>
    
    <script>
    export default {
        name: 'GIFT'


    }
    </script>
    
    <style>
    .gift {
        display: flex;
        position: relative;
        flex-direction: column;
        align-items: center;
        z-index: 10;
    }

    .gift-top{
        width: 100px;
        height: 25px;
        background-color: rgb(39, 139, 36);
    }

    .gift-body{
        width: 90px;
        height: 60px;
        background-color: rgb(25, 105, 32);
    }
    .gift-tie-1{
        position: absolute; 
        width: 15px;
        height: 85px;
        background-color: red;
    }
    .gift-tie-2{
        position: absolute;
       justify-content: center;
        top: 40px;
        width: 90px;
        height: 15px;
        background-color: rgb(255, 0, 0);
    }
    
    </style>