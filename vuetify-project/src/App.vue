<template>
  <v-app theme="dark"> 
  <VAppBar>
    <VAppBarTitle>My App</VAppBarTitle>
  </VAppBar>
    <v-main>
      <h1 class="text-teal-accent-2 ma-5">
          Hello vue
        </h1>
      <v-container>
        <v-row>
          <v-col v-for="n in 4" :key="n"> 
            <v-card max-width="350" class="">
              <v-img src="https://images.pexels.com/photos/70080/elephant-africa-african-elephant-kenya-70080.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="align-end text-white  ">
                <v-card-title primary-title  >
                  Animais fantasticos
                </v-card-title>
              </v-img>
              <v-card-subtitle class="mt-4">
                <h3>Animais africanos</h3>
              </v-card-subtitle>
             <v-card-text>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste id quibusdam repellendus quas mollitia officiis repudiandae, consequuntur dolore tempore. Pariatur accusamus eligendi recusandae assumenda quam et nesciunt quasi iste voluptatem.
             </v-card-text>
             <v-card-actions>
               <v-btn color="success ma-2">Ver mais</v-btn>
               <v-btn color="success ma-2">Explorar</v-btn>
             </v-card-actions>
            </v-card>
          </v-col>
        </v-row>

      </v-container>
      <!-- <HelloWorld /> -->
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
  import HelloWorld from '@/components/HelloWorld.vue'
import { VCol, VRow } from 'vuetify/lib/components/index.mjs';
</script>
