# Entrega 05 - Expansão do Sistema de Gerenciamento de Biblioteca (SGB)

## Objetivo da Entrega
Esta entrega é uma continuação do projeto desenvolvido na **Entrega 04**. Agora, os candidatos devem aprimorar o Sistema de Gerenciamento de Biblioteca (SGB) com a implementação obrigatória de **AJAX** e **WebAPI**, além de outras melhorias que agreguem valor ao sistema.

O objetivo é proporcionar maior interatividade e eficiência ao sistema, tornando a experiência do usuário mais fluida e otimizando as operações realizadas na plataforma.

---

## Requisitos da Entrega

### 1. Implementação de AJAX
Para aprimorar a experiência do usuário e evitar recarregamentos desnecessários da página, o sistema deve utilizar AJAX para:
- **Busca Dinâmica de Livros:** Permitir que os usuários pesquisem livros na listagem sem precisar recarregar a página.
- **Gerenciamento de Empréstimos:** Atualizar automaticamente a disponibilidade dos livros ao realizar ou cancelar um empréstimo.
- **Cadastro Rápido de Autores e Categorias:** Criar um modal para adicionar novos autores ou categorias sem sair da tela de cadastro de livros.
- **Validação Assíncrona:** Implementar verificações em tempo real para evitar duplicações de autores e categorias.

### 2. Implementação de WebAPI
Para tornar o sistema mais escalável e modular, deve-se implementar uma **WebAPI** que permita a comunicação entre o front-end e o back-end, proporcionando maior flexibilidade para futuras expansões do sistema. As principais diretrizes incluem:
- Criar endpoints para **CRUD** de livros, autores, categorias e empréstimos.
- Retornar os dados no formato **JSON**, garantindo compatibilidade com AJAX.
- Implementar autenticação nos endpoints para proteger operações sensíveis.
- Criar um endpoint para **relatórios** (ex.: livros mais emprestados, usuários mais ativos).

### 3. Melhorias na Interface do Usuário
A interface deve ser aprimorada utilizando:
- **Bootstrap e CSS modernizado** para um layout responsivo e agradável.
- **Componentes dinâmicos** para melhorar a experiência do usuário.
- **Feedback visual em operações AJAX** (ex.: loaders, notificações).

### 4. Novas Funcionalidades e Melhorias (Diferenciais opcionais)
Além dos requisitos anteriores, os candidatos devem implementar as seguintes melhorias:

- **Histórico de Empréstimos:** Registrar quando um livro foi emprestado e devolvido.
- **Melhorias nos Relatórios:** Adicionar gráficos ou métricas adicionais sobre empréstimos e livros mais populares.
- **Sistema de Usuários e Login:** Criar um sistema básico de autenticação para restringir acesso a determinadas funções.
- **Notificações Automáticas:** Implementar um sistema de alerta para prazos de devolução dos livros.

---

## Critérios de Avaliação

1. **Uso correto de AJAX**: Implementação adequada de chamadas assíncronas para melhorar a interação no sistema.
2. **Implementação correta da WebAPI**: Endpoints bem estruturados e documentados.
3. **Interface do Usuário intuitiva**: Design limpo, responsivo e moderno.
4. **Funcionalidades implementadas corretamente**: Cumprimento dos requisitos da entrega e funcionalidades adicionais bem desenvolvidas.
5. **Organização do Código e Padrões de Projeto**: Separação adequada de camadas, boas práticas de codificação e uso eficiente do Entity Framework.
6. **Boas práticas de usabilidade**: Garantia de uma experiência agradável e eficiente ao usuário final.
7. **Versionamento Git**: Versionamento da entrega feito com qualidade, boas práticas de commits e constância. 

---

## Entrega 
- Façam um backup do projeto 04 para este repositório atual, com um commit descrevendo isso. A partir daí, inicie as implementações solicitadas.
- Deve ser entregue junto ao projeto a documentação contendo:
  - Instruções de instalação e execução.
  - Explicação das funcionalidades implementadas.
  - Informações sobre a estrutura do projeto.
- O prazo para entrega do projeto é até dia **28/02** às 23:59.

---

## Checklist de Desenvolvimento ✅

Antes de submeter sua entrega, verifique se os seguintes pontos foram atendidos:

- [ ] Implementação de AJAX para melhorar a interatividade do sistema.
- [ ] Implementação de busca dinâmica de livros sem recarregar a página.
- [ ] Gerenciamento de empréstimos atualizado automaticamente via AJAX.
- [ ] Modal para cadastro rápido de autores e categorias.
- [ ] Validação assíncrona para evitar dados duplicados.
- [ ] Implementação de uma WebAPI para gerenciar dados do sistema.
- [ ] Endpoints da WebAPI estruturados e funcionando corretamente.
- [ ] Interface responsiva e moderna utilizando Bootstrap e CSS aprimorado.
- [ ] Inclusão de histórico de empréstimos.
- [ ] Adição de gráficos ou relatórios sobre empréstimos e popularidade dos livros.
- [ ] Implementação de sistema de usuários e login básico.
- [ ] Notificações automáticas para prazos de devolução.
- [ ] Código organizado e seguindo padrões de boas práticas.
- [ ] Documentação completa explicando o funcionamento e instalação.

Foco nos estudos e boa sorte à todos!

