# Histórias de Usuário

## <a>Histórico de Versão</a>
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|30/12/2022|02/01/2023|1.0|Criação do documento| [Pedro Lucas](https://github.com/PedroLSF) | [Ana Luiza](https://github.com/AnHoff) e [Thiago Oliveira](https://github.com/Thiab394) |
|03/01/2023|04/01/2023|1.1|Adição dos critérios de aceitação| [Thiago Oliveira](https://github.com/Thiab394) | [Ana Luiza](https://github.com/AnHoff) |
|24/01/2023|25/01/2023|1.2|Correção com base na Verificação| [Thiago Oliveira](https://github.com/Thiab394) | [Ana Luiza](https://github.com/AnHoff) |


## <a>Introdução</a>
Um componente-chave do desenvolvimento de software ágil é colocar as pessoas em primeiro lugar; essa ação é posta em prática pelas histórias de usuário, que colocam os usuários finais reais sob os holofotes.

Uma história de usuário é uma explicação informal e geral sobre um recurso de software escrita a partir da perspectiva do usuário final. Seu objetivo é articular como um recurso de software pode gerar valor para o cliente. [1]

## <a>Metodologia</a>

Será utilizado um __card__ para definir as histórias de usuário, assim como visto na Tabela 1:

| **ID** | **Nome** |
|:-------|:---------|
| USXX | Título |
| Descrição | _Eu, como_ XXX, _desejo_ XXX  |
| Critérios de Aceitação | Deve conter as seguintes opções: </br> > XXX </br> > XXX </br> |

**Tabela 1 - Modelo De US**<br>
A partir da tabela 1, foram feitos os US's, representados em uma especie de épicos, tendo no "épico 1" a "Tabela 2" e "Tabela 3", no "épico 2" temos a "Tabela 4" e
"Tabela 5", no terceiro épico temos as Tabelas de 6 a 11, no quarto epico temos as tabelas "Tabela 12", "Tabela 13" e "Tabela 14", no ultimo épico temos as tabelas restantes, "Tabela 15", "Tabela 16", "Tabela 17" e "Tabela 18".

**Legenda:**

* US - User Story (História de Usuário)
* EP - Épico
* FT - Feature

## <a>Features</a>
### <a>1. Cadastro e Autenticação</a>
#### <a>1.1 Cadastro</a>
| **ID** | **Nome** |
|:-------|:---------|
| US01 | Realizar Cadastro |
| Descrição | _Eu, como_ _**Usuário**_, _desejo enviar toda minhas documentações cadastrais pelo aplicativo para não precisar acessar várias plataformas diferentes durante o cadastro_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel Realizar o cadastro no aplicativo </li><li> O aplicativo deve instruir o usuário para a criação do CNPJ</li></ul>|
| Rastro | [BS01](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 2 - US01**
 

#### <a>1.2 Autenticar</a>
| **ID** | **Nome** |
|:-------|:---------|
| US02 | Autenticar |
| Descrição | _Eu, como_ _**Usuário**_, _desejo autenticar que sou eu utilizando meu MEI para evitar frustações_  |
| Critérios de Aceitação |  <ul><li>O aplicativo deve exigir um CNPJ já em circulação para ser acessado</li><li>O aplicativo deve exigir ID/E-mail e senha para ser acessado </li> </ul>|
| Rastro | [IS07](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Introspeccao/) |

**Tabela 3 - US02**

### <a>2. Login e Logout</a>
#### <a>2.1 Login</a>
| **ID** | **Nome** |
|:-------|:---------|
| US03 | Realizar Login |
| Descrição | _Eu, como_ _**Usuário**_, _desejo utilizar um sistema de login para obter dados únicos e ter mais segurança_  |
| Critérios de Aceitação | <ul><li>O aplicativo deve ter um sistema de login com senha, ID de usuário e CNPJ</li><li> O aplicativo deve ter um sistema de verificação de robôs (Bots)</ul></li>|
| Rastro | [BS02](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 4- US03**

#### <a>2.2 Logout</a>
| **ID** | **Nome** |
|:-------|:---------|
| US04 | Realizar Logout |
| Descrição | _Eu, como_ _**Usuário**_, _desejo sair da minha conta para garantir minha privacidade caso use o dispositivo de outra pessoa_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel realizar logout de sua conta a qualquer momento pelo aplicativo</li><li> Deve haver uma notificação fixa mostrando que o usuário continua online em sua conta ao minimizar ou fechar o aplicativo sem realizar logout</li></ul> |
| Rastro | [ENT5](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Entrevista/) |

**Tabela 5 - US04**

### <a>3. Configurações</a>
#### <a>3.1 Lembrete</a>
| **ID** | **Nome** |
|:-------|:---------|
| US05 | Lembrar os pagamentos |
| Descrição | _Eu, como_ _**Usuário**_, _desejo receber um lembrete para pagamento do DAS para não perder a data limite de pagamento_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel receber uma notificação de lembrete do pagamento do DAS</li><li>O lembrete deve ser enviado um mês antes e no começo de cada semana seguinte, sendo que, na última semana, deve ser enviado todos os dias (configuração padrão)</li><li>Deve ser possivel ativar e desativar a qualquer momento o envio de lembretes</li><li>Deve ser possivel editar as datas/períodos em que o lembrete aparecerá para o usuário</li></ul> |
| Rastro | [BS03](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 6 - US05**

#### <a>3.2 Aviso</a>
| **ID** | **Nome** |
|:-------|:---------|
| US06 | Avisar sobre a realização de uma ação |
| Descrição | _Eu, como_ _**Usuário**_, _desejo receber um aviso para saber se realizei uma ação com sucesso ou não_  |
| Critérios de Aceitação | <ul><li>Deve aparecer um pop-up de confirmação dizendo que a atividade foi realizada com sucesso ou que houve erro(s), citando-os</li><li>O pop-up deve aparecer apenas para atividades relevantes, como o pagamento do DAS, excluindo atividades simples como configurar o aplicativo</li></ul> |
| Rastro | [BS06](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 7 - US06**

#### <a>3.3 Autorizar</a>
| **ID** | **Nome** |
|:-------|:---------|
| US07 | Autorizar a obtenção de dados |
| Descrição | _Eu, como_ _**Usuário**_, _desejo autorizar o acesso do aplicativo a determinados dados de outros sistemas para não utilizar sites externos_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel autorizar o acesso a dados de sistemas externos ao aplicativo</li><li>Deve haver uma opção nas configurações para realizar a autorização desse processo</li><li>Deve aparecer os termos de uso com todas as condições do comparilhamento de dados e no que isso implica</li><li>Deve ser necessário a aceitação dos termos de uso para ativar o recurso</li></ul> |
| Rastro | [BS04](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 8 - US07**

#### <a>3.4 Dispositivos</a>
| **ID** | **Nome** |
|:-------|:---------|
| US08 | Autorizar a obtenção de dados |
| Descrição | _Eu, como_ _**Usuário**_, _desejo utilizar o MEI em diversos modelos de dispositivos para conseguir usar o aplicativo em modelos antigos ou não tão populares_  |
| Critérios de Aceitação | <ul><li>O aplicativo deve ser tratado em cada uma de suas atualizações para atingir o maior numero de dispositivos possiveis, tanto em diversidade de dispositivos quanto em versionamento de sistemas, sem comprometer suas funções e desempenho</li></ul> |
| Rastro | [BS08](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 9 - US08**

#### <a>3.5 Acessibilidade</a>
| **ID** | **Nome** |
|:-------|:---------|
| US09 | Garantir acessibilidade|
| Descrição | _Eu, como_ _**Usuário**_, _desejo ter recursos de acessiblidade para não depender de outras pessoas para utilizar o aplicativo_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel ativar e desativar recursos de acessibilidade nas configurações, como a mudança de cores e a leitura de tela</li><li>Deve ser possivel ler toda a pagina por meio de um leitor de tela ao entrar na mesma </li><li>Deve ter uma descrição detalhada para cada imagem presente no aplicativo, para que o leitor de tela possa ser utilizado de forma eficaz</li><li>Deve-se ter um som de confirmação ao tocar em um botão e abrir um pop-up de confirmação de cada ação de botão pressionado em atividades relevantes</li><li>Deve possuir facil integração com os leitores de tela de softwares externos</li><li>Deve ser possivel aumentar a fonte dos textos</li></ul> |
| Rastro | [BS11](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 10 - US09**

#### <a>3.6 Dados</a>
| **ID** | **Nome** |
|:-------|:---------|
| US10 | Alterar/Salvar Dados|
| Descrição | _Eu, como_ _**Usuário**_, _desejo alterar e salvar os dados durante a utilização do MEI para manter meu cadastro em dia_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel alterar e salvar os dados durante a utilização do MEI</li><li>Os salvamentos de dados ocorrerão automaticamente ao realizar alguma operação que modifique os mesmos, ou ao ser modificado pelo próprio usuário</li></ul> |
| Rastro | [ENT4](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 11 - US10**

### <a>4. Suporte</a>

#### <a>4.1 Chat</a>
| **ID** | **Nome** |
|:-------|:---------|
| US11 | Buscar auxílio no chat |
| Descrição | _Eu, como_ _**Usuário**_, _desejo entrar em um chat com o suporte para tirar eventuais dúvidas_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel entrar em um chat de conversa com um atendente do suporte</li><li>Ao entrar no chat de suporte, devem aparecer mensagens prontas explicando o que fazer e referenciar possíveis soluções do problema em um F.A.Q geral do aplicativo</li><li>Deve ser possivel encerrar a sessão de atendimento a qualquer momento</li><li>Deve ser possivel enviar um feedback sobre o seu atendimento por chat, mesmo ao encerrar previamente</li></ul> |
| Rastro | [BS07](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 12 - US11**

#### <a>4.2 Texto</a>
| **ID** | **Nome** |
|:-------|:---------|
| US12 | Entender os texto |
| Descrição | _Eu, como_ _**Usuário**_, _desejo ter acesso a explicações sobre os processos e siglas do MEI para entender melhor o aplicativo_  |
| Critérios de Aceitação | <ul><li>O aplicativo deve possuir uma verificação por login que verá se é o primeiro login daquele usuário no app, e a partir disso mostrará uma pagina de "primeia vez utilizando o MEI"</li><li>Em tal pagina de "primeira vez utilizando o MEI" deve ter explicações sobre os processos e siglas do MEI</li><li>Deve ser possivel fechar tal página a qualquer momento</li></ul>Deve ser possivel conferir tal página a qualquer momento a partir de uma opção no menu |
| Rastro | [BS12](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Brainstorming/) |

**Tabela 13 - US12**

#### <a>4.3 FAQ</a>
| **ID** | **Nome** |
|:-------|:---------|
| US13 | Acesso a Perguntas Frequentes |
| Descrição | _Eu, como_ _**Usuário**_, _desejo ver as dúvidas mais frequentes para solucionar os meus problemas rapidamente_  |
| Critérios de Aceitação | <ul><li>O aplicativo deve possuir uma página de FAQ, onde as dúvidas mais frequentes são respondidas</li><li>Deve ser possivel acessar a página do FAQ mesmo sem realizar login</li><li>A pagina de FAQ deve ser separada por categorias e subcategorias de problemas</li></ul> |
| Rastro | [IS05](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Introspeccao/) |

**Tabela 14 - US13**

### <a>5. Documentação</a>

#### <a>5.1 Emitir Boletos</a>
| **ID** | **Nome** |
|:-------|:---------|
| US14 | Emitir |
| Descrição | _Eu, como_ _**Usuário**_, _desejo emitir meus boletos pelo MEI para pagá-los rapidamente_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel emitir os boletos pelo MEI</li><li>Antes de emitir o boleto, deve ser disponibilizada uma prévia do mesmo para o usuário</li><li>Deve ser possivel baixar o boleto somente após a prévia de visualização ser apresentada ao usuário</li></ul>
| Rastro | [IS02](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Introspeccao/) |

**Tabela 15 - US14**

#### <a>5.2 Solicitar Restituição</a>
| **ID** | **Nome** |
|:-------|:---------|
| US15 | Restituir |
| Descrição | _Eu, como_ _**Usuário**_, _desejo solicitar uma Restituição pelo aplicativo MEI para evitar filas e burocracias em agências presenciais_  |
| Critérios de Aceitação | <ul><li>O aplicativo deve ter uma página isolada para "Solicitação de restituição"</li><li>Deve ter uma breve explicação do que é a solicitação de restituição na página da mesma</li><li>Deve ser possivel realizar a solicitação de restituição</li></ul> |
| Rastro | [IS04](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Introspeccao/) |

**Tabela 16 - US15**

#### <a>5.3 Informações CNPJ</a>
| **ID** | **Nome** |
|:-------|:---------|
| US16 | Buscar Informações do CNPJ |
| Descrição | _Eu, como_ _**Usuário**_, _desejo buscar informações sobre meu CNPJ e status pelo aplicativo do MEI para conferir se está tudo de acordo com o esperado_  |
| Critérios de Aceitação | <ul><li>Deve ter uma página isolada para "consultar meu CNPJ" no aplicativo</li><li>Deve ser possível visualizar as informações do CNPJ e o status do mesmo</li></ul> |
| Rastro | [IS03](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Introspeccao/) |

**Tabela 17 - US16**

#### <a>5.4 Pagar Boletos</a>
| **ID** | **Nome** |
|:-------|:---------|
| US17 | Pagar |
| Descrição | _Eu, como_ _**Usuário**_, _desejo pagar meus boletos pelo MEI para evitar maiores burocracias_  |
| Critérios de Aceitação | <ul><li>Deve ser possivel realizar o pagamento dos boletos</li><li>O aplicativo deve ter uma página apenas para pagamento de boletos</li><li>Deve-se mostrar um resumo do valor total ou valores individuais caso vários boletos sejam pagos de uma vez</li></ul> |
| Rastro | [IS02](https://requisitos-de-software.github.io/2022.2-MEI/Requisitos/Elicitacao/Introspeccao/) |

**Tabela 18 - US17**

## <a>Bibliografia</a>

[1] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 46 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.
