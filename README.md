# 🛠️ Automação de Indicadores – OnePage para Lojas

![Python](https://img.shields.io/badge/Python-3.9%2B-FFD43B?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?logo=pandas)
![Excel](https://img.shields.io/badge/Excel-Reports-217346?logo=microsoft-excel)
![Outlook](https://img.shields.io/badge/Outlook-E--mail-0078D4?logo=microsoft-outlook)
![Status](https://img.shields.io/badge/Status-Funcional-8A2BE2)


## 📌 Sobre o Projeto
O **Automação de Indicadores** é uma solução completa que transforma processos manuais de análise de vendas e geração de relatórios em uma **rotina 100% automatizada**.  

Imagine acordar e descobrir que **todos os relatórios e indicadores da sua rede de lojas** já estão prontos, enviados e organizados, sem que ninguém precise abrir uma planilha manualmente.


## 🎯 Objetivo
Este projeto tem como objetivo criar um fluxo automatizado que:  

- Calcule automaticamente os **principais indicadores** de cada loja.  
- Gere o **OnePage personalizado** para cada gerente.  
- Envie o OnePage **no corpo do e-mail** e os dados completos da loja em anexo.  
- Dispare um relatório especial para a diretoria com **rankings diários e anuais**.  


## 🛍️ Cenário
Você é Analista de Dados em uma rede com **25 lojas espalhadas pelo Brasil**.  
Todos os dias, o sistema produz automaticamente:  

- Comparações rápidas entre lojas.  
- Indicadores diários e acumulados do ano.  
- Status de metas (✅ ou ❌).  


## 📂 Estrutura e Arquivos

| Arquivo | Descrição |
|---------|-----------|
| **Emails.xlsx** | Contém nome, loja e e-mail de cada gerente. |
| **Vendas.xlsx** | Registro de vendas de todas as lojas. |
| **Lojas.csv** | Lista completa das lojas da rede. |
| **Saída** | Pastas com planilhas e OnePages gerados, organizados por data. |

> ⚠️ Para testes iniciais, a pasta "Backup Arquivos Lojas" deve estar vazia.


## 📈 Indicadores Calculados

| Indicador | Meta Dia | Meta Ano |
|-----------|---------|----------|
| Faturamento | 1.000 | 1.650.000 |
| Diversidade de Produtos | 4 | 120 |
| Ticket Médio por Venda | 500 | 500 |

> Todos os indicadores são calculados para o **dia mais recente** e para o **acumulado do ano**.


## 📤 Envio de E-mails

### Gerentes de Loja
- Recebem o **OnePage no corpo do e-mail**.  
- Recebem uma **planilha anexa** contendo apenas os dados da própria loja.  
> ⚠️ Cada gerente **não tem acesso** a informações de outras lojas.

### Diretoria
- Recebe dois rankings em anexo:  
  1. Ranking diário das lojas.  
  2. Ranking anual das lojas.  
- No corpo do e-mail, destaques sobre:  
  - Melhor e pior loja do dia.  
  - Melhor e pior loja do ano.


## 💡 Diferenciais
- 💻 Totalmente automatizado.  
- 🔒 Proteção de dados — cada gerente recebe **somente suas informações**.  
- 📂 Histórico organizado por pastas e datas.  
- 📊 Indicadores claros, objetivos e de fácil interpretação.  
- ⚙️ Fácil adaptação para outras redes ou cenários corporativos.


## 🚀 Como Executar
1. Clone o repositório.  
2. Adicione os arquivos **Emails.xlsx**, **Vendas.xlsx** e **Lojas.csv** na mesma pasta do notebook.  
3. Abra o Jupyter Notebook `Automacao de Processo.ipynb`.  
4. Execute as células **na ordem**.  
5. Os OnePages serão gerados, os e-mails enviados e os backups organizados automaticamente. ✨  


## 📜 Licença
Este projeto é de **uso livre** para fins educacionais e pode ser adaptado para diferentes realidades empresariais.


💌 Automatizar não é apenas economizar tempo; é **garantir que o tempo seja usado para o que realmente importa**.


