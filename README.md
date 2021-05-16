# calculo-combustivel
<div id="app"></div>
<script>
    // 12km = 1L de gasolina
    // O tempo gasto dirigido e a velocidade média do carro
    // velocidade media = D / T
    var distancia = parseFloat(prompt("Qual foi a distância percorrida ? ")); // 400KM
    var tempoGasto = parseFloat(prompt("Qual foi o tempo gasto da viagem ? ")); // 50 horas
    var vlcMedia = distancia / tempoGasto; // 200/30 = 8KM por hora
    var gasolina = 0;
    document.write("A distância percorrida foi: " + distancia + "km/h <br/>");
    document.write("O tempo gasto foi: " + tempoGasto + "hr/s <br/>");
    document.write("A velocidade média foi de: " + vlcMedia.toFixed(2) + "km/h <br/>");
    for(contador = 1; contador < vlcMedia; contador++){
        gasolina+=vlcMedia;
        document.write("Na " + contador + " hora de viagem, Chico Bento gastou " + gasolina.toFixed(2) + "L<br/>");
    }

</script>
