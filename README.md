# Habilidades

- Buscar documentos no banco
- Usar filtros na busca
- Deletar documentos conforme filtro
- Contar documentos compreendidos nos filtros pedidos
- Inserir documentos no banco

# Entregáveis

Temos, neste projeto, uma série de desafios com diferentes níveis de complexidade que devem ser resolvidos cada um em seu arquivo próprio.

1. Leia a pergunta e crie no diretório `challenges` um arquivo chamado `desafioN.js`, em que N é o número do desafio.

2. O arquivo deve conter apenas o código MQL (_Mongo Query Language_) do desafio resolvido. **Não se esqueça de incluir o ponto e vírgula (";")** no final de suas queries, como no exemplo a seguir:
    ```js
    db.voos.find();
    ```
    ⚠️ **Restrições** ⚠️:

      - **Não se deve usar aspas simples** para especificar campos e/ou valores. Quando for necessário usar aspas, **use somente aspas duplas**;

      - **Não se deve usar o comando `use dataFlights`**, haja visto que **os testes já se conectam automaticamente à base `dataFlights`**.

3. Faça isso até finalizar todos os desafios e depois siga as instruções de como entregar o projeto em [**Instruções para entregar seu projeto**](#instruções-para-entregar-seu-projeto).

4. Para entregar o seu projeto você deverá criar um _Pull Request_ neste repositório. Este _Pull Request_ deverá conter no diretório `challenges` os arquivos `desafio1.js`, `desafio2.js` e assim por diante até o `desafio28.js`, que conterão seu código `MQL` de cada desafio, respectivamente.