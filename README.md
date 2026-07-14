# 📊 Dashboard de Análise de Salários na Área de Dados

Dashboard interativo desenvolvido em **Python** e **Streamlit** para explorar dados salariais de profissionais da área de dados. O projeto foi construído durante a **Imersão Dados com Python da Alura**, com o objetivo de aplicar, na prática, conceitos de análise exploratória, manipulação de dados com Pandas e visualização de dados com Plotly.

## 🔍 Sobre o projeto

A aplicação carrega uma base de dados salariais e permite filtrar as informações por ano, senioridade, tipo de contrato e tamanho da empresa, exibindo métricas gerais e gráficos dinâmicos que ajudam a entender como os salários se distribuem no setor de dados.

## ✨ Funcionalidades

- **Filtros interativos** na barra lateral: ano, senioridade, tipo de contrato e tamanho da empresa
- **Métricas (KPIs)**: salário médio, salário máximo, total de registros e cargo mais frequente
- **Top 10 cargos** por salário médio
- **Distribuição de salários** (histograma)
- **Proporção dos tipos de trabalho** (remoto, híbrido, presencial)
- **Salário médio de Cientista de Dados por país** (mapa coroplético)
- **Tabela de dados detalhados** com os registros filtrados

## 🛠️ Tecnologias utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/) — construção da interface web
- [Pandas](https://pandas.pydata.org/) — manipulação e filtragem dos dados
- [Plotly Express](https://plotly.com/python/plotly-express/) — visualização de dados

## 📁 Estrutura do projeto

```
├── app.py               # Código principal do dashboard (Streamlit)
├── df_limpo.csv          # Base de dados tratada
├── requirements.txt       # Dependências do projeto
└── .gitignore
```

## 🚀 Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/BarbaraVitor/Dashboard-analise-salarios-dados.git
   cd Dashboard-analise-salarios-dados
   ```

2. (Opcional, mas recomendado) Crie um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute a aplicação:
   ```bash
   streamlit run app.py
   ```

5. Acesse no navegador o endereço indicado no terminal (geralmente `http://localhost:8501`).

## 📚 Sobre a imersão

Este projeto foi desenvolvido como parte da **Imersão Dados com Python**, promovida pela [Alura](https://www.alura.com.br/), com foco em análise de dados, criação de dashboards e boas práticas com Python para ciência de dados.

## 👩‍💻 Autora

Desenvolvido por [Barbara Vitor](https://github.com/BarbaraVitor).

📎 [LinkedIn](https://www.linkedin.com/in/bárbara-vitor-b072383a5)
