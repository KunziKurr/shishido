<template>
  <div class="base">
    <HeaderSection />
    <!-- end of header section -->
    <!-- base component -->
    <div class="base_container">
      <div class="base_container_controller">
        <div class="base_container_controller_sub1">
        <div class="base_container_controller_sub1_wrapper">
          <button class="base_container_controller_sub1_wrapper_btn_left">
           <svg version="1.1" xmlns="http://www.w3.org/2000/svg" width="768" height="768" viewBox="0 0 768 768">
              <path d="M513 352.5v-96l127.5 127.5-127.5 127.5v-96h-385.5v-63h385.5z"></path>
            </svg>
          </button>
          <div class="base_container_controller_sub1_wrapper_mid_cont">
            <span class="base_container_controller_sub1_wrapper_mid_cont_headline">SHISHIDO</span>
            <div class="base_container_controller_sub1_wrapper_mid_cont_seller">
              <!-- IMAGE -->
            </div>
          </div>
          <button class="base_container_controller_sub1_wrapper_btn_right">
           <svg version="1.1" xmlns="http://www.w3.org/2000/svg" width="768" height="768" viewBox="0 0 768 768">
             <path d="M513 352.5v-96l127.5 127.5-127.5 127.5v-96h-385.5v-63h385.5z"></path>
            </svg>
          </button>
        </div>
        </div>
        <div class="base_container_controller_sub2">
          <div class="base_container_controller_sub2_wrapper">
          <div class="base_container_controller_sub2_wrapper_container">
            <div class="base_container_controller_sub2_wrapper_price">
              KSH 1,200
            </div>
            <div class="base_container_controller_sub2_wrapper_ratings">
              <svg id="icon-star_outline" viewBox="0 0 24 24" height="25" width="23">
                <path d="M12 15.422l3.75 2.25-0.984-4.266 3.328-2.906-4.406-0.375-1.688-4.031-1.688 4.031-4.406 0.375 3.328 2.906-0.984 4.266zM21.984 9.234l-5.438 4.734 1.641 7.031-6.188-3.75-6.188 3.75 1.641-7.031-5.438-4.734 7.172-0.609 2.813-6.609 2.813 6.609z"></path>
              </svg>
              <svg id="icon-star_outline" viewBox="0 0 24 24" height="25" width="23">
                <path d="M12 15.422l3.75 2.25-0.984-4.266 3.328-2.906-4.406-0.375-1.688-4.031-1.688 4.031-4.406 0.375 3.328 2.906-0.984 4.266zM21.984 9.234l-5.438 4.734 1.641 7.031-6.188-3.75-6.188 3.75 1.641-7.031-5.438-4.734 7.172-0.609 2.813-6.609 2.813 6.609z"></path>
              </svg>
              <svg id="icon-star_outline" viewBox="0 0 24 24" height="25" width="23">
                <path d="M12 15.422l3.75 2.25-0.984-4.266 3.328-2.906-4.406-0.375-1.688-4.031-1.688 4.031-4.406 0.375 3.328 2.906-0.984 4.266zM21.984 9.234l-5.438 4.734 1.641 7.031-6.188-3.75-6.188 3.75 1.641-7.031-5.438-4.734 7.172-0.609 2.813-6.609 2.813 6.609z"></path>
              </svg>
              <svg id="icon-star_outline" viewBox="0 0 24 24" height="25" width="23">
                <path d="M12 15.422l3.75 2.25-0.984-4.266 3.328-2.906-4.406-0.375-1.688-4.031-1.688 4.031-4.406 0.375 3.328 2.906-0.984 4.266zM21.984 9.234l-5.438 4.734 1.641 7.031-6.188-3.75-6.188 3.75 1.641-7.031-5.438-4.734 7.172-0.609 2.813-6.609 2.813 6.609z"></path>
              </svg>
              <svg id="icon-star_outline" viewBox="0 0 24 24" height="25" width="23">
                <path d="M12 15.422l3.75 2.25-0.984-4.266 3.328-2.906-4.406-0.375-1.688-4.031-1.688 4.031-4.406 0.375 3.328 2.906-0.984 4.266zM21.984 9.234l-5.438 4.734 1.641 7.031-6.188-3.75-6.188 3.75 1.641-7.031-5.438-4.734 7.172-0.609 2.813-6.609 2.813 6.609z"></path>
              </svg>
            </div>
            <div class="base_container_controller_sub2_wrapper_desc">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit, eaque magni.
              Ducimus minus optio consequuntur.
              Est suscipit explicabo, nostrum distinctio et architecto illum numquam rerum,
              incidunt ullam magnam, optio vitae.
            </div>
          

          </div>
            <div class="base_container_controller_sub2_buy_now">
              BUY NOW
               <svg version="1.1" xmlns="http://www.w3.org/2000/svg" width="768" height="768" viewBox="0 0 768 768">
              <path d="M513 352.5v-96l127.5 127.5-127.5 127.5v-96h-385.5v-63h385.5z"></path>
            </svg>
            </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HeaderSection from './Header.vue'
export default {
  name: 'BaseContainer',
  components:{
      HeaderSection
  }

}
</script>

<style lang="scss">
  @import '../../scss/base.scss';
</style>
