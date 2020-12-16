<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-12 col-lg-6 address">
                   Copyright 2020 @bscdapps 
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        data: function () {
            return {
                tipsAddress: '0xAceBabe64807cb045505b268ef253D8fC2FeF5Bc'
            };
        }
    };
</script>

<style lang="sass" scoped>
    @import "../css/variables"
    footer
        padding: 1rem 0 0.5rem
        background-color: $panel-background
        color: $text-alt
        a
            text-decoration: none
        .address
            margin-bottom: 20px
            color: $text
            a
                font-family: $monospace-font
                margin-left: 15px
                word-break: break-all
        .links
            text-align: right
            a
                margin-right: 30px
                padding-bottom: 2px
                i
                    font-size: 1.2em

    @media screen and (max-width: 480px)
        footer
            padding-bottom: 1em
</style>
