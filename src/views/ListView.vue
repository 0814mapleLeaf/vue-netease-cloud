<template>
    <ListViewHeader></ListViewHeader>
</template>

<script>
    import {getPlayListDetail} from "@/api"
    import ListViewHeader from "@/components/list-view/ListViewHeader";

    export default {
        name: "ListView",
        components: {
            ListViewHeader
        },
        data() {
            aaa:[]
        },
        created() {
            this.getPlayListMusic()
        },
            methods: {
            async getPlayListMusic() {
                const res = await getPlayListDetail(this.$route.query.id)
                console.log(res.data)
            }
        }
    }
</script>

<style scoped>

</style>