<template>
    <img :src="orgin" :alt="text" :style="{ width: largura }">
</template>

<script>
export default {
    props: {
        orgin: String,
        text: String,
        largura: [Number , String]
    }
}
</script>