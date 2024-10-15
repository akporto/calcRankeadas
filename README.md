# Calculadora de Partidas Rankeadas

Este projeto em JavaScript é uma calculadora de partidas rankeadas para jogadores, que classifica o nível do jogador com base no número de vitórias. Ele também calcula o saldo de vitórias subtraindo o número de derrotas.

## 🛠️ Funcionalidades

- Calcula o saldo de vitórias (vitórias - derrotas).
- Classifica o jogador em um nível com base no número de vitórias.
- Exibe uma mensagem com o saldo e o nível do jogador.

## 🚀 Como Usar

1. Clone o repositório ou baixe os arquivos no seu computador.
2. Abra o arquivo `.js` no seu editor de código favorito.
3. Use a função `calcularSaldoELevel(vitorias, derrotas)` para calcular o saldo e nível do jogador.
4. Passe os valores de vitórias e derrotas como argumentos para a função.
5. Execute o código para ver o resultado no console, que será uma mensagem com o saldo de vitórias e o nível do jogador.

## 🔄 Exemplo de Uso

let vitorias = 85;
let derrotas = 40;

calcularSaldoELevel(vitorias, derrotas);

Ao executar o código acima, a saída será:

O Herói tem de saldo de 45 está no nível de Diamante

## 🔢 Lógica de Classificação
Se vitórias for menor do que 10 = Ferro
Se vitórias for entre 11 e 20 = Bronze
Se vitórias for entre 21 e 50 = Prata
Se vitórias for entre 51 e 80 = Ouro
Se vitórias for entre 81 e 90 = Diamante
Se vitórias for entre 91 e 100 = Lendário
Se vitórias for maior ou igual a 101 = Imortal

## 🧑‍💻 Tecnologias Utilizadas
JavaScript: A linguagem principal utilizada para a lógica do programa.
