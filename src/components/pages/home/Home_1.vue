<template>
    <div class="h-100 homepage__top">
        <!-- start changes here -->
        <h1 class="display-3">
           <span class="mx-5" style=""> Creating <span class=""><img style="height:40px" src="@/assets/ring.svg"></span> Products <span class=""><img style="height:13px" src="@/assets/left-arrow.svg"></span>
            <span class=""><img  style="height:40px" src="@/assets/bud.svg"></span></span><br>
            <span class="font-italic mx-5" style="padding-left:160px;">With outstanding <span class=""><img style="height:40px" src="@/assets/elipse-shape.svg"></span> Visual</span><br>
            <span class="mx-5" style="padding-left:320px">and Great <span class=""><img style="height:40px" src="@/assets/wave-shape.svg"></span>Functionality</span>
        </h1>

        <div class="vertival__line">
            <span class="copy__right">
                <img style="height:200px" src="@/assets/vertical__line.png">
            </span>
            <span class="copy__right__year">
             {{ currentYear }} © 
            </span>
        </div>
        <b-row>
            <b-col cols="10" class="mx-auto my-4">
                <b-row class="d-flex justify-content-between">
                    <b-col cols-sm="12" cols="6">
                        <p class="text-justify f-18">
                            <span class="mx-3"></span>   DeBrander is a multidisciplinary design agency that combines <b>design, technology, art,</b>
                            and <b>strategy</b> to create state-of-the-art visual identity and experiences.
                        </p>
                    </b-col>
                    <b-col cols-sm="12" class="text-right">
                        <router-link to="/talk" class="">
                            <img style="height:100px; padding-left:297px" src="@/assets/contact-us.svg">
                        </router-link>
                    </b-col>
                </b-row>
            </b-col>
        </b-row>
    </div>
</template>

<script>
export default {
    data() {
        return {
            currentYear: new Date().getFullYear(),
        };
    }
}
</script>

<style lang="scss" scoped>
.homepage__top {
//  background: #DCDCDC;
}
.copy__right{
    position:absolute;
    top:200px;
    left:60px;
}
.copy__right__year{
    position:absolute;
    top:420px;
    writing-mode: vertical-lr;
}
.f-18 {
    font-size: 16px;
}
</style>
