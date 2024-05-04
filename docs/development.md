# Programação de Funcionalidades

Implementação do sistema descritas por meio dos requisitos funcionais e/ou não funcionais. Deve relacionar os requisitos atendidos os artefatos criados (código fonte) além das estruturas de dados utilizadas e as instruções para acesso e verificação da implementação que deve estar funcional no ambiente de hospedagem.

Para cada requisito funcional, pode ser entregue um artefato desse tipo.

O professor Rommel Carneiro apresenta alguns exemplos prontos para serem utilizados como referência:
- Login do sistema: [https://repl.it/@rommelpuc/LoginApp](https://repl.it/@rommelpuc/LoginApp) 
- Cadastro de Contatos: [https://repl.it/@rommelpuc/Cadastro-de-Contatos](https://repl.it/@rommelpuc/Cadastro-de-Contatos)


> **Links Úteis**:
>
> - [Trabalhando com HTML5 Local Storage e JSON](https://www.devmedia.com.br/trabalhando-com-html5-local-storage-e-json/29045)
> - [JSON Tutorial](https://www.w3resource.com/JSON)
> - [JSON Data Set Sample](https://opensource.adobe.com/Spry/samples/data_region/JSONDataSetSample.html)
> - [JSON - Introduction (W3Schools)](https://www.w3schools.com/js/js_json_intro.asp)
> - [JSON Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/json/index.htm)

## Exemplo

## Requisitos Atendidos

As tabelas que se seguem apresentam os requisitos funcionais e não-funcionais que relacionam o escopo do projeto com os artefatos criados:

### Requisitos Funcionais

|ID    | Descrição do Requisito | Responsável | Artefato Criado |
|------|------------------------|------------|-----------------|
|RF-001| A aplicação deve permitir que o usuário gerencie suas tarefas | João | index.html / index.css|
|RF-002| A aplicação deve permitir que os usuários se cadastrem. | João | cadastro.html / cadastro.css |
|RF-003| A aplicação deve fornecer um sistema de autenticação seguro, permitindo que os usuários acessem suas contas por meio de um processo de login. | João | login.html / login.css | 
|RF-004| A aplicação deve oferecer um processo de recuperação de senha, permitindo que usuários redefinam suas senhas em caso de esquecimento ou perda. | João | recuperar_senha.html / recuperar_senha.css | 
|RF-005| A aplicação deve permitir que os usuários cadastrem suas tarefas estipulando graus de prioridade | João | cadastrar-tarefa.html / cadastrar-tarefa.css|
|RF-006| A aplicação deve permitir que os usuários cadastrem suas tarefas estipulando prazo para conclusão | João | cadastrar-tarefa.html / cadastrar-tarefa.css |
|RF-007| A aplicação deve permitir que os usuários cadastrem ou excluam suas tarefas. | João | verificar_tarefas.html / verificar_tarefas.css |
|RF-008| A aplicação deve permitir que os usuários vejam e administrem suas tarefas, podendo filtrar por status "Em aberto" | João | verificar_tarefas.html / verificar_tarefas.css |
|RF-009|A aplicação deve permitir que os usuários vejam e administrem suas tarefas, podendo filtrar por status "Em atraso" | João | verificar_tarefas.html / verificar_tarefas.css |
|RF-010| A aplicação deve permitir que os usuários vejam e administrem suas tarefas, podendo filtrar por status "Finalizado" | João | cverificar_tarefas.html / verificar_tarefas.css |
|RF-011| A aplicação deve permitir que os usuários gerenciem suas informações de perfil como: alterar os dados a qualquer momento. | João | informacoes_cadastrais.html / informacoes_cadastrais.css |
|RF-012| A aplicação deve permitir que os usuários gerenciem suas informações de perfil como: excluir os dados a qualquer momento. | João | informacoes_cadastrais.html / informacoes_cadastrais.css |
|RF-013| A aplicação deve permitir que os usuários gerenciem suas informações de perfil como: consultar os dados a qualquer momento. | João | informacoes_cadastrais.html / informacoes_cadastrais.css |
|RF-014| A aplicação deve permitir a emissão de um relatório de tarefas realizadas no periodo selecionado. | João | informacoes_cadastrais.html / informacoes_cadastrais.css |
## Descrição das estruturas:

## Usuario
|  **Nome**      | **Tipo**          | **Descrição**                             | **Exemplo**                                    |
|:--------------:|-------------------|-------------------------------------------|------------------------------------------------|
| Id             | Numero (Inteiro)  | Identificador único do usuário            | 1                                              |
| Nome           | Texto             | Nome do usuário                         | João Antônio Veiga                                   |
| E-mail         | Texto             | E-mail do usuário                       | jav@gmail.com                                 |
| Senha  | Numero (Inteiro)  | Senha do usuário | 112345678**                                             |

