# Estudo de Caso 03
## Dashboard de Vendas, Custo, Margem de Lucro & KPI
#### Definição do Problema de Negócio

Reproduzir o dashboard abaixo:
<br>
<img height="450" src="https://github.com/romulovieira777/Power_BI_Data_Science_Academy_2.0/blob/master/Cap%C3%ADtulo%2004/Exercicio.png"/>
</br>

Sua fonte de dados é um [arquivo CSV](https://github.com/romulovieira777/Power_BI_Data_Science_Academy_2.0/blob/master/Cap%C3%ADtulo%2004/Custos.csv)
| Coluna | Descrição |
| ------ | --------- |
| Data	| Data de vendas |
| Produto	| ID do produto |
| Serial number	| Número serial |
| Valor de venda	| Valor de venda do produto |
| Preço custo	| Preço de custo do produto |
| Duração Venda | Telefone (mins)	Duração da venda em minutos via telefone |
| Tempo Preparação (mins)	| Tempo de preparação para venda em minutos |

Os gráficos a serem apresentados serão:

1. Média de Vendas
2. Valor de Venda X Preço de Custo
3. Margem de Lucro por Produto
4. KPI - Meta de Margem de Lucro

Para construir o gráfico foi utilizado duas funções DAX para calcular a média (Média de venda = (AVERAGE(CustosGeral[Valor de Venda])), já para a Margem de Lucro
(Margem de Lucro = 1 - (DIVIDE(CustosGeral[Preço Custo],CustosGeral[Valor de Venda],0)))

## Dashboard Construído
[Arquivo Power BI](https://github.com/romulovieira777/Power_BI_Data_Science_Academy_2.0/blob/master/Cap%C3%ADtulo%2004/Cap04-Proj03.pbix)

**Visão Geral**
<br>
<img height="480" src="https://github.com/romulovieira777/Power_BI_Data_Science_Academy_2.0/blob/master/Cap%C3%ADtulo%2004/Estudo%20de%20Caso%2003.png"/>
</br>
