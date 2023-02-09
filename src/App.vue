<template>
  <v-app>
    <v-main>
      <div class="card" style="display: inline-block; margin: 10px 10px 10px 90px">


        <router-link to="/" active-class="active" exact>
  
  
          <v-btn>
            <span>Home</span>
          </v-btn>
  
  
  
  
        </router-link>
      </div>
      <div class="card" style="display: inline-block; margin: 10px 5px">


<router-link to="/about" active-class="active" exact>


  <v-btn>
    <span>About</span>
  </v-btn>




</router-link>
</div>      <div class="card" style="display: inline-block; margin: 10px 5px">


<router-link to="/weather" active-class="active" exact>


  <v-btn>
    <span>Weather</span>
  </v-btn>




</router-link>
</div>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',

  data() {
    return {
      //
    }
  },
})
</script>
