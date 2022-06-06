<template>
    <div class="h-100 joinpage__top p-0 m-0 mb-5 position-relative">
        <!-- join us page start here -->
        <div class="col-12 joinpage_section_1">
            <div class="col-10 mx-auto">
                <div class=" position-absolute   joinpage_section_1-spot-bg">
                    <img src="@/assets/images/Spots.svg" width="100%">
                </div>
                 <div class="d-flex joinpage_section_1-info mx-auto">
                    <p class="joinpage_section_1-para mt-4 mx-5 pl-5 justify-between-content ">Digital agency helping SaaS brands <br><span class="joinpage_section_1-para-right">build amazing websites</span></p>     
                    <h1><span class="joinpage_section_1-quando ">Let’s start </span></h1>    
                </div>
                 <div class="mx-2">
                     <h1 class="joinpage_section_1-project postion-absolute mx-5 pl-5 display-1">a project together<span class="joinpage_section_1-project-dot">.</span></h1>
                     
                 </div>  
                <div class="col-12 p-5 m-5 text-center">
                    <div class=" col-8 mx-auto">
                        <p class="mx-5 perhaps">Perhaps there’s a way your business could benefit by partnering with 
                            BB Agency? Please share your thoughts in the form below, and we’ll 
                            respond within 48 hours of receiving the inquiry. 
                        </p>
                    </div>
                    <div class="pt-5">
                        <img src="@/assets/images/downward-arrow.png">
                    </div>

        <div class="col-12 form-container pt-5 mt-5">
            <form class=" col-12 form-container-signup-form pt-5">
                <div class=" col-12 input-container mb-5">
                    <label class="">My name is</label><span class="mx-5"><input id="name" type="" placeholder="Okoyomon Paul"  required/></span>
                    <label class="">and I work with</label> <span class="mx-3"> <input class="" id="company_name" type="text" placeholder="Company name" required /></span>
                </div>
                <div class="col-12 input-container mb-5  px-3">
                    <label class="">I’m looking for a partner to help me with</label> <span class=""> <input class="" id="goal" type="text" placeholder="My Goal" required /></span>

                </div>

                <div class="col-12 input-container mb-5 ">
                    <label  class="">with an idea of having that completed on</label> <span class=""> <input class="" id="completed date" type="text" placeholder="Date" /></span>
                </div>
                <div class="input-container mb-5">
                    <label class="">am hoping to stay around a budget range of</label>
                    <span class="mx-4">
                        <select id="price" class="mx-3" name="price">
                            <option>$250.00 - $500.000</option>
                            <option>$550.00 - $750.000</option>
                            <option>$800.00 - $1000.000</option>
                            <option>$1250.00 - $1500.000</option>
                            <option>$1550.00 - $2000.000</option>
                        </select>
                    </span>    
                </div>
                <div class="input-container mb-5">
                    <label class="">You can reach me at</label> <span class="mx-5"><input id="email" type="email" placeholder="Email Address"></span>
                </div>
            </form>
            
        </div>            
            </div>   
                <div class="col-12 mx-5">
                    <div class="col-10  mx-5">
                        <span>
                            <h3 class="mx-5 py-4 px-4">
                                <span class=""><img class="" src="@/assets/images/messages-2.png"></span> 
                                <span class="mx-2 joinpage_section_1-message">To start the conversation.<br>Optionally, I’m sharing more</span>
                            </h3>
                        </span>
                    </div>
                </div>
                <div class="col-12 mb-5 mx-5 my-4">
                    <div class="col-8 joinpage_section_1-project_1 mx-5">
                        <textarea class="joinpage_section_1-textarea mx-5" placeholder="Project Details"></textarea>
                    </div>
                </div>
                <div class="col-12">
                    <div class="col-12 p-5 m-5">
                        <div class="col-8  mb-5 text-center">
                            <router-link  to="/" class=" joinpage_section_1-btn position-absolute">
                                Our approach
                            </router-link>
                        </div>
                        <div class="col-10 pt-3">
                            <p class="text-center">By clicking on “Send Inquiry” button, you agree to our Privacy Policy, and allow The Brander Agency to use this information for marketing purposes.</p>
                        </div>
                    </div>
                    
                </div>
               
            </div>
        </div>  
        
    <!-- joinpage section_2 start here -->
        <div class="joinpage_section_2 p-5">
            <b-row class="col-12  mx-auto my-3 project pt-5 mt-5">
                <b-col cols="6">
                    <div class="text-justify d-flex align-items-end">
                        <div class="my-5 mx-5">
                            <h1 class=" mx-3 mt-4 pl-5 ml-5 project_title quando">If you prefer, send us an email for new business opportunities or job openings.</h1>
                        </div>
                    
                    </div>
                    <div class="mb-5 pt-4">
                        <router-link  to="/" class="ml-5 project_btn">
                            <img src="@/assets/images/open_position_btn.png" width="40%" class="mx-5 pl-5 ml-5">
                        </router-link>
                    </div>
                    <div class="joinpage_section_2-zigzag">
                               <img class="zigzag_image" src="@/assets/images/zigzag_image.png" height="250px">    
                    </div>
                    </b-col>
                    <b-col cols="6" class="">
                        <div class="">
                            <img src="@/assets/images/cup_image.png" height="100px"><span class="px-4">Hello There! I’m Lamii Lambo</span>
                            
                        </div>

                        <div class="pt-3">
                            <img src="@/assets/images/textarea_image.png" class="w-100" height="130px">
                        </div>
                    </b-col>
                </b-row>
            </div>
            <div class="joinpage_section_3 p-5">
                <div class="col-12 mx-4 my-4 pt-5">
                    <div class="col-12 mx-5">
                        <div class="col-10">
                            <h1 class=" display-2 mx-2">Get a better understanding of our capabilities. </h1>
                            <div class="mb-5">
                                <router-link  to="/" class=" joinpage_section_3-btn mx-5 my-4 position-absolute">
                                    Our Services
                                </router-link>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
    </div>
        
