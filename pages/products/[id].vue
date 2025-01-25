<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Accusantium officiis est, soluta quidem veniam magnam error repellat molestiae. Fugiat voluptate maxime debitis facilis ab! Veritatis amet itaque doloremque dignissimos dolore?</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style scoped>

</style>