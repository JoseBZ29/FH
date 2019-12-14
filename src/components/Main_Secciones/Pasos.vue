<template>
      <section class="full-width formated-section">
		<h1 class="text-center font-oswald" style="font-family:'Montserrat', sans-serif;">Encuentra el mejor trabajo de acuerdo a tu perfil y experiencia!</h1><br>
    <h1 class="text-center font-oswald" style="font-family:'Montserrat', sans-serif;">Te ayudamos a OBTENER TRABAJO en solo 4 pasos...</h1><br>
    <div class="container">
			<div class="row">
				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-3" justify-self="center">
          <v-col md="12" cols="12"><v-row justify="center">
          <img src="https://i.ibb.co/4JmvGgP/regis.png" alt="Sucursal" class="img-responsive"><br>
          </v-row>
					<h3 class="text-center" style="font-family:'Montserrat', sans-serif;">Registrate!</h3>            
          <v-row justify="center">
              <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Elige un usuario y contraseña.
					</span><br>
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Añade tu CV a nuestra plantilla.
          </span>
            </v-row>
          </v-col>

				</div>
				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-3" justify-self="center">
          <v-col md="12" cols="12"><v-row>
					<img src="https://i.ibb.co/FbzjjbJ/postulate.png" alt="Sucursal" class="img-responsive2"></v-row>
					<h3 class="text-center" style="font-family:'Montserrat', sans-serif;">Postulate!</h3>
					<v-row justify="center">
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Ingresa el puesto o zona de trabajo.
					</span><br>
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Revisa el listado de vacantes.
          </span><br>
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						 - Elige el mas adecuado a tu perfil.
          </span>
					</v-row>
          </v-col>
				</div>
				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-3">
          <v-col md="12" cols="12" ><v-row>
					<img src="https://i.ibb.co/0cwWB4M/entrevis.png" alt="Sucursal" class="img-responsive3"></v-row>
					<h3 class="text-center" style="font-family:'Montserrat', sans-serif;">Entrevistate!</h3>
          <v-row justify="center">
					<span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Administra tus postulaciones.
					</span><br>
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Recibe alertas de tu candidatura.
          </span><br>
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Revisa tu fecha de entrevista.
          </span>
          </v-row>
          </v-col>
				</div>
				<div class="col-xs-12 col-sm-12 col-md-6 col-lg-3">
          <v-col md="12" cols="12" ><v-row justify="center">
					<img src="https://i.ibb.co/s91fmzd/traba.png" alt="Sucursal" class="img-responsive4"></v-row>
					<h3 class="text-center" style="font-family:'Montserrat', sans-serif;">A Trabajar!</h3>
          <v-row justify="center">
					<span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Recibe notificaciones si eres finalista.
					</span><br>
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Envia tu informacion.
          </span><br>
          <span class="tex" style="font-family:'Montserrat', sans-serif;">
						- Recibe la informacion de la empresa.
          </span><br>
          </v-row>
          </v-col>
          
				</div>
        <v-row justify="center">
              <v-btn x-large rounded color="secondary" style="margin-right:15px; font-family: 'Montserrat', sans-serif;" class="holas">Encontrar Trabajo</v-btn>
              </v-row><br>
			</div>
		</div><br>
	</section>
    
</template>
<script>
  export default {
    data () {
      return {
      }
    },
  }
</script>
<style>

.img-responsive{
  width: 150px;
  height: auto;
  margin-left: 65px;
  
}
.img-responsive2{
  width: 150px;
  height: auto;
  margin-left: 55px;
  
}
.img-responsive3{
  width: 150px;
  height: auto;
  margin-left: 55px;
  
}
.img-responsive4{
  width: 150px;
  height: auto;
  margin-left: 70px;
  
}
@media only screen and (max-width: 768px) {
  .img-responsive2{
  width: 150px;
  height: auto;
  margin-left: 100px;
  
}
.img-responsive3{
  width: 150px;
  height: auto;
  margin-left: 100px;
  
}
}
</style>