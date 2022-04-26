<template>
    <ul id="listLang">
        <li v-for="item in arrListLang">
            <p>{{ item }}</p>
        </li>
    </ul>
</template>
<script>
export default{
    name: 'listLang',
    data(){
        return({
            arrListLang: ['PHP','JS','Java','C#']
        })
    }
}     
</script>

<style scoped>
    p{
    font-size: 4em;
    font-weight: 500;
    margin-bottom: 0.4rem;
    color:cadetblue;
    }
</style>>