# 11. HISTÓRIAS DOS USUÁRIOS

## HISTÓRIA 1

**Persona:** Bruna Costa  
**Funcionalidade:** Preencher Visão do Produto

### 1.1. Como Bruna Costa, quero criar a estrutura inicial da visão do produto para direcionar estrategicamente o MVP.

**Tarefas:**
- Criar tela inicial com formulário da visão.
- Adicionar labels e placeholders descritivos.

**Critérios de Aceite:**
- Deve haver campos para missão, visão, público-alvo e diferenciais.
- A estrutura deve ser clara, intuitiva e responsiva.

**Habilitadores Técnicos e Exploratórios:**
- Escolha do framework de formulários (ex: React Hook Form, Formik).
- Definição da estrutura de dados no backend (modelagem).

**Interface mockup:**  

![História 1.1](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF1.png)

**Interface alta fidelidade:**  
**Interface alta fidelidade:**  
![História 1.1](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF0.png) 
![História 1.1](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF1.png)

---

### 1.2. Como Bruna Costa, quero validar os campos obrigatórios da visão do produto para garantir o alinhamento entre os envolvidos desde o início do projeto.

**Tarefas:**
- Implementar validação obrigatória nos campos essenciais.
- Exibir mensagens de erro acessíveis para campos não preenchidos.

**Critérios de Aceite:**
- O sistema não permite salvar se campos obrigatórios estiverem vazios.
- Feedback visual é exibido para cada campo inválido.

**Interface mockup:**  
![História 1.2](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF2.png)

**Interface alta fidelidade:**  
![História 1.2](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF2.png)

---

### 1.3. Como Bruna Costa, quero salvar o conteúdo da matriz de visão para manter um registro centralizado e atualizado da missão, visão e diferenciais.

**Tarefas:**
- Criar endpoint para persistência dos dados.
- Implementar botão "Salvar" com mensagem de sucesso.

**Critérios de Aceite:**
- O conteúdo deve ser salvo no banco de dados e ser recuperável.
- Mensagem de confirmação deve ser exibida após o salvamento.

**Interface mockup:**  
![História 1.3](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF3.png)

**Interface alta fidelidade:**  
![História 1.3](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF3.png)
---

## HISTÓRIA 2

**Persona:** Camila Rezende  
**Funcionalidade:** Preencher Interface “É, Não É, Faz, Não Faz”

### 2.1. Como Camila Rezende, quero preencher a definição do escopo do produto para deixar claro o que o produto é, não é, faz e não faz.

**Tarefas:**
- Criar layout da matriz de 4 quadrantes.
- Implementar campos de texto com validação básica.

**Critérios de Aceite:**
- O usuário pode inserir conteúdo em todos os 4 quadrantes.
- Deve haver limite de caracteres por quadrante.

**Interface mockup:**  
![História 2.1](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF4.png)

**Interface alta fidelidade:**  
![História 2.1](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF4.png)


---

### 2.2. Como Camila Rezende, quero validar a consistência entre os quadrantes para reduzir ruídos e decisões desalinhadas.

**Tarefas:**
- Criar função de verificação de contradições entre textos dos quadrantes.
- Adicionar alertas não intrusivos na interface.

**Critérios de Aceite:**
- O sistema alerta se houver contradições diretas entre os quadrantes (ex: “É” = rápido / “Não É” = rápido).
- O alerta não bloqueia o usuário, apenas informa.

**Interface mockup:**  
![História 2.2](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF5.png)

**Interface alta fidelidade:**  
![História 2.2](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF5.png)

---

### 2.3. Como Camila Rezende, quero salvar o conteúdo da matriz para facilitar a comunicação visual e o compartilhamento do foco do produto.

**Tarefas:**
- Implementar salvamento no banco com chave por produto.
- Adicionar botão “Salvar” com confirmação visual.

**Critérios de Aceite:**
- Todos os quadrantes devem ser salvos corretamente e visíveis posteriormente.
- Nome do produto vinculado à matriz.

**Interface mockup:**  
![História 2.3](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF6.png)

**Interface alta fidelidade:**  
![História 2.3](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF6.png)


---

## HISTÓRIA 3

**Persona:** Felipe Tavares  
**Funcionalidade:** Criar Interface de Composição de Personas

### 3.1. Como Felipe Tavares, quero preencher dados do usuário final para que a IA gere personas relevantes, visando uma geração confiável de perfis de usuários para orientar decisões.

**Tarefas:**
- Criar formulário com campos padronizados para entrada de dados.
- Adicionar validação e UX responsiva.

**Critérios de Aceite:**
- O usuário consegue inserir dados básicos como idade, profissão e metas.
- Campos obrigatórios são destacados.

**Interface mockup:**  
![História 3.1](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF7.png)

**Interface alta fidelidade:**  
![História 3.1](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF7.png)


---

### 3.2. Como Felipe Tavares, quero que a IA gere automaticamente personas relevantes a partir dos dados inseridos.

**Tarefas:**
- Integrar modelo de IA via API.
- Exibir resultado gerado de forma visual (card ou painel).

**Critérios de Aceite:**
- A IA gera persona com nome, descrição, objetivos e dores a partir dos dados.
- Feedback claro de carregamento e sucesso.

**Habilitadores Técnicos e Exploratórios:**
- Selecionar modelo de IA (ex: OpenAI, LLaMA, local).
- Definir prompt padrão para geração da persona.

**Interface mockup:**  
![História 3.2](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF8.png)

**Interface alta fidelidade:**  
![História 3.2](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF8.png)


---

### 3.3. Como Felipe Tavares, quero editar manualmente os dados da persona gerada para estimular empatia e foco no usuário durante o desenvolvimento.

**Tarefas:**
- Criar editor online para os campos da persona.
- Adicionar botão “Salvar alterações”.

**Critérios de Aceite:**
- Todos os dados gerados pela IA podem ser ajustados manualmente.
- Alterações são salvas e mantidas.

**Interface mockup:**  
prototipos\moockups (baixafidelidade)\BF9.png

![História 3.3](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/moockups%20(baixafidelidade)/BF9.png)

**Interface alta fidelidade:**  
![História 3.3](https://github.com/Engenharia-de-Software-PUC/Engenharia1-Trab/blob/main/prototipos/figma(altafidelidade)/AF9.png)

