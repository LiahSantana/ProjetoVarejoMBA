# 🛒 Análise de Cesta de Compras (Market Basket Analysis)  

## 📌 Sobre o Projeto  

Este projeto tem como objetivo realizar uma **Análise de Cesta de Compras (Market Basket Analysis)** para identificar padrões de compra e relações significativas entre produtos vendidos no varejo.  

Utilizando **Regras de Associação**, extraímos insights valiosos sobre os hábitos dos consumidores, permitindo a otimização de estratégias como **recomendações de produtos, organização de layout de loja e campanhas de marketing direcionadas**.  

Utilizei o **Algoritmo Apriori**, que identifica **conjuntos frequentes de itens (frequent itemsets)** e gera regras baseadas em suporte, confiança e lift, permitindo uma análise detalhada do comportamento de compra dos clientes.  

---

## 🚀 Tecnologias Utilizadas  

✅ **Jupyter Notebook** → Desenvolvimento do código e análise exploratória dos dados.  
✅ **Python** → Manipulação de dados e implementação do **Algoritmo Apriori**.  
✅ **Google Cloud & BigQuery** → Armazenamento e processamento de dados em larga escala.  
✅ **SQL** → Extração, transformação e modelagem dos dados.  
✅ **Star Schema** → Estruturação do banco de dados para otimização de consultas analíticas.  

---

## 🔍 Etapas do Projeto  

1️⃣ **Coleta e Armazenamento de Dados**  
- Os dados transacionais foram armazenados no **Google BigQuery**, garantindo escalabilidade e performance nas consultas.  
- Aplicação de **Star Schema**, modelando as tabelas para facilitar a análise das transações.  

2️⃣ **Pré-processamento dos Dados**  
- Extração dos dados brutos utilizando **SQL**.  
- Tratamento e organização dos dados no **Jupyter Notebook com Python**.  
- Estruturação das transações para aplicação do **Algoritmo Apriori**.  

3️⃣ **Extração de Regras de Associação**  
- Aplicação do **Algoritmo Apriori** para identificar padrões de compra.  
- Cálculo das métricas **suporte, confiança e lift** para definir a relevância das regras.  
- Geração de regras do tipo:  
  - "Clientes que compram **café** têm alta probabilidade de comprar **leite**."  
  - "Compradores de **arroz** frequentemente compram **feijão** juntos."  

4️⃣ **Análise e Visualização dos Resultados**  
- Interpretação das regras de associação geradas.  
- Identificação de oportunidades estratégicas para o varejo.  

---

## 📈 Resultados e Benefícios  

🔹 **Descoberta de padrões de compra** para otimização de vendas.  
🔹 **Melhoria no cross-selling**, sugerindo produtos frequentemente comprados juntos.  
🔹 **Aprimoramento da disposição dos produtos** nas prateleiras e e-commerce.  
🔹 **Tomada de decisões baseada em dados** para campanhas promocionais mais eficazes.  


