<template>
    <div class="h-100 homepage__section_2 p-5">

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
                <b-col class="">
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
.homepage__section_2 {
    background-color: #11271F;
    position: relative;
    color: #fff;
    & .quando {
        font-family: 'Quando', serif;
    }
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
</style>
