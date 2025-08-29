<template>
<button class="button">
    Начать игру
</button>
</template>


<script setup lang="ts">

</script>


<style scoped>

.button {
font-family: var(--font);
font-weight: 400;
font-size: 24px;
line-height: 36px;
letter-spacing: 0%;
text-align: center;

width: 335px;
height: 68px;
border-radius: 100px;
padding-top: 16px;
padding-right: 10px;
padding-bottom: 16px;
padding-left: 10px;
opacity: 1;

cursor: pointer;
background: var(--color-blue);
border-color: white;
color:#FFFFFF;
/* border: none; */
  border: 0px solid transparent;
}

.button:focus {
  outline: none;
}
.button:active {
  outline: none;
}

</style>