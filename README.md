# 🛠️ Automação de Indicadores – OnePage para Lojas

## 📌 Sobre o Projeto
Imagine acordar e descobrir que **todos os relatórios e indicadores da sua rede de lojas** já estão prontos, enviados e organizados… **sem que ninguém precise abrir uma planilha manualmente**.  
Bem-vindo ao **Automação de Indicadores**, um projeto que transforma um processo repetitivo e trabalhoso em uma **rotina 100% automatizada**.

---

## 🎯 Objetivo
Criar um processo **do zero até a entrega final**, que:
- Calcule automaticamente os **principais indicadores** de cada loja.
- Gere o **OnePage** personalizado para cada gerente.
- Envie por e-mail o **OnePage no corpo da mensagem** e os dados completos da loja em anexo.
- Dispare um relatório especial para a diretoria com **rankings diários e anuais**.

---

## 🛍️ Cenário
Você é Analista de Dados de uma rede com **25 lojas espalhadas pelo Brasil**.  
Todas as manhãs, a equipe de análise prepara e envia o **OnePage** de cada loja — um **resumo visual** com:
- Comparações rápidas entre lojas.
- Indicadores diários e anuais.
- Status de metas (✅ ou ❌).

---

## 📂 Estrutura e Arquivos Importantes
- **Emails.xlsx** → Nome, loja e e-mail de cada gerente (use seu e-mail para testes).
- **Vendas.xlsx** → Registro de vendas de **todas as lojas** (cada gerente recebe apenas os dados da própria loja).
- **Lojas.csv** → Lista com o nome de todas as lojas.
- **Saída** → Planilhas geradas para cada loja, salvas em sua pasta específica com **data no nome** para manter histórico.

---

## 📈 Indicadores Calculados
- **Faturamento**  
  - Meta Ano: 1.650.000  
  - Meta Dia: 1.000  
- **Diversidade de Produtos** (quantidade de produtos diferentes vendidos)  
  - Meta Ano: 120  
  - Meta Dia: 4  
- **Ticket Médio por Venda**  
  - Meta Ano: 500  
  - Meta Dia: 500  

📌 *Todos os indicadores são calculados para o dia mais recente e para o acumulado do ano.*

---

## 📤 Envio de E-mails

### Gerentes de Loja
Cada gerente recebe:
- O **OnePage** da sua própria loja **no corpo do e-mail**.  
- Uma **planilha em anexo** contendo apenas os dados da sua loja.  
> ⚠️ Importante: **não é enviado informações de outras lojas**.

### Diretoria
A diretoria recebe:
- **Dois rankings em anexo**:  
  1. Ranking diário das lojas.  
  2. Ranking anual das lojas.  
- No corpo do e-mail, destaques sobre:  
  - Melhor e pior loja do dia.  
  - Melhor e pior loja do ano.

---

## 💡 Diferenciais
✔ Totalmente automatizado.  
✔ Proteção de dados — cada gerente recebe **somente** suas informações.  
✔ Histórico organizado por pastas e datas.  
✔ Indicadores claros e objetivos.  
✔ Fácil adaptação para outros cenários e empresas.

---

## 🚀 Como Executar
1. Clone o repositório.
2. Adicione os arquivos **Emails.xlsx**, **Vendas.xlsx** e **Lojas.csv** à mesma pasta do notebook.
3. Abra o **Jupyter Notebook** chamado `Automacao de Processo.ipynb`.
4. Execute as células do notebook **na ordem**.
5. Observe a mágica acontecer ✨: os OnePages serão gerados, os e-mails enviados e os backups organizados automaticamente.

---

## 📜 Licença
Este projeto é de uso livre para fins educacionais e pode ser adaptado para diferentes realidades empresariais.

---

💌 Automatizar não é só ganhar tempo. É garantir que o tempo seja usado para o que realmente importa.

