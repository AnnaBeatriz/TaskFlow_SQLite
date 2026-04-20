# TaskFlow SQLite

Sistema simples de gerenciamento de tarefas desenvolvido com Python, SQLite e Gradio.

---

## 📌 Funcionalidades

- Criar tarefas  
- Editar tarefas  
- Excluir tarefas  
- Definir prioridade (Baixa, Média, Alta)  
- Definir status (Pendente, Em andamento, Concluída)  
- Informar data de vencimento  
- Filtrar tarefas  
- Visualizar indicadores por status  

---

## 🧰 Tecnologias utilizadas

- Python  
- SQLite  
- Gradio  
- Pandas  

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/taskflow-sqlite.git
cd taskflow-sqlite
```

### 2. Instale as dependências

```bash
pip install gradio pandas
```

### 3. Execute a aplicação

```bash
python app.py
```

---

## 🗂 Estrutura do projeto

```
taskflow-sqlite/
├── app.py
├── tarefas.db
├── README.md
└── requirements.txt
```

---

## 🗄 Banco de dados

A aplicação utiliza uma tabela chamada `tarefas` com os seguintes campos:

- `id` → identificador único  
- `titulo` → nome da tarefa  
- `descricao` → detalhes  
- `prioridade` → Baixa / Média / Alta  
- `status` → Pendente / Em andamento / Concluída  
- `data_vencimento` → data no formato YYYY-MM-DD  

---

## 🎯 Objetivo do projeto

Este projeto foi criado com foco em aprendizado prático, demonstrando como integrar:

- Interface visual (Gradio)  
- Lógica de negócio (Python)  
- Persistência de dados (SQLite)  

---

## 📄 Licença

Este projeto pode ser utilizado livremente para fins de estudo e adaptação.
