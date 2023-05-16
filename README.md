# Análise de Dados em Python: Dataset Housing da Califórnia

## Descrição do Dataset:

_O dataset "Housing" foi criado a partir do censo de 1990 dos Estados Unidos e contém várias informações relacionadas à habitação em diferentes regiões da Califórnia. Abaixo temos os atibutos do dataset analisado:_

  - **Longitude:**  a longitude geográfica da localização da habitação.
  - **Latitude:** a latitude geográfica da localização da habitação.
  - **Housing_median_age:** a idade mediana das habitações em uma determinada área.
  - **Total_rooms:** o número total de quartos nas habitações.
  - **Total_bedrooms:** o número total de quartos nas habitações.
  - **Population:** a população da área onde a habitação está localizada.
  - **Households:** o número total de domicílios na área.
  - **Median_income:** a renda mediana dos domicílios na área.
  - **Median_house_value:** media dos valores do imóveis.



## Sobre a Análise dos Dados:

Para esta análise foi utilizado a linguagem Python com as seguintes bibliotecas:

**Pandas e  Numpy** para processamento dos dados.

**Matpotlib e Seaborn** para plotagem dos gráficos.

Ao analisar o dataset "Housing" da Califórnia, é possível obter alguns insights interessantes sobre a habitação no estado. 
Parte dos insights podem ser observados pelo método describe() na base principal  e pela análise gráfica com a seleção de alguns atriutos do dataframe. Com a aplicação de filtro com uso da bilioteca Pandas sobre as Latitudes e Longitudes foi possível selcionar algumas cidades do Estado da Califórnia afim de se fazer uma análise mais pontual, replicando os métodos usados antetiormente no dataset agregado.

Importante destacar que antes foi feito todo procedimento de boa prática , no intuito de se analisar a estutura dos dados, tais como valores repetidos, nulos ou redutantes.  Assim como veficação dos tipos de dados, quantidade de linhas e colunas coforme comandos executados no notebook Colab.

**Insights de destaque:**

Distribuição de Valores das Casas:

Os imóveis mais próximos ao litoral são os de maiores valores conforme mostra  gráfico dispersão do **Matplotlib** do Pandas.

Relação entre Renda e Valor das Casas:

 há uma correlação entre o atributo da **renda média (median_income)** e a váriavel preço **média dos imóveis (median_house_value)**,
 conforme o analise de correlação pelo método **corr()** do Pandas, onde esse valor é de **0.66**.

Características dos Domicílios:

Idade média dos imóveis que é de 28 anos com valores de variam de 1 ano até 52 anos. Valor médio do imóvel de U$ 206 mil.


Fonte dos dados:
https://drive.google.com/uc?id=15bz_HvryzxzVBbiwk3k1z-PhYrn0sxOZ











  







