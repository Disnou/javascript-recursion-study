javascript-recursion-study
🇧🇷 Implementação e estudo de lógica recursiva em JavaScript através do cálculo de fatorial. 🇺🇸 Implementation and study of recursive logic in JavaScript through factorial calculation.

# 🔄 Recursividade em JS | Recursion in JS

> Estudo detalhado sobre lógica recursiva e pilhas de execução utilizando o cálculo matemático de Fatorial.
> Detailed study on recursive logic and call stacks using the Factorial mathematical calculation.

<p align="center">
  <img src="https://img.shields.io/badge/Language-JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black" alt="JS Badge">
  <img src="https://img.shields.io/badge/Concept-Algorithms-blue?style=for-the-badge" alt="Algorithms Badge">
</p>

---

 🇧🇷 Português

📖 Sobre o Projeto
Este repositório foca em um dos conceitos mais sofisticados da ciência da computação: a Recursividade. Através de um script simples e eficiente, demonstro como uma função pode invocar a si mesma para resolver problemas complexos que podem ser divididos em subproblemas menores.

 🧠 O que é Recursividade?
Uma função recursiva é aquela que se chama repetidamente até atingir uma condição de parada(caso base). No exemplo do Fatorial (5!), a lógica funciona como uma pilha:
1. `5  fatorial(4)`
2. `4  fatorial(3)`
3. ...até chegar em `fatorial(0)`, que retorna `1`.

🧪 Conteúdo Técnico
Caso Base:Implementação da condição de segurança para evitar loops infinitos (`if (x < 1)`).
Chamada Recursiva: A lógica onde a função diminui o problema a cada passo (`x * fatorial(x-1)`).
Console API:** Uso do terminal para depuração e visualização do resultado final.

---

 🇺🇸 English

📖 About the Project
This repository focuses on one of the most sophisticated concepts in computer science: Recursion. Through a simple and efficient script, I demonstrate how a function can invoke itself to solve complex problems that can be broken down into smaller subproblems.

 🧠 What is Recursion?
A recursive function is one that calls itself repeatedly until it reaches a base case (stop condition). In the Factorial (5!) example, the logic works like a stack:
1. `5  factorial(4)`
2. `4 fatorial(3)`
3. ...until it reaches `factorial(0)`, which returns `1`.

 🧪 Technical Content
Base Case: Implementation of the safety condition to avoid infinite loops (`if (x < 1)`).
Recursive Call: The logic where the function reduces the problem size at each step (`x * fatorial(x-1)`).
Console API: Using the terminal for debugging and viewing the final result.

--
Desenvolvido por / Developed by: Disnou
