# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto.

Caso deseje atribuir uma imagem a sua persona, utilize o site https://thispersondoesnotexist.com/

## Personas

![4](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2024-1-pe1-t2-gestor_de_tempo/assets/136640488/52020a3a-d059-47b8-abea-fe94dc6feea2)
![3](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2024-1-pe1-t2-gestor_de_tempo/assets/136640488/74470ffd-be96-4044-882f-956b8e513bfa)
![2](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2024-1-pe1-t2-gestor_de_tempo/assets/136640488/d5c6a29c-5425-4806-83fc-ebfd0780d95e)
![1](https://github.com/ICEI-PUC-Minas-PMV-SI/pmv-si-2024-1-pe1-t2-gestor_de_tempo/assets/136640488/617a9adb-ac78-4236-a98b-39012c7590d1)

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
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | 
|------|-----------------------------------------|----| 
|RF-001|Deve existir uma página inicial (landing page) informativa que apresenta o propósito da plataforma e metodologia utilizada | ALTA |  
|RF-002| A aplicação deve permitir que os usuários se cadastrem. | ALTA | 
|RF-003| A aplicação deve fornecer um sistema de autenticação seguro, permitindo que os usuários acessem suas contas por meio de um processo de login. | ALTA | 
|RF-004| A aplicação deve oferecer um processo de recuperação de senha, permitindo que usuários redefinam suas senhas em caso de esquecimento ou perda. | MÉDIA | 
|RF-005| A aplicação deve permitir que os usuários cadastrem suas tarefas estipulando graus de prioridade | MÉDIA | 
|RF-006| A aplicação deve permitir que os usuários cadastrem suas tarefas estipulando prazo para conclusão | MÉDIA |
|RF-007| A aplicação deve permitir que os usuários cadastrem ou excluam suas tarefas. | MÉDIA | 
|RF-008| A aplicação deve permitir que os usuários vejam e administrem suas tarefas, podendo filtrar por status "Em aberto" | MÉDIA | 
|RF-009| A aplicação deve permitir que os usuários vejam e administrem suas tarefas, podendo filtrar por status "Em atraso" | MÉDIA |
|RF-010| A aplicação deve permitir que os usuários vejam e administrem suas tarefas, podendo filtrar por status "Finalizado" | MÉDIA | 
|RF-011| A aplicação deve permitir que os usuários gerenciem suas informações de perfil como: alterar os dados a qualquer momento. | MÉDIA | 
|RF-012| A aplicação deve permitir que os usuários gerenciem suas informações de perfil como: excluir os dados a qualquer momento. | MÉDIA |
|RF-013| A aplicação deve permitir que os usuários gerenciem suas informações de perfil como: consultar os dados a qualquer momento. | MÉDIA |
|RF-014| A aplicação deve permitir a emissão de um relatório de tarefas realizadas no periodo selecionado. | MÉDIA |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve oferecer uma interface com design responsivo que se adapte aos dispositivos móveis e desktops. | MÉDIA | 
|RNF-002| A aplicação deve apresentar um layout simples e de fácil utilização. |  MÉDIA | 
|RNF-003| As senhas dos usuários devem ser criptografadas antes de serem armazenada |  MÉDIA | 
|RNF-004| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 

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
