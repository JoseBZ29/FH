<template>
  <section class="full-width formated-section">
    <h1 class="text-center" style="font-family:'Montserrat', sans-serif;">
      Empresas mejor valoradas!
    </h1>
    <br />
    <v-container>
      <v-row justify="center">
        <v-col md="3" v-for="n in 8" :key="n" justify-self="center">
          <v-col md="12" cols="12">
            <img
              class="card-img-top"
              src="https://i.ibb.co/Pctz82v/dd127127306ca52c740b75fca6c4f4e6.png"
              alt="Sucursal"
            />
          </v-col>
          <v-col justify-self="center" md="12" cols="12">
            <v-row justify="center">
              <v-rating
                class="card-img-body ra"
                v-model="rating"
                color="yellow darken-3"
                background-color="grey darken-1"
                empty-icon="$ratingFull"
                half-increments
                hover
              ></v-rating>
            </v-row>
          </v-col>
        </v-col>
      </v-row>
    </v-container>
    <v-divider style="margin-left:220px;margin-right:220px"></v-divider>
  </section>
</template>

<script>
export default {
  data: () => ({
    rating: 0,
    rating2: 0,
    rating3: 0,
    rating4: 0,
    rating5: 0,
    rating6: 0,
    rating7: 0,
    rating8: 0
  })
};
</script>