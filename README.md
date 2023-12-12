# Gráfico de Pipeline no Databricks

## Aluno: Vinícius Oliveira Fernandes
## Professor: Afonso Brandão 

### Dashboard

![image (33)](https://github.com/Vfernandes1/teste_de_hipotese_automatico_M-C_Solutions/assets/99264567/c83629cf-9c9e-47d3-9f6c-da1323f4f422)

### Gráficos plotados

1. Venda de Arroz e Carne por Estado: Este é um gráfico de barras verticais que mostra a venda total de arroz e carne em diferentes estados, indicados pelas siglas dos estados no eixo X. SP tem as vendas mais altas, seguido por RJ e MG. Podemos inferir que esses estados possuem uma demanda maior, possivelmente devido à sua população ou preferências alimentares.

2. Desvio Padrão da Taxa de Inflação nas Vendas em SP: Este é um medidor que indica o desvio padrão da taxa de inflação nas vendas em SP de 0.19.

3. Soma da Renda Total dos Moradores por UF: É um gráfico de barras verticais mostrando a soma total da renda dos moradores por unidade federativa. São Paulo lidera novamente, o que pode estar correlacionado com as altas vendas observadas no primeiro gráfico.

4. Taxa Selic x Vendas dos Produtos: Este é um gráfico linear com produtos no eixo X e a taxa selic no Y. Todos os produtos foram vendidos em uma época de taxa constante, sugerindo estabilidade nas vendas desses itens específicos ao longo do tempo, e que não houve variação determinante na Selic no tempo em que estes produtos foram vendidos.

5. Média de calorias no Consumo Alimentar por semana: É um gráfico de barras horizontais com os dias da semana no eixo X e as calorias médias consumidas no Y. O consumo calórico parece ser consistente ao longo da semana, sem picos significativos ou quedas.

Exemplos de Inferências feitas nos gráficos 3 e 4: A alta renda total em SP pode ser uma razão para as elevadas vendas neste estado; há uma correlação visível aqui. A estabilidade na taxa selic das vendas dos produtos sugere que não houve eventos significativos ou mudanças nos padrões de compra durante o período analisado.

## Segue alguns outros gráficos realizados pelo grupo no Metabase (de forma complementar), e suas inferências

### Gráfico de Impacto do Dolár nas Vendas (Dados do Bacen + Dados da API do Cliente)

![image (32)](https://github.com/Vfernandes1/teste_de_hipotese_automatico_M-C_Solutions/assets/99264567/f2457912-2faa-4bbf-ae07-4c362f19d556)

O gráfico mostra o impacto do valor do dólar sobre as vendas. A linha no gráfico indica que, à medida que o valor do dólar aumenta (de 0 - 0,13 para 5,38 - 5,5), as vendas tendem a diminuir de um pouco acima de 50 para cerca de 40. Isso pode ser explicado pelo fato de que, quando o valor do dólar aumenta, os produtos se tornam mais caros para os consumidores, o que pode levar a uma diminuição nas vendas.

A sua visualização pode ser definida num gráfico linear com uma linha descendente. O eixo Y representa as vendas, variando de 0 a um pouco acima de 50. O eixo X representa o valor do dólar em diferentes intervalos. Há sete pontos no gráfico indicando diferentes valores das vendas em relação aos valores específicos do dólar. A cor da linha é roxa com marcadores circulares nos pontos de dados.

### Mediana de preço por produto em rondonia

![image (32)](https://github.com/Vfernandes1/teste_de_hipotese_automatico_M-C_Solutions/assets/99264567/f64c5602-8ed0-4f84-9d12-713e4fc49541)

O gráfico mostra a mediana de preço para diferentes produtos em Rondônia. Os produtos listados são: Arroz, Açúcar, Batata Palha, Carne, Cerveja, Feijão, Ketchup, Macarrão, Molho de Tomate e Queijo. As medianas de preço variam para cada produto. As medianas de preço variam para cada produto. Podemos ver que a cerveja e o molho de tomate têm os preços medianos mais altos entre os produtos listados, enquanto a basta plástica tem um dos preços medianos mais baixos. Isso pode ser útil para os consumidores que desejam comparar preços entre diferentes produtos.

O tipo utilizado foi o de barras, com o propósito de visualizar a mediana da melhor mais possível. O eixo X é rotulado como “Produto” e lista dez produtos diferentes. O eixo Y é rotulado como “Mediana de Preço” e mostra uma escala de 0 a 700. Cada barra representa a mediana de preço de cada produto em Rondônia. As barras para Cerveja e Molho de Tomate são as mais altas, indicando que têm os preços medianos mais altos entre os produtos listados. A barra para Basta Plástica é notavelmente mais curta do que as outras, mostrando que tem um dos preços medianos mais baixos.

Aqui está a tabela com as medianas de preço para cada produto:

| Produto          | Mediana de Preço |
|-------------------|-------------------|
| Arroz             | 20                |
| Açúcar            | 5                 |
| Carne             | 30                |
| Cerveja           | 700               |
| Feijão            | 15                |
| Ketchup           | 5                 |
| Macarrão          | 10                |
| Molho de Tomate   | 700               |
| Queijo            | 50                |