</template>

<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.joinpage_section_1{
    &-spot-bg{
        mix-blend-mode: soft-light; 
        background-size: 100% 100%;
        left:200px
    
    }
    &-para{
        color:#11271F
    }
    &-para-right{
        float:right
    }
    &-quando{
       font-family: 'quando', serif; 
       font-size: 100px;
       
    }
    &-perhaps{
        color:#11271F
    }
    &-project{
       
       &-dot{
           color:#FDCA55;
       }
    }
    &-textarea{
        background-color: #000;
        height: 300px;
        width:100%;
        color:#fff
    }
    &-message{
        font-family: 'quando', serif;
        font-size: 36.75px;
    }
    &-btn{
        background: #FEAC5E;
        justify-content: center;
        color: #000;
        border-radius: 2px;
        padding: 10px 20px;
        font-size:18px;
        
        
        &:hover {
            text-decoration: none;
            background: #faae68;
        }
    }
    }
    .form-container{
        
        &-signup-form{
        
        }
        #name{
            background: #000;
            padding:10px 15px;
            color:#fff;
            
        }
        input[type=text]{
        background: transparent;
        border:none;
        border-bottom: 2px solid #193F31;
        }
        input[type=email]{
            background: transparent;
            border:none;
            border-bottom: 2px solid #193F31;
        }
        select{
        background: transparent;
            border:none;
            border-bottom: 2px solid #193F31;
        } 
        label{
            font-size: 20px;
        }  
    }    
    

.joinpage_section_2{
    background: #FFFFFFA1;
    &-zigzag{
        position:absolute;
        bottom: -200px;
        right:-200px
    }
}
.joinpage_section_3{
    &-btn{
        background: #FEAC5E;
        justify-content: center;
        color: #000;
        border-radius: 2px;
        padding: 10px 20px;
        font-size:18px;
        bottom:0px;
        right:150px;
        &:hover {
            text-decoration: none;
            background: #faae68;
        }
    }
}

</style>