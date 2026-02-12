# 🚀 Projeto 3 — Automatizando Web Scraping para Extração, Transformação e Carga de Dados (ETL)

## 📌 Sobre o Projeto

Este projeto implementa um pipeline completo de **ETL (Extract, Transform, Load)** utilizando Python.

O sistema realiza:

- 🔎 Extração automatizada de dados a partir de uma página HTML
- 🔄 Transformação e tratamento das informações
- 📊 Geração automática de planilha Excel
- 🗄️ Persistência dos dados em banco SQLite

O fluxo é executado de forma automatizada, demonstrando na prática conceitos de **Web Scraping, manipulação de dados e engenharia de dados básica**.

---

## 🏗️ Arquitetura do Processo

O pipeline segue as seguintes etapas:

### 1️⃣ Extract
- Conexão com página HTML
- Captura estruturada dos dados via BeautifulSoup

### 2️⃣ Transform
- Limpeza de dados
- Conversão de unidades
- Padronização de valores

### 3️⃣ Load
- Exportação para planilha Excel
- Inserção dos dados em banco SQLite

---

## 🛠️ Tecnologias Utilizadas

- Python
- Requests
- BeautifulSoup
- OpenPyXL
- SQLite
- Pandas (se aplicável)

---

## 📂 Estrutura do Projeto

```
Projeto-3/
│
├── dados/
├── banco/
├── output.xlsx
├── script.py
└── README.md
```

---

## ▶️ Como Executar o Projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/GUIBATMART/Projeto-3---Automatizando-Web-Scraping-Para-Extra-o-Transforma-o-e-Carga-de-Dados.git
```

### 2️⃣ Acesse a pasta do projeto

```bash
cd Projeto-3---Automatizando-Web-Scraping-Para-Extra-o-Transforma-o-e-Carga-de-Dados
```

### 3️⃣ Instale as dependências

```bash
pip install requests beautifulsoup4 openpyxl pandas
```

### 4️⃣ Execute o script

```bash
python script.py
```

---

## 📊 Resultados Gerados

Ao executar o projeto, serão gerados:

- ✅ Arquivo Excel com os dados tratados
- ✅ Banco de dados SQLite populado
- ✅ Processo automatizado de ponta a ponta

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- Praticar construção de pipelines ETL
- Aplicar Web Scraping de forma estruturada
- Consolidar conhecimentos em manipulação de dados
- Simular cenários reais de Engenharia de Dados

---

## 📈 Possíveis Melhorias Futuras

- Implementação de logs estruturados
- Tratamento avançado de exceções
- Containerização com Docker
- Agendamento automático (cron / task scheduler)
- Integração com PostgreSQL

---

## 👨‍💻 Autor

**Guilherme Batista**  
Analista de Sistemas | Automação de Processos | Engenharia de Dados em evolução  

🔗 GitHub: https://github.com/GUIBATMART  
🔗 LinkedIn: www.linkedin.com/in/guilherme-batista-175b31223
