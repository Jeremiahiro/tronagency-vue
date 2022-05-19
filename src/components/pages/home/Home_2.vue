<template>
    <div class="h-100 homepage__section">
        
    </div>
</template>            

<script>
export default {
    data() {
        return {
            // 
        };
    }
}
</script>

<style lang="scss" scoped>
.homepage__section {
    .solutions {
        font-size: 52px;
        font-weight: 400;
    }
    .partners {
        font-size: 28px;
    }
    .new_segment {
        background-image: url('../../../assets/images/blur_bg.png');
        background-size: 100% 100%;
        background-repeat: no-repeat;
    }
    .work__together {
        &-container {
            background-color: #fff;
        }
        &_top {
            font-size: 50px;
        }
        &_desc {
            line-height: 50px;
            font-size: 24px
        }
    }
    .join__container {
        &-top {
            font-size: 34px;
        }
        &-desc {
            font-size: 18px
        }
        &-btn {
            background: #11271F;
            justify-content: center;
            color: #fff;
            border-radius: 6px;
            padding: 10px 20px;
            &:hover {
                text-decoration: none;
            }
        }
    }
}

</style>
