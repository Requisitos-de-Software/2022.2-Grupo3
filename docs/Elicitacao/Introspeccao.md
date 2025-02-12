# Introspecção

|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:----------:| :------: | :-----------: | :---------: |:---------: |
|04/12/2022|05/12/2022|1.0|Criação do documento| [Arthur Taylor](https://github.com/Eruel6) |[Ana Luiza](https://github.com/AnHoff)|
|08/12/2022|09/12/2022|1.1|Adição de detalhes do método| [Arthur Taylor](https://github.com/Eruel6) | [Ana Luiza](https://github.com/AnHoff)|
|19/01/2023|20/01/2023|1.2|Correções com base na verificação|[Ana Luiza](https://github.com/AnHoff)| [Arthur Taylor](https://github.com/Eruel6)|

## <a>Introdução</a>

A instrospecção é uma técnica utilizada para elicitar requisitos. Caso deseje saber mais detalhadamente sobre essa técnica, acesse o documento de [técnicas de elicitação](./index.md).

Foram obtidos a partir desse método dados sobre o nível de benefício e de penalidade que cada requisito agrega ao sistema caso seja implementado ou não, além da identificação de alguns requisitos.

## <a>Elicitação através da Introspecção</a>
A introspecção foi realizada dia 05 de dezembro de 2022 às 15h pelo celular próprio do avaliador. O sistema utilizado foi Android, no dispositivo Galaxy S10.

### Acesso ao aplicativo

Ao abrir o aplicativo deve aparecer uma tela pedindo a inserção do CNPJ para login.

### Com o login realizado através do CNPJ

Devem ser apresentados os dados do microempreendedor;

Deve ser apresentado uma opção para emitir o DAS;

Deve ser apresentado um botão para realizar a consulta detalhada do CNPJ;

Deve ser apresentado uma opção de consulta do SIMEI;

Deve ser apresentado uma opção para solicitar e acompanhar um pedido de restituição;

Deve ser apresentado a opção de fazer a declaração anual do MEI;

Deve ser apresentado a opção de preguntas e respostas sobre o MEI;

### Com a emissão do DAS selecionado 

Deve ser apresentado um calendário com as informações sobre a situação da DAS (liquidado ou a vencer);

Deve ser possível emitir um boleto para pagamento das DAS que estão "a vencer" ou "vencido";

Deve ser apresentada a legenda da situação da DAS:

- Verde: o DAS foi pago, débito liquidado;
- Cinza: a empresa não é optante do SIMEI, não é possível emitir a DAS;
- Amarelo: débito se encontra em aberto, podendo ser paga sem multa;
- Vermelho: débito vencido, devendo ser pago com multa e juros;
- Roxo: débito enviado para dívida ativa, não e possível gerar a DAS;

Deve ser possível compartilhar um print da situação atual da visão dos DAS.

### Com a consulta do CNPJ selecionada

Deve ser apresentado os segunites dados referentes ao CNPJ logado:
- Situação cadastral;
- Nome fantasia;
- Natureza jurídica;
- CNAE;
- Capital Social;
- Endereço;
- Telefone(s);
- Endereço eletrônico.

Deve ser possível compartilhar um print da tela de informações do CNPJ.

### Com a consulta do SIMEI selecionada

Deve ser apresentado os seguintes dados referentes ao CNPJ logado:
- Situação atual de opção (optante ou não) do "Simples nacional" e do "SIMEI";
- Data do momento em que se tornou optante.

Deve ser apresentado o cálculo do valor devido mensalmente para o MEI no ano corrente;

Deve ser possível compartilhar um print da tela de consulta do SIMEI.

### Com o pedido de restituição selecionado

Deve apresentar uma tela para acompanhamento dos pedidos de restituição cadastrados no CNPJ;

Deve apresentar a opção de realizar um novo pedido de restituição.

### Com a declaração anual do MEI seleiconada

Deve ser aberto uma aba no navegador redirecionando o usuário para realizar a declaração.

### Com perguntas e respostas selecionada

Deve fazer download de um arquivo PDF contendo a solução de dúvidas mais frequentes e manual da utilização do MEI e Simples Nacional.

## Parecer do Avaliador 

### Arthur Taylor 

Durante a utilização do aplicativo foi desafiador encontrar algumas funcionalidades, com algumas necessitando da realização de ações em diferentes telas. Outro ponto que deve ser ressaltado é a necessidade de redirecionamento para um site externo ao aplicativo para a realização da declaração anual e também a nescessidade de download de um arquivo com as principais perguntas que poderia ser substitído por algum tipo de chatbot ou fórum para facilitar o encontro de respostas para suas perguntas sem a necessidade de acessar um documento externo.

## Tabela de requisitos funcionais:
A tabela 1 abaixo apresenta os requisitos funcionais identificados.

<center>

|ID|Requisito|Descrição|Nível de Benefício| Penalidade |
| :----------: |:----------:| :------: | :-----------: | :---------: |
|IS01|Login|Deve ser possível realizar login a partir de um CNPJ|9|9|
|IS02|Emissão|Deve ser possível emitir o DAS|5|3|
|IS03|Informação|Deve ser possível Consultar informações do CNPJ|5|5|
|IS04|Restituição|Deve ser possível pedir restituição|5|3|
|IS05|FAQ|Deve ser possível consultar perguntas e respostas frequentes|5|3|

*Tabela 1 - Requisitos funcionais*

</center>

## Tabela de requisitos não funcionais:
A tabela 2 abaixo apresenta os requisitos não funcionais identificados.
<center>

|ID|Requisito|Descrição|Nível de Benefício| Penalidade |
| :----------: |:----------:| :------: | :-----------: | :---------: |
|IS06|Compatibilidade|O aplicativo deve ser suportado pelos principais sistemas mobile|9|7|
|IS07|Segurança|Deve se exigir um CNPJ para acesso do aplicativo|8|8|
|IS08|Facilidade de uso|O aplicativo deve ser de fácil entendimento e uso por seus usuários|6|7|

*Tabela 2 - Requisitos não funcionais*

</center>

## <a>Bibliografia</a>
[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) _Interação Humano-Computador e Experiência do usuário_. Autopublicação. ISBN: 978-65-00-19677-1.
