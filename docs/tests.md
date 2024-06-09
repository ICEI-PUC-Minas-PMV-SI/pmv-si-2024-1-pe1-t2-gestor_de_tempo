# Testes

Neste projeto serão realizados dois tipos de testes:

 - O **Teste de Software**, que utiliza uma abordadem de caixa preta, e tem por objetivo verificar a conformidade do software com os requisitos funcionais e não funcionais do sistema.
 - O **Teste de Usabilidade**, que busca avaliar a qualidade do uso do sistema por um usuário do público alvo. 

Se quiser conhecer um pouco mais sobre os tipos de teste de software, leia o documento [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/).

A documentação dos testes é dividida nas seguintes seções:

 - [Plano de Testes de Software](#plano-de-testes-de-software)
 - [Registro dos Testes de Software](#registro-dos-testes-de-software)
 - [Avaliação dos Testes de Software](#avaliação-dos-testes-de-software)
 - [Cenários de Teste de Usabilidade](#cenários-de-teste-de-usabilidade)
 - [Registro dos Testes de Usabilidade](#registro-dos-testes-de-usabilidade)
 - [Avaliação dos Testes de Usabilidade](#avaliação-dos-testes-de-usabilidade)

# Teste de Software

Nesta seção o grupo deverá documentar os testes de software que verificam a correta implementação dos requisitos funcionais e não funcionais do software.

## Plano de Testes de Software

Preencha a tabela com o plano dos testes. Para cada Caso de Teste (CT), associe qual o Requisito Funcional ou não funcional que ele está verificando. Associe também a página (ou artefato) onde o teste será realizado e descreva o cenário do teste. Veja a tabela de exemplo.


**Caso de Teste** | **CT01 - Criar conta**
 :--------------: | ------------
**Procedimento**  | 1) Acesse o endereço https://icei-puc-minas-pmv-si.github.io/pmv-si-2024-1-pe1-t2-gestor_de_tempo/ <br> 2) Clique em criar conta <br> 2) Preencha todos os campos do formulário <br> 3) Clique no botão "Continuar".
**Requisitos associados** | RF-002
**Resultado esperado** | Prosseguir para a parte 2 do cadastro
**Dados de entrada** | Inserção de dados válidos no formulário de cadastro
**Resultado obtido** | Sucesso

**Caso de Teste** | **CT02 - Fazer login**
 :--------------: | ------------
**Procedimento**  | 1) Preencha todos os campos do formulário <br> 2) Clique no botão "Entrar" <br> 
**Requisitos associados** | RF-003
**Resultado esperado** | Usuário validado e prosseguimento para página de cadastro de tarefas
**Dados de entrada** | Inserção de dados válidos no formulário de cadastro
**Resultado obtido** | Sucesso



## Registro dos Testes de Software

Esta seção deve apresentar o relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado no plano de testes pré-definido. Documente cada caso de teste apresentando um vídeo ou animação que comprove o funcionamento da funcionalidade. Veja os exemplos a seguir.

|*Caso de Teste*                                 |*CT01 - Criar conta parte 1*                                         |
|---|---|
|Requisito Associado | RF-002 – A aplicação deve permitir que os usuários se cadastrem.|
|Link do vídeo do teste realizado: | https://1drv.ms/u/s!AhD2JqpOUvJChapRtRSQ9vPzbNLwGA?e=mxZs6t| 

|*Caso de Teste*                                 |*CT02 - Criar conta parte 2*                                        |
|---|---|
|Requisito Associado | RF-003 - A aplicação deve fornecer um sistema de autenticação seguro, permitindo que os usuários acessem suas contas por meio de um processo de login.|
|Link do vídeo do teste realizado: | https://1drv.ms/v/s!AhD2JqpOUvJChapQ8CPXL-TI_A7iVg?e=spD3Ar | 


## Avaliação dos Testes de Software

Site pouco intuitivo e um pouco confuso. Os pontos fortes são a escolha de cores, iconografia, tipografia e a ideia central do site. 

## Testes de unidade automatizados (Opcional)

Se o grupo tiver interesse em se aprofundar no desenvolvimento de testes de software, ele podera desenvolver testes automatizados de software que verificam o funcionamento das funções JavaScript desenvolvidas. Para conhecer sobre testes unitários em JavaScript, leia 0 documento  [Ferramentas de Teste para Java Script](https://geekflare.com/javascript-unit-testing/).

# Testes de Usabilidade

O objetivo do Plano de Testes de Usabilidade é obter informações quanto à expectativa dos usuários em relação à  funcionalidade da aplicação de forma geral.

Para tanto, elaboramos quatro cenários, cada um baseado na definição apresentada sobre as histórias dos usuários, definido na etapa das especificações do projeto.

Foram convidadas quatro pessoas que os perfis se encaixassem nas definições das histórias apresentadas na documentação, visando averiguar os seguintes indicadores:

Taxa de sucesso: responde se o usuário conseguiu ou não executar a tarefa proposta;

Satisfação subjetiva: responde como o usuário avalia o sistema com relação à execução da tarefa proposta, conforme a seguinte escala:

1. Péssimo; 
2. Ruim; 
3. Regular; 
4. Bom; 
5. Ótimo.

Tempo para conclusão da tarefa: em segundos, e em comparação com o tempo utilizado quando um especialista (um desenvolvedor) realiza a mesma tarefa.

Objetivando respeitar as diretrizes da Lei Geral de Proteção de Dados, as informações pessoais dos usuários que participaram do teste não foram coletadas, tendo em vista a ausência de Termo de Consentimento Livre e Esclarecido.

Apresente os cenários de testes utilizados na realização dos testes de usabilidade da sua aplicação. Escolha cenários de testes que demonstrem as principais histórias de usuário sendo realizadas. Neste tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo de usuários que foi escolhido para participar do teste e as ferramentas utilizadas.

> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)


## Cenários de Teste de Usabilidade

| Nº do Cenário | Descrição do cenário |
|---------------|----------------------|
| 1             | Você é uma pessoa que deseja comprar um iphone. Encontre no site um iphone e veja detalhes de localização e contato da loja que anunciando. |
| 2             | Você é uma pessoa que deseja comprar um smartphone até R$ 2.000,00. Encontre no site smartphone's nessa faixa de preço. |



## Registro de Testes de Usabilidade

Cenário 1: Você é uma pessoa que deseja criar uma conta no site do gestor de tempo.

| Usuário | Taxa de sucesso | Satisfação subjetiva | Tempo para conclusão do cenário |
|---------|-----------------|----------------------|---------------------------------|
| 1       | SIM             | 5                    | 27.9 segundos                  |
| 2       | SIM             | 4                    | 39.1 segundos                  |
| 3       | SIM             | 4                    | 48.9 segundos                  |
|  |  |  |  |
| **Média**     | 100%           | 4,33                | 38.63 segundos                           |
| **Tempo para conclusão pelo especialista** | SIM | 5 | 10.7 segundos |


    Comentários dos usuários: Site pouco intuitivo. Falta um botão de cadastre-se. 


Cenário 2: Você é uma pessoa que deseja logar em sua conta no site do gestor de tempo.

| Usuário | Taxa de sucesso | Satisfação subjetiva | Tempo para conclusão do cenário |
|---------|-----------------|----------------------|---------------------------------|
| 1       | SIM             | 5                    | 12.7 segundos                          |
| 2       | SIM             | 5                    | 21.6 segundos                          |
| 3       | SIM             | 4                    | 18.4 segundos                          |
|  |  |  |  |
| **Média**     | 100%           | 4.67                | 17,56 segundos                           |
| **Tempo para conclusão pelo especialista** | SIM | 5 | 4.6 segundos |


    Comentários dos usuários: Interface simples e objetiva após acessar a página de cadastro.
Cenário 3: Você é uma pessoa que deseja logar em sua conta no site do gestor de tempo, não sendo direcionado a página de login após o cadastro.

| Usuário | Taxa de sucesso | Satisfação subjetiva | Tempo para conclusão do cenário |
|---------|-----------------|----------------------|---------------------------------|
| 1       | SIM             | 5                    | 17.6 segundos                          |
| 2       | SIM             | 4                    | 11.3 segundos                          |
| 3       | SIM             | 4                    | 16.5 segundos                          |
|  |  |  |  |
| **Média**     | 100%           | 4.33                | 15,13 segundos                           |
| **Tempo para conclusão pelo especialista** | SIM | 5 | 6.8 segundos |


    Comentários dos usuários: Mesmo comentário do primeiro cenário. Site pouco intuitivo. Falta um botão de entrar ou login. 


   

## Avaliação dos Testes de Usabilidade

Após entender e aprender a usar o menu dropdown, que é representado pelos traços no canto superior esquerdo da tela, a velocidade para logar aumenta comparada a velocidade para cadastrar usuário. 
E, com os comentários feitos acerca a usabilidade do site, entende-se que botões com suas funções especificadas fora do menu dropdown deixariam o site muito mais intuitivo. 



