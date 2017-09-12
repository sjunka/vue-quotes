<template>
    <div class="container">
        <app-quote-grid :props ></app-quote-grid>
    </div>
</template>

<script>
    import QuoteGrid from './components/Quotegrid.vue'
    export default {
        data () {
            return {
                maxQuotes: 10,
                quotes: ['primer cuot']

            }
        },
        components (){
            return {
                appQuoteGrid: QuoteGrid
            }
        }
        
    }
</script>

<style>
</style>
