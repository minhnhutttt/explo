<template>
    <HeaderMain />
    <HomeSearch />
    <div
        :style="{
            backgroundImage:
                'url(' + require('@/assets/images/bg-main.png') + ')',
        }"
    >
        <div class="mx-auto w-full max-w-[1280px] py-4 md:py-8">
            <HomeArticles />
            <HomeTable />
        </div>
    </div>
    <FooterMain />
</template>

<script>
import HomeArticles from './components/Home/HomeArticles.vue'
import HeaderMain from './components/Header/HeaderMain.vue'
import HomeSearch from './components/Home/HomeSearch.vue'
import HomeTable from './components/Home/HomeTable/HomeTable.vue'
import FooterMain from './components/Footer/FooterMain.vue'

export default {
    name: 'App',
    components: {
        HeaderMain,
        HomeSearch,
        HomeArticles,
        HomeTable,
        FooterMain,
    },
}
</script>
