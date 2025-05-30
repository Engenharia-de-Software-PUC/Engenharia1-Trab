# TRABALHO DE ENGENHARIA DE SOFTWARE I: Produtim

## CONTEXTO

O produto consiste na criação de um sistema automatizado voltado para a otimização da produção de MVPs e PPBs, baseado nas metodologias propostas por Paulo Caroli e Fábio Aguiar. A iniciativa parte do princípio de que **tudo pode ser automatizado e melhorado**, unindo práticas ágeis, foco na entrega de valor contínuo e automação inteligente dos processos de descoberta e construção de produtos.

## VISÃO DO PRODUTO

**Para:** Criadores de produto e empresas com times de produto,
**Cujo o desafio é:** Não saber por onde começar ao elaborar um novo produto,
**O Produtim,**
**É:** Uma aplicação web responsiva,
**Que:** Facilita e otimiza a ideação de novos produtos em poucos dias, ao invés de uma semana ou mais, com um número pequeno de usuários.
**Diferente de:** Ferramentas como Jira, ClickUp, Trello ou Miro,
**O nosso produto oferece:** Uma estrutura focada exclusivamente na ideação rápida e colaborativa com poucas pessoas, promovendo a criação de um MVP funcional e seu template inicial, sem a necessidade de papéis, post-its ou quadros físicos.

## O QUE O PRODUTO É - NÃO É - FAZ E NÃO FAZ

### É
*   É um manual passo a passo para concepção de um MVP;
*   Facilitador para a construção de produtos;
*   É uma aplicação web gratuita;
*   É uma plataforma destinada exclusivamente para criação de MVP funcionais.
*   É uma plataforma que organiza e acelera o início de projetos, mesmo sem muita informação inicial.

### NÃO É
*   Não é um sistema completo de gestão de projetos como Jira, ClickUp ou Trello.
*   Não é um espaço para documentação extensa ou gestão de backlog a longo prazo.
*   Não é uma ferramenta para times grandes com fluxos complexos e hierarquias rígidas.
*   Não é um app de design, prototipagem visual ou wireframe (como Figma ou Miro).

### FAZ
*   Ajuda a estruturar ideias brutas em um esboço funcional de produto (pré-MVP).
*   Sugere templates e etapas práticas para gerar o primeiro escopo em poucas horas ou dias baseado em metodologias já testadas (PBB e Lean Inspection).
*   Facilita o alinhamento rápido entre criadores com base em objetivos e entregas simples.
*   Incentiva a validação rápida de hipóteses e a documentação leve da ideia.
*   Elimina a necessidade de usar papéis, post-its ou quadros físicos no início.
*   Elimina a necessidade de passos intensos maçantes que podem ser otimizados com I.A.

### NÃO FAZ
*   Não substitui o uso de ferramentas completas de desenvolvimento, acompanhamento ou deploy.
*   Não faz prototipação visual ou fluxogramas interativos.
*   Não gera código ou entrega técnica do produto.
*   Não substitui pesquisas de mercado, testes com usuários ou entrevistas qualitativas.

## TRADE - OFFS TEMPLATE

1.  **Usabilidade:** Tem que ser o mais necessário visto que esse produto visa melhorar a utilização e a construção de templates de metodologias ágeis.
2.  **Desempenho:** Pode ter várias pessoas em uma mesma sessão.
3.  **Segurança:** Como são produtos que estão sendo concebidos, os dados devem estar seguros sem vazamentos (espionagem empresarial).
4.  **Confiabilidade:** O sistema tem que prever problemas de falha de conexão ou algo do tipo para poder salvar os dados das pessoas.
5.  **Suportabilidade:** Tem que ser responsivo para uma sessão pode ser realizada no celular.

## PERSONAS

