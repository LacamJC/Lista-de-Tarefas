
### Readme.md

# 📝 Lista de Tarefas

Uma aplicação simples para gerenciar tarefas, onde você pode criar tarefas, marcar como concluídas e removê-las da lista.

## 💻 Como Rodar o Projeto

### Pré-requisitos:
- Um navegador de internet para executar o projeto localmente.

### Passos:
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/lista-de-tarefas.git
   ```

2. Acesse o diretório do projeto:
   ```sh
   cd lista-de-tarefas
   ```

3. Abra o arquivo `index.html` no seu navegador.

## 🔧 Funcionalidades
- **Criar Tarefa**: Adicione uma nova tarefa ao sistema.
- **Marcar como Concluída**: Marque a tarefa como concluída ao clicar na caixa de seleção.
- **Remover Tarefa**: Após ser concluída, a tarefa será removida da lista com uma animação suave.
  
## 🖥️ Tecnologias
- **HTML**: Estrutura básica da página.
- **CSS**: Estilização da interface.
- **JavaScript**: Funcionalidade de criação, marcação e remoção de tarefas.

## 📂 Estrutura do Projeto

```plaintext
Lista-de-Tarefas/
├── README.md
├── index.html
└── css/
    └── style.css
```

## 🛠️ Como Funciona o Código

### index.html

- Contém a estrutura da interface, onde as tarefas podem ser inseridas e visualizadas.
- A lista de tarefas é manipulada dinamicamente com JavaScript, onde as tarefas são adicionadas, concluídas e removidas ao clicar nas caixas de seleção.

### style.css

- Estilos personalizados para a interface, com animações suaves e responsividade para dispositivos móveis.
  
### script no index.html

- **Função `verificar()`**: Detecta pressionamento da tecla Enter para criar uma nova tarefa.
- **Função `tarefa()`**: Cria uma nova tarefa e a adiciona à lista.
- **Função `concluir()`**: Marca a tarefa como concluída, aplica uma animação de fade-out e remove da lista após 1 segundo.

---

Feito por [LacamJC](https://github.com/LacamJC)
```

