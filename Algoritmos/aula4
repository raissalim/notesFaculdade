<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estrutura de Desisão</title>
    
    <style>
    .vermelho{
     color:red;
    font-weight:bold;
    font-style:italic;
}
    .azul{
        color:blue;
        
    }
    .black{
        color:black;
    }
</style>
</head>
<body>
    <center>
    <p> exercicio 1 Desisão</p>
         <input type="text" id="idade"  placeholder="Digite sua idade"><br><br>
         <button type="button"  id= "btnFesta" onclick="festa()">Ir para a festa</button><br><br>

         <p> exercicio 2 </p>
         <input type="text" id="quantRefri"  placeholder="Digite quantas latinhas de refir voce toma por dia"><br><br>
         <button type="button"  id= "btnRefri" onclick="calcule()">Quantos refris?</button><br><br>

         <p> exercicio 3</p>
         <input type="text" id="nota1"  placeholder="Digite sua primeira nota"><br><br>
         <input type="text" id="nota2"  placeholder="Digite sua segunda nota"><br><br>
         <input type="text" id="nota3"  placeholder="Digite sua terceira nota"><br><br>
         <button type="button"  id= "btnDesempenho" onclick="media()">Analisar desempenho</button><br><br>
    
         
         <p> exercicio 4</p>
         <input type="text" id="valor"  placeholder="Digite o valor da pizza"><br><br>
         <input type="text" id="quantamigos"  placeholder="Digite quantos amigos são"><br><br>
         <button type="button"  id= "btnPizza" onclick="Pizza()">Rola pizza?</button><br><br>
         
           <p> exercicio 4a</p>
         <input type="text" id="valordif"  placeholder="Digite o valor da pizza"><br><br>
         <input type="text" id="quantamigosdif"  placeholder="Digite quantos amigos são"><br><br>
         <button type="button"  id= "btnPizzadif" onclick="PizzaDiferente()">Rola pizza?</button><br><br>
        <p id="msgPizza"></p><br>

           
           <p> exercicio 5</p>
         <input type="text" id="quantkwh"  placeholder="Digite quantidade de kwh consumido por mes"><br><br>
         <button type="button"  id= "btnquantkwh" onclick="calculeKwh()">Calcular conta de luz</button><br><br>

          <p> exercicio 6</p>
         <input type="text" id="renda"  placeholder="Digite sua renda familiar"><br><br>
         <input type="text" id="prestacao"  placeholder="Digite valor da prestação"><br><br>
         <button type="button"  id= "btnFinanciamento" onclick="Financiamento()"> Verificar Financiamento</button><br><br>
          <p id="msgFinanciamento"></p><br>

         <p> exercicio 7</p>
         <input type="text" id="saldo"  placeholder="Digite seu saldo"><br><br>
         <input type="text" id="debito"  placeholder="Digite valor que deseja retirar"><br><br>
         <button type="button"  id= "btnSaldo" onclick="verificarSaldo()"> Analisar conta</button><br><br>
          <p id="msgSaldo"></p><br>

        <p> exercicio 8</p>
         <input type="text" id="quanthomens"  placeholder="Digite quantidade de homens"><br><br>
         <input type="text" id="quantMulheres"  placeholder="Digite quantidade de mulheres"><br><br>
         <button type="button"  id= "btnPeso" onclick="verificarPeso()"> Analisar peso</button><br><br>
          <p id="msgElevador"></p><br>

         <p> exercicio 9</p>
         <input type="text" id="serie"  placeholder="Digite a ultima serie SITCOM que viu"><br><br>
         <input type="text" id="totalep"  placeholder="Digite quantidade episodios que já exitiu dessa série"><br><br>
         <button type="button"  id= "btnNivel" onclick="analisarNivel()"> Verificar nivel</button><br><br>
          <p id="msgNivel"></p><br>

        <p> exercicio 10</p>
         <input type="text" id="saldousu"  placeholder="Digite seu saldo no banco"><br><br>
         <button type="button"  id= "btnFinancas" onclick="verificarFinancas()"> Verificar Finanças</button><br><br>
          <p id="msgFinancas"></p><br>
         </center>



         <script>
            function festa(){
                let idadee=Number(idade.value);
                 if(idadee<18){
                    alert("Pedir permissão pro responsável");
                 }
                  else{
                    alert("#partiuFesta");
                  }
            }
            function calcule(){
                let quantRefrii=Number(quantRefri.value);
                let Resultado= quantRefrii*365;
                 alert("Voce consome " +Resultado+ "latinas de refri por ano");
                 if(Resultado>500){
                    alert("Cuidado com a diabetes!")
                 }
                }
           function media(){
            let notaprimeira=Number(nota1.value);
            let notasegunda=Number(nota2.value);
            let notaterceira=Number(nota3.value);
            let media=(notaprimeira+notasegunda+notaterceira)/3;
            alert("sua media foi de  " +media);
               if(media>9.4){
                alert("Parabéns, você é fora de série!")
               }
           }
           
           function Pizza(){
            let valorr=Number(valor.value);
            let quantamigoss=Number(quantamigos.value);
            let valorindividual= valorr/quantamigoss;
            alert("Cada amigo vai pagar R$" + valorindividual+ " pela pizza");
                if (valorindividual>20){
                    alert("Deu ruim! Pizza muito cara!");

                    }
            }
                

      
            function PizzaDiferente(){
                            
            let valorPizza = Number(valordif.value);
            let amigos = Number(quantamigosdif.value);

            let valorindividualdif = valorPizza / amigos;

            if (valorindividualdif > 20){

            msgPizza.innerHTML =
            "<span class='vermelho'>Deu ruim! Pizza muito cara!<br>Cada amigo vai pagar R$ "
            + valorindividualdif.toFixed(2) +
            "</span>";

            }
            else{

            msgPizza.innerHTML =
            "Rola pizza! Cada amigo vai pagar R$ "
            + valorindividualdif.toFixed(2);

            }

        }
        // revisar essa pois esta dado erro na condição
        function calculeKwh(){
            let quantkwhh = Number(quantkwh.value);
            let conta=quantkwhh;

            if(quantkwhh<101){
            conta=conta*0.90;;
          
        }
          alert("Sua conta de luz é de R$ " + conta);
            }
           
        function Financiamento(){
            let rendaa=Number(renda.value);
            let pretacaoo=Number(prestacao.value);
            let valorPrestacao=(pretacaoo/rendaa)*100;
 
            msgFinanciamento.innerHTML= "Valor da prestação corresponde a " + valorPrestacao.toFixed(2) + "% da renda familiar.<br>";
            if(valorPrestacao>30){

            msgFinanciamento.innerHTML =
            "<span class='vermelho'>Será necessário complementar a renda familiar "
            + valorPrestacao.toFixed(2) +
            "</span>";

            }
        }
        function verificarSaldo(){
            let saldoo=Number(saldo.value);
            let debitoo=Number(debito.value);
            let saldoAtual=(saldoo-debitoo);

            msgSaldo.innerHTML="Saldo atual RS"+ saldoAtual.toFixed(2)+ "<br>";
            if (saldoAtual<=0){

             msgSaldo.innerHTML +=
            "<span class='vermelho'>Saldo insuficiente!<br>Seu saldo atual é de R$ " + saldoAtual.toFixed(2) + "</span>";
            }
        }

        function verificarPeso(){
            let quantidadeh=Number(quanthomens.value);
            let quantidadem=Number(quantMulheres.value);
            quantidadeh=quantidadeh*80;
            quantidadem=quantidadem*60;
            let pesoTotal=quantidadeh+quantidadem;

            msgElevador.innerHTML=" Este elevador suporta 800 Kg e o peso estimado desta lotação é de "+ pesoTotal.toFixed(2)+ "Kg.<br>";
            if(pesoTotal>800){
                msgElevador.innerHTML += "<span class='azul'>Será necessário que alguém desça para que o elevador se movimente</span>";
            }
        }

        function analisarNivel(){
            let seriee=(serie.value);
            let totalepi=Number(totalep.value);
            let totalHoras = totalepi * 0.36;

            msgNivel.innerHTML =
            "Vejo que você gosta da série " + seriee +
            " e já assistiu aproximadamente " + totalHoras.toFixed(2) + " horas.<br>";

            if (totalHoras>30){
                msgNivel.innerHTML += "<span>Uau, você realmente gosta dessa série!</span>";
            }

        }

        function verificarFinancas(){
            let saldoousu=Number(saldousu.value.replace(",", "."));

            if(saldoousu==0){
            msgFinancas.innerHTML="<span class='black'>Conta zerada</span>";

            }
            else if(saldoousu<0){
            msgFinancas.innerHTML="<span class='vermelho'>Está devendo!</span>";
            
            }
            else{
                msgFinancas.innerHTML="<span class='azul'>Saldo positivo! 😊</span>";
            }
        }
         </script>
</body>
</html>
