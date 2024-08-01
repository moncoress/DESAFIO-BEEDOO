# DESAFIO BEEDOO 🔸 Analista de Qualidade de Software Júnior
---
- As informações sobre como foram desenvolvidas as User Stories, os Cenários, Casos de Teste e Relatórios de Bugs estão detalhadas na seção de Documentação do Projeto disponível na página **"Wiki"** deste Repositório.
---

## 🔸Índice:

- [User Story 1: Acesso a Tela Inicial de Cursos](#user-story-1)
- [User Story 2: Criação de Novo Curso](#user-story-2)
- [User Story 3: Verificação de Curso Criado](#user-story-3)
- [User Story 4: Acesso a Lista de Cursos](#user-story-4)
- [User Story 5: Exclusão de Curso](#user-story-5)
- [User Story 6: Verificação de Cursos Criados](#user-story-6)
- [User Story 7: Validação de Campos Obrigatórios](#user-story-7)
- [User Story 8: Limite de Caracteres](#user-story-8)
- [Bônus: User Story 9: Acessibilidade com Voice Over](#user-story-9)
- [Análise de Acessibilidade com AccessMonitor](#bônus-análise-de-url-com-accessmonitor)

---

### 🔶 User Story 1

**Como** primeira vez utilizando a plataforma Beedoo, **eu quero** acessar a tela inicial de cursos **para** entender como a aplicação funciona.

#### Critérios de Aceitação:

1. O usuário deve ter acesso ao link da plataforma.
2. O usuário deve ser capaz de ver a tela inicial ao abrir o link.

**Pontos de Melhoria:**

1. A tela inicial deve conter um header com botões de redirecionamento para outras áreas do site.
2. A tela inicial deve conter um subtítulo explicando resumidamente o serviço oferecido pela Beedoo.
3. A tela inicial deve conter um footer com informações de contato com o SAC e as redes sociais da empresa.

---

### 🔶 User Story 2

**Como** usuário da plataforma Beedoo, **eu quero** acessar a página "Cadastrar Cursos" pelo header **para** verificar se é possível cadastrar um curso.

#### Critérios de Aceitação:

1. O usuário deve estar na plataforma.
2. O usuário deve ser capaz de clicar no botão do header para acessar a página "Cadastrar Cursos".
3. A página "Cadastrar Cursos" deve exibir um formulário para preencher e realizar o cadastro.
4. O formulário deve incluir campos obrigatórios como nome, descrição, instrutor, URL da imagem de capa, duração, número de vagas e tipo de curso (presencial ou online).
5. O usuário deve ser capaz de submeter o formulário e receber uma confirmação se o curso foi cadastrado com sucesso ou uma mensagem de erro se houver problemas.

---


### 🔶 User Story 3

**Como** usuário da plataforma Beedoo, **eu quero** acessar a tela de cursos **para** ver que os cursos que criei foram adicionados com sucesso.

### Critérios de Aceitação:

1. O usuário deve ser capaz de navegar até a tela de cursos a partir do header.
2. A tela de cursos deve exibir os cursos criados pelo usuário.
3. A lista de cursos deve ser atualizada automaticamente para refletir a adição dos novos cursos.
   
### Exemplo de Mensagens:

- **Sucesso:** "Curso adicionado com sucesso e disponível na lista de cursos."
- **Erro:** "Não foi possível adicionar o curso. Por favor, tente novamente mais tarde."
   
**Pontos de Melhoria:**

1. Os cursos criados pelo usuário devem ser claramente identificáveis na lista (ex.: com um rótulo "Criado por mim" ou similar).
2. O sistema deve exibir uma mensagem de confirmação após a criação de um curso, informando que ele foi adicionado com sucesso.

---

### 🔶 User Story 4

**Como** usuário da plataforma Beedoo, **eu quero** acessar a página de listagem de cursos pelo header **para** ver todos os cursos numa lista.

#### Critérios de Aceitação:

1. O usuário deve estar na plataforma.
2. O usuário deve ser capaz de clicar no botão do header para acessar a página de listagem de cursos.
3. A página deve exibir todos os cursos em formato de lista.

---

### 🔶 User Story 5

**Como** usuário da plataforma Beedoo, **eu quero** ser notificado se a exclusão de um curso for bem-sucedida **para** que eu saiba que o curso foi removido corretamente.

### Critérios de Aceitação:

1. O usuário deve estar na plataforma.
2. O usuário deve ser capaz de excluir um curso a partir da lista de cursos.
3. O sistema deve exibir uma mensagem de confirmação quando um curso for excluído com sucesso.
4. A lista de cursos deve ser atualizada automaticamente para refletir a exclusão do curso.
5. Se a exclusão falhar, o sistema deve exibir uma mensagem de erro clara, explicando o motivo da falha e oferecendo opções para o usuário (ex.: tentar novamente).

### Exemplo de Mensagens:

- **Sucesso:** "Curso excluído com sucesso."
- **Erro:** "Não foi possível excluir o curso. Por favor, tente novamente mais tarde."

---

### 🔶 User Story 6

**Como** usuário da plataforma Beedoo, **eu quero** acessar a tela de cursos **para** ver que os cursos que criei foram adicionados com sucesso.

### Critérios de Aceitação:

1. O usuário deve ser capaz de navegar até a tela de cursos a partir do header.
2. A tela de cursos deve exibir os cursos criados pelo usuário.
3. A lista de cursos deve ser atualizada automaticamente para refletir a adição dos novos cursos.
   
### Exemplo de Mensagens:

- **Sucesso:** "Curso adicionado com sucesso e disponível na lista de cursos."
- **Erro:** "Não foi possível adicionar o curso. Por favor, tente novamente mais tarde."
   
**Pontos de Melhoria:**

1. Os cursos criados pelo usuário devem ser claramente identificáveis na lista (ex.: com um rótulo "Criado por mim" ou similar).
2. O sistema deve exibir uma mensagem de confirmação após a criação de um curso, informando que ele foi adicionado com sucesso.

---

### 🔶 User Story 7

**Como** usuário da plataforma Beedoo, **eu quero** garantir que não seja possível cadastrar um curso sem preencher todos os campos obrigatórios **para** que o curso seja criado com todas as informações necessárias.

### Critérios de Aceitação:

1. O sistema deve validar o preenchimento dos campos obrigatórios antes de permitir a submissão do formulário.
2. Se qualquer campo obrigatório estiver vazio, o sistema deve exibir uma mensagem de erro clara indicando quais campos precisam ser preenchidos.
3. O formulário deve impedir a submissão até que todos os campos obrigatórios estejam devidamente preenchidos.
4. Após o preenchimento correto de todos os campos e a submissão do formulário, o sistema deve confirmar o sucesso do cadastro do curso.

### Exemplo de Mensagens:

- **Erro de Preenchimento:** "Por favor, preencha todos os campos obrigatórios antes de submeter o formulário."
- **Sucesso:** "Curso cadastrado com sucesso."

---

### 🔶 User Story 8

**Como** usuário da plataforma Beedoo, **eu quero** que haja um limite de caracteres para os campos ao cadastrar um curso **para** garantir que as informações inseridas sejam concisas.

### Critérios de Aceitação:

1. Cada campo do formulário de cadastro de curso deve ter um limite máximo de caracteres especificado.
2. O sistema deve restringir a entrada de dados para não permitir a inserção de mais caracteres do que o limite permitido.
3. Se o usuário tentar inserir mais caracteres do que o permitido, o sistema deve exibir uma mensagem de erro indicando que o limite de caracteres foi excedido.
4. O sistema deve fornecer uma contagem de caracteres restantes ou já utilizados nos campos relevantes para informar o usuário sobre o limite.
5. Após a correção dos dados para atender aos limites de caracteres e a submissão do formulário, o sistema deve confirmar o sucesso do cadastro do curso.

### Exemplo de Mensagens:

- **Erro de Limite de Caracteres:** "O campo 'Descrição' excedeu o limite máximo de 500 caracteres. Por favor, reduza o texto."
- **Sucesso:** "Curso cadastrado com sucesso."

---
# 💡Bônus: Validando Acessibilidade
### 🔶 User Story 9

**Como** usuário da plataforma Beedoo que utiliza serviços de voice over, **eu quero** que todas as informações do site sejam legíveis por esse serviço **para** que eu possa concluir o fluxo de cadastro de um novo curso de forma acessível.

### Critérios de Aceitação:

1. Todos os campos e labels no formulário de cadastro de curso devem ser corretamente identificados e descritos para serem lidos por serviços de voice over.
2. O sistema deve garantir que as instruções e mensagens de erro sejam acessíveis e lidas de forma clara e completa pelo serviço de voice over.
3. Elementos de navegação, botões e links devem ter textos alternativos e descrições apropriadas para serem lidos pelo serviço de voice over.
4. O fluxo de cadastro de curso deve ser navegável e funcional utilizando apenas teclado e serviços de voice over, sem necessidade de interação visual.
5. O sistema deve permitir que o usuário revise e corrija as informações inseridas com feedback audível claro em todas as etapas do processo.

### Exemplo de Mensagens:

- **Descrição Acessível:** "O campo 'Nome do Curso' é obrigatório. Por favor, insira o nome do curso."
- **Erro Acessível:** "A descrição do curso excedeu o limite de 500 caracteres. Reduza o texto e tente novamente."

---

## 🔶 Análise de URL com AccessMonitor

- teste



