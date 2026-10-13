# Análise de viagens a serviço do governo federal em 2025

Análise dos gastos com viagens a serviço do governo federal brasileiro em 2025, usando dados públicos do Portal da Transparência.

## Perguntas respondidas
1. Quanto foi gasto no total?
2. Quais órgãos mais gastaram?
3. Quais são os destinos mais visitados?
4. Qual é o gasto médio por viagem e quais viagens fogem do normal?
5. Como o gasto varia ao longo do ano?

## Principais resultados
- As viagens realizadas custaram cerca de **2,48 bilhões de reais** (gasto líquido).
- O **Ministério da Justiça e Segurança Pública** concentra cerca de um terço do gasto.
- **Brasília** é o destino mais frequente, seguida por São Paulo e Rio de Janeiro.
- A viagem típica custa cerca de **1,4 mil reais** (mediana), mas poucas viagens muito caras elevam a média para **3,1 mil**.
- **Janeiro** é o mês de maior gasto e **fevereiro** o de menor.

## Método
- Foram analisadas apenas as viagens **realizadas** (cerca de 99% do total).
- Gasto líquido = diárias + passagens + outros gastos - devolução.

## Ferramentas
Python, pandas e Google Colab.

## Como reproduzir
1. Baixe o arquivo de viagens de 2025 no Portal da Transparência (seção Download de dados > Viagens).
2. Salve o arquivo `2025_Viagem.csv` no seu Google Drive.
3. Abra o notebook `analise_viagens_portal_transparencia.ipynb` no Google Colab.
4. Ajuste o caminho do arquivo na célula de leitura e execute todas as células.

## Limitações
- A coluna `Cargo` tem cerca de 305 mil valores vazios.
- Cerca de 14% das viagens têm destino em sigilo.
- Viagens com vários destinos contam como um destino único no ranking.
- As viagens não realizadas ficaram fora da análise.

## Próximos passos
- Cruzar com as tabelas de passagens, pagamentos e trechos.
- Contar cada cidade separadamente nas viagens com vários destinos.

## Autora
Cauane Brenda dos Santos Silva
[GitHub](https://github.com/ccaauu) | [LinkedIn](https://www.linkedin.com/in/cauane-silva)
