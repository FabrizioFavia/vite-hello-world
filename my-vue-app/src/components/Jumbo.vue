<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "Jumbo",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <div class="imgContainer">
        <img src="../assets/vinyl.jpg" alt="">
    </div>
</template>

<!-- Lo stile da applicare in QUESTO componente è il seguente -->
<!-- In style.css abbiamo invece lo stile generico -->
<style scoped>
img {
    object-fit: cover;
    height: 500px;
    width: 100%;
}

.imgContainer {
    width: 100vw;
    height: 500px;


}
</style>