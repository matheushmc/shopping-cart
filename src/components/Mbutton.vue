<script setup>
const props = defineProps({
    texto: String
})    
</script>



<template>

<button type="button">{{ props.texto }}</button>

</template>


<style scoped>
button {
  background-color: rgb(0, 0, 0);
  color: white;
  font-size: 1rem;
  border: 1px solid rgb(0, 0, 0);
  border-radius: 5px;
  padding: 5px 10px;
  cursor: pointer;  
}

button:hover{
background-color: white;
color: black;
border: 1px solid rgb(0, 0, 0);
padding: 5px 10px;
}

</style>