<template>
    <div class="tab">
        <router-link to='/recommend' type='div' class="tab-item">
            <span class="tab-link">推荐</span>
        </router-link>
        <router-link to='/singer' type='div' class="tab-item">
            <span class="tab-link">歌手</span>
        </router-link>
        <router-link to='/rank' type='div' class="tab-item">
            <span class="tab-link">排名</span>
        </router-link>
        <router-link to='/search' type='div' class="tab-item">
            <span class="tab-link">搜索</span>
        </router-link>
    </div>
</template>

<script>
export default {}
</script>

<style lang='stylus'>
    @import '~common/stylus/variable'

    .tab
        display flex
        height 44px
        line-height 44px
        font-size $font-size-medium
        .tab-item
            text-align center
            flex auto
            .tab-link
                padding-bottom 5px
                color $color-text-1
            &.router-link-active span
                color $color-theme
                border-bottom 2px solid $color-theme
</style>