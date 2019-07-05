<template>
    <div class="tableto">
        <div class="niveles">
            <span>Nivel:</span>
            <span class="nivel">1</span>
            <span class="nivel">2</span>
            <span class="nivel">3</span>
        </div>
        <div class="panel">
            <div class="marcador minas-restantes">
                999     
            </div>
            <div class="cara">
                <span>😀</span>
            </div>
            <div class="marcador segundos">
                999
            </div>
        </div>
        <div class="matriz">

        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
    .tableto{
        display: grid;
        justify-content: center;
        background-color: rgb(121, 136, 121);
        padding: 10px;
    }
    .niveles{
        display: grid;
        grid-auto-flow: column;

    }
    .nivel{
        width: 32;
        height: 32;
    }
    .panel{
        display: grid;
        grid-auto-flow: column;
        font-size: 40px;
    }
    .marcador{
        background-color: black;
        color: red;
        height: 48px;
    }
    .minas-restantes{
        justify-self: start;
    }
    .cara{
        display: grid;
        justify-content: center;
        align-items: center;
        justify-self: center;
        width: 48px;
        height: 48px;
    }
    .segundos{
        justify-self: end;
    }
    .matriz{
        display: grid;
        background-color: #7b7b7b;
        width: 400px;
        height: 200px;
    }

</style>