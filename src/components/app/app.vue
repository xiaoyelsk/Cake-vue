<template>
    <div style="height:100%">
        <router-view></router-view>
    </div>
</template>

<script>
    export default {
        mounted(){
            this.$store.commit('setCarlistLen')
        }
    }
</script>