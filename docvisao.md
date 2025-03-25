# Documento de Visão - Alexandria (Sistema de Gerenciamento Bibliotecário)

## **Data**
| Data | Versão | Modificação | Autor |
|------|--------|--------------|-------|
| 24/03/2025 | 3.0 | Atualização do Documento | Maria Júlia Griggi Rondon |

## **1. Introdução**
  O documento de visão define o escopo de alto nível e o propósito do software a ser desenvolvido. Esse visa estabelecer as expectativas e reduzir os riscos do produto, protegendo o cliente e os desenvolvedores do projeto.

### **1.1 Finalidade**
  Este documento tem como objetivo apresentar a visão geral do **Alexandria**, um sistema de gerenciamento bibliotecário desenvolvido para otimizar a administração de acervos, controle de usuários e gestão de empréstimos. Ele visa padronizar processos, reduzir falhas e melhorar a experiência de bibliotecários e leitores.

### **1.2 Escopo**
  O **Alexandria** é um sistema projetado para bibliotecas de diversos portes, permitindo o cadastro e controle de livros, usuários, empréstimos e penalidades de forma automatizada. O sistema será responsivo e acessível via navegador web, facilitando o acesso a informações relevantes sobre o acervo e histórico de empréstimos.

### **1.3 Referências**
- Caso de Uso: **Gestão de Empréstimos e Reservas – Alexandria**.

## **2. Posicionamento**
### **2.1 Oportunidade de Negócio**
  O Alexandria surge como uma solução inovadora para bibliotecas que enfrentam dificuldades com a gestão manual de acervos e o uso de sistemas desatualizados. Muitos bibliotecários e instituições lidam com processos ineficazes, o que leva a erros, extravios de livros e dificuldades no controle de empréstimos. A automação de processos, como o controle de reservas, multas e prazos, pode reduzir significativamente esses problemas e otimizar a operação da biblioteca.

  Além disso, com a crescente demanda por soluções tecnológicas no setor educacional, o mercado de bibliotecas, especialmente públicas e educacionais, está cada vez mais inclinado a adotar ferramentas digitais. Isso cria uma oportunidade de negócio significativa para o Alexandria, que pode atender tanto bibliotecas de diferentes portes quanto centros de leitura, escolas e universidades. A necessidade de modernização e de recursos acessíveis para a gestão de acervos oferece um grande potencial de expansão para o sistema.

### **2.2 Descrição do Problema**
| O problema de | Afeta | Cujo impacto é | Uma boa solução seria |
|--------------|------|----------------|----------------|
| Falta de um sistema eficiente para bibliotecas | Bibliotecários e leitores | Atrasos, dificuldades na organização e falha na aplicação de penalidades | Digitalização e automação dos processos |

### **2.3 Sentença de Posição do Produto**
| Para | Que | O Alexandria | Que | Nosso produto |
|------|----|-------------|----|--------------|
| Bibliotecas e centros de leitura | Precisam de um sistema eficiente para gestão do acervo | É uma plataforma | Automatiza o controle de usuários, livros, empréstimos e penalidades | Proporciona uma experiência fluida e organizada para bibliotecários e leitores |

## **3. Descrição dos Envolvidos e Usuários**
  Os principais envolvidos neste projeto serão a equipe de desenvolvimento e gestão, responsáveis pela criação e administração do sistema, além dos bibliotecários e administradores, que atuarão como principais usuários da plataforma.

  O público-alvo do Alexandria será os bibliotecários, que gerenciarão o acervo, e os leitores, que interagirão diretamente com a plataforma para realizar consultas, empréstimos e reservas de livros.

  Os principais benefícios do sistema incluem a automação dos processos de empréstimos e reservas, o controle eficiente do acervo e a melhoria na gestão de multas e prazos.

