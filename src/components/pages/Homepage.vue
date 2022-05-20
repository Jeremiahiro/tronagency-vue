<template>
    <div class="h-100 homepage__component">
        <div class="homepage__top p-0 m-0 position-relative">
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
                            <router-link  to="/" class="homepage_btn">
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

            <!-- Home section 3 starts here -->
            <div class="homepage__section_3 pt-5">
                <div class="col-8 mx-auto solutions">
                    <span class="quando">
                        We translate research into solutions, crafting thoughtful and unified
                    </span>
                    <em>brands, apps, websites, interfaces, and systems.</em>
                    <img class="" src="@/assets/images/foot.png">
                </div>
                <div class="p-5 m-4 d-flex justify-content-between align-items-start">
                    <img class="mt-5" src="@/assets/images/brooke-cagle.png" alt="responsive-image">
                    <img class="ml-4" height="500" src="@/assets/images/priscillia.png" alt="responsive-image">
                </div>
                <div class="new_segment">
                    <div class="col-9 mx-auto mb-3">
                        <p class="text-justify partners">
                            <img src="@/assets/images/right-arrow.svg"> 
                            We partner with design leaders of tech brands and growing businesses to create simple, functional, and scalable digital solutions. Our global team of researchers, strategists, creatives, and engineers work with streamlined processes to break through organizational roadblocks and shape the brands of tomorrow.
                        </p>
                    </div>
                    <div class="mx-auto p-5 text-center">
                        <router-link to="/">
                            <img src="@/assets/images/right-button.svg">
                        </router-link>
                    </div>
                    <b-row class="work__together-container align-items-center p-5">
                        <b-col class="work__together px-5" cols-md="12" cols="5">
                            <p class="work__together_top">
                                <span class="quando">How can we</span> <br> work together?
                            </p>
                            <p class="work__together_desc">
                                We’ve developed a simple onboarding process to help us better understand our client's strategic needs.
                            </p>
                        </b-col>
                        <b-col class="px-5">
                            <img src="@/assets/images/group_icons.png" width="90%">
                        </b-col>
                    </b-row>

                    <b-row class="align-items-center p-5">
                        <b-col class="">
                            <img src="@/assets/images/about_img.png" width="100%">
                        </b-col>
                        <b-col>
                            <p class="join__container-top">
                                <span class="quando">
                                    <span class="mx-5"></span>Join Tech Mates to shape experiences of tomorrow
                                </span>
                            </p>
                            <p class="join__container-desc py-3">
                                Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.
                            </p>
                            <div class="text-center">
                                <router-link to="/about" class="homepage_btn">
                                    About
                                </router-link>
                            </div>
                        </b-col>
                    </b-row>
                </div>
            </div>
            <!-- Home section 3 ends here -->

            <!-- Home testimonail section starts here -->
            <div class="testimonail__section">
                <div class="" >
                    <b-row cols="2" class="my-5 col-9 mx-auto testimonial__section">
                        <b-col class="testimonial__section-left p-4" cols="6">
                            <P class="text-justify">
                                “I’d highly recommend TheBrander as a web design agency, having worked with them on the design and development of a new website over the past 3-4 months.
                                From initial brand development and refinement, to the design and implementation of statements that it’s can’t be done! ”
                            </P>
                            <img  class="float-right mt-5 " src="@/assets/images/group_img.png" style="height:80px">
                        </b-col>
                        <b-col class="testimonial__section-right p-4 d-flex flex-column justify-content-between">
                            <h4 class="m-0 p-0">Testimonial</h4>
                            <p class="">
                                Williams Shakesspared <br>
                                ~ Founder of Being A Company
                            </p>
                        </b-col>
                    </b-row>
                </div>
                
                <div class="col-8 mx-auto my-3 project">
                    <div class="text-justify d-flex align-items-end">
                        <img style="" src="@/assets/images/zigzag_image.svg" height="250px"> 
                        <h1 class="pl-5 project_title quando">Have a project in mind? Let’s get to work.</h1>
                    </div>
                    <div class="mb-5 pt-4">
                        <router-link  to="/" class="ml-5 project_btn">
                            Start A Project
                        </router-link>
                    </div>
                </div>
            </div>
            <!-- Home testimonail section ends here -->

            <!-- bottom addon -->
            <img src="@/assets/images/big_wave.png" alt="" class="big_wave">
        </div>
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
.homepage__component {
    .copy__right{
        position:absolute;
        top:200px;
        left:60px;
    }
    .quando {
        font-family: 'Quando', serif;
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
    .big_wave {
        position: absolute;
        bottom: -120px;
        right: 0;
        z-index: 1;
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

    .homepage__section_2 {
        background-color: #11271F;
        position: relative;
        color: #fff;
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

    .homepage__section_3 {
        .solutions {
            font-size: 56px;
            font-weight: 400;
        }
        .partners {
            font-size: 28px;
        }
        .new_segment {
            background-image: url('../../assets/images/blur_bg.png');
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
        }
    }

    .homepage_btn {
        background: #11271F;
        justify-content: center;
        color: #fff;
        border-radius: 6px;
        padding: 10px 20px;
        &:hover {
            text-decoration: none;
            background: rgb(30, 71, 54);
        }
    }

    .testimonail__section {
        .project {
            &_title {
                font-size: 60px;
                font-weight: 400;
            }
            &_btn {
                background: #FEAC5E;
                justify-content: center;
                color: #000;
                border-radius: 2px;
                padding: 10px 20px;
                font-size:16px;
                &:hover {
                    text-decoration: none;
                    background: #faae68;
                }
            }
        }
        .testimonial__section {
            font-size:20px;
            border-top: 1px solid #000000;
            border-bottom: 1px solid  #000000;

            &-right {
                border-left :1px solid  #000000;
            }
        }
    }

}
</style>
