<template>
    <h1>{{ title }}</h1>
    <button @click="onClick()" v-bind:style="{ background:color}" class="btn" color="green">{{text}}</button>
</template>

<script>
export default{
    name: 'Button',
    props:{
        text: String,
        color: String,
    },
    methods:{
        onClick(){
            console.log("clicked clicky click")
        }

    }
}

</script>
