
# Teste Teórico Dev PS

## Javascript

1. **Qual é o operador lógico usado para verificar a negação de uma expressão?**
   **Resposta:** c) !
   **Explicação:** O operador lógico `!` é usado para negar uma expressão em JavaScript. Ele inverte o valor booleano da expressão, transformando `true` em `false` e vice-versa.

2. **Qual dos seguintes métodos é usado para adicionar um elemento ao final de um array?**
   **Resposta:** a) push()
   **Explicação:** O método `push()` adiciona um ou mais elementos ao final de um array e retorna o novo comprimento do array.

3. **O que o método “Array.map()” faz?**
   **Resposta:** b) Mapeia os elementos de um array para um novo array com base em uma função de mapeamento.
   **Explicação:** O método `map()` cria um novo array com os resultados da chamada de uma função fornecida em cada elemento do array original.

4. **Qual é a função do método “Array.filter()”?**
   **Resposta:** b) Remover elementos do array com base em uma função de filtro.
   **Explicação:** O método `filter()` cria um novo array com todos os elementos que passam no teste implementado pela função fornecida.

5. **O que é async/await em JavaScript?**
   **Resposta:** c) Um conjunto de palavras-chave que tornam as funções assíncronas mais legíveis e fáceis de usar.
   **Explicação:** `async` e `await` são palavras-chave usadas para lidar com operações assíncronas em JavaScript, permitindo escrever código assíncrono de maneira síncrona, melhorando a legibilidade.

6. **Qual é a sintaxe correta para definir uma função assíncrona chamada "getData"?**
   **Resposta:** c) async function getData() { return new Promise({}); }
   **Explicação:** A palavra-chave `async` antes de uma função define que ela é assíncrona e retornará uma promessa. A sintaxe correta para declarar uma função assíncrona é usando `async function`.

7. **O que será impresso no código abaixo?**
   **Resposta:** b) A.
   **Explicação:** O valor da variável `palavra` é `"ABC"`, que corresponde ao case `"ABC"` no switch, imprimindo "A".

8. **Escreva uma função em JavaScript chamada “somaImpares” que recebe um número inteiro positivo “n” como parâmetro e retorna a soma de todos os números ímpares de 1 até n.**
   **Resposta:** A função itera de 1 até `n`, verifica se o número é ímpar (`i % 2 !== 0`), e se for, adiciona à soma total. Retorna a soma dos números ímpares até `n`.
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
   **Resposta:** A função divide a string em um array de caracteres (`split('')`), inverte a ordem dos elementos no array (`reverse()`), e junta os caracteres de volta em uma string (`join('')`).

   ```javascript

   function inverterPalavra(str) {
      return str.split('').reverse().join('');
   }

   ```

10. **Considere o seguinte trecho de código em JavaScript que tenta realizar a divisão de dois números:**
    **Resposta:** A função tenta dividir `number1` por `number2`. Se `number2` for 0, lança um erro. O bloco `catch` captura o erro e retorna a mensagem de erro.

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
    **Resposta:** Em JavaScript, você pode percorrer e mapear um array JSON usando diferentes métodos, como "map", "forEach" e "for...of". `map()` cria um novo array com os resultados da chamada de uma função fornecida em cada elemento do array original. `forEach()` executa uma função fornecida uma vez para cada elemento do array. `for...of` permite iterar sobre elementos de um array.
        ```markdown
    Em JavaScript, você pode percorrer e mapear um array JSON usando diferentes métodos, como "map", "forEach" e "for...of".
    - `map()`: Este método cria um novo array com os resultados da chamada de uma função fornecida em cada elemento do array original.
    - `forEach()`: Este método executa uma função fornecida uma vez para cada elemento do array.
    - `for...of`: Esta estrutura permite iterar sobre elementos de um array.
    ```

12. **O que são variáveis em JavaScript? Explique como declarar e atribuir valores a uma variável.**
    **Resposta:** Variáveis em JavaScript são contêineres que armazenam dados. Elas podem armazenar diferentes tipos de valores, como números, strings, objetos, entre outros. Para declarar uma variável, você pode usar `var`, `let` ou `const`.

