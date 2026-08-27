# ## 🦸‍♂️ Desafio Classificador de Nível de Herói

Projeto desenvolvido para classificar o nível de um herói com base na sua quantidade de experiência (XP), utilizando conceitos básicos de lógica de programação em JavaScript.

### 📌 Tecnologias e Conceitos Utilizados
- **Variáveis (`let`):** Para armazenar o nome, o XP e o nível do herói.
- **Operadores de Comparação e Lógicos (`<`, `>=`, `&&`):** Para checar em qual faixa de XP o herói se encontra.
- **Estruturas Condicionais (`if / else if / else`):** Para determinar a classificação correspondente ao XP.
- **Template Literals (Interpolação de Strings):** Para formatar a mensagem final de saída no console.

### 🎯 Regras de Classificação (XP)
- **Menor que 1.000:** Ferro
- **1.001 a 2.000:** Bronze
- **2.001 a 5.000:** Prata
- **5.001 a 7.000:** Ouro
- **7.001 a 8.000:** Platina
- **8.001 a 9.000:** Ascendente
- **9.001 a 10.000:** Imortal
- **Maior ou igual a 10.001:** Radiante

### 🚀 Exemplo de Saída
Com os valores declarados no código:
- **Nome:** Homem Aranha
- **XP:** 8.500

A mensagem exibida no console será:
> `O Herói de nome Homem Aranha está no nível de Ascendente`