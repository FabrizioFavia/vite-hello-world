<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "Jumbo",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <img src="../assets/pexels-photo.jpg" alt="">
</template>

<!-- Lo stile da applicare in QUESTO componente è il seguente -->
<!-- In style.css abbiamo invece lo stile generico -->
<style scoped>
img{
    width: 100%;
    height: 100%;
}
</style>