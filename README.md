# Sistema de Gerenciamento de Tarefas (To-Do List)

Este é um projeto simples em Java que implementa um sistema de gerenciamento de tarefas (To-Do List). O sistema permite adicionar, listar, marcar como concluída e remover tarefas. É um projeto ideal para portfólio, pois demonstra conceitos básicos de programação em Java, como classes, objetos, listas e interação com o usuário.

## Funcionalidades

- **Adicionar Tarefa**: Adiciona uma nova tarefa à lista.
- **Listar Tarefas**: Exibe todas as tarefas cadastradas, mostrando o status (concluída ou pendente).
- **Marcar Tarefa como Concluída**: Marca uma tarefa específica como concluída.
- **Remover Tarefa**: Remove uma tarefa da lista.
- **Sair**: Encerra o programa.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

    projeto-todo-list/
    ├── src/
    │ ├── Tarefa.java
    │ ├── GerenciadorDeTarefas.java
    │ └── Main.java
    └── bin/
    ├── Tarefa.class
    ├── GerenciadorDeTarefas.class
    └── Main.class


- **`Tarefa.java`**: Contém a classe `Tarefa`, que representa uma tarefa com descrição e status.
- **`GerenciadorDeTarefas.java`**: Contém a classe `GerenciadorDeTarefas`, que gerencia a lista de tarefas e implementa as operações.
- **`Main.java`**: Contém a classe `Main`, que é o ponto de entrada do programa e gerencia a interação com o usuário.

## Como Executar o Projeto

### Pré-requisitos

- Java Development Kit (JDK) instalado (versão 8 ou superior).
- Um terminal ou prompt de comando.

### Passos para Execução

1. **Clone o repositório** (se estiver usando Git):
   ```
   git clone https://github.com/alveskevinn/todo-list.git
   cd todo-list

2. ***Compile o projeto:***

Navegue até a pasta do projeto e compile os arquivos Java:

    javac -d bin src/*.java
**Execute o projeto:**
Após a compilação, execute o programa:

    java -cp bin Main
**Interaja com o sistema:**
Siga as instruções no terminal para adicionar, listar, marcar como concluída ou remover tarefas.

**Expansões Futuras**
Este projeto pode ser expandido com as seguintes funcionalidades:

**Persistência de Dados:** Salvar as tarefas em um arquivo para que elas não sejam perdidas ao fechar o programa.

**Interface Gráfica:** Usar Java Swing ou JavaFX para criar uma interface gráfica.

**Prioridades:** Adicionar prioridades às tarefas (alta, média, baixa).

**Categorias:** Permitir categorizar as tarefas (trabalho, pessoal, estudos, etc.).

**Data de Vencimento:** Adicionar uma data de vencimento para cada tarefa.

### Contribuição
Se você quiser contribuir para este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request. Todas as contribuições são bem-vindas!