| Nome           | Perfil                                                                                                | Comportamento                                                                                                                                                                                             | Necessidades                                                                                                                                                                                                |
|----------------|-------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Camila Rezende | **Idade:** 34 anos<br>**Cargo:** Product Owner<br>**Empresa:** Startup de soluções logísticas            | Prática, com agenda cheia, busca reduzir o tempo entre a ideia e o MVP. Prefere processos objetivos e resultados rápidos.                                                                             | Tirar ideias do papel em poucas horas. Estruturar um MVP com poucos cliques. Validar hipóteses com clientes sem depender de processos complexos.                                                              |
| Felipe Tavares | **Idade:** 28 anos<br>**Cargo:** Dev Fullstack Júnior<br>**Empresa:** Fábrica de Software.              | Motivado, curioso e comprometido. Gosta de entender o impacto do que está desenvolvendo, mas sente frustração quando recebe demandas mal explicadas ou constantemente alteradas. É produtivo quando tem direcionamento claro e autonomia. | Entender rapidamente o que deve ser feito e como deve ser feito. Receber escopos claros, objetivos e priorizados, sem ruído de comunicação. Acessar protótipos funcionais e simples, sem depender de explicações extensas. Desenvolver somente o necessário, com foco no valor real da funcionalidade. Evitar retrabalho e tarefas sem propósito. Conhecer previamente a tecnologia exigida para a tarefa, com aptidão técnica para execução. Evitar desculpas, mudanças sem contexto e interpretações dúbias. |
| Bruna Costa    | **Idade:** 28 anos<br>**Cargo:** Scrum Master e facilitadora ágil em consultoria de TI<br>**Empresa:** Fábrica de Software. | Organizada, dinâmica, atua como ponte entre áreas. Gosta de processos visuais e ferramentas que agilizem rituais ágeis.                                                                           | Agilizar a fase de concepção e alinhamento do produto. Reduzir tempo de planejamento de sprints. Garantir entregas com objetivos bem definidos desde o início.                                          |

## BRAINSTORM DE FUNCIONALIDADES

1.  Interface da visão do produto;
2.  Interface para preenchimento produto é, não é, faz não faz;
3.  Interface de composição de personas (Retorno feito por IA);
4.  Interface de Brainstorm de funcionalidades (Gerada por IA);
5.  Revisão da interface de personas e brainstorm (modificada pelos usuários);
6.  Interface de criação de jornada dos usuários (Gerada por IA);
7.  Interface e ajustes na união de Jornadas dos usuários + funcionalidades;
8.  Interface de seleção de esforço, valor de UI e valor para o cliente;
9.  Interface de retorno do sequenciador e ajustes para o usuário;
10. Interface de overview geral (canvas mvp)
11. Exportar a ideia do MVP (Talvez já atribuir ao Trello ou Jira).

### Níveis de Confiança das Funcionalidades (O QUE FAZER / COMO FAZER)

1.  **Interface da visão do produto:** Alta / Alta
2.  **Interface para preenchimento produto é, não é, faz não faz:** Alta / Alta
3.  **Interface de composição de personas (Retorno feito por IA):** Alta / Médio
4.  **Interface de Brainstorm de funcionalidades (Gerada por IA):** Médio / Médio
5.  **Revisão da interface de personas e brainstorm (modificada pelos usuários):** Alta / Médio
6.  **Interface de criação de jornada dos usuários (Gerada por IA):** Médio / Baixo
7.  **Interface e ajustes na união de Jornadas dos usuários + funcionalidades:** Baixo / Médio
8.  **Interface de seleção de esforço, valor de UI e valor para o cliente:** Alta / Alta
9.  **Interface de retorno do sequenciador e ajustes para o usuário:** Alta / Médio
10. **Interface de overview geral (canvas mvp):** Baixo / Baixo
11. **Exportar a ideia do MVP (Talvez já atribuir ao Trello ou Jira):** Alta / Alta

## REVISÃO TÉCNICA DE UX DE NEGÓCIO

**Legenda:**
*   **Confiança:** Verde (Alta), Amarelo (Média), Vermelho (Baixa) - *Interpretado das cores no documento original.*
*   **Esforço:** E (Baixo), EE (Médio), EEE (Alto)
*   **Valor UX:** ♥ (Baixo), ♥♥ (Médio), ♥♥♥ (Alto)
*   **Valor $ (Negócio):** $ (Baixo), $$ (Médio), $$$ (Alto)

| Núm | Funcionalidade                                                                 | Confiança | Esforço | Valor UX | Valor $ | OBS                      |
|-----|--------------------------------------------------------------------------------|-----------|---------|----------|---------|--------------------------|
| 1   | Interface da visão do produto;                                                 | Alta      | Baixo   | Alto     | Alto    | Interface de entrada de dados |
| 2   | Interface para preenchimento produto é, não é, faz não faz;                      | Alta      | Baixo   | Baixo    | Baixo   | Qual o foco do MVP       |
| 3   | Interface de composição de personas (retorno feito por ia)                      | Alta      | Médio   | Médio    | Médio   | Uso de AI                |
| 4   | Interface de brainstorm de funcionalidades (gerada por ia)                       | Baixa     | Alto    | Médio    | Médio   |                          |
| 5   | Revisão da interface de personas e brainstorm (modificada pelos usuários)        | Média     | Médio   | Alto     | Alto    |                          |
| 6   | Interface de criação de jornada dos usuários (gerada por ia)                     | Baixa     | Alto    | Alto     | Alto    | Uso de AI                |
| 7   | Interface e ajustes na união de jornadas dos usuários + funcionalidades          | Alta      | Baixo   | Médio    | Médio   |                          |
| 8   | Interface de seleção de esforço, valor de ui e valor para o cliente              | Alta      | Baixo   | Baixo    | Médio   |                          |
| 9   | Interface de retorno do sequenciador e ajustes para o usuário;                   | Média     | Médio   | Alto     | Alto    | Uso de AI                |
| 10  | Interface de overview geral (canvas mvp)                                       | Baixa     | Alto    | Alto     | Alto    |                          |
| 11  | Exportar a ideia do mvp (talvez já atribuir ao trello ou jira)                   | Alta      | Baixo   | Alto     | Alto    |                          |

