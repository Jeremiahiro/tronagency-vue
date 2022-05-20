<template>
    <div class="h-100 homepage__section">
        <!-- continue here -->
        
            
        <div class="d-flex inline m-5 col-10 p-5" >
           <b-row cols="2" class="highly-recommend__container ml-5">
                    <b-col class="p-3">
                        <div>
                            <P>“I’d highly recommend TheBrander as a web design agency, having worked
                                 with them on the design and development of a new website over the past 3-4 months.
                                  From initial brand development
                                 and refinement, to the design and implementation of the statements that 
                                 it’s can’t be done! ”
                            </P>
                        </div>

                        <div class="text-right">
                            <img  class="mt-5 " src="@/assets/images/Group_line_image.png" style="height:80px">
                        </div>
                    </b-col>
                    <b-col class="middle-line  pt-4 py-3">
                        <h4 class="m-0 p-0">Testimonial</h4>
                        

                       <div lass="position-absolute-bottom">
                           <p class=" wiliams_shakesspared pt-5 mt-5">Williams Shakesspared</p>
                           <p class=" founder" >- Founder of Being A Company</p>
                       </div>
                    </b-col>
                   
                </b-row>

        </div>
           
        <div class="col-9 mx-auto mb-3">
                    <h1 class="text-justify">
                        <img style="" src="@/assets/images/zigzag_image.svg" width="30px"> 
                        Have a project in mind? <span class="ml-5 pl-4">Let’s get to work.</span>
                    </h1>
                    <div class="mb-5 pt-4">
                        <router-link  to="/" class="ml-5 start_a_project_btn">
                                Start A Project
                        </router-link>
                    </div>

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
.homepage__section {
    
    .start_a_project_btn{
    background: #FEAC5E;
    justify-content: center;
    color: #000;
    border-radius: 2px;
    padding: 10px 20px;
    font-size:16px;
    

    &:hover {
        text-decoration: none;
        background: #ac8660;
    }
}

.have_a_project {
        font-size: 36px;
        font-weight: 400;
    }
.highly-recommend__container{
    border-top:1px solid  #000000;
    border-bottom:1px solid  #000000;
    font-size:20px
}
.middle-line{
    border-left :1px solid  #000000;
}
.wiliams_shakesspared{
    
    font-size:16px;
    margin-top:100px;
}
.founder{
    font-size:16px
}
.text-justify{
    font-size:74px;
    
}

}


</style>
 