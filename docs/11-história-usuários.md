# 11. HISTÓRIAS DOS USUÁRIOS


## HISTÓRIA 1

PERSONA: BRUNA COSTA 
<br>
FUNCIONALIDA 1: PREENCHER VISÃO DO PRODUTO 

* 1.1: Como Bruna Costa, posso criar a estrutura inicial da visão do produto para Direcionamento estratégico para o MVP

### Tarefas 
+ Criar tela inicial com formulário da visão.
+ Adicionar labels e placeholders descritivos.

### Critérios de aceite 
+ Deve haver campos para missão, visão, público-alvo e diferenciais.
+ A estrutura deve ser clara, intuitiva e responsiva.

### Habilitadores Técnicos e Exploratórios 
+ Escolha do framework de formulários (Ex: React Hook Form, Formik).
+ Definição de estrutura de dados da visão no backend (modelagem).

### Interface moockup 




* 1.2.: Como Bruna Costa, posso validar os campos obrigatórios da visão do produto para alinhamento entre os envolvidos logo no início do projeto

### Tarefas 
+ Implementar validação obrigatória nos campos essenciais.
+ Exibir mensagens de erro acessíveis para campos não preenchidos.

### Critérios de aceite 
+ O sistema não permite salvar se campos obrigatórios estiverem vazios.
+ Feedback visual é exibido para cada campo inválido.

### Interface moockup 



* 1.3: Como Bruna Costa, posso salvar o conteúdo alinhado da matriz para Registro centralizado e atualizado da missão, visão e diferenciais

### Tarefas 
+ Criar endpoint para persistência dos dados da visão.
+ Implementar botão "Salvar" com mensagem de sucesso.

### Critérios de aceite 
+ O conteúdo deve ser salvo no banco de dados e recuperável.
+ Mensagem de confirmação deve ser exibida após o salvamento.

### Interface moockup 

## HISTÓRIA 2

PERSONA: CAMILA REZENDE 
<br>
FUNCIONALIDA 2: PREENCHER INTERFACE“É, Não É, Faz, Não Faz”

* 2.1: Como Camila Rezende, posso preencher a definição do escopo do que o produto É, NÃO É, FAZ E NÃO FAZ, para Definição clara do que o produto é, não é, faz e não faz.

### Tarefas 
+ Criar layout da matriz de 4 quadrantes.
+ Implementar campos de texto com validação básica.


### Critérios de aceite 
+ Usuário pode inserir conteúdo em todos os 4 quadrantes.
+ Limite de caracteres por quadrante definido.

### Interface moockup 

* 2.2: Como Camila Rezende, posso validar a consistência entre os quadrantes do produto para Redução de ruídos e decisões desalinhadas.

### Tarefas 
+ Criar função de verificação entre textos dos quadrantes.
+ Adicionar alertas não intrusivos na interface.

### Critérios de aceite 
+ Alertar se houver contradições diretas entre quadrantes (ex: “É” = rápido / “Não É” = rápido).
+ Aviso não bloqueia o usuário, apenas alerta.

### Interface moockup 


* 2.3: Como Camila Rezende, posso salvar o conteúdo alinhado da matriz para comunicação visual e compartilhável do foco do produto.

### Tarefas 
+ Implementar salvamento no banco com chave por produto.
+ Adicionar botão “Salvar” com confirmação visual.


### Critérios de aceite 
+ Todos os quadrantes devem ser salvos corretamente e visíveis posteriormente.
+ Nome do produto vinculado à matriz.

### Interface moockup 

## HISTÓRIA 3

PERSONA: FELIPE TAVARES
<br>
FUNCIONALIDA 3: CRIAR INTERFACE DE COMPOSIÇÃO DE PERSONAS

* 3.1: Como Felipe Tavares, posso preencher dados do usuário final para a IA gerar personas relevantes para geração confiável de perfis de usuários para orientar decisões.

### Tarefas 
+ Criar formulário com campos padronizados para entrada de dados.
+ Adicionar validação e UX responsiva.


### Critérios de aceite 
+ Usuário consegue inserir dados básicos como idade, profissão, metas.
+ Campos obrigatórios são destacados.

### Interface moockup 

* 3.2: Como Felipe Tavares, posso criar o modelo de IA para criação rápida e automática de personas relevantes.

### Tarefas 
+ Integrar modelo de IA via API.
+ Exibir resultado gerado de forma visual (card ou painel).

### Critérios de aceite 
+ IA gera persona com nome, descrição, objetivos e dores a partir dos dados.
+ Feedback claro de carregamento e sucesso.

### Habilitadores Técnicos/Exploratórios
+ Selecionar modelo de IA (ex: OpenAI, Llama, local).
+ Definir prompt padrão para geração da persona.

### Interface moockup 

* 3.3: Como Felipe Tavares, posso participar da edição manual dos dados da persona para gerar empatia e foco no usuário durante desenvolvimento e validações.

### Tarefas 
+ Criar editor online para os campos da persona.
+ Adicionar botão “Salvar alterações”.

### Critérios de aceite 
+ Todos os dados gerados pela IA podem ser ajustados manualmente.
+ Alterações são salvas e mantidas.

### Interface moockup 