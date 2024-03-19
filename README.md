# 🚀 Formação Agile Test Engineer - Testes Manuais

## O que você vai encontrar nesse repositório?

Neste repositório, você encontrará o desafio da disciplina Fundamentos em testes da software realizado durante a formação  Agile Test Engineer fornecida pela [E2E Treinamentos](https://e2etreinamentos.com.br/formacao-agile-test-engineer/)

## ✨ Sobre o desafio de testes manuais

###  🎯 Primeira etapa

A primeira etapa do desafio dos testes manuais se deu por participação ativa em reunião de refinamento para entendimento dos requisitos de negócio da aplicação E2E Suporte.

- Entendimento de escolpo de testes.
- Análise dos requisitos.
-  Escrita de histórias de usuário, segundo a técnica INVEST.
-  Análise de layout (FIGMA).
-  Participação na Planning e estimativa de histórias (planning poker).

### 🎯 Segunda etapa

Segunda etapa prática:
-  Planejamento de testes.
- Estratégia dos testes.
-  Técnicas de teste como: Particionamento de Equivalência, Análise de Valor Limite e Tabela de Decisão.
- Modelagem e especificação de casos de testes (step by step e/ou Gherkin).
-  Solicitação e preparação de Massa de testes.
- Gerenciamento e monitoramento de testes.
- Execução de testes funcionais.
- Abertura e gerenciamentos de defeitos(Bugs) identificados.


### 🎯 Terceira etapa

Terceira etapa prática:
- Métricas de Qualidade
-  Relatórios de fechamento do ciclo de testes
- Elaboração de status report para apoiar a tomada de decisão de negócio
-  Apresentação da Review
- Participação na Restrospectiva.


##   👨🏻‍💻Sobre o objeto de testes.

### Requisitos iniciais do projeto

[Requisitos E2E Suporte](https://e2e-suporte.vercel.app/) - inserir link do notion

### MVP da Plataforma testada

[E2E Suporte](https://e2e-suporte.vercel.app/) - usuários do suporte autenticados via Google.
[E2E Suporte/open](https://e2e-suporte.vercel.app/open) - link externo para abertura de chamado (não autenticado)

### Imagens da plataforma

<div align="center">

#### E2E Suporte - Cadastro de Novo Aluno
![Orange HRM - Login](https://github.com/leonardonps/desafios-finais-testes-manuais-automatizados-minsait/blob/main/desafio-testes-automatizados/imagens/tela-login.png)

#### E2E Suporte- Dashboard
![Menus principais do site](https://github.com/leonardonps/desafios-finais-testes-manuais-automatizados-minsait/blob/main/desafio-testes-automatizados/imagens/orange-menus.png)

#### E2E Suporte - Novo Chamado
![Orange HRM - Seção Admin](https://github.com/leonardonps/desafios-finais-testes-manuais-automatizados-minsait/blob/main/desafio-testes-automatizados/imagens/orange-admin.png)

#### E2E Suporte - Novo Chamado – rota externa
![Orange HRM - Seção PIM](https://github.com/leonardonps/desafios-finais-testes-manuais-automatizados-minsait/blob/main/desafio-testes-automatizados/imagens/orange-pim.png)

</div>

### ⚙️ Ferramentas utilizadas para a elaboração dos casos de testes

-  [QASE](https://qase.io/) - ferramenta para escrita, e report de execução de testes.
-  [Planilha de Casos de teste](https://pt-br.reactjs.org)
 - Abordagem de teste: Caixa-preta

###  🧪 Como foi planejado os testes?

Os testes foram divididos em 3 suítes principais focadas em determinadas partes da plataforma E2E Suporte. São elas:

#### 📝Suíte Login | Objetivo: Verificar a tela de login

Para essa suíte, 4 casos foram pensados:

- Caso 1: login com credenciais válidas, realizando adequadamente o caminho pensado.

- Caso 2: contraponto do Caso 1. Nele, foram testadas duas situações: o usuário inserindo credenciais inválidas e nulas.


#### 📝 Suíte Cadastro de Novo Aluno | Objetivo: Verificar principais funcionalidades 


- Caso 1: cadastrar aluno com  informações básicas (nome completo) 
 

####  📝Suíte Dashboard | Objetivo: Verificar funcionalidades gerais da página principal 

- Caso 1: Escrever as condições de teste.

####  📝Suíte Novo Chamado | Objetivo: Verificar funcionalidades gerais da página principal 

- Caso 1: Escrever as condições de teste.

####  📝Suíte Abertura de Chamado | Objetivo: Verificar funcionalidade em rota externa

- Caso 1: Escrever as condições de teste.


###  📌Gerenciamento de Defeitos:

-   [Relatório de Defeitos](https://pt-br.reactjs.org) - inserir link do relatório

###  📌Fechamento de ciclo de testes e artefactos de teste:

-   [Dasboard de Métricas](https://pt-br.reactjs.org) - inserir link do relatório