## JORNADAS DOS USUÁRIOS

### Jornada de Camila Rezende (Product Owner)
**Objetivo:** Transformar rapidamente uma ideia em um MVP funcional para validação.
**Passos da Jornada:**
1.  Acessa a plataforma Produtim pelo navegador (desktop ou mobile).
2.  Seleciona "Novo Projeto" na interface inicial.
3.  Preenche a visão do produto (O que é, não é, faz e não faz).
4.  Gera automaticamente personas com auxílio de IA e faz ajustes se necessário.
5.  Executa o brainstorm de funcionalidades, utilizando sugestões da IA.
6.  Cria e revisa a jornada dos usuários, ajustando pontos críticos.
7.  Associa as funcionalidades às jornadas, priorizando.
8.  Define esforço, valor para o usuário e valor de negócio.
9.  Visualiza o Canvas MVP, com visão geral do produto.
10. Exporta o Canvas MVP, podendo integrar com ferramentas como Jira ou Trello.

### Jornada de Felipe Tavares (Dev Fullstack Júnior)
**Objetivo:** Compreender claramente o que precisa ser desenvolvido e com quais prioridades.
**Passos da Jornada:**
1.  Recebe o link ou acesso ao projeto criado por Camila ou Bruna.
2.  Acessa a visão do produto para entender contexto, objetivo e limites.
3.  Consulta a seção de personas, para entender quem são os usuários finais.
4.  Visualiza as funcionalidades priorizadas, incluindo descrições objetivas.
5.  Acompanha as jornadas dos usuários, entendendo como cada funcionalidade se encaixa na experiência.
6.  Verifica o Canvas MVP e o sequenciamento das entregas.
7.  Começa o desenvolvimento com clareza no que deve ser feito.

### Jornada de Bruna Costa (Scrum Master / Facilitadora Ágil)
**Objetivo:** Acelerar o alinhamento do time e estruturar o planejamento das sprints iniciais.
**Passos da Jornada:**
1.  Inicia sessão na plataforma Produtim.
2.  Cria ou acessa um projeto já existente do time.
3.  Facilita o preenchimento da visão do produto, guiando o time.
4.  Conduz a geração de personas e discute com o time para validações.
5.  Coordena o brainstorm de funcionalidades, priorizando entregas de maior valor.
6.  Valida e revisa as jornadas dos usuários junto ao time.
7.  Faz o mapeamento de funcionalidades com jornadas.
8.  Orienta a definição de esforço, valor para o usuário e para o negócio.
9.  Usa o Canvas MVP como ferramenta de alinhamento nas reuniões.
10. Exporta o projeto para o backlog (Trello, Jira, etc.) e organiza o planejamento da sprint.

## FUNCIONALIDADES NA JORNADA

### Camila Rezende – Product Owner (PO): CRIAÇÃO DE UM MVP
| PASSO                                               | FUNCIONALIDADE                             |
|-----------------------------------------------------|--------------------------------------------|
| Acessa o Produtim                                   | -                                          |
| Cria um novo projeto                                | Interface de criação de projeto            |
| Preenche a visão do produto                         | Interface da visão do produto              |
| Preenche o "É, Não é, Faz, Não Faz"                 | Template de definição rápida de escopo     |
| Gera personas automaticamente                       | Geração de personas via IA                 |
| Ajusta e revisa as personas                         | Edição de personas                         |
| Realiza brainstorm de funcionalidades               | Brainstorm de funcionalidades via IA       |
| Ajusta e prioriza funcionalidades                   | Edição manual e priorização                |
| Cria jornadas dos usuários                          | Geração de jornada via IA                  |
| Revisa e ajusta as jornadas                         | Edição da jornada                          |
| Faz a união entre jornadas e funcionalidades        | Vinculação de jornadas às funcionalidades    |
| Define esforço, valor de UI e valor para o cliente  | Matriz de esforço x valor                  |
| Visualiza o Canvas MVP                              | Geração do Canvas MVP                      |
| Exporta o projeto para Trello/Jira                  | Exportação de backlog                      |

