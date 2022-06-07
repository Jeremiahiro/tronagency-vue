<template>
    <div class="h-100 talk__component">
        <!-- start changes here -->
        <Talk1/>
    </div>
</template>

<script>
import Talk1 from './talk/Talk_1.vue';
export default {
    components: { Talk1 },
    data() {
        return {
            // 
        };
    }
}
</script>

<style lang="scss" scoped>
.talk__component {
    background: #fff;
}
</style>
