<template>
 <div class="grey container">
        <v-img class="image" src="../assets/tumblr_pqxqaoW2jv1tawn8uo1_1280.png.jpg" style="margin:auto;height: 620px;border-radius: 5px;" >
          
          
          
          <h1 style="margin-top: 70px;color: aliceblue;padding: 1px;width: 8%;height: 420px;margin-left: 900px;">
            <p>H</p><br>
            <p>O</p><br>
            <p>M</p><br>
            <p>E</p><br>
          </h1>
        </v-img>
      </div>

</template>

<script lang="ts">
import { defineComponent } from 'vue';



export default defineComponent({
  name: 'HomeView',


});
</script>
<style scoped>
#allbck{
  background-image: url(../assets/weatherApp.jpg);
 background-repeat: no-repeat;
 background-size: cover;
}
#header {
  display: flex;
  background-color: blue;
  margin: 10px 10px;
  color: aliceblue;
  border-radius: 3px;
  border: 1px solid black;
  height: 10%;
}

#parag{
  font-size: 30px;
  margin: auto;
}
p{
  font-size: 60px;
}


</style>
