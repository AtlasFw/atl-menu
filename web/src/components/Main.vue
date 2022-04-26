<script lang="ts">
    
</script>

<template>
    <div class='wrapper'>
        <div class='box-wrap'>
            <div class='title-box'>
                <span class='title'>Shop menu</span>
            </div>
            <div class='box'>
                <div class='item'>

                    <div class='item-info'>
                        <span></span>
                        <span></span>
                    </div>

                    <div class='item-line'>
                        <div class='line'>

                        </div>
                    </div>

                    <div class='item-icon'>
                        <span class='material-icons'>info</span>
                    </div>
                    
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .wrapper {
        position: absolute;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100vh;
        display: flex;
        justify-content: end;
        align-items: center;
    }

    .title {
        text-align: center;
        font-size: 1.2rem;
    }

    .box-wrap {
        width: 15vh;
        margin: 1vh;
    }

    .title-box {
        position: relative;
        border-radius: .3vh;
        padding: 1.2rem;
        background-color: var(--primary-color);
        margin-bottom: 1vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .box {
        position: relative;
        border-radius: .3vh;
        min-height: 3.5vh;
        height: auto;
        background-color: var(--primary-color);
        margin-bottom: 1vh;
        padding: 1.1rem;
        display: grid;
        gap: 1.2rem;
    }

    .item {
        position: relative;
        height: 3vh;
        background-color: var(--secondary-color);
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    .item-info {
        width: 70%;
        background-color: beige;
        height: 100%;
    }
    
    .item-line {
        width: 10%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .line {
        height: 80%;
        background-color: azure;
        width: 2px;
    }

    .item-icon {
        width: 20%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

</style>