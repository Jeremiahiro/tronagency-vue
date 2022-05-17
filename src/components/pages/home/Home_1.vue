<template>
    <div class="h-100 homepage__top p-0 m-0">
        <!-- Homepage top starts here -->
        <div class="py-3 px-5">
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
        <!-- Homepage top ends here -->

        <!-- case study section starts here -->
        <b-row class="mt-5 px-5 position-relative">
            <b-col cols-sm="12" cols="6" class="position-relative">
                <img src="@/assets/sylvia.png" height="600px">
                <router-link to="/work" class="recent__work">
                    <span class=""><img width="200" src="@/assets/Recent-work.svg"></span>
                </router-link>
            </b-col>
            <b-col cols-sm="12" cols="6" class="d-inline-flex mt-5">
                <b-row cols="3" class="case__study__container">
                    <b-col class="p-5">
                        <div>
                            <h4 class="heading">Clic</h4>
                            <p class="" style="color: #767376;">UI/UX Design Branding</p>
                        </div>
                    </b-col>
                    <b-col class="colored_container py-5 px-4">
                        <h4 class="heading">Rainmaker</h4>
                        <p>UI/UX Design, Branding, Development</p>

                        <router-link to="/" class="nav_link mt-5">
                            Read Case Study <img src="@/assets/case-study-arrow.svg">
                        </router-link>
                    </b-col>
                    <b-col class="p-5">
                        <div>
                            <h4 class="heading">ADA Compliance</h4>
                            <p class="" style="color: #767376;">UI/UX Design Branding</p>
                        </div>
                    </b-col>
                </b-row>
            </b-col>
        </b-row>
        <!-- case study section ends ere -->

        <div class="position-relative mb-5">
            <div class="overlay__container w-100">
                <b-row class="px-5 py-3">
                    <b-col cols-sm="12" cols="7" class="p-5 mt-5 overlay__container_text text-justify">
                        <p>
                            <span class="ml-5 pl-3"></span> Our clients are the companies and startups who make the world go round — they treat diseases, move parcels, insure cars, create jobs, send emails and publish courses.
                        </p>
                        <p>
                            Vast and complex businesses like these need digital experiences that are just as people-friendly as they are robust and scalable. <br>
                            Through challenging core assumptions, we shape the products and services that improve the lives of thousands every single day.
                        </p>
                    </b-col>
                    <b-col class="p-5">
                        <h1 class="overlay__container_legend display-3">
                            We bring everything that's <img style="width:40px" src="@/assets/emoji-happy.svg">
                            require to build a product.
                        </h1>
                    </b-col>
                </b-row>
            </div>
        </div>
        
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
.recent__work{
    position: absolute;
    top:150px;
    right:30px;
}
.case__study {
    &__container {
        border:2px solid #11271F;
        color: #767376;
        .heading {
            font-weight: bold;
            color: #11271F;
            padding-top: 10px
        }
        .nav_link {
            color: #767376;
            text-decoration: underline;
            &:hover {
                color: #858385;
            }
        }
        .colored_container {
            background-color: #11271F;
            .heading {
                color: #fff;
            }
        }
    }
}
.overlay__container {
    background-color: #c4c4c4;
    position: relative;
    margin-top: -160px;
    opacity: 1;
    &_text {
        font-size: 24px;
    }
    &_legend {
        color: #010101;
        font-weight: 600
    }
}


.down__overlay{
    position:relative;
    width:100%;
}
.overlay{
    position: absolute;
    background:#C4C4C480;
    top:400px;
    width:100%
}
.our__approach__button{
    background: #11271F;
    justify-content: center;
    width: 150px;
}
    


</style>
