<template>
<div>
  <div class="h-100 insightpage__top p-0 m-0 position-relative">
      <div class="col-8 px-5">
          <div class="col-12 pl-5 build_grow">
             <h1 class="pl-5"><span class="display-4 build">Build <span class="dot display-2">.</span></span><span class="display-3 grow"> Grow <span class="dot display-3">.</span></span></h1>
          </div>
          <div class="p-0 m-0 col-12 pl-5 ">
               <h1 class="pl-5 "><span class="display-4 serve">Serve <span class="dot display-3 ">.</span></span> <span class="position-absolute  px-2"><p class="paragraph pl-2"> We shape the products and services that 
                   improve the lives of thousands every single day.</p></span>
                </h1>
          </div>
      </div>

      <b-row class="p-5 m-5">
          <b-col col="6" class="">
              <img src="@/assets/images/group_image_1.png">
          </b-col>

          <b-col col="6" class="@/assets/images/group_image_2.png">
              <img src="">
          </b-col>
      </b-row>
  </div>
</div>
    
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.dot{
    color:#FDCA55;
}
.grow{
    font-size:100px
}
.paragraph{
    font-size:15px;
    margin-left:340px
}
.build{
font-size:100px
}
.build_grow{
 margin-left:150px;
 
}
.serve{
    margin-left:100px;
    margin-top:-50px;
    position: absolute;
}
</style>