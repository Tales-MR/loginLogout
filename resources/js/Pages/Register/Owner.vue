<script setup>
import ModalNewOwner from "@/Components/ModalNewOwner.vue"; //Modal for creation of new owner


</script>

<template>
    <main>
        <div class="nav"></div>
            <h1>Teste</h1>
        <div class="last-add">

        </div>

        <div class="abrir-modal">
            <!-- Button trigger modal -->
            <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#staticBackdrop">
                Launch static backdrop modal
            </button>

            <ModalNewOwner/>
        </div>
    </main>
</template>



<script>
    import Layout from "@/Components/Layout/Layout.vue";
    export default {
        layout: Layout,
    }
</script>
