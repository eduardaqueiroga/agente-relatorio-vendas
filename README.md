## Agente de Relatório de Vendas com IA (Groq + Python)

Este projeto gera **relatórios automáticos de vendas** a partir de um arquivo Excel (`.xlsx`) ou PDF usando **Inteligência Artificial Groq (modelo Llama 3.1)**.  
O sistema lê os dados, resume as informações e cria um **relatório executivo em PDF**, incluindo análises e recomendações estratégicas.

---

### 📊 Base de Dados

Os dados de vendas utilizados neste projeto foram obtidos a partir do Kaggle:  
[Retail Insights: A Comprehensive Sales Dataset](https://www.kaggle.com/datasets/rajneesh231/retail-insights-a-comprehensive-sales-dataset)

---

### 🚀 Acesse o Notebook no Google Colab

Clique abaixo para executar o projeto diretamente no Colab:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eduardaqueiroga/agente-relatorio-vendas/blob/main/agente_relatorio_vendas.ipynb)  

---

### 🧠 Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| **Python 3.12+** | Linguagem principal do projeto |
| **Pandas** | Leitura e manipulação de planilhas Excel |
| **pdfplumber** | Extração de texto de arquivos PDF |
| **FPDF** | Geração do relatório final em PDF |
| **Groq API** | Inteligência Artificial (modelo `llama-3.1-8b-instant`) |
| **getpass** | Entrada segura da chave de API |
| **Google Colab** | Ambiente de execução do projeto |

### 📊 Funcionalidades

- ✅ Leitura de arquivos Excel ou PDF
- ✅ Resumo automático dos dados (estatísticas + amostra)
- ✅ Geração de relatório com linguagem natural via IA Groq
- ✅ Exportação em PDF formatado
- ✅ Entrada segura da chave de API

