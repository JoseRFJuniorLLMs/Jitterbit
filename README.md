
# Teste Teórico Dev PS 2024

## Javascript

1. **Qual é o operador lógico usado para verificar a negação de uma expressão?**
   **Resposta:** c) !

2. **Qual dos seguintes métodos é usado para adicionar um elemento ao final de um array?**
   **Resposta:** a) push()

3. **O que o método “Array.map()” faz?**
   **Resposta:** b) Mapeia os elementos de um array para um novo array com base em uma função de mapeamento.

4. **Qual é a função do método “Array.filter()”?**
   **Resposta:** b) Remover elementos do array com base em uma função de filtro.

5. **O que é async/await em JavaScript?**
   **Resposta:** c) Um conjunto de palavras-chave que tornam as funções assíncronas mais legíveis e fáceis de usar.

6. **Qual é a sintaxe correta para definir uma função assíncrona chamada "getData"?**
   **Resposta:** c) async function getData() { return new Promise({}); }

7. **O que será impresso no código abaixo?**
   **Resposta:** b) A.

8. **Escreva uma função em JavaScript chamada “somaImpares” que recebe um número inteiro positivo “n” como parâmetro e retorna a soma de todos os números ímpares de 1 até n.**
   **Resposta:**
   ```javascript
   function somaImpares(n) {
      let soma = 0;
      for (let i = 1; i <= n; i++) {
         if (i % 2 !== 0) {
            soma += i;
         }
      }
      return soma;
   }
   ```

9. **Escreva uma função chamada” inverterPalavra” que recebe uma string como parâmetro e retorna a string com as letras invertidas.**
   **Resposta:**
   ```javascript
   function inverterPalavra(str) {
      return str.split('').reverse().join('');
   }
   ```

10. **Considere o seguinte trecho de código em JavaScript que tenta realizar a divisão de dois números:**
    **Resposta:**
    ```javascript
    function dividirNumeros(number1, number2) {
       try {
          if (number2 === 0) {
             throw new Error("Divisão por zero não é permitida.");
          }
          return number1 / number2;
       } catch (error) {
          return "Erro: " + error.message;
       }
    }
    ```

11. **Como você pode percorrer e mapear um array JSON em JavaScript? Explique como usar métodos como "map", "forEach" ou "for...of" para iterar e manipular os elementos do array.**
    **Resposta:**
    ```markdown
    Em JavaScript, você pode percorrer e mapear um array JSON usando diferentes métodos, como "map", "forEach" e "for...of".
    - `map()`: Este método cria um novo array com os resultados da chamada de uma função fornecida em cada elemento do array original.
    - `forEach()`: Este método executa uma função fornecida uma vez para cada elemento do array.
    - `for...of`: Esta estrutura permite iterar sobre elementos de um array.
    ```

12. **O que são variáveis em JavaScript? Explique como declarar e atribuir valores a uma variável.**
    **Resposta:**
    ```markdown
    Variáveis em JavaScript são contêineres que armazenam dados. Elas podem armazenar diferentes tipos de valores, como números, strings, objetos, entre outros. Para declarar uma variável, você pode usar `var`, `let` ou `const`.
    ```

13. **Em JavaScript, é possível ter múltiplas condições em uma estrutura "if/else"? Descreva como usar operadores lógicos (como "&&" e "||") para combinar condições.**
    **Resposta:**
    ```markdown
    Sim, em JavaScript é possível ter múltiplas condições em uma estrutura "if/else" usando operadores lógicos como `&&` (E lógico) e `||` (OU lógico).
    ```

14. **Descreva a sintaxe do bloco "try" em JavaScript. Dê um exemplo prático de como usar o "try" para envolver um código suscetível a erros.**
    **Resposta:**
    ```markdown
    O bloco `try` em JavaScript é usado para envolver um código que pode lançar exceções. Se uma exceção for lançada dentro do bloco `try`, ela será capturada pelo bloco `catch`.
    ```

15. **Como você pode lançar manualmente uma exceção em JavaScript? Explique o uso da palavra-chave "throw" para criar e lançar exceções personalizadas.**
    **Resposta:**
    ```markdown
    Em JavaScript, você pode lançar manualmente uma exceção usando a palavra-chave `throw`. Isso permite criar e lançar exceções personalizadas.
    ```

## SQL

1. **Como você seleciona todas as colunas de uma tabela em SQL?**
   **Resposta:** b) SELECT *

2. **Qual é o comando SQL utilizado para filtrar resultados em uma consulta?**
   **Resposta:** d) WHERE

3. **Qual é o comando SQL utilizado para ordenar os resultados de uma consulta em ordem ascendente?**
   **Resposta:** d) ORDER BY

4. **Qual é o comando SQL utilizado para inserir novos dados em uma tabela?**
   **Resposta:** b) INSERT

5. **Qual é o comando SQL utilizado para atualizar dados em uma tabela?**
   **Resposta:** b) UPDATE

## Integração de Sistemas

1. **O que é integração de sistemas?**
   **Resposta:** a) É um processo de comunicação entre diferentes sistemas de computador para permitir o compartilhamento de dados e funcionalidades.

2. **O que significa API (Interface de Programação de Aplicativos) em integração de sistemas?**
   **Resposta:** c) Um conjunto de funções e procedimentos que permitem a comunicação entre sistemas.

3. **O que é um Web Service?**
   **Resposta:** c) É uma solução para conectar sistemas diferentes via web, usando padrões como XML e SOAP.

4. **O que é um token de acesso em integração de sistemas?**
   **Resposta:** c) Uma chave de autenticação usada para autorizar o acesso a um serviço.

5. **O que é um "webhook" na integração de sistemas?**
   **Resposta:** d) É uma URL pública fornecida por um sistema para receber notificações automáticas de outro sistema.

6. **O que é JSON?**
   **Resposta:** c) Um formato de dados leve e de fácil leitura usado para trocar informações entre sistemas.

7. **Qual é o código de status HTTP que indica sucesso na solicitação?**
   **Resposta:** a) 200 OK.

8. **O que são headers HTTP?**
   **Resposta:** b) Informações adicionais enviadas pelo cliente e servidor em uma solicitação ou resposta HTTP.

9. **Quais são os delimitadores usados para marcar tags em XML?**
   **Resposta:** d) < >

10. **Qual é a diferença entre integração de sistemas síncrona e assíncrona?**
    **Resposta:** a) Na síncrona, a comunicação ocorre em tempo real com respostas imediatas, enquanto na assíncrona, a resposta pode ser recebida em um momento posterior.
