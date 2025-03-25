# Sistema de Gerenciamento Bibliotecário

Este **Sistema de Gerenciamento Bibliotecário** foi desenvolvido para a disciplina de **Engenharia de Software**, com integração aos conceitos de **Algoritmos 2**, visando otimizar o controle e a organização de livros em bibliotecas. O sistema permite o cadastro, empréstimo, devolução e busca de livros, garantindo eficiência no gerenciamento das operações.

---

## 📝 **Documento de Visão**

### 🎯 **Objetivo**
Apresentar a visão geral do sistema, incluindo seus objetivos, escopo e requisitos principais, com foco na solução de problemas comuns em bibliotecas, como a organização de livros e o controle de empréstimos.

### 🔄 **Escopo**
- **Cadastro de Livros:** Registro de novos livros na biblioteca.
- **Empréstimo e Devolução:** Controle de empréstimos e devoluções de livros.
- **Busca de Livros:** Busca eficiente por título, autor ou categoria.

### 📋 **Requisitos de Alto Nível**
- Registro e organização de livros.
- Busca rápida e eficiente por informações.
- Controle de empréstimos e devoluções.
- Relatórios de livros mais emprestados.

---

## 👥 **Stakeholders**
- **Bibliotecários:** Responsáveis pelo gerenciamento de livros e empréstimos.
- **Leitores:** Usuários que buscam e realizam empréstimos de livros.

---

## ⚙️ **Caso de Uso**

### 🎯 **Objetivo do Caso de Uso**
Descrever as interações entre os usuários (bibliotecários e leitores) e o sistema, detalhando os fluxos de atividades que atendem às funcionalidades essenciais do sistema, como a busca e o empréstimo de livros.

### 🔄 **Fluxos Principais**
1. **Cadastro de Livro:** 
   - O bibliotecário adiciona novos livros ao sistema.
   - O sistema valida os dados e confirma o registro.

2. **Empréstimo de Livro:**
   - O leitor seleciona um livro disponível.
   - O sistema registra o empréstimo e atualiza o status do livro.

3. **Devolução de Livro:**
   - O leitor devolve o livro na data prevista.
   - O sistema registra a devolução e atualiza o status do livro.

### 🚨 **Fluxos Alternativos**
- **Livro Não Disponível:**
   - O sistema avisa ao leitor que o livro não está disponível para empréstimo.
- **Atraso na Devolução:**
   - O sistema alerta sobre o atraso e gera uma multa, se aplicável.

---

## 📊 **Conclusão**
Este sistema visa melhorar a eficiência das operações diárias de uma biblioteca, integrando conceitos de algoritmos para otimizar a busca e o gerenciamento de livros, proporcionando uma experiência mais fluida para bibliotecários e leitores.

