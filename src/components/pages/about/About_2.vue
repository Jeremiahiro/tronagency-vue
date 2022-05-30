<template>
<div>
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


    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
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


</style>
