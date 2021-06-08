<template>
   <div class="covers_containers">
       <img :src="item.thumb" :alt="item.series">
       <h3>{{ item.series }}</h3>
   </div>
</template>

<script>
export default {
    name: "Covers",
    props: ['item']
}
</script>

<style scoped>

.covers_containers {
    width: calc(100% / 6);
}

h3 {
    color: white;
}

</style>>
    