### Felipe Tavares – Dev Fullstack Júnior: CONSULTA PARA DESENVOLVIMENTO
| PASSO                                               | FUNCIONALIDADE                             |
|-----------------------------------------------------|--------------------------------------------|
| Recebe o link de acesso ao projeto criado           | -                                          |
| Acessa a visão do produto                         | Interface da visão do produto              |
| Consulta as personas definidas                      | Visualização de personas                   |
| Visualiza as funcionalidades priorizadas            | Visualização do backlog funcional          |
| Acompanha as jornadas dos usuários                  | Visualização da jornada dos usuários       |
| Verifica o Canvas MVP com o sequenciamento          | Visualização do Canvas MVP                 |
| Exporta tarefas para Jira/Trello                    | Exportação para ferramentas externas       |
| Inicia o desenvolvimento com base no escopo         | -                                          |

### Bruna Costa – Scrum Master / Facilitadora Ágil: PLANEJAMENTO DA SPRINT
| PASSO                                                    | FUNCIONALIDADE                             |
|----------------------------------------------------------|--------------------------------------------|
| Cria um novo projeto ou acessa um existente              | Interface de criação/acesso de projeto     |
| Facilita o preenchimento da visão do produto             | Interface da visão do produto              |
| Gera personas rapidamente com IA                         | Geração de personas via IA                 |
| Organiza o brainstorm de funcionalidades com o time      | Brainstorm de funcionalidades via IA       |
| Revisa as jornadas dos usuários                          | Visualização e edição da jornada           |
| Confere se todas as funcionalidades atendem às jornadas  | Vinculação de jornadas às funcionalidades    |
| Faz a priorização de funcionalidades                     | Matriz de esforço x valor                  |
| Acompanha a criação do Canvas MVP                        | Visualização do Canvas MVP                 |
| Exporta para Jira/Trello e organiza o backlog            | Exportação para ferramentas de gestão      |
| Conduz o planejamento da sprint com o time               | -                                          |

## SEQUENCIADOR

**Legenda para Esforço, Valor $, Valor UX:** (mesma da Revisão Técnica)
*   **Esforço:** E (Baixo), EE (Médio), EEE (Alto)
*   **Valor $ (Negócio):** $ (Baixo), $$ (Médio), $$$ (Alto)
*   **Valor UX:** ♥ (Baixo), ♥♥ (Médio), ♥♥♥ (Alto)

### Onda 1
| Tarefa                                                              | Esforço | Valor $ | Valor UX |
|---------------------------------------------------------------------|---------|---------|----------|
| Interface da visão do produto                                       | Baixo   | Alto    | Alto     |
| Interface para preenchimento produto é, não é, faz não faz;           | Baixo   | Baixo   | Baixo    |
| Interface de composição de personas (retorno feito por ia).           | Médio   | Médio   | Médio    |

### Onda 2
| Tarefa                                                                    | Esforço | Valor $ | Valor UX |
|---------------------------------------------------------------------------|---------|---------|----------|
| Interface de brainstorm de funcionalidades (gerada por ia)                  | Alto    | Médio   | Médio    |
| Revisão da interface de personas e brainstorm (modificada pelos usuários) | Médio   | Alto    | Alto     |
| Interface de seleção de esforço, valor de ui e valor para o cliente       | Baixo   | Médio   | Baixo    |

### Onda 3
| Tarefa                                                                    | Esforço | Valor $ | Valor UX |
|---------------------------------------------------------------------------|---------|---------|----------|
| Interface de retorno do sequenciador e ajustes para o usuário;            | Médio   | Alto    | Alto     |
| Interface e ajustes na união de jornadas dos usuários + funcionalidades   | Baixo   | Médio   | Médio    |

### Onda 4
| Tarefa                                                                    | Esforço | Valor $ | Valor UX |
|---------------------------------------------------------------------------|---------|---------|----------|
| Interface de retorno do sequenciador e ajustes para o usuário             | Médio   | Alto    | Alto     |
| Interface de overview geral (canvas mvp)                                  | Alto    | Alto    | Alto     |
| Exportação (Trello/Jira)                                                  | Baixo   | Alto    | Alto     |

## CANVAS MVP
(Conteúdo não detalhado no documento)
