<template>
    <div class="h-100 homepage__top">
        <!-- start changes here -->
        <h1 class="display-3">
           <span class="mx-5" style=""> Creating <span class=""><img style="height:40px" src="@/assets/ring.svg"></span> Products <span class=""><img style="height:13px" src="@/assets/left-arrow.svg"></span>
            <span class=""><img  style="height:40px" src="@/assets/bud.svg"></span></span><br>
            <span class="font-italic mx-5" style="padding-left:160px;">With outstanding <span class=""><img style="height:40px" src="@/assets/elipse-shape.svg"></span> Visual</span><br>
            <span class="mx-5" style="padding-left:320px">and Great <span class=""><img style="height:40px" src="@/assets/wave-shape.svg"></span>Functionality</span>
        </h1>

        <div class="vertival__line">
            <span class="copy__right">
                <img style="height:200px" src="@/assets/vertical__line.png">
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
                            <img style="height:100px; padding-left:297px" src="@/assets/contact-us.svg">
                        </router-link>
                    </b-col>
                </b-row>
            </b-col>
        </b-row>
        <div class="down__overlay">
        <b-row>
            <b-col cols-sm="12" cols="4">
                <span class=""><img style="height:630px" src="@/assets/sylvia-image.svg"></span>
                
            </b-col>
            <b-col cols-sm="12" cols="2" class="recent__work">
                <router-link to="/work">
                    <span class=""><img style="height:80px;" src="@/assets/Recent-work.svg"></span>
                </router-link>
            </b-col>
            <b-col cols-sm="12" cols="6" class="d-inline-flex " style="margin-top:130px">
               <span class="first-rec p-2">
                    <h4 class="pt-5 mx-5">Clic</h4>
                    <p class="mx-5" style="color: #767376;">UI/UX Design Branding</p>
               </span>
               <span class="second-rec p-2">
                      <h4 class="pt-5 mx-3 text-white">Rainmaker</h4>
                      <p class="mx-3" style="color: #767376;"> UI/UX Design, Branding, Development</P>
                      <router-link to="/">
                      
                      <span class=""><p class="case__study pt-5 mx-3" style="color: #767376">Read Case Study
                          <img src="@/assets/case-study-arrow.svg">
                      </p></span>
                      

                      </router-link>

               </span>
               <span class="third-rec p-2">
                      <h4 class="pt-5 mx-4">ADA Compliance</h4>
                      <p class="mx-4" style="color: #767376;">UI/UX Design Branding</p>

                      <p></p>
               </span>
                
            </b-col>
               
        </b-row>
        </div>
        


        
            

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
.homepage__top {
//  background: #DCDCDC;
}
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
    margin-top:130px;
}
.first-rec{
    border:2px solid #11271F;
    width:220px;
    height:350px;

}
.second-rec{
        border:2px solid #11271F;
        width:220px;
        height:350px;
        background:#11271F; 

}
.third-rec{
        border:2px solid #11271F;
        width:220px;
        height:350px;

}
.case__study{
    text-decoration: none;
  
}
.down__overlay{
    position:relative;
    width:100%;
}
.overlay{
    position: absolute;
    background:#C4C4C480;
    top:0px;
    width:100%
}
    


</style>
