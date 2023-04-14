<template>
    <div>
        <h1>LOGO</h1>
        <nav>
            <p>LINK ONE</p>
            <p>LINK TWO</p>
            <p>LINK THREE</p>
        </nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    div{ 
        display: grid;
        grid-template-columns: 1fr 1fr;
        align-items: center;
        justify-items: start;
    }

    nav {
        display: grid;
        justify-self: end;
        grid-auto-flow: column;
    }
</style>