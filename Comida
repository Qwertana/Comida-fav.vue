<template>
  <div>
  <input type="text" v-model="nome" placeholder="seu nome?">
  <p v-if="comida === ''">Digite seu nome::</p>
   <input type="text" v-model="comida" placeholder="comida favorita?">
   <p v-if="comida === ''">Digite sua comida favorita:</p>
  <p v-else=>Olá, {{ nome }}, sua {{ comida }} chegará em breve!</p>
  </div>
</template>

<script setup>
import {ref} from 'vue'

const nome = ref('')
const comida = ref('')
</script>
