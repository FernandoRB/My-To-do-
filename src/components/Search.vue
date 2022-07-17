<template>
    <div id="search-container">
        <input placeholder="Search  my Task" type="text" v-model="query" v-on:input="$emit('query-change', query)"
        aa
        >
    </div>
</template>

<script>
export default {
    name: 'Search',
    data(){
        return {
            query: ''
        }
    }
}
</script>

<style scoped>
    #search-container{
        width: 600px;
        margin: 0 auto;
    }

    input{
        padding: 10px;
        width: 100%;
        outline: none;
        background-color: rgb(89, 93, 228);

    }
</style>