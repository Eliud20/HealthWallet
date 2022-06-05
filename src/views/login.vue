<template>
<v-container>
   <img id="logo" class="itemheader" src="@/assets/tasa-de-cafe.png">
   <div class=topright>No tienes cuenta?
      <v-btn rounded outlined><b>Registrate</b>
      </v-btn>
   </div>
   <v-layout >
      <v-flex>
         <div class=centered>
            <h1>Bienvenido</h1>
            <v-text-field
               type="password"
               label="Correo Electronico"
               rounded
               single-line
               outlined></v-text-field>
            <v-text-field
               type="password"
               label="Contraseña"
               rounded
               single-line
               outlined
               class="shrink">
            </v-text-field>
               <v-col align="center" justify="space-around">
                  <v-btn id="logbtn" rounded color="#fff176"><b>Ingresar</b></v-btn>
               </v-col>
               <div class="test">
                  <hr class="solid">
                  Ingresar con
               </div>
               <div>
                  <v-col align="center">
                     <div>
                        <v-btn id="SocialMediabtn"
                        rounded
                        outlined
                     >
                        <img src="@/assets/twitter.png">
                        Ingresar con Twitter
                        </v-btn>
                     </div>
                     <div>
                        <v-btn id="SocialMediabtn"
                        rounded
                        outlined
                        >
                        <img src="@/assets/facebook.png">
                        Ingresar con Facebook
                        </v-btn>
                     </div>
                     <div>
                        <v-btn id="SocialMediabtn"
                        rounded
                        outlined
                        >
                        <img src="@/assets/google.png">
                        Ingresar con Google
                        </v-btn>
                     </div>
                  </v-col>
               </div>
         </div>
      </v-flex>
   </v-layout>
</v-container>
</template>

<script>
export default {
}
</script>

<style scoped>
   h1{
      text-align: center;
      color:black;
      margin: 30px;
   }

   #logo{
      width: auto;
      height: 50px;
      margin: 10px;
      position: absolute;
      top: 8px;
      left: 0px;
      }
   .topright{
      position: absolute;
      top: 30px;
      right: 16px;
      font-size: 18px;
      }
   .topleft{
      position: absolute;
      top: 30px;
      left: 16px;
      font-size: 18px;}
      .centered {
      width: auto;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
   }

   #logbtn
   {
      width:300px;
      height: 50px;
   }
   #vdivider
   {
      width:50px;
   }
   .test
   {
      text-align: center;
      margin-bottom: 5px;
      margin-top: 32px;
   }
   #SocialMediabtn
   {
      width:300px;
      height: 50px;
      margin: 10px;
   }
   hr.solid {
      border-top: 3px solid #bbb;
      margin:10px;
   }

</style>
