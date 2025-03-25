# Caso de Uso - Alexandria (Sistema de Gerenciamento Bibliotecário)

### Introdução
  O sistema **Alexandria** tem como objetivo automatizar a gestão de bibliotecas, otimizando o controle de acervo, usuários e empréstimos. Ele busca eliminar processos manuais ineficientes, proporcionando uma experiência mais fluida e organizada para bibliotecários e leitores. A plataforma permite que os bibliotecários monitorem o acervo de maneira mais eficiente, enquanto os leitores podem acessar informações detalhadas sobre os livros disponíveis, realizar empréstimos e efetuar reservas de forma simples e rápida.

  O Alexandria também inclui funcionalidades de notificações automáticas para lembrar os leitores sobre prazos de devolução e penalidades aplicáveis em caso de atraso. Dessa forma, busca-se reduzir significativamente problemas como livros extraviados, acervo desatualizado e dificuldades no gerenciamento de multas e reservas.

---

### 1. Atores
- **Bibliotecário**: Responsável por administrar o acervo, registrar empréstimos e devoluções.
- **Leitor**: Usuário que pode reservar e tomar livros emprestados.
- **Sistema Alexandria**: Gerencia o acervo, controla prazos e aplica penalidades.

---

### 2. Pré-condições
- O bibliotecário e o leitor devem estar cadastrados no sistema.
- O livro deve estar disponível para empréstimo ou reserva.
- O leitor não deve possuir pendências impeditivas, como multas.

---

### 3. Fluxos do Caso de Uso

#### 3.1 Fluxo Principal - Empréstimo de Livro
1. O leitor acessa o sistema e realiza login.
2. Ele pesquisa um livro no acervo.
3. Se o livro estiver disponível, ele solicita o empréstimo.
4. O sistema verifica as condições do leitor (multas, limite de empréstimos, etc.).
5. Se estiver apto, o sistema registra o empréstimo e define a data de devolução.
6. O bibliotecário confirma o empréstimo e entrega o livro ao leitor.
7. O sistema atualiza o status do livro para "Emprestado".

#### 3.2 Fluxo Alternativo - Reserva de Livro
- **FA1**: Se o livro não estiver disponível, o leitor pode solicitar uma reserva.
- **FA2**: Quando o livro for devolvido, o sistema notifica o primeiro leitor da fila de reservas.
- **FA3**: O leitor tem um prazo definido para retirar o livro antes que ele fique disponível para outros leitores.

#### 3.3 Fluxos de Exceção
- **FE1 - Leitor com Multas Pendentes**: Se o leitor possuir multas não pagas, o sistema bloqueia o empréstimo até a regularização.
- **FE2 - Livro Extraviado ou Danificado**: Caso o livro não seja devolvido ou seja devolvido danificado, o sistema aplica penalização ao leitor.
- **FE3 - Atraso na Devolução**: O sistema aplica automaticamente a multa correspondente e notifica o leitor.

---

### 4. Pós-condições
- O status do livro é atualizado no sistema.
- O histórico do leitor e do bibliotecário é atualizado.
- Multas são aplicadas automaticamente, se necessário.
- Leitores na fila de reservas são notificados quando um livro se torna disponível.

---

### 5. Pontos de Inclusão
- Cadastro e autenticação de usuários.
- Integração com sistema de notificações.
- Geração de relatórios para bibliotecários.

---

### 6. Pontos de Extensão
- Implementação de um sistema de avaliação de leitores.
- Opção de renovação de empréstimos online.

---

### 7. Aprovação
| Data | Função | Nome | Assinatura |
|------|--------|------|------------|
| 25/03/2025 | Aluna de Sistemas de Informação | Maria Júlia Griggi Rondon | Maria Griggi |


