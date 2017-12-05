<template>
    <div class="m-header">
        <div class="icon"></div>
        <div class="text">Chicken Music</div>
    </div>
</template>

<script>
    export default {}
</script>

<style lang='stylus'>
    @import '~common/stylus/variable'
    @import '~common/stylus/mixin'
    .m-header
        position: relative
        height: 44px
        text-align: center
        color: $color-theme
        font-size: 0
        .icon
            vertical-align top
            display inline-block
            margin-top 6px
            width 30px
            height 32px
            margin-right 6px
            bg-image('logo')
            background-size 30px 32px
        .text
            display inline-block
            top 0
            right 0
            line-height 44px
            font-size $font-size-large
</style>
