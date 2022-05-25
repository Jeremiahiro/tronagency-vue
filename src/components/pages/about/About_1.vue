<template>
     <div class="h-100 aboutpage__top p-0 m-0 mb-5 position-relative">
         <!-- aboutpage section1  start here-->
         <div class="col-8 mx-auto  text__container">
             <h1 class="quando display-2">The <span class="pl-3 pr-3"><img src="@/assets/images/vertical_ring.svg" height="60px"></span>work we do</h1>
             <p class="pl-5 people_we_help">and the people we help. <span class="pl-2"><img src="@/assets/images/people_we_help_image.png" height="30px"></span></p>
         </div>

        <div class="mx-auto text-center w-full p-5 mt-5">
                    <img  src="@/assets/images/saas_coy.png" width="100%" class="mx-auto pt-5" alt="Responsive image" />
        </div>
        <b-row class="col-12  mx-auto  project">
                    <b-col cols="6" class="px-5">
                        <div class="text-justify d-flex align-items-end pl-2">
                           <p class="pl-5 pr-5 customer_acquisition"> Clientforce is customer acquisition and sales 
                            automation platform that helps you find your 
                            ideal customers with a few clicks.
                           </p>
                        </div>
                        
                         
                        </b-col>
                        <b-col cols="6" class="">
                           
                        <div class="mb-5 pt-4 text-center">
                            <router-link  to="/" class="ml-5 project_btn ">
                                <img  class=""  src="@/assets/images/view_project_button.png" height="90px">
                            </router-link>
                        </div>
                           
                        </b-col>
                </b-row>
        <!-- aboutpage section1 ends here -->
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

.quando{
    
    font-weight: 400;
}
.people_we_help{
    font-size:45px;
}
.customer_acquisition{
    font-size:22px;
    line-height:50px;
}

</style>