<script>

    export let numero = 0;

    export let chiave;

    let tipo2txt = {
        gg: 'Giorni',
        hh: 'Ore',
        mm: 'Minuti',
        ss: 'Secondi'
    }

    

</script>

<div class="riquadro">
    <div class="count">{numero}</div>
    <div class="testo">{tipo2txt[chiave]}</div>
</div>




<style>

@media (max-width: 480px) {

    .riquadro{
        display: grid;
        width: 60%;
        
        
        border-radius: 15px;
        grid-template-rows: 2fr 1fr;
        margin: auto;
        border: 2px solid green  ;
        box-shadow: 1px 0px 8px 0px green;
        
    }

    .count{
        
        font-family: 'Black Ops One', cursive;
        font-size: 66px;
        color: #F9F871;
        text-shadow: 4px 4px 10px #051937;
        display: flex;
        align-items: center;
        justify-content: center;
        
}

.testo{
    font-family: 'Black Ops One', cursive;
    font-size: 38px;
    color: #F9F871;

}


}





/*----------------*/

@media (min-width: 481px) {

    .riquadro{
        display: grid;
        width: 90%;
        
        
        border-radius: 15px;
        grid-template-rows: 2fr 1fr;
        margin: auto;
        
    }

    .count{
        
            font-family: 'Black Ops One', cursive;
            font-size: 18vh;
            color: #F9F871;
            text-shadow: 4px 4px 10px #051937;
            display: flex;
            align-items: center;
            justify-content: center;
            
    }

    .testo{
        font-family: 'Black Ops One', cursive;
        font-size: 38px;
        color: #F9F871;

    }

}

    





</style>