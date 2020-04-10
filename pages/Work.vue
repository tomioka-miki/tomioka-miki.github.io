<template>
    <div class="container" id="work">
        <div>
            <h2>Work</h2>
        </div>
        <div class="work_items">
            <div class="img_wrap">
              <img src="~/assets/images/todo-app.png" alt="" @click="modal1=true;">
              <p>TODO App</p>
            </div>
            <div class="img_wrap">
              <img src="~/assets/images/Meow.png" alt="" @click="modal2=true;">
              <p>Portfolio Site</p>
            </div>
        </div>
        <Modal1 @closeModal="modal1=false" v-if="modal1"/>
        <Modal2 @closeModal="modal2=false" v-if="modal2"/>
  </div>
</template>

<script>
import Modal1 from '~/components/pages/Modal1.vue'
import Modal2 from '~/components/pages/Modal2.vue'

export default {
 components: {
   Modal1,
   Modal2
 },
 data () {
   return {
     modal1: false,
     modal2: false,
   }
 }
}
</script>