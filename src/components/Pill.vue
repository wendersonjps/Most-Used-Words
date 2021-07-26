<template>
    <div class="pill">
        <span class="name">{{name}}</span>
        <span class="amount">{{amount}}</span>
    </div>
</template>

<script>
export default {
    props: ['name', 'amount']
}
</script>

<style scoped>
    .pill {
        color: white;
        background-color: royalblue;

        border-radius: 30px;
        margin: 10px;
        height: 55px;

        font-size: 1.3rem;
        font-weight: bold;

        display: flex;
        align-items: center;
    }

    .pill .name {
        margin-left: 15px;
    }

    .pill .amount {
        color: royalblue;
        background-color: white;

        border-radius: 18px;
        margin: 10px;
        height: 35px;
        width: 35px;
        padding: 5px;

        font-size: 14px;

        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>