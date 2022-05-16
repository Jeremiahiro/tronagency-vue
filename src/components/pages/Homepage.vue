<template>
    <div class="h-100 homepage__component">
        <Home1 />
        <Home2 />
    </div>
</template>

<script>
import Home1 from './home/Home_1.vue';
import Home2 from './home/Home_2.vue';

export default {
    components: { Home1, Home2 },
    data() {
        return {
            // 
        };
    }
}
</script>

<style lang="scss" scoped>
.homepage__component {
    background: #fff;
}
</style>
