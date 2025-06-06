# Documento de Requisitos - Alexandria (Sistema de Gerenciamento Bibliotecário)

### 1. Introdução

#### 1.1 Objetivo
  Descrever os requisitos funcionais e não funcionais do sistema Alexandria – Sistema de Gerenciamento Bibliotecário, garantindo que todas as funcionalidades estejam alinhadas às necessidades da biblioteca e seus usuários.

---

#### 1.2 Escopo do Sistema
O Alexandria é um sistema web para bibliotecas acadêmicas que permite o cadastro de livros e usuários, além da gestão de empréstimos, devoluções e busca no acervo. Seus principais módulos são:

- Cadastro de livros e usuários
- Empréstimo e devolução de livros
- Busca de livros por diferentes critérios
- Geração de relatórios administrativos

---

#### 1.3 Definições, Acrônimos e Abreviações
- **SRS**: Software Requirements Specification
- **UI**: User Interface
- **CRUD**: Create, Read, Update, Delete
- **RF**: Requisito Funcional
- **RNF**: Requisito Não Funcional

---

### 2. Visão Geral

#### 2.1 Perspectiva do Produto
O sistema será desenvolvido como um sistema independente, com interface web acessível por navegadores modernos. O Alexandria será utilizado em bibliotecas para otimizar a gestão de acervo e o controle de empréstimos.

---

#### 2.2 Funções do Sistema

- Cadastro de livros e usuários
- Registro de empréstimos e devoluções
- Busca de livros por título, autor ou ISBN
- Geração de relatórios de movimentação
- Controle de prazos e multas

---

#### 2.3 Características dos Usuários
- **Bibliotecários**: Usuários com familiaridade média a alta com tecnologia, responsáveis pela administração do sistema
- **Leitores**: Estudantes e professores, com conhecimento básico em navegação na web

---

#### 2.4 Restrições
- Deve ser compatível com navegadores atualizados (Chrome, Firefox, Edge)
- Armazenamento em banco de dados relacional

---

### 3. Requisitos Funcionais
| Código | Descrição |
|------------------------|-----------------|
| RF01 | O sistema deve permitir o cadastro de livros com título, autor, editora, ano e ISBN. |
| RF02 | O sistema deve permitir o cadastro de usuários com nome, matrícula e contato. |
| RF03 | O sistema deve registrar o empréstimo de livros a usuários cadastrados. |
| RF04 | O sistema deve registrar a devolução de livros e atualizar sua disponibilidade. |
| RF05 | O sistema deve permitir a busca de livros por título, autor ou ISBN. |
| RF06 | O sistema deve gerar relatórios de empréstimos e devoluções com filtros. |

---

### 4. Requisitos Não Funcionais
| Código | Descrição |
|------------------------|-----------------|
| RNF01 | O sistema deve responder a qualquer solicitação do usuário em até 2 segundos. |
| RNF02 | A interface deve ser responsiva e acessível em diferentes tamanhos de tela. |
| RNF03 | Os dados do sistema devem ser armazenados com segurança, respeitando princípios de LGPD. |
| RNF04 | O sistema deve estar disponível em pelo menos 99% do tempo (alta disponibilidade). |
| RNF05 | A UI deve seguir boas práticas de usabilidade e acessibilidade (WCAG 2.1). |

---

### 5. Regras de Negócio
- Um usuário pode ter no máximo 3 livros emprestados ao mesmo tempo.
- O prazo de devolução padrão é de 14 dias corridos.
- Em caso de atraso, será aplicada uma multa diária conforme política da biblioteca.
- Apenas usuários cadastrados e ativos podem realizar empréstimos.








