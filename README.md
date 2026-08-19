# 📋 Documento de Requisitos — ParticipaCTBJ

> Documento de requisitos da plataforma **ParticipaCTBJ**, desenvolvida para facilitar o registro, a organização e a consulta da participação dos estudantes em atividades escolares e extracurriculares do Colégio Técnico de Bom Jesus (CTBJ).

---

## 1. Introdução

### 1.1 Objetivo

O objetivo deste documento é apresentar os requisitos necessários para o desenvolvimento do **ParticipaCTBJ**, definindo as principais funcionalidades e características que a plataforma deverá possuir.

### 1.2 Público-alvo

A plataforma será destinada principalmente a:

- **Alunos do CTBJ**;
- **Professores do CTBJ**;
- **Responsáveis pela organização das atividades escolares**.

---

## 2. Descrição da solução

O **ParticipaCTBJ** será uma plataforma para registrar e organizar a participação dos estudantes em atividades realizadas pela escola.

Os usuários autorizados poderão cadastrar atividades e registrar os alunos participantes.

As atividades poderão incluir:

- Projetos;
- Feiras;
- Olimpíadas;
- Apresentações;
- Competições;
- Oficinas;
- Eventos escolares;
- Outras atividades extracurriculares.

A plataforma permitirá consultar as atividades realizadas e o histórico de participação dos estudantes.

O sistema não terá como objetivo registrar notas, frequência ou desempenho acadêmico.

---

## 3. Tipos de usuários

| Usuário | Descrição |
|---|---|
| **Aluno** | Poderá consultar suas participações e o histórico de atividades das quais participou. |
| **Professor** | Poderá cadastrar atividades e registrar os estudantes participantes, conforme suas permissões. |
| **Responsável pela organização** | Poderá gerenciar atividades e consultar informações sobre as participações registradas. |

---

## 4. Requisitos Funcionais

> Os requisitos funcionais descrevem as funcionalidades que o sistema deverá oferecer aos usuários.

### RF01 — Cadastro de usuário

**Descrição:** O sistema deverá permitir o cadastro dos usuários que terão acesso à plataforma.

**Atores:** Aluno, Professor e Responsável pela organização.

### RF02 — Login

**Descrição:** O sistema deverá permitir que usuários cadastrados realizem login para acessar as funcionalidades disponíveis para seu perfil.

**Atores:** Aluno, Professor e Responsável pela organização.

### RF03 — Cadastro de atividades

**Descrição:** O sistema deverá permitir que usuários autorizados cadastrem atividades realizadas pela escola.

**Informações da atividade:**

- Nome;
- Descrição;
- Categoria;
- Data;
- Local;
- Responsável.

**Atores:** Professor e Responsável pela organização.

### RF04 — Registro de participantes

**Descrição:** O sistema deverá permitir registrar os estudantes que participaram de uma determinada atividade.

**Atores:** Professor e Responsável pela organização.

### RF05 — Consulta de atividades

**Descrição:** O sistema deverá permitir que os usuários consultem as atividades cadastradas na plataforma.

**Atores:** Aluno, Professor e Responsável pela organização.

### RF06 — Consulta de participantes

**Descrição:** O sistema deverá permitir visualizar os estudantes participantes de uma determinada atividade.

**Atores:** Professor e Responsável pela organização.

### RF07 — Histórico de participação

**Descrição:** O sistema deverá permitir que o aluno consulte o histórico das atividades das quais participou.

**Ator:** Aluno.

### RF08 — Organização por categorias

**Descrição:** O sistema deverá permitir organizar as atividades de acordo com suas categorias.

**Exemplos:**

1. Projetos;
2. Feiras;
3. Olimpíadas;
4. Apresentações;
5. Competições;
6. Oficinas;
7. Eventos.

**Atores:** Professor e Responsável pela organização.

### RF09 — Painel de participação

**Descrição:** O sistema deverá apresentar informações organizadas sobre as participações registradas, permitindo visualizar dados gerais das atividades e dos estudantes participantes.

**Ator:** Responsável pela organização.

### RF10 — Diferenciação de usuários

**Descrição:** O sistema deverá identificar os diferentes tipos de usuários e disponibilizar as funcionalidades correspondentes a cada perfil.

**Tipos de usuário:**

1. Aluno;
2. Professor;
3. Responsável pela organização.

---

## 5. Requisitos Não Funcionais

> Os requisitos não funcionais definem características de qualidade e funcionamento que a plataforma deverá apresentar.

| Código | Requisito | Descrição |
|---|---|---|
| **RNF01** | Usabilidade | A plataforma deverá possuir uma interface simples e fácil de utilizar. |
| **RNF02** | Segurança | Os dados dos usuários e estudantes deverão ser protegidos contra acesso não autorizado. |
| **RNF03** | Desempenho | As consultas e buscas deverão apresentar os resultados de forma rápida. |
| **RNF04** | Organização | As informações sobre atividades e participações deverão ser apresentadas de maneira organizada. |
| **RNF05** | Responsividade | A plataforma deverá funcionar adequadamente em computadores, tablets e celulares. |
| **RNF06** | Privacidade | As informações pessoais dos estudantes deverão ser acessíveis somente aos usuários autorizados. |

---

## 6. Atividades registradas

A plataforma deverá permitir o registro de diferentes tipos de atividades escolares, como:

- **Projetos**;
- **Feiras**;
- **Olimpíadas**;
- **Apresentações**;
- **Competições**;
- **Oficinas**;
- **Eventos escolares**;
- **Outras atividades extracurriculares**.

---

## 7. Organização das atividades

As atividades poderão ser organizadas utilizando diferentes informações:

| Categoria | Exemplos |
|---|---|
| **Tipo de atividade** | Projeto, Feira, Olimpíada, Competição |
| **Período** | Data de realização |
| **Local** | Espaço onde a atividade ocorreu |
| **Responsável** | Professor ou responsável pela atividade |

Essa organização deverá facilitar a consulta das atividades e das participações registradas.

---

## 8. Fluxo básico do sistema

O funcionamento básico da plataforma seguirá o seguinte fluxo:

1. O usuário acessa a plataforma;
2. Realiza o **cadastro** ou **login**;
3. O usuário acessa as funcionalidades disponíveis para seu perfil;
4. O professor ou responsável cadastra uma atividade;
5. Os estudantes participantes são registrados;
6. As informações ficam armazenadas na plataforma;
7. O aluno poderá consultar seu histórico de participação;
8. Os responsáveis poderão consultar as informações gerais das participações.

---

## 9. Regras gerais

- O usuário deverá possuir uma conta para utilizar as funcionalidades que exigem autenticação.
- Cada atividade deverá possuir informações básicas para seu cadastro.
- Uma atividade poderá possuir vários estudantes participantes.
- Um estudante poderá participar de várias atividades.
- Cada registro de participação deverá estar relacionado a um estudante e a uma atividade.
- Somente usuários autorizados poderão cadastrar ou alterar informações das atividades e participações.
- A participação registrada não deverá ser utilizada para calcular notas ou médias.
- O sistema não terá como finalidade avaliar o desempenho acadêmico dos estudantes.

---

## 10. Relação entre solução e requisitos

| Funcionalidade da solução | Requisito relacionado |
|---|---|
| Cadastro de usuários | RF01 |
| Login | RF02 |
| Cadastro de atividades | RF03 |
| Registro de participantes | RF04 |
| Consulta de atividades | RF05 |
| Consulta de participantes | RF06 |
| Histórico de participação | RF07 |
| Organização por categorias | RF08 |
| Painel de participação | RF09 |
| Diferentes tipos de usuários | RF10 |

---

## 11. Considerações finais

O **ParticipaCTBJ** tem como proposta facilitar o registro, a organização e a consulta da participação dos estudantes em atividades escolares e extracurriculares do CTBJ.

Os requisitos apresentados neste documento servirão como base para as próximas etapas de desenvolvimento do projeto, orientando a construção das funcionalidades da plataforma.zada de acompanhar essas informações.
