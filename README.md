# Customer Segmentation - Exploratory Clustering (Marketing Analytics)

Este projeto e um estudo de caso de **exploratory clustering** para entender perfis de pedidos em um cenario de delivery
(pizza, bebida, salada e sobremesa) e apoiar decisoes de marketing. O foco e manter o pipeline simples, claro e
interpretavel.

## Por que clustering?
- Identificar perfis de consumo sem rotulos previos.
- Direcionar campanhas e combos por comportamento.
- Gerar hipoteses para validacao futura.

## O que temos aqui
- Notebook com EDA e 2 segmentacoes simples:
  - Segmentacao 1: Pizza x Sobremesa
  - Segmentacao 2: Pizza x Salada
- Avaliacao por WCSS (elbow) + Silhouette (amostrada para velocidade).
- Resumo executivo e tabelas de medias por cluster.

## Conclusao (exploratory)
- Existem perfis claros de volume (baixo vs alto) e de preferencia (pizza-heavy vs salada-heavy).
- Os clusters sao interpretaveis e suficientes para gerar acoes iniciais de marketing.
- Proximo passo: validar os clusters com margem/retorno por item antes de ativar campanhas.

## Como rodar
1. Garanta o arquivo `dataset.csv` na raiz do projeto (separador `;`).
2. Abra `Marketing-Analytics_Client_Clustering.ipynb`.
3. Execute as celulas em ordem.

## Estrutura (resumo)
- `Marketing-Analytics_Client_Clustering.ipynb` - analise principal
- `dataset.csv` - dados brutos (separador `;`)

## Observacoes
- Este e um estudo **exploratorio** (nao e modelo final de producao).
- A Silhouette e calculada por amostra para manter tempo de execucao baixo.
