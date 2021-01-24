<template>
  <div id="app flex container mx-auto px-10 bg-gray-200">
    <div class="mx-20  mt-5 flex h-screen w-3/4  justify-center">
      <div
        class="bg-gray-500 bg-opacity-90 w-80 rounded-l rounded-t p-4 flex flex-col items-center"
      >
        <div class="w-40 h-40 rounded-full">
          <img
            class="rounded-full w-40 h-40 object-cover"
            src="https://images.unsplash.com/photo-1582233479366-6d38bc390a08?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1361&q=80"
          />
        </div>
        <div class="text-2xl text-white font-bold">Arkadiusz Stępak</div>
        <div class="text-lg text-white border-b-2 w-full mt-10">INFO</div>
        <div class="flex flex-col text-gray-300 mt-5">
          <div class="flex items-center text-sm mb-2">
            <font-awesome-icon
              class="text-3xl"
              icon="envelope"
            ></font-awesome-icon>
            <div class="flex flex-col mx-3">
              <div class="text-lg">Email</div>
              <div class="font-bold">stepakarkadiusz@gmail.com</div>
            </div>
          </div>

     <div class="flex items-center text-sm mb-2  ">
            <font-awesome-icon
              class="text-3xl"
              icon="birthday-cake"
            ></font-awesome-icon>
            <div class="flex flex-col mx-3">
              <div class="text-lg">Birth Date</div>
              <div class="font-bold">Apr 19, 1993</div>
            </div>
          </div>

               <div class="flex items-center text-sm mb-2">
            <font-awesome-icon
              class="text-3xl"
              icon="map-marker-alt"
            ></font-awesome-icon>
            <div class="flex flex-col mx-3">
              <div class="text-lg">Habitation</div>
              <div class="font-bold">Wojnicz, Poland</div>
            </div>
          </div>


        </div>
      </div>
      <div class="bg-gray-100 flex-1 border bg-opacity-50">
        <div class="bg-white rounded-sm m-4 shadow h-full bg-opacity-90 h-screen">
          
   <particles-bg  type="cobweb" :num=500 :alpha=2 :color="'#aaaaaa'" :config="config" :bg="true" />

        </div>
      </div>
    </div>
  </div>
</template>

<script>

import { ParticlesBg } from "particles-bg-vue";


export default {
  name: "App",
  components: {ParticlesBg},

 data: function() {
    return {
      config: {
 
      
        alpha: [0.1, 0],
      
      }
    };
  }


};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
