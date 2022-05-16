<template>
    <div class="h-100 homepage__top">
        <!-- start changes here -->
        <h1 class="display-3">
           <span class="mx-5" style=""> Creating <span class=""><img   style="height:40px" src="@/assets/ring.svg"></span> Products <span class=""><img style="height:13px" src="@/assets/left-arrow.svg"></span>
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

            <b-row>
                <b-col cols-sm="12">
                   <span class=""> <p   style="padding-left:100px" class="mx-5"><span class="mx-5">DeBrander is a multidisciplinary that design agency that</span> <br>combines <strong> design, technology, art </strong>and <strong>strategy </strong> create<br> state-of-the-art visual identity and experiency</p></span>
                </b-col>
                <b-col cols-sm="12">
                    <img style="height:100px; padding-left:297px" src="@/assets/contact-us.svg">
                </b-col>
            </b-row>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            currentYear: new Date().getFullYear() + 2, // 2024
        };
    }
}
</script>

<style lang="scss" scoped>
.homepage__top {
 
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
</style>
