<template>
<VApp>
    <SidebarPanel />
    <VMain>
        <ImageGallery />
    </VMain>
</VApp>
</template>

<script>
import SidebarPanel from "./components/SidebarPanel.vue";
import ImageGallery from "./components/ImageGallery.vue";
export default {
    name: 'App',
    components: {
        SidebarPanel,
        ImageGallery
    },

    data: () => ({
        //
    }),
}
</script>
