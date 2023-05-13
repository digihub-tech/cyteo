<script setup lang="ts">
</script>

<template>
  <main>
    <h2>Academic Portal</h2>

    <div class="modals">

        <div class="modal-content">
            
           <a href="https://bigsky.benilde.edu.ph/d2l/home" target="_blank"><img src="https://i.imgur.com/y3VicGb.png" class="modal-image"></a>
        </div>

        <div class="modal-content">
            <a href="https://apps.benilde.edu.ph/sis/?ReturnUrl=%2fsisv23%2fMain" target="_blank"><img src="https://i.imgur.com/uy5hxc0.png" class="modal-image"></a>
        </div>

        <div class="modal-content">
            <a href="https://apps1.benilde.edu.ph/payonline" target="_blank"><img src="https://i.imgur.com/EX8FdO6.png" class="modal-image"></a>
        </div>

        <div class="modal-content">
            <a href="https://clr.benilde.edu.ph/" target="_blank"><img src="https://i.imgur.com/bjKNlPc.png" class="modal-image"></a>
        </div>


    </div>

  </main>
</template>

<style scoped>
h2{
    padding:20px;
}
.modals{
    display:flex;
    gap:10px;
    align-items: center;
    justify-content: center;
    margin-left: 2%;
}
.modal-image{
    width:200px;
    height:200px;
}
.modal-content{
    width:200px;
    height: 200px;
}
.modal-content a:hover{
    border-bottom: 3px solid #DDFFBB;
}
</style>