<template>
    <div class="testimonail__section">
        <div class="" >
            <b-row cols="2" class="my-5 col-9 mx-auto testimonial__section">
                <b-col class="testimonial__section-left p-4" cols="6">
                    <P class="text-justify agency">
                        “TheBrander Agency was a game changer for Teachable — we used them to design our homepage (and have used that for many years) and they were the first people we turned to when we needed to build a marketplace. 
                        I highly recommend them and our team loves working with them.”                      </P>
                    <img  class="float-right mt-5 " src="@/assets/images/debrander-game-image.png" style="height:80px">
                </b-col>
                <b-col class="testimonial__section-right p-4 d-flex flex-column justify-content-between">
                    <h4 class="m-0 p-0">100k+ — creators using <br>
                    Teachable every day.
                    </h4>
                    <p class="">
                        Anthony Raden<br>
                        ~ Founder of Being A Company
                    </p>
                </b-col>
            </b-row>
        </div>
</div>
            
</template><script>
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
            
            
            border-bottom: 1px solid  #000000;
            &-right {
                border-left :1px solid  #000000;
            }
        }
    }

</style>