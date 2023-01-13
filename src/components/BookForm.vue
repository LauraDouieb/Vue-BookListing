<template>
    <form class="" action="#" method="post">
        <input type="text" name="title" value="" placeholder="Book Title">
        <input type="text" name="author" value="" placeholder="Book Author">
        <button type="submit" name="button" v-on:click="bookSubmit">Add Book</button>
    </form>
</template>

<script>
    export default {
        name : 'BookForm',
        props: ['book'],
        data() {
            return {
                bookTitle : '',
                bookAuthor : ''
            };
        },
    }
    method : {
        bookSubmit () {
            
        }
    }
</script>

<style>

</style>