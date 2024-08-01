# DESAFIO BEEDOO 🔸 Analista de Qualidade de Software Júnior
💡Informações sobre o proceso de criação e desenvolvimento de cada ponto do desafio estão nas páginas "Wiki" deste repositório.
 
---
## Índice:

- [User Story 1 a 8](#User-Story)
- [Bônus User Story de Acessibilidade](#user-story-9)
- [Análise de URL com AccessMonitor](#bônus-análise-de-url-com-accessmonitor) 
- [Planilha de Casos de Teste e Evidências MP4](#Tabela-de-Casos-de-Teste-Evidências-e-Registro-de-Bugs)
- [Registro de Bugs](#)
---
# 1️⃣ User Story
Um total de 9 User Stories foram elaboradas no formato Markdown, descritas neste arquivo README, conforme solicita o desafio. 

---
### 🔸 User Story 1: Acesso a Tela Inicial de Cursos
- **Como** primeira vez utilizando a plataforma Beedoo, **eu quero** acessar a tela inicial de cursos **para** entender como a aplicação funciona.

**1. Critérios de Aceitação:**

- O usuário deve ter acesso ao link da plataforma.
- O usuário deve ser capaz de ver a tela inicial ao abrir o link.

**2. Pontos de Melhoria:**

- A tela inicial deve conter um header com botões de redirecionamento para outras áreas do site.
- A tela inicial deve conter um subtítulo explicando resumidamente o serviço oferecido pela Beedoo.
- A tela inicial deve conter um footer com informações de contato com o SAC e as redes sociais da empresa.

---

### 🔸 User Story 2: Criação de Novo Curso

- **Como** usuário da plataforma Beedoo, **eu quero** acessar a página "Cadastrar Cursos" pelo header **para** verificar se é possível cadastrar um curso.

**1. Critérios de Aceitação:**

- O usuário deve estar na plataforma.
- O usuário deve ser capaz de clicar no botão do header para acessar a página "Cadastrar Cursos".
- A página "Cadastrar Cursos" deve exibir um formulário para preencher e realizar o cadastro.
- O formulário deve incluir campos obrigatórios como nome, descrição, instrutor, URL da imagem de capa, duração, número de vagas e tipo de curso (presencial ou online).
- O usuário deve ser capaz de submeter o formulário e receber uma confirmação se o curso foi cadastrado com sucesso ou uma mensagem de erro se houver problemas.

---

### 🔸 User Story 3: Verificação de Curso Criado

- **Como** usuário da plataforma Beedoo, **eu quero** acessar a tela de cursos **para** ver que os cursos que criei foram adicionados com sucesso.

**1. Critérios de Aceitação:**

- O usuário deve ser capaz de navegar até a tela de cursos a partir do header.
- A tela de cursos deve exibir os cursos criados pelo usuário.
- A lista de cursos deve ser atualizada automaticamente para refletir a adição dos novos cursos.
   
**2. Exemplo de Mensagens:**

- **Sucesso:** "Curso adicionado com sucesso e disponível na lista de cursos."
- **Erro:** "Não foi possível adicionar o curso. Por favor, tente novamente mais tarde."
   
**3. Pontos de Melhoria:**

1. Os cursos criados pelo usuário devem ser claramente identificáveis na lista (ex.: com um rótulo "Criado por mim" ou similar).
2. O sistema deve exibir uma mensagem de confirmação após a criação de um curso, informando que ele foi adicionado com sucesso.

---

### 🔸 User Story 4: Acesso a Lista de Cursos

- **Como** usuário da plataforma Beedoo, **eu quero** acessar a página de listagem de cursos pelo header **para** ver todos os cursos numa lista.

**1. Critérios de Aceitação:**

- O usuário deve estar na plataforma.
- O usuário deve ser capaz de clicar no botão do header para acessar a página de listagem de cursos.
- A página deve exibir todos os cursos em formato de lista.

---

### 🔸 User Story 5:  Exclusão de Curso

- **Como** usuário da plataforma Beedoo, **eu quero** ser notificado se a exclusão de um curso for bem-sucedida **para** que eu saiba que o curso foi removido corretamente.

**1. Critérios de Aceitação:**

- O usuário deve estar na plataforma.
- O usuário deve ser capaz de excluir um curso a partir da lista de cursos.
- O sistema deve exibir uma mensagem de confirmação quando um curso for excluído com sucesso.
- A lista de cursos deve ser atualizada automaticamente para refletir a exclusão do curso.
- Se a exclusão falhar, o sistema deve exibir uma mensagem de erro clara, explicando o motivo da falha e oferecendo opções para o usuário (ex.: tentar novamente).

**2. Exemplo de Mensagens:**

- **Sucesso:** "Curso excluído com sucesso."
- **Erro:** "Não foi possível excluir o curso. Por favor, tente novamente mais tarde."

---

### 🔸 User Story 6: Verificação de Cursos Criados

- **Como** usuário da plataforma Beedoo, **eu quero** acessar a tela de cursos **para** ver que os cursos que criei foram adicionados com sucesso.

**1. Critérios de Aceitação:**

- O usuário deve ser capaz de navegar até a tela de cursos a partir do header.
- A tela de cursos deve exibir os cursos criados pelo usuário.
- A lista de cursos deve ser atualizada automaticamente para refletir a adição dos novos cursos.
   
**2. Exemplo de Mensagens:**

- **Sucesso:** "Curso adicionado com sucesso e disponível na lista de cursos."
- **Erro:** "Não foi possível adicionar o curso. Por favor, tente novamente mais tarde."
   
**Pontos de Melhoria:**

- Os cursos criados pelo usuário devem ser claramente identificáveis na lista (ex.: com um rótulo "Criado por mim" ou similar).
- O sistema deve exibir uma mensagem de confirmação após a criação de um curso, informando que ele foi adicionado com sucesso.

---

### 🔸 User Story 7: Validação de Campos Obrigatórios

- **Como** usuário da plataforma Beedoo, **eu quero** garantir que não seja possível cadastrar um curso sem preencher todos os campos obrigatórios **para** que o curso seja criado com todas as informações necessárias.

**1. Critérios de Aceitação:**

- O sistema deve validar o preenchimento dos campos obrigatórios antes de permitir a submissão do formulário.
- Se qualquer campo obrigatório estiver vazio, o sistema deve exibir uma mensagem de erro clara indicando quais campos precisam ser preenchidos.
- O formulário deve impedir a submissão até que todos os campos obrigatórios estejam devidamente preenchidos.
- Após o preenchimento correto de todos os campos e a submissão do formulário, o sistema deve confirmar o sucesso do cadastro do curso.

**2. Exemplo de Mensagens:**

- **Erro de Preenchimento:** "Por favor, preencha todos os campos obrigatórios antes de submeter o formulário."
- **Sucesso:** "Curso cadastrado com sucesso."

---

### 🔸 User Story 8: Limite de Caracteres

- **Como** usuário da plataforma Beedoo, **eu quero** que haja um limite de caracteres para os campos ao cadastrar um curso **para** garantir que as informações inseridas sejam concisas.

**1. Critérios de Aceitação:**

- Cada campo do formulário de cadastro de curso deve ter um limite máximo de caracteres especificado.
- O sistema deve restringir a entrada de dados para não permitir a inserção de mais caracteres do que o limite permitido.
- Se o usuário tentar inserir mais caracteres do que o permitido, o sistema deve exibir uma mensagem de erro indicando que o limite de caracteres foi excedido.
- O sistema deve fornecer uma contagem de caracteres restantes ou já utilizados nos campos relevantes para informar o usuário sobre o limite.
- Após a correção dos dados para atender aos limites de caracteres e a submissão do formulário, o sistema deve confirmar o sucesso do cadastro do curso.

**2. Exemplo de Mensagens:**

- **Erro de Limite de Caracteres:** "O campo 'Descrição' excedeu o limite máximo de 500 caracteres. Por favor, reduza o texto."
- **Sucesso:** "Curso cadastrado com sucesso."

---

## ✨ Bônus: Validando Acessibilidade com Leitor de Tela e AcessMonitor
Embora acessibilidade não tenha sido um requisito do desafio, usei uma ferramentas que normalmente aplico em minhas análises para garantir que a funcionalidade esteja bem implementada.

### 🔸 User Story 9 - Acessibilidade com Leitor de Tela

- **Como** usuário da plataforma Beedoo que utiliza serviços de voice over, **eu quero** que todas as informações do site sejam legíveis por esse serviço **para** que eu possa concluir o fluxo de cadastro de um novo curso de forma acessível.

**1. Critérios de Aceitação:**

- Todos os campos e labels no formulário de cadastro de curso devem ser corretamente identificados e descritos para serem lidos por serviços de voice over.
- O sistema deve garantir que as instruções e mensagens de erro sejam acessíveis e lidas de forma clara e completa pelo serviço de voice over.
- Elementos de navegação, botões e links devem ter textos alternativos e descrições apropriadas para serem lidos pelo serviço de voice over.
- O fluxo de cadastro de curso deve ser navegável e funcional utilizando apenas teclado e serviços de voice over, sem necessidade de interação visual.
- O sistema deve permitir que o usuário revise e corrija as informações inseridas com feedback audível claro em todas as etapas do processo.

**2. Exemplo de Mensagens:**

- **Descrição Acessível:** "O campo 'Nome do Curso' é obrigatório. Por favor, insira o nome do curso."
- **Erro Acessível:** "A descrição do curso excedeu o limite de 500 caracteres. Reduza o texto e tente novamente."

---

### 🔸Análise de URL com AccessMonitor
Pontos para observar após a análise:
- Foi encontrado apenas 1 cabeçalho na página. As páginas Web devem ser marcadas com uma estrutura hierarquizada de títulos e subtítulos. Cada página deve ter, no mínimo, um título de nível 1. O nível 2 deve marcar as secções e o nível 3 as subsecções destas.
- Foi localizada três combinações de cores cuja relação de contraste é inferiorao racio mínimo de contraste permitido pela WCAG (3 para 1 para textos com letra grande e 4,5 para 1 para textos com letra normal).
- O idioma principal está marcado como "en-US".  Os usuários brasileiros esperam que o conteúdo esteja em português.

Para mais informações:

[H57: Utilizar atributo language no elemento html](https://www.w3.org/WAI/WCAG21/Techniques/html/H57.html)

[Critério de sucesso 1.3.1 (Nível A) Noções sobre o CS 1.3.1](https://www.w3.org/WAI/WCAG21/Understanding/info-and-relationships.html)

[Critério de sucesso 2.4.10 (Nível AAA) Noções sobre o CS 2.4.10](https://www.w3.org/WAI/WCAG21/Understanding/section-headings.html)

[Critério de sucesso 1.4.3 (Nível AA) Noções sobre o CS 1.4.3](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)

---
# 2️⃣ Tabela de Casos de Teste e Evidências em Vídeo
As evidências em vídeos e os relatórios de bugs estão incluídos na tabela de Casos de Teste. Isso facilita a localização dessas informações, mantendo-as organizadas em um local de fácil visualização.
Porém, como o desafio pede para mantê-los aqui no README, o link se encontra disponível abaixo.

**🔸User Story 1: Acesso a Tela Inicial de Cursos**
- [Tabela Google Docs](https://docs.google.com/spreadsheets/d/1BgEgTdqSm6RgXx6gHXnDIkkYP53QbVCjgYhXaHYL0a4/edit?gid=0#gid=0)
- [Evidências MP4 - Google Drive](https://drive.google.com/drive/u/1/folders/1CML-umn3gJqtLu2tHuR1UNjW-JuqPmVD)

**🔸User Story 2 a 8: Funcionalidade "Cadastrar Cursos"**
- [Tabela Google Docs](https://docs.google.com/spreadsheets/d/1BNY0udQeUtEVB8vzKHq1ggI-15_eRWYjzgbSZlhI9OM/edit?gid=0#gid=0)
- [Evidências MP4 - Google Drive](https://drive.google.com/drive/folders/1WACwY7Yi6p8bcZRRS3do6tuHfuGr3pbe?usp=drive_link)

**🔸User Story 9: Acessibilidade com Voice Over**
- [Tabela Google Docs](https://docs.google.com/spreadsheets/d/1Uwhn5uwlZXIGWURo8DAhHX4rwkxVF56TFFYk1e9n5-M/edit?gid=0#gid=0)
- [Evidências MP4 - Google Drive](https://drive.google.com/drive/u/1/folders/18PcUEWJ2vurakXxclWfmWAvgH_bPUx3V)

---
#  3️⃣ Registro de Bugs
Os bugs estão alencados no campo "Issues" deste repositório
- Bug #01: [Atualização da página ''Cadastro de Curso'' retorna 404 - Page not found](https://github.com/moncoress/DESAFIO-BEEDOO/issues/1#issue-2442802175)
- Bug #02: [Caracteres especiais em campos obrigatórios ao cadastrar novo curso](https://github.com/moncoress/DESAFIO-BEEDOO/issues/2#issue-2442841415)
- Bug #03: [Cadastro de curso com data inválida](https://github.com/moncoress/DESAFIO-BEEDOO/issues/3)
- Bug #04: [Endereço presencial inválido ao cadastrar novo curso](https://github.com/moncoress/DESAFIO-BEEDOO/issues/4)
- Bug #05: [Ausência de limite de caracteres ao cadastrar um curso](https://github.com/moncoress/DESAFIO-BEEDOO/issues/5)
- Bug #06: [O campo "Link de Inscrição" permite a entrada de texto normal](https://github.com/moncoress/DESAFIO-BEEDOO/issues/6)
- Bug #07: [Falta de validação para campos obrigatórios vazios ao cadastrar um curso](https://github.com/moncoress/DESAFIO-BEEDOO/issues/7)
- Bug #08: [Não é possível editar curso cadastrado](https://github.com/moncoress/DESAFIO-BEEDOO/issues/8)
- Bug #09: [Não é possível excluir um curso](https://github.com/moncoress/DESAFIO-BEEDOO/issues/9)
- Bug #10: [Problemas de Responsividade com Zoom](https://github.com/moncoress/DESAFIO-BEEDOO/issues/10)
