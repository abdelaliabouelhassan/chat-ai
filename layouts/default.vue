<template>
    <div class=" overflow-hidden w-full h-full">
           <slot />
    </div>
</template>
  

<script setup>
const colorMode = useColorMode();
onMounted(() => {
    const mode = localStorage.getItem('color-mode');
    if (mode) {
        colorMode.value = mode;
    }
});

</script>
  
