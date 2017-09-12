<template>
    <div class="row">
        <appQuote v-for="quote in quotes">{{ quote }}</appQuote>
    </div>
</template>

<script>
    import Quotes from './Quote.vue'
    export default {
        props (){
            return {
                props: ['quotes']
            }
        },

        components(){
            return {
                appQuote: Quote
            }
        }

    }
</script>

<style>

</style>