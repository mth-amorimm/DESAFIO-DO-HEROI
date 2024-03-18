# CLASSIFICADOR DE HEROI - DESAFIO DE LOGICA DE PROGRAMAÇÃO 👨🏻‍💻

# 1️⃣ Proposta do Desafio 

**O Que foi utilizado:**

- Variáveis;
- Operadores;
- Estruturas de decisões;

## Objetivo 🚀

Criar uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilizar uma estrutura de decisão para apresentar alguma das mensagens abaixo:

- Se XP for menor do que 1.000 = Ferro;
- Se XP for entre 1.001 e 2.000 = Bronze;
- Se XP for entre 2.001 e 5.000 = Prata;
- Se XP for entre 5.001 e 7.000 = Ouro;
- Se XP for entre 7.001 e 8.000 = Platina;
- Se XP for entre 8.001 e 9.000 = Ascendente;
- Se XP for entre 9.001 e 10.000= Imortal;
- Se XP for maior ou igual a 10.001 = Radiante;

## Na saída

No final do programa deve se exibir a seguinte mensagem:
"O Herói de nome **{nome}** está no nível de **{nivel}** !"


let NomeHeroi = "Glads"
let xpHeroi = 5001
let rankHeroi

if (xpHeroi <= 1000){rankHeroi = "Ferro"}
else if (xpHeroi >= 1001 && xpHeroi<= 2000){rankHeroi = "bronze"}
else if (xpHeroi >= 2001 && xpHeroi<= 5000){rankHeroi = "prata"}
else if (xpHeroi >= 5001 && xpHeroi<= 7000){rankHeroi = "ouro"}
else if (xpHeroi >= 7001 && xpHeroi<= 8000){rankHeroi = "platina"}
else if (xpHeroi >= 8001 && xpHeroi<= 9000){rankHeroi = "ascendente"}
else if (xpHeroi >= 9001 && xpHeroi<= 10000){rankHeroi = "imortal"}
else {rankHeroi = "radiantee"}

console.log("O herói de nome "+ NomeHeroi + " está no nível de " + rankHeroi)
