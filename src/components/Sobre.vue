<template>
    <div>
        <p class="nome">Citações</p>
        
        <p class="versao"> Manoel</p>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    div {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        border: 1px solid #DDD;
        height: 140px;
        width: 140px;
        border-radius: 100px;
        
    }

    p {
        margin: 0;
    }

    .nome {
        font-size: 1.1rem;
        font-weight: bold;
    }

    .versao {
        font-size: 1.4rem;
    }
</style>
