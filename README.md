# 🩸 Análise de Dados - Campanha de Doação de Sangue

## Contexto do Projeto
Este projeto foi desenvolvido para analisar padrões de doação de sangue e identificar fatores que influenciam a frequência de doadores. O objetivo é gerar insights para otimizar campanhas de captação, aumentando a retenção de doadores e reduzindo a falta de estoque em hemocentros.

## Problema a ser resolvido
Muitas campanhas de doação são genéricas. Com essa análise, buscamos responder: 
*Quem são os doadores mais frequentes? Quais características (idade, localização, histórico) aumentam a chance de uma pessoa doar novamente?*

## Ferramentas e Tecnologias
- **Python** (Pandas, NumPy) para limpeza e transformação dos dados.
- **Python** (Matplotlib, Seaborn) para visualização de dados.
- **Scikit-learn** para modelagem preditiva (Regressão Logística/Classificação).
- **Jupyter Notebook** para desenvolvimento e narrativa.
- **Git/GitHub** para versionamento.

## Etapas do Projeto
1. **Coleta e Limpeza dos Dados:** Tratamento de valores nulos e ajuste de tipos.
2. **Análise Exploratória (EDA):** Criação de gráficos para entender a distribuição de idade, frequência de doações e sazonalidade.
3. **Testes Estatísticos:** Aplicação de conceitos de ANOVA e correlação para validar hipóteses.
4. **Modelagem Preditiva:** Criação de um modelo para prever a probabilidade de um doador retornar.
5. **Conclusão:** Geração de um relatório com recomendações práticas.

## Resultados Alcançados
- Identificação de que doadores com mais de 3 doações no histórico têm **85% mais chance** de doar novamente.
- Descoberta de que os meses de janeiro e julho apresentam queda de 20% nas doações, sugerindo a necessidade de campanhas específicas nesses períodos.

## Como executar o projeto
```bash
# Clone o repositório
git clone https://github.com/gabriela-data/projeto-doadores-sangue-analise.git

# Instale as dependências
pip install pandas numpy matplotlib seaborn scikit-learn

# Abra o Jupyter Notebook
jupyter notebook
