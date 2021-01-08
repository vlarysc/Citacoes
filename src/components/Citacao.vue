<template>
    <div class="citacao">
        <slot name="fonte"></slot>
        <slot> </slot>
        <div class="autor"><slot name="autor"></slot></div>       
    </div>
</template>

<script>


export default {
    created(){
        console.log('created')
    }
}
</script>

<style scoped>
    .citacao {
        border: 1px solid #DDD;
        background-color: rgba(0, 0, 0, .1);
        padding: 25px;
        max-width: 450px;
    }
</style>
