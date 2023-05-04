<script>
export default{
    name: "CardComp",
    props: ['dettaglicards']
}
</script>

<template>
    <div class="card">
        <img :src="dettaglicards.thumb" class="card-img-top" alt="">
        <div>
            <h6 class="card-title">{{dettaglicards.series}}</h6>
        </div>
    </div>
</template>

<style scoped lang="scss">
.card{
    width: calc(100% / 6 - 10px);
    background-color: transparent;
    border: none;
    color: white;
    text-transform: uppercase;
    img{
        height: 300px;
        margin-bottom: 5px;
    }
}
</style>