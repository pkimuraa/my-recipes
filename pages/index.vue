<template>
  <div class="container">
    <div class="center grid">
      <vs-row>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" w="12">
            <NuxtLink to="/createRecipe">
              <vs-card type="2">
                <template #title>
                  <h3>Criar uma receita</h3>
                </template>
                <template #img>
                  <img src="../assets/img/knife.png" alt="">
                </template>
                <template #text>
                  <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                  </p>
                </template>
              </vs-card>
            </NuxtLink>
        </vs-col>
      </vs-row>
    </div>
  </div>
</template>

<script>


export default {
  data() {
    return{
      value: '',
    }  
  },
}
</script>

<style>

</style>
