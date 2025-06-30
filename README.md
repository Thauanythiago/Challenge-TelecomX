# 📊 Challenge Telecom X - Análise de evasão de clientes (churn)

## Sobre o projeto
Este projeto tem como objetivo analisar os dados dos clientes da operadora fictícia Telecom X e entender os fatores relacionados à evasão (churn). A análise envolve o tratamento dos dados, geração de métricas e visualizações exploratórias, com o propósito de fornecer insights que ajudem a reduzir a saída de clientes.
O desafio foi proposto como parte prática da formação "Aprendendo a fazer ETL" da Trilha de Data Science da Alura.

## Objetivos da Análise
- **Importação e preparação dos dados**: Extração de informações via API, normalização do JSON e limpeza.
- **Criação de métricas derivadas**: Cálculo da coluna de custo diário (`Contas_Diarias`).
- **Padronização de variáveis**: Conversão de respostas binárias ("Yes"/"No") para 1 e 0.
- **Exploração do churn**: Análises por gênero, faixa etária, tipo de contrato, serviços contratados, forma de pagamento, tempo de permanência e custo mensal.
- **Geração de insights e recomendações**: Identificação de padrões e sugestões práticas para retenção.

## Tecnologias utilizadas

<div style="display: flex; flex-wrap: wrap; gap: 10px;">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
<img src="https://img.shields.io/badge/Seaborn-4C4C9D?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn">
<img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white" alt="Google Colab">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">

</div>

## Resultados

Durante a análise, diversos padrões importantes foram identificados:

- **Clientes com contrato mensal** têm taxas de evasão significativamente mais altas, sugerindo pouca fidelização.
- **Pagamentos por Electronic Check** estão fortemente associados ao churn, enquanto métodos como débito automático demonstram maior retenção.
- **Idosos** possuem uma taxa de churn de 41,7%, quase o dobro da taxa observada entre clientes mais jovens.
- **Clientes que contratam menos serviços** ou utilizam apenas o serviço básico apresentam maior risco de cancelamento.
- Há uma tendência de maior churn entre clientes com **custos mensais e diários mais elevados**, indicando que o preço pode ser um fator de insatisfação.
- A **quantidade de serviços contratados** mostrou relação inversa com o churn: quanto mais serviços, menor a evasão.

Esses padrões ajudaram a construir sugestões práticas para manter os clientes por mais tempo e melhorar sua relação com a empresa.

## 💡 Recomendações

Com base nos insights da análise, foram feitas as seguintes sugestões:

- Incentivar a migração para contratos anuais ou bienais, com benefícios associados.
- Criar campanhas específicas para **novos clientes**, especialmente nos primeiros meses.
- Oferecer pacotes promocionais ou combos que aumentem o engajamento com serviços adicionais.
- Direcionar ofertas personalizadas para clientes com **alto custo mensal**, promovendo equilíbrio entre valor pago e percebido.
- Estimular a utilização de métodos de pagamento mais estáveis (ex: débito automático).

> 📘 **[Acesse a análise completa no notebook](https://github.com/Thauanythiago/Challenge-TelecomX/blob/main/TelecomX_Challenge.ipynb)**

> 📊 Todos os gráficos estão salvos em formato `.png` na [pasta de imagens do repositório](https://github.com/Thauanythiago/Challenge-TelecomX/tree/main/imagens).
## 

## 👤 Autor
Desenvolvido por Thauany Eugenia Thiago como parte dos estudos na Alura e do programa ONE - Oracle Next Education.\
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thauany-eugenia-thiago-629048203)
