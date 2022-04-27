<template>
    <HeaderCom></HeaderCom>
    <SwiperCom></SwiperCom>
    <IconList></IconList>
    <MusicList></MusicList>
</template>

<script>
    import SwiperCom from "@/components/swiper/SwiperCom";
    import IconList from "@/components/icon-list/IconList";
    import MusicList from "@/components/music-list/MusicList";
    import HeaderCom from "@/components/header/HeaderCom";

    export default {
        name: 'HomeView',
        components: {
            SwiperCom, IconList, MusicList, HeaderCom
        }
    }
</script>
