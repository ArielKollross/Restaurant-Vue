<template>
  <transition name="slide" appear>
    <div class="modal">
      <v-card class="card">
      <v-card-title>Novo Prato</v-card-title>
      <v-text-field 
        class="input"
        label="URL da imagem" 
        outlined 
        solo 
        flat></v-text-field>
      <v-text-field 
        class="input" 
        label="Nome do prato" 
        outlined 
        solo 
        flat></v-text-field>
      <v-text-field 
        class="input-price" 
        label="Preço" 
        value="R$ " 
        outlined 
        solo 
        flat></v-text-field>
      <v-text-field 
        class="input" 
        label="Descrição do produto" 
        outlined 
        solo 
        flat></v-text-field>
      <v-btn color="success" depressed class="button">Adicionar Prato</v-btn>
    </v-card>
    </div>
  </transition>
</template>

<script>
export default {};
</script>
<style>
.modal {
  position: absolute;
  top: 0px;
  left: 0px;
  width: 736px;
  height:564px;
  
}
.card{
  background: #F0F0F5;
  border-radius: 8px;
}
.button{
  display: flex;
  align-self: center;
  padding: 15px;
  text-align: center;  
}
.input{
  padding: 15px;
}
</style>