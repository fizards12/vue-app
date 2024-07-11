<script setup>
import { RouterView } from 'vue-router';

</script>
<template>
    <div>
        <div class="route">
            <RouterView/>
        </div>
    </div>
</template>

<style lang="css">
.route{
    width: 500px;
    background-color: blue;
}

</style>