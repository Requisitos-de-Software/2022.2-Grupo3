# Entrevista

## <a>Histórico de Versão</a>

|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:----------:| :------: | :-----------: | :---------: |:---------: |
|03/12/2022|04/12/2022|1.0|Criação do documento| [Pedro Lucas](https://github.com/PedroLSF) | [João Lucas](https://github.com/HacKairos)|
|19/01/2023|20/01/2023|1.1|Correções com base na verificação|[Ana Luiza](https://github.com/AnHoff)|[Eduardo](https://github.com/edudsan)|

## <a>Introdução</a>

Depois de definir alguns tipos de perfis de usuários e personas, foi necessário conversar com algum dos possíveis usuários do aplicativo para entender as necessidades para que o usuário continue usando o MEI.

Será utilizado o modelo de **Entrevista Fechada**, ou seja, definimos perguntas que serão interessantes para o levantamentos de requisitos e irei apresentar para o entrevistado. 

Esse documento foca em disponibilizar os dados resultantes da entrevista realizada. Caso queira saber mais sobre a técnica de entrevista, clique [aqui](./index.md).

## <a>Dados</a>

* Entrevistador: Pedro Lucas S. Fernandes
* Data: 03/12/2022
* Horário: 13:00
* Duração 7:57 minutos

### <a>Entrevistado</a>

Nome: Renan Almeida de Souza.<br>Idade: 26 anos.<br>Sexo: Masculino.<br>Escolaridade: Ensino Superior Completo.<br>Classe Social: Media.

## <a>Perguntas e Respostas</a>

* **Qual o seu trabalho?**

Resposta: Apoiador linguístico pelo Goethe-Institut.

* **Quantos funcionários o seu serviço demanda?**

Resposta: Apenas o Renan.

* **Quanto tempo você utiliza o MEI?**

Resposta: 2 anos.

* **Qual o motivo da utilização do MEI?**

Resposta: Para receber o salário do Goethe-Institut.

* **Possui problemas com o Aplicativo?**

Resposta: Desistiu do uso, pois tinha muitos problemas. Não conseguia utilizar e optou pelo site.

* **Detalhes dos Problemas:**

-> Acessar o aplicativo e não completar as task

-> Precisar digitar o CNPJ várias vezes

-> Página vir em branco

-> Erro na página

-> Não salvar as ações

-> Difícil entender o contexto

* **Pode descrever a experiência?**

Resposta: Negativa, forçando a migração

* **Sentiu falta de alguma função?**

Resposta: Não consegue citar

* **Qual a frequência de uso do celular?**

Resposta: Está sempre na mão e usa frequentemente os aplicativos do governo, porém o MEI é um assunto muito delicado e importante, por isso evita o stress e abandonou o aplicativo.

* **Você se considera familiarizado com a tecnologia atual?**

Resposta: Sem dificuldades.

### <a>Gravação</a>

<center>

<audio controls>
  <source src="../../assets/outros/AudioEntrevistaRenan.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

</center>

## <a>Requisitos Elicitados</a>
A elicitação de requisitos levou em consideração também o nível de benefício e penalidade que cada um traria ao sistema caso seja implementado ou não. Confira a tabela 1 abaixo.

<center>

|ID|Requisito|Descrição|Nível de Benefício|Penalidade|Tipo|
| :----------: |:----------:| :------: | :-----------: |:-----------: | :----: |
|ENT1|Validação|O aplicativo deve solicitar o CNPJ apenas uma vez|7|5| Não Funcional |
|ENT2|Consistência|O aplicativo deve ir até o final da operação antes de realizar qualquer outra etapa|9|9| Não Funcional |
|ENT3|Confiabilidade|O aplicativo deve evitar os erros e telas brancas através do uso |9|9| Não Funcional|
|ENT4|Salvamento|O aplicativo deve salvar as informações|7|6| Não Funcional |
|ENT5|Outros Logins|O aplicativo deve realizar o login em mais de uma conta |5|5| Funcional |

*Tabela 1 - Requisitos elicitados*

</center>

**Legendas**:

* ENT -> ID da entrevista
* Nível de Benefício -> Vaira de 1 a 9, onde 1 é pouco benéfico e 9 é muito benéfico
* Penalidade -> Varia de 1 a 9, onde 1 não gera muitos problemas e 9 impossibilita o uso do usuário

## <a>Bibliografia</a>
[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) _Interação Humano-Computador e Experiência do usuário_. Autopublicação. ISBN: 978-65-00-19677-1.
