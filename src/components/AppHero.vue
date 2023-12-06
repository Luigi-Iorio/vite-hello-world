<script>
export default {
    data() {
        return {
            text: "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sit sequi et repudiandae nam vero corporis error obcaecati tempore voluptates ex doloremque perferendis itaque soluta ratione omnis iste, excepturi minima consectetur."
        }
    }
}
</script>

<template>
    <p>{{ text }}</p>
    <button>Button</button>
</template>

<style scoped>
button {
    padding: 10px 20px;
    background-color: rgb(11, 109, 77);
    border: none;
    border-radius: 10px;
    transition: 0.4s;
}

button:hover {
    cursor: pointer;
    background-color: rgb(8, 72, 51);
}
</style>