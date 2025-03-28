# Calculadora_Rankeada

Utilizada para exercício prosposto curso de Linguagem de Programação 



function pontuarTotal (vitorias, derrotas){ 
  return vitorias - derrotas 
  }

let saldoVitorias = pontuarTotal(1000,30)



//function pontuacaoFinal(saldoVitorias){
  //let ferro = (<=10)



if(saldoVitorias < 10){ 
 
   let ferro = "ferro"
      console.log("O Herói tem de saldo de " + saldoVitorias + " e está no nível de " + ferro)
}
  
else if (saldoVitorias >= 11 && saldoVitorias <= 20){

   let bronze = "bronze"
       console.log("O Herói tem de saldo de " + saldoVitorias + " e está no nível de " + bronze)
}
else if (saldoVitorias >= 21 && saldoVitorias <= 50){

    let prata = "prata"
          console.log("O Herói tem de saldo de " + saldoVitorias + " e está no nível de " + prata)
}
else if (saldoVitorias >= 51 && saldoVitorias <= 80){

    let ouro = "ouro"
        console.log("O Herói tem de saldo de " + saldoVitorias + " e está no nível de " + ouro)
}
else if (saldoVitorias >= 81 && saldoVitorias <= 90){

    let diamante = "diamante"
      console.log("O Herói tem de saldo de " + saldoVitorias + " e está no nível de " + diamante)
}
else if (saldoVitorias >= 91 && saldoVitorias <= 100){

    let lendario = "lendário"
     console.log("O Herói tem de saldo de " + saldoVitorias + " e está no nível de " + lendario)
}
else if (saldoVitorias >= 101){

    let imortal = "imortal"
      console.log("O Herói tem de saldo de " + saldoVitorias + " e está no nível de " + imortal)

}
