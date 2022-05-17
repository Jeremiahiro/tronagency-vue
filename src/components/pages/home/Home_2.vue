<template>
    <div class="h-100 homepage__top">
        <!-- start changes here -->
        <b-row class="first__text__container px-5 py-5">
            <b-col  cols-sm="12" cols="6" class=" text-justify">
                <h2 class="headings p-3 ">The work we do, and the people we work</h2>

            </b-col>
             <b-col  cols-sm="12" class="p-3 mx-5">
                <p class="heading p-3"><span class="ten">10 </span> — SaaS companies we’ve helped in the past 24 months. Our holistic
                     process takes care of discovery, branding, design, and development.</p>
            </b-col>
        </b-row>

        
        <b-row>  
              
              <b-col class="">
                <div class="image__frame__container ml-5 mb-5 mr-5">
                    
                   <b-row class="px-5">
                       <b-col  cols="4" class="">
                           <div class="dashboard__img_container  w-100 ml-5 mt-5">
                               <img class=" w-100 p-3" src="@/assets/first__dashboard__image.png">
                               <img class="ml-2" src="@/assets/clientforce-logo.svg">
                               <p class="ml-2 p-3" style="color: #767376;"> UI/UX Design, Branding,<br>Development</p>
                               
                           </div>
                       </b-col>
                       <b-col  cols="6" class="secoond__dashboard  px-5 py-3">
                           <img  class="mt-5 pr-5 mr-5 second__dashboard__image" src="@/assets/second__dashboard__image.png">
                       </b-col>
                   </b-row> 

                   <b-row class="px-2 py-2">
                       <b-col class="">
                           <router-link to="/">
                           <img  class="p-5 ml-5"  src="@/assets/left-button.png">
                           </router-link>
                       </b-col>

                       <b-col class="mx-5 p-3">
                           <p class="storyteller_para p-5" style="color:#FFFFFF">We are all storytellers. We all live in a network of stories. 
                               There isn’t a stronger connection between people than storytelling.” 
                               – Jimmy Neil Smith
                            </p>
                       </b-col>
                   </b-row>
                   <b-row class="">
                       <b-col class="6">
                           <div class="position-relative mb-5">
                               <div class="overlap__image__container">
                                   <b-row class="px-3 py-3">
                                       <b-col class="">
                                           <img class="w-100 ml-5" src="@/assets/christianal__img.png">
                                       </b-col>

                                       <b-col class="overlap__image">
                                           <img class="w-50 pb-5" src="@/assets/image 4.png">
                                       </b-col>
                                   </b-row>
                               </div>
                               
                           </div>
                        

                       </b-col>
                       <b-col class="px-5 py-5">
                           <h4 class="mr-5 mt-5 pt-5 display-4 marsha__para"> 
                              <span class="mx-5 px-2"> Marshal — Creating a</span>
                                dynamic and scalable design 
                               language to help power the future.
                            </h4>

                            <div class="">
                                <b-row class="px-5 py-5">
                                    <b-col class="">
                                        <img  class="ml-3" src="@/assets/clientforce-logo.svg">
                                        
                                    </b-col>
                                    <b-col class="px-3">
                                        <p class="pr-5 p-2" style="color: #767376">UI/UX Branding, development</p>
                                    </b-col>
                                    
                                
                                  
                                </b-row>
                                
                                    
                            </div>
                       </b-col>
                       
                   </b-row>
                   <b-col class="px-1 py-1">
                            <router-link>
                                <img class="" src="@/assets/left-button.png">  
                            </router-link>
                        </b-col>
                </div>
             </b-col>
        </b-row>
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
.homepage__top {
    background-color: #11271F;
    position: relative;
    margin-top: -50px;
    .heading{
        color: #fff;
        font-size:18.76px;
        .ten{
            color:#FEAC5E;
        }
    }
    .headings{
        color:#fff;
        font-size:70.51px
        
    }
    .image__frame__container{
        background-color:#4D4D4D45;
        .dashboard__img_container{
            background:#11271F ;
        }
        .second__dashboard__image{
            margin-left:-200px;
        }
        
        }
    .storyteller_para{
        font-size:19.4px;
    }
    .overlap__image{
        
        margin-left: -470px;
        padding-top:330px;
        
    }
    .marsha__para{
            color:#ffff;
            margin-left:-170px;
            
        }
}

        
        
        

    
</style>
