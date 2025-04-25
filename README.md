![Capa do projeto](A_digital_graphic_design_banner_titled_PREVISÃO_D.png.png)

# Previsão de Cancelamento de Clientes (Churn)

Este projeto tem como objetivo prever o cancelamento de clientes (churn) de uma empresa de telecomunicações, utilizando técnicas de machine learning. O foco foi identificar perfis com maior risco de churn e entender os fatores que mais influenciam a decisão de permanência ou saída do cliente.

---

## Objetivos

- Prever clientes propensos ao cancelamento
- Analisar as principais características que influenciam o churn
- Testar e comparar diferentes modelos de machine learning
- Interpretar os resultados com foco em negócios e tomada de decisão

---

## Sobre os dados

- **Fonte**: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Registros**: 7043 clientes
- **Atributos**: gênero, contrato, serviços, cobrança, etc.
- **Alvo**: Churn (Sim/Não)

---

## Técnicas e ferramentas utilizadas

- Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- Modelos de ML: `Logistic Regression`, `Decision Tree`, `Random Forest`
- Métricas de avaliação: `Accuracy`, `Recall`, `F1-score`, `Confusion Matrix`
- Visualizações: gráficos e heatmaps
- Interpretação: `Feature Importance`

---

## Comparação de modelos

| Modelo              | Acurácia | Recall Churn | F1-score Churn |
|---------------------|----------|--------------|----------------|
| Regressão Logística | 78.75%   | **0.52**     | **0.56**       |
| Árvore de Decisão   | 72.49%   | 0.52         | 0.50           |
| Random Forest       | 78.54%   | 0.48         | 0.54           |

**Modelo escolhido**: Regressão Logística (melhor equilíbrio entre desempenho e interpretabilidade).

---

## Principais insights

**Fatores que mais aumentam o risco de churn:**
- Internet via fibra óptica
- Cobrança digital (Paperless Billing)
- Pagamento com cheque eletrônico

**Fatores que indicam fidelidade:**
- Contrato de 2 anos
- Pagamento automático via cartão
- Serviços como segurança online e suporte técnico

---

## Conclusão

Este projeto demonstrou como aplicar Machine Learning para prever churn de clientes com boa performance e interpretar os resultados com clareza para o negócio. Com os insights gerados, é possível agir de forma estratégica para reduzir cancelamentos e aumentar a retenção de clientes.

---

## Sobre o autor

**Ernany Cunha do Amaral**  
Graduando em Economia e Marketing, une visão estratégica de negócios com formação analítica. É sócio-fundador de uma empresa de serviços de backoffice, onde lidera o desenvolvimento de soluções com inteligência artificial para automatização do atendimento e ganho de eficiência operacional.  
Atua com foco em projetos de dados aplicados à realidade do mercado, com interesse em aliar ciência de dados e decisões de negócio para gerar impacto real.

🔗 GitHub: [github.com/Ernany34](https://github.com/Ernany34)  
LinkedIn: [linkedin.com/in/ernanyamaral](https://www.linkedin.com/in/ernanyamaral/)

---

📄 [Baixe o PDF com o projeto completo](Projeto_Churn_Ernany.pdf)
💻 [Acesse o notebook com o código completo](projeto_churn_telecom.ipynb)

