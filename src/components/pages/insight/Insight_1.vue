<template>
<div>
  <div class="h-100 insightpage__top p-0 m-0 position-relative">
      <!-- insight section_1 start here -->
      <div class="col-8 px-5 ">
          <div class="col-12 mx-auto justify-content-between">
             <h1 class="mx-5 build_grow"><span class="display-4 build">Build <span class="dot display-2">.</span></span><span class="display-1 grow"> Grow <span class="dot display-3">.</span></span></h1>
          </div>
          <div class="p-0 m-0 col-12 pl-5 ">
               <h1 class="pl-5 ml-4"><span class="quando">Serve <span class="dot display-3 ">.</span></span> <span class="position-absolute"><p class="paragraph p-3 m-3"> We shape the products and services that 
                   improve the lives of thousands every single day.</p></span>
                </h1>
          </div>
      </div>

      <b-row class="p-5 m-5">
          <b-col col="6" class="">
            <img src="@/assets/images/group_image_1.png" width="100%">
          </b-col>

          <b-col col="" class="pt-5 mt-5 m-5">
               <img class="pt-5 mt-5" src="@/assets/images/group_image_2.png" width="100%">
          </b-col>
      </b-row>
      <b-row class="p-5 m-5">
          <b-col col="6" class="">
            <img src="@/assets/images/group_image_3.png" width="100%">
          </b-col>

          <b-col col="" class="pt-5 mt-5 m-5">
               <img class="pt-5 mt-5" src="@/assets/images/group_image_4.png" width="100%">
          </b-col>
      </b-row>
      <!-- insight section_1 end here -->
      <img src="@/assets/images/ring_group.svg" height="150px" class="float-right ring_group">
      <div class="insight_section_2 p-5">
          <b-row class="">
              <b-col cols-sm="12" cols="6">
                  <h1 class="quando pl-5">Building amazing SaaS websites.</h1>
                  <p class="mx-5 my-5 offer">We offer package solutions to help fast-growing 
                      SaaS companies scale up their website in line with
                       their expanding workforce and customer base.
                  </p>
              </b-col>
              <b-col cols-sm="12" cols="6" class="new_person_frame_image">
                  <img src="@/assets/images/new_person_image.png" height="900px" class="w-100">
                  <img src="@/assets/images/frame_image.png"  height="300px" class="w-100  position-absolute frame_image ">
                  
              </b-col>
          </b-row>

          
      </div>

     </div>
</div>
    
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.insightpage__top{
    background: #DCDCDC;
    .dot{
        color:#FDCA55;
    }
    .build_grow{
        padding-left:100px
    }
    .grow{
        font-size:100px;
        font-weight:500
    }
    .paragraph{
        font-size:15px;
        
    }
    .build{
        font-size:100px
    }
    
    .quando{
        font-family: 'Quando', serif;
        font-size: 60px;
        

        
    }
    .insight_section_2{
        background-color: #FEAC5E80;
        .offer{
            font-size:28px
        }
        .new_person_frame_image{
            margin-top:-50px;
            .frame_image{
            left:-250px;
            bottom:-50px
            }

        }
        
    }

    .ring_group{
        margin-top:-60px
    }
}
</style>