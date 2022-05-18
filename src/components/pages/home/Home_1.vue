<template>
    <div class="h-100 homepage__top p-0 m-0">
        <!-- Homepage top starts here -->
        <div class="py-3 px-5">
            <h1 class="display-3">
            <span class="mx-5" style=""> Creating <span class=""><img style="height:40px" src="@/assets/images/ring.svg"></span> Products <span class=""><img style="height:13px" src="@/assets/images/left-arrow.svg"></span>
                <span class=""><img  style="height:40px" src="@/assets/images/bud.svg"></span></span><br>
                <span class="font-italic mx-5" style="padding-left:160px;">With outstanding <span class=""><img style="height:40px" src="@/assets/images/elipse-shape.svg"></span> Visual</span><br>
                <span class="mx-5" style="padding-left:320px">and Great <span class=""><img style="height:40px" src="@/assets/images/wave-shape.svg"></span>Functionality</span>
            </h1>

            <div class="vertival__line">
                <span class="copy__right">
                    <img style="height:200px" src="@/assets/images/vertical__line.png">
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
                                <img style="height:100px; padding-left:297px" src="@/assets/images/contact-us.svg">
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
                <img src="@/assets/images/sylvia.png" height="600px">
                <router-link to="/work" class="recent__work">
                    <span class=""><img width="200" src="@/assets/images/Recent-work.svg"></span>
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
                            Read Case Study <img src="@/assets/images/case-study-arrow.svg">
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

        <!-- Our approach starts here -->
        <div class="position-relative">
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
                    <b-col class="p-5 text-center">
                        <router-link  to="/" class="our__approach_button">
                            Our approach
                        </router-link>
                    </b-col>
                    </b-col>
                    <b-col class="p-5">
                        <h1 class="overlay__container_legend display-3">
                            We bring everything that's <img style="width:40px" src="@/assets/images/emoji-happy.svg">
                            require to build a product.
                        </h1>
                    </b-col>
                </b-row>
            </div>
        </div>
        <!-- Our approach ends here -->

        <!-- Home section 2 starts here-->
        <div class="homepage__section_2 p-5">
            <b-row class="p-4">
                <b-col  cols-sm="12" cols="6" class=" text-justify">
                    <h2 class="the_work p-3"><span class="quando">The work we do,</span> <br> and the people we help.</h2>
                </b-col>
                <b-col  cols-sm="12" class="p-3 mx-5">
                    <div class="sass_coy p-3">
                        <span class="count">10 </span> — SaaS companies we’ve helped in the past 24 months.
                        <p class="m-0 p-0">Our holistic process takes care of discovery, branding, design, and development.</p>
                    </div>
                </b-col>
            </b-row>

            <b-row class="saas_companies px-4 py-5">
                <div class="mx-auto text-center w-full">
                    <img src="@/assets/images/saas_coy.png" width="100%" class="mx-auto" alt="Responsive image" />
                </div>
                <b-row class="p-4 align-items-center">
                    <b-col  cols-sm="12" cols="6" class="text-center">
                        <router-link to="/">
                            <img  class=""  src="@/assets/images/left-button.png">
                        </router-link>
                    </b-col>
                    <b-col  cols-sm="12" class="p-3 mx-5 position-relative">
                        <img  class="position-absolute quote" src="@/assets/images/open_quote.png">
                        <p>
                            We are all storytellers. We all live in a network of stories. There isn’t a stronger connection between people than storytelling.”
                        </p>
                        <p class="p-0 m-0"> – Jimmy Neil Smith</p>
                    </b-col>
                </b-row>

                <b-row class="my-5 position-relative align-items-center">
                    <b-col cols-sm="12" class="">
                        <img src="@/assets/images/project.png" class="mx-auto" alt="Responsive image" />
                    </b-col>
                    <b-col>
                        <div class="design_lang">
                            <span class="quando ml-5">Marshal —</span> Creating a dynamic and scalable design language to help power the future.
                        </div>
                        <b-row class="mx-4 my-5">
                            <b-col>
                                <router-link to="/">
                                    <img  class=""  src="@/assets/images/clientforce.png">
                                </router-link>
                            </b-col>
                            <b-col>
                                <p class="text-muted">
                                    UI/UX Design, Branding, Development
                                </p>
                            </b-col>
                        </b-row>
                        <div class="ml-auto text-right">
                            <router-link to="/">
                                <img  class=""  src="@/assets/images/left-button.png">
                            </router-link>
                        </div>
                    </b-col>
                </b-row>
            </b-row>
        </div>
        <!-- Home section 2 ends here-->

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
        font-weight: 500;
        font-family: 'Quando', serif;
    }
}

.our__approach_button{
    background: #11271F;
    justify-content: center;
    color: #fff;
    border-radius: 6px;
    padding: 10px 20px;
    &:hover {
        text-decoration: none;
    }
}

.homepage__section_2 {
    background-color: #11271F;
    position: relative;
    color: #fff;
    & .quando {
        font-family: 'Quando', serif;
    }
    .the_work {
        font-weight: 500;
        font-size: 48px;
    }
    .sass_coy {
        .count {
            color:#FEAC5E;
            font-size: 40px
        }
    }
    
    .saas_companies {
        background-color:#4D4D4D45;
        border-radius: 10px;

        .quote {
            top: -12px;
            left: -30px;
        }

        .design_lang {
            font-size: 40px;
            margin-left: -70px
        }

    }
}   


</style>
  