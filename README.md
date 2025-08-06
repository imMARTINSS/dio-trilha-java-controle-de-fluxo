# Desafio de Código DIO: Controle de Fluxo

Este projeto foi desenvolvido para o desafio "Controle de Fluxo" da trilha **Java Básico**, oferecida pela [Digital Innovation One (DIO)](https://www.dio.me/).

---

## 📝 Descrição do Desafio

O objetivo é exercitar os conceitos de controle de fluxo em Java, como condicionais e laços de repetição, além do tratamento de exceções customizadas.

O programa deve receber dois números inteiros como parâmetros via terminal. A lógica principal consiste em:
1.  Verificar se o primeiro parâmetro é maior que o segundo. Se for, o programa deve lançar uma exceção customizada.
2.  Caso contrário, o programa deve calcular a diferença entre os dois números e usar esse valor para realizar um laço de repetição (`for`), imprimindo no console cada número da iteração.

### Requisitos Técnicos
* **Classe `Contador`**: Contém a lógica principal, incluindo a leitura dos parâmetros e o tratamento da exceção.
* **Classe `ParametrosInvalidosException`**: Uma exceção customizada que é lançada quando o segundo parâmetro não é maior que o primeiro.

---

## ⚙️ Funcionalidade

* **Entrada:**
    * `parametroUm` (inteiro): O primeiro número.
    * `parametroDois` (inteiro): O segundo número.

* **Comportamento:**
    * **Se `parametroUm` < `parametroDois`**: O sistema calcula `parametroDois - parametroUm` e imprime no console a contagem, de 1 até o resultado da diferença.
        * Exemplo de entrada: `12` e `30`.
        * Exemplo de saída: "Imprimindo o número 1", "Imprimindo o número 2", ..., "Imprimindo o número 18".
    * **Se `parametroUm` >= `parametroDois`**: O sistema lança a exceção `ParametrosInvalidosException` com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".

---

## 🚀 Como Executar o Projeto

Para testar a solução em seu ambiente:

1.  **Clone o repositório:**
    ```bash
    git clone [URL-DO-SEU-REPOSITORIO-AQUI]
    ```
2.  **Abra o projeto** em sua IDE de preferência.
3.  **Execute a classe principal `Contador.java`**.
4.  Insira os dois parâmetros numéricos no terminal quando solicitado.
5.  Observe a saída no console, que irá variar conforme as regras do desafio.

---

## 👨‍💻 Autor da Solução

* **Raul Pereira Martins**
    * [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/martinsraull/)
    * [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/imMARTINSS)
    * [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/raull__martinss/)