### **3.1 Resumo dos Envolvidos**
| Nome | Descrição | Responsabilidades |
|------|-----------|-----------------|
| Bibliotecário | Administrador da biblioteca | Gerenciar livros, usuários, penalidades e relatórios |
| Usuário (Leitor) | Pessoa que realiza empréstimos e reservas | Consultar acervo, realizar empréstimos e acompanhar prazos |
| Sistema Alexandria | Plataforma digital | Registrar transações, controlar prazos e gerar relatórios |

# **3.2 Resumo dos Usuários**
| Nome             | Descrição                                                   | Responsabilidades                                               |
|------------------|-------------------------------------------------------------|-----------------------------------------------------------------|
| **Bibliotecários**| Profissionais responsáveis pela administração da biblioteca. | Utilizar o sistema para gerenciar o acervo, controlar empréstimos e multas. |
| **Leitores**     | Usuários da biblioteca que realizam empréstimos e reservas.  | Consultar o acervo, fazer empréstimos, reservas e acompanhar prazos. |

### **3.3 Principais Necessidades dos Usuários**
| Necessidade | Prioridade | Preocupação | Solução Proposta |
|------------|-----------|-------------|----------------|
| Gerenciar empréstimos e devoluções | Alta | Atrasos e extravios | Controle digital e automatizado |
| Aplicar multas automaticamente | Alta | Erros humanos no cálculo | Sistema automático de penalidades |
| Reservar livros indisponíveis | Média | Longa espera sem previsão | Fila de reservas com notificação |
| Acompanhar histórico de leituras | Baixa | Falta de controle pessoal | Painel do usuário |

## **4. Descrição da Solução**
### **4.1 Perspectiva do Produto**
  O Alexandria visa transformar a gestão de bibliotecas, proporcionando uma plataforma moderna e eficiente. Ao substituir processos manuais por soluções digitais, o sistema garante maior agilidade no controle de acervo, empréstimos e penalidades. Ele é intuitivo e fácil de usar, permitindo que bibliotecários e leitores naveguem sem dificuldades. Além disso, a plataforma é segura, com protocolos que asseguram a integridade das informações, ao mesmo tempo em que é acessível de qualquer dispositivo, tornando a biblioteca mais organizada e eficiente no dia a dia.

### **4.2 Resumo dos Recursos**
| Benefício para o Cliente | Recursos de Suporte |
|------------------------|-----------------|
| Controle de empréstimos e devoluções | Sistema de gestão automatizado |
| Multas automáticas | Cálculo de penalidades integrado |
| Reservas de livros | Notificação quando livro estiver disponível |
| Painel administrativo | Relatórios sobre uso e status do acervo |

## **5. Recursos do Produto**
- Cadastro e gerenciamento de usuários.
- Controle de livros e acervo.
- Registro e acompanhamento de empréstimos e devoluções.
- Aplicação automática de multas.
- Fila de reservas de livros.
- Notificações sobre prazos e penalidades.
- Relatórios para bibliotecários.

## **6. Requisitos Funcionais**
| Funcionalidade | Prioridade |
|---------------|-----------|
| Cadastro e edição de usuários | Alta |
| Registro e controle de livros | Alta |
| Gerenciamento de empréstimos e devoluções | Alta |
| Cálculo automático de multas | Alta |
| Reservas de livros | Média |
| Notificações automáticas | Média |

## **7. Restrições**
- O sistema precisa de conexão com a internet.
- Uso restrito a bibliotecas cadastradas.
- Interface responsiva e compatível com navegadores modernos.

## **8. Qualidade e Implementação**
## 8.1 Requisitos de Implementação
O sistema será desenvolvido para ser acessado via navegador web e dispositivos móveis, permitindo que os funcionários visualizem horários, informações dos veículos e chamados de manutenção de forma prática e acessível, otimizando o dia a dia.

## 8.2 Requisitos de Sistema
O sistema será compatível com Windows, Linux, MacOS, Android e iOS, e exigirá conexão com a internet. Ele será otimizado para navegadores modernos.

## 8.3 Requisitos de Design
A interface será intuitiva, fácil de usar e responsiva, proporcionando uma experiência de usuário fluida e acessível em diversos dispositivos.
