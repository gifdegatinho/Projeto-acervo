# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|  
|Futuro Usuario | Fazer Login |  Ter acesso |
|Estudante | Adquirir acesso ao menu de diversos Temas e Gêneros textuais | Agilizar minha procura |
|Professor | Ter acesso especifico para docentes com vários temas | Alcançar de maneira ágil todo o material direcionado para ensino didático |
|Pesquisador científico  |  Ter um histórico de minhas aquisições, e solicitações de reserva |  Ter um registro de minhas pesquisas | 
|Profissional no ramo de Engenharia Civil |  Opção de visualizar material mais alinhado com minha área de atuação |  Localizar tópicos específicos |
|Amante da leitura  |  Acesso por Título, Autor, Assunto, Tema |  Tornar minha busca Personalizada à minha escolha |
|Portador de deficiência  |  Usufruir de ferramentas que me conceda acessibilidade , como leitores de telas, tradutores de língua para libras... |  Ter inclusão social |
|Usuário do sistema |  Quero poder baixar E-Books |  Ter acesso of-Line, E-Reards...| 
|Usu´rio do sistema |  Fazer Impressão | Ter acesso físico a alguma informa | 
|Usuário do sistema |  Ver de forma sucinta as regras de serviço, como: empréstimos, valores, multas, renovação, reservas |  tomar ciência sem perder tempo |
|Usuário  do sistema |  Canal de comunicação como: chat, e-mail, WhatsApp |  Tirar dúvidas  | 
|Administrador |  Alterações no cadastro do usuário  |  Controle e administração |
|Administrador | Relatório de locações com filtro de datas | Controle financeiro |
|Administrador | Canal de comunicação com o usuário do sistema | Alertas de vencimento de entrega|
|Administrador  | De acordo com o perfil do usuário sugerir opções | Ter um contato mais próximo com o cliente| 
|Administrador | cadastro com senha na hierarquia de administração  | controle ordenado por nível de comando|

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

> |RF-001| O sistema deve permitir o registro de livros, incluindo informações como título, autor, editora, ano de publicação, número de páginas. |ALTA| 
>
> |RF-002| O sistema deve permitir a catalogação dos livros de acordo com diferentes critérios, como autor, título, assunto. |MÉDIA|
>
> |RF-002| O sistema deve permitir o empréstimo de livros para usuários cadastrados, incluindo a definição de prazos e limites de empréstimo. |ALTA| 
>
> |RF-003| O sistema deve permitir a renovação do empréstimo de livros, desde que o prazo de devolução não tenha expirado. |MÉDIA|
>
> |RF-004| O sistema deve permitir a geração de relatórios, como relatórios de empréstimos. |MÉDIA|
>
> |RF-005| O sistema deve permitir que os usuários acessem o acervo de livros remotamente, através de uma plataforma online, por exemplo. |ALTA| 
>
> |RF-006| O sistema deve permitir o cadastro, consulta, atualização e exclusão dos usuários. |ALTA| 

### Requisitos não Funcionais


> |RNF-001| O sistema deve ser capaz de lidar com um grande número de usuários e transações simultâneas sem comprometer o desempenho. |MÉDIA| 
> 
> |RNF-002| O sistema deve estar disponível para uso a maior parte do tempo, com tempos de inatividade planejados para manutenção. |MÉDIA| 
> 
> |RNF-003| O sistema deve ser flexível e capaz de se adaptar às mudanças nos requisitos e na estrutura organizacional. |ALTA| 
> 
> |RNF-004| O sistema deve ser confiável, com alteração de backup e recuperação de falhas para garantir a integridade dos dados. |MÉDIA| 
> 
> |RNF-005| O sistema deverá ser desenvolvido na linguagem C#. |ALTA| 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