13. **Em JavaScript, é possível ter múltiplas condições em uma estrutura "if/else"? Descreva como usar operadores lógicos (como "&&" e "||") para combinar condições.**
    **Resposta:** Sim, em JavaScript é possível ter múltiplas condições em uma estrutura "if/else" usando operadores lógicos como `&&` (E lógico) e `||` (OU lógico).

14. **Descreva a sintaxe do bloco "try" em JavaScript. Dê um exemplo prático de como usar o "try" para envolver um código suscetível a erros.**
    **Resposta:** O bloco `try` em JavaScript é usado para envolver um código que pode lançar exceções. Se uma exceção for lançada dentro do bloco `try`, ela será capturada pelo bloco `catch`.

15. **Como você pode lançar manualmente uma exceção em JavaScript? Explique o uso da palavra-chave "throw" para criar e lançar exceções personalizadas.**
    **Resposta:** Em JavaScript, você pode lançar manualmente uma exceção usando a palavra-chave `throw`. Isso permite criar e lançar exceções personalizadas.

## SQL

1. **Como você seleciona todas as colunas de uma tabela em SQL?**
   **Resposta:** b) SELECT *
   **Explicação:** O comando `SELECT *` é usado para selecionar todas as colunas de uma tabela em uma consulta SQL.

2. **Qual é o comando SQL utilizado para filtrar resultados em uma consulta?**
   **Resposta:** d) WHERE
   **Explicação:** O comando `WHERE` é usado para filtrar registros em uma consulta SQL com base em uma condição específica.

3. **Qual é o comando SQL utilizado para ordenar os resultados de uma consulta em ordem ascendente?**
   **Resposta:** d) ORDER BY
   **Explicação:** O comando `ORDER BY` é usado para ordenar os resultados de uma consulta em ordem ascendente (ou descendente, se especificado).

4. **Qual é o comando SQL utilizado para inserir novos dados em uma tabela?**
   **Resposta:** b) INSERT
   **Explicação:** O comando `INSERT INTO` é usado para inserir novos registros em uma tabela no banco de dados.

5. **Qual é o comando SQL utilizado para atualizar dados em uma tabela?**
   **Resposta:** b) UPDATE
   **Explicação:** O comando `UPDATE` é usado para modificar registros existentes em uma tabela no banco de dados.

## Integração de Sistemas

1. **O que é integração de sistemas?**
   **Resposta:** a) É um processo de comunicação entre diferentes sistemas de computador para permitir o compartilhamento de dados e funcionalidades.
   **Explicação:** Integração de sistemas é o processo de conectar diferentes sistemas de TI e softwares de forma a funcionar como um todo coordenado.

2. **O que significa API (Interface de Programação de Aplicativos) em integração de sistemas?**
   **Resposta:** c) Um conjunto de funções e procedimentos que permitem a comunicação entre sistemas.
   **Explicação:** API é um conjunto de rotinas e padrões de programação para acesso a um aplicativo de software ou plataforma baseado na Web.

3. **O que é um Web Service?**
   **Resposta:** c) É uma solução para conectar sistemas diferentes via web, usando padrões como XML e SOAP.
   **Explicação:** Web Service é uma tecnologia que utiliza protocolos padrão da Web (HTTP, XML, SOAP) para permitir a comunicação entre sistemas diferentes.

4. **O que é um token de acesso em integração de sistemas?**
   **Resposta:** c) Uma chave de autenticação usada para autorizar o acesso a um serviço.
   **Explicação:** Um token de acesso é um objeto que representa a autorização concedida a um cliente para acessar um serviço.

5. **O que é um "webhook" na integração de sistemas?**
   **Resposta:** d) É uma URL pública fornecida por um sistema para receber notificações automáticas de outro sistema.
   **Explicação:** Um webhook é um método de augmentação de APIs que permite que um aplicativo forneça informações em tempo real a outros aplicativos.

6. **O que é JSON?**
   **Resposta:** c) Um formato de dados leve e de fácil leitura usado para trocar informações entre sistemas.
   **Explicação:** JSON (JavaScript Object Notation) é um formato de dados leve e de fácil leitura que é usado para trocar informações entre sistemas.

