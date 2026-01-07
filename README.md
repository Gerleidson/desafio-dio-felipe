# Classificador de Nível de Herói 🛡️⚔️

Este projeto é um exercício básico de **lógica de programação em JavaScript**, onde o nível de um herói é determinado com base na sua quantidade de experiência (XP).

## 🧠 Objetivo

Criar um sistema que:
- Receba o nome de um herói
- Receba a quantidade de XP
- Determine o nível do herói usando estruturas condicionais
- Exiba a mensagem final no console conforme o padrão solicitado

## 🧩 Níveis do Herói

A classificação de nível segue as regras abaixo:

| XP do Herói        | Nível       |
|-------------------|------------|
| Menor que 1000    | Ferro      |
| 1001 a 2000       | Bronze     |
| 2001 a 5000       | Prata      |
| 5001 a 7000       | Ouro       |
| 7001 a 8000       | Platina    |
| 8001 a 9000       | Ascendente |
| 9001 a 10000      | Imortal    |
| Maior que 10000   | Radiante   |

## 💻 Código Utilizado

```javascript
let nomeHeroi = "Aragorn";
let xpHeroi = 1000;
let nivelHeroi = "";

if (xpHeroi < 1000) {
    nivelHeroi = "Ferro";
} else if (xpHeroi >= 1001 && xpHeroi <= 2000) {
    nivelHeroi = "Bronze";
} else if (xpHeroi >= 2001 && xpHeroi <= 5000) {
    nivelHeroi = "Prata";
} else if (xpHeroi >= 5001 && xpHeroi <= 7000) {
    nivelHeroi = "Ouro";
} else if (xpHeroi >= 7001 && xpHeroi <= 8000) {
    nivelHeroi = "Platina";
} else if (xpHeroi >= 8001 && xpHeroi <= 9000) {
    nivelHeroi = "Ascendente";
} else if (xpHeroi >= 9001 && xpHeroi <= 10000) {
    nivelHeroi = "Imortal";
} else {
    nivelHeroi = "Radiante";
}

console.log("O Herói de nome " + nomeHeroi + " está no nível de " + nivelHeroi);
