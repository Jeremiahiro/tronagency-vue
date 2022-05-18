<template>
    <div class="h-100 homepage__section p-5">
        <!--section3 first paragraph start here-->
        <div class="py-5 px-5">
            <h1 class="pl-5 display-2"><span class="quando">We translate research into solutions, 
                crafting thoughtful and unified</span> <span class="font-italic">brands, apps, websites, 
                interfaces, and systems.</span>
                <span class=""><img src="@/assets/images/wave-shape.svg"></span>
                <img class="m-0 p-0" src="@/assets/images/pet.svg">
                </h1>

        </div>
        <!--section3 first paragraph end here-->

        <!-- section3 images start here-->
        <div class="">
            <b-row class="px-5 py-5">
                <b-col cols-sm="12" cols="4" class="">
                    <img class="m-1 pt-5 " src="@/assets/images/priscilla.png" alt="responsive-image">
                </b-col>
                <b-col cols-sm="12" cols="7" class="right-image ">
                    <img  class="m-3 pl-5" width="115%" src="@/assets/images/brooke-cagle.png" alt="responsive-image">
                 </b-col>

            </b-row>
        </div>
        <!-- section3 images end here-->

        <!-- section3 last para start here -->
        <div class=" partner-paragraph justify-content-justify px-5 py-5 ">
            <p class=" pl-5 pr-5 "><span class="pr-2"><img src="@/assets/images/right-arrow.svg" style="height:20px"></span>We partner with design leaders of tech brands and growing businesses to create simple, functional, and scalable digital solutions.
               Our global team of researchers, strategists, creatives, and engineers work with streamlined processes to
               break through organizational roadblocks and shape the brands of tomorrow.
            </p>
        </div>
         <div class="ml-auto text-center">
            <router-link to="/">
                <img  class=""  src="@/assets/images/right-button.svg">
            </router-link>
        </div>
        <!-- section3 last para end here -->
        
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
    
    .right-image{
       padding-left:80px;
}
    .partner-paragraph{
        font-size:35px;
        margin-left:50px;
        margin-right:30px
    }
}

</style>
