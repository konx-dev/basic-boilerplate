<template>
    <div>
        Homepage
    </div>
</template>

<script>
// import HomeEntry from '~/apollo/content/singles/home'

export default {
    components: {
    },
    data() {
        return {
            entry: null
        }
    }
    // apollo: {
    //     entry: {
    //         prefetch: true,
    //         manual: true,
    //         query: HomeEntry,
    //         variables() {
    //             return {
    //                 siteId: process.env.SITE_ID
    //             }
    //         },
    //         result({ data }) {
    //             // Prevents apollo killing the app
    //             if (!data) {
    //                 return
    //             }
    //             this.entry = data.entry
    //         }
    //     }
    // }
}
</script>