7. **Qual é o código de status HTTP que indica sucesso na solicitação?**
   **Resposta:** a) 200 OK.
   **Explicação:** O código de status HTTP `200 OK` indica que a solicitação foi bem-sucedida.

8. **O que são headers HTTP?**
   **Resposta:** b) Informações adicionais enviadas pelo cliente e servidor em uma solicitação ou resposta HTTP.
   **Explicação:** Os headers HTTP são campos adicionais enviados juntamente com uma solicitação ou resposta HTTP, fornecendo informações sobre a solicitação ou resposta, como tipo de conteúdo, tamanho, autorização, etc.

9. **Quais são os delimitadores usados para marcar tags em XML?**
   **Resposta:** d) <>
   **Explicação:** As tags em XML são delimitadas por sinais de menor e maior (<>). Por exemplo, `<tag>` é uma tag XML.

10. **Qual é a diferença entre integração de sistemas síncrona e assíncrona?**
    **Resposta:** a) Na síncrona, a comunicação ocorre em tempo real com respostas imediatas, enquanto na assíncrona, a resposta pode ser recebida em um momento posterior.
    **Explicação:** Na integração síncrona, o cliente espera a resposta do servidor antes de continuar o processamento. Na assíncrona, o cliente pode continuar a execução e processar a resposta quando esta estiver disponível, permitindo uma maior eficiência e não bloqueio.

# Desafio

**Desenvolvimento de uma API em Node.js usando JavaScript**

Você deve criar uma API simples para gerenciar pedidos. A API deve permitir a criação, leitura, atualização e exclusão de pedidos, conforme descrito nas instruções fornecidas. Aqui está um esqueleto básico de como você pode implementar isso usando Express e MongoDB:

1. **Instale as dependências necessárias:**
   ```sh
   npm init -y
   npm install express mongoose body-parser

2. **servidor e configure o Express:**

```javascript

const express = require('express');
const bodyParser = require('body-parser');
const mongoose = require('mongoose');

const app = express();
app.use(bodyParser.json());

mongoose.connect('mongodb://localhost:27017/ordersDB', { useNewUrlParser: true, useUnifiedTopology: true });

const orderSchema = new mongoose.Schema({
   orderId: String,
   value: Number,
   creationDate: Date,
   items: [{
      productId: Number,
      quantity: Number,
      price: Number
   }]
});

const Order = mongoose.model('Order', orderSchema);

// Criar um novo pedido
app.post('/order', async (req, res) => {
   const { numeroPedido, valorTotal, dataCriacao, items } = req.body;
   const order = new Order({
      orderId: numeroPedido,
      value: valorTotal,
      creationDate: new Date(dataCriacao),
      items: items.map(item => ({
         productId: item.idItem,
         quantity: item.quantidadeItem,
         price: item.valorItem
      }))
   });

   try {
      await order.save();
      res.status(201).send(order);
   } catch (error) {
      res.status(400).send(error);
   }
});

// Obter os dados do pedido
app.get('/order/:id', async (req, res) => {
   try {
      const order = await Order.findOne({ orderId: req.params.id });
      if (!order) return res.status(404).send("Pedido não encontrado");
      res.send(order);
   } catch (error) {
      res.status(500).send(error);
   }
});

// Listar todos os pedidos
app.get('/order/list', async (req, res) => {
   try {
      const orders = await Order.find();
      res.send(orders);
   } catch (error) {
      res.status(500).send(error);
   }
});

// Atualizar o pedido
app.put('/order/:id', async (req, res) => {
   try {
      const updatedOrder = await Order.findOneAndUpdate({ orderId: req.params.id }, req.body, { new: true });
      if (!updatedOrder) return res.status(404).send("Pedido não encontrado");
      res.send(updatedOrder);
   } catch (error) {
      res.status(400).send(error);
   }
});

// Deletar o pedido
app.delete('/order/:id', async (req, res) => {
   try {
      const deletedOrder = await Order.findOneAndDelete({ orderId: req.params.id });
      if (!deletedOrder) return res.status(404).send("Pedido não encontrado");
      res.send(deletedOrder);
   } catch (error) {
      res.status(500).send(error);
   }
});

app.listen(3000, () => {
   console.log('Servidor rodando na porta 3000');
});

    ```