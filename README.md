# Análise 1: Análise de picos de buscas
## 1) Qual é a análise:
Análise de picos de buscas

## 2) Motivação da análise
Entender as variações de quantidade de buscas ao longo do tempo, para identificar possíveis tendencias ou comportamentos padrão, podendo suportar melhor altas quantidades de buscas.

## 3) Como executar
Fazer um levantamento de eventos de busca por dia e hora, relacionando com variáveis de data de ida (quantos dias antes da viagem é feita a busca em média) para poder prever picos antes de datas de alto volume de procura.

# Análise 2: Análise da região de partida com mais buscas
## 1) Qual é a análise:
Análise da região de partida com mais buscas

## 2) Motivação da análise
Motivo: Entender quais são as regiões (aeroportos de ida) com maior procura, para otimizar campanhas regionalizadas

## 3) Como executar
Cruzamento de dados entre maiores quantidades de buscas (aeroportos) por dias da semana e dia do mês.

# Análise 3: Análise de performance das buscas
## 1) Qual é a análise:
Análise de performance das buscas

## 2) Motivação da análise
Motivo: Demonstrar a eficiência do serviço e suas vantagens, mostrar a transparência das buscas e mostrar em quantas ocasiões a MM é mais vantajosa

## 3) Como executar
Extrair histogramas e médias dos dados de quantidade de voos, quantidades mais baratos e etc

# Análise escolhida: 1 - Análise de picos de buscas
## Levantamento de hipóteses
### Hipótese 1 - Quantidade de buscas são maiores em dias de semana
Analisando a quantidade de registros por dia da semana, podemos ver que a quantidade é maior nos dias de semana (Segunda a sexta), sendo especialmente maior nas segundas feiras, como mostrado no gráfico
![dias da semana](https://user-images.githubusercontent.com/46407752/50975167-0b7eea80-14d4-11e9-8872-7cd8de6d1156.PNG)
Podemos ver que sabado e domingo tem uma diferença que chega a aproximadamente 28% menos buscas que nas segundas feiras
![dif semana](https://user-images.githubusercontent.com/46407752/50975359-847e4200-14d4-11e9-8cee-d7f9a4176201.PNG)
### Hipótese 2 - Buscas são feitas para viagens com muita antecedência
Fazendo um gráfico com a quantidade de dias anterior a busca e a quantidade de buscas, podemos ver que a maior quantidade se concentra em viagens até 10 dias antes, com um pico em 20 dias. Dessa forma, podemos entender que a maior parte do público do site busca por passagens **"de última hora"**
![image](https://user-images.githubusercontent.com/46407752/50976778-f5732900-14d7-11e9-9993-3a0c0ab0a52d.png)
### Hipótese 3 - Datas comemorativas tem maiores quantidades de busca
Podemos ver pelo gráfico abaixo, que as datas próximas a 28/02/2017 - Carnaval, tem uma concentração maior de buscas, sendo dia 24 a maior concentração, por ser uma sexta feira pré carnaval.
![image](https://user-images.githubusercontent.com/46407752/50977439-6e26b500-14d9-11e9-8b00-91fc895f8387.png)
### Hipótese 4 - Os comportamentos das hipóteses 2 e 3 ocorrem ao mesmo tempo
Pela gráfico abaixo, podemos ver que esses comportamentos ocorrem ao mesmo tempo, fazendo com que o número de buscas seja muito maior poucos dias antes de uma data comemorativa.
![image](https://user-images.githubusercontent.com/46407752/51002296-fc229000-1519-11e9-95b0-ef2bcb2d053c.png)

### Hipótese 5 - Horário comercial é o horário que tem maior volume de buscas

