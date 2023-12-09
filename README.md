# DataRenda_Insights
# Análise de Variáveis Qualitativas e Renda

## Introdução
Este projeto tem como objetivo analisar se as variáveis qualitativas "posse de imóvel" e "posse de veículo" podem ser consideradas boas preditoras da variável quantitativa "renda". Utilizei técnicas estatísticas e visualizações de dados para explorar essas relações.

## Passos Realizados

1. **Carregamento dos Dados:**
   - Utilizei o Pandas para carregar o conjunto de dados "previsao_de_renda.csv".

2. **Limpeza de Dados:**
   - Verifiquei e corrigi valores faltantes nas colunas numéricas preenchendo-os com a média.

3. **Visualização de Dados:**
   - Converti os valores booleanos de "posse_de_imovel" e "posse_de_veiculo" em rótulos categóricos.
   - Criei gráficos de ponto usando Seaborn para analisar as relações entre posse de veículo, posse de imóvel e renda.

4. **Teste t:**
   - Dividi o DataFrame em dois com base na posse de veículo ("Com Veículo" e "Sem Veículo").
   - Realizei um teste t para duas amostras independentes para comparar as médias de renda entre os dois grupos.

5. **Resultados:**
   - Imprimi estatísticas como a estatística t e o valor p.
   - Verifiquei a significância estatística usando um limiar comum de 0.05.

## Conclusões

Com base nos resultados do teste t, observamos que [explique os resultados e conclusões].

## Como Executar o Código
1. Certifique-se de ter o Python e as bibliotecas necessárias instaladas (pandas, seaborn, matplotlib, scipy).
2. Baixe o arquivo "previsao_de_renda.csv".
3. Execute o código Python, ajustando o caminho do arquivo conforme necessário.

---
