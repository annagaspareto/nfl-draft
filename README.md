# Análise de Dados - NFL: Draft, Seleções All-Pro e Talentos Universitários

Neste repositório, realizo uma análise detalhada sobre o desempenho dos jogadores de futebol americano profissional, com foco no Draft da NFL, nas seleções All-Pro e nas universidades responsáveis pela formação de estrelas da liga. Utilizando dados históricos obtidos do [Pro Football Reference](https://www.pro-football-reference.com), busquei revelar padrões e insights sobre o impacto da posição no Draft, a performance de jogadores ao longo de suas carreiras e como as universidades e franquias têm moldado o talento da NFL.

## Sumário

- [Objetivo](#objetivo)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Funciona a Análise](#como-funciona-a-análise)
- [Conclusões Principais](#conclusões-principais)

## Objetivo

O objetivo principal dessa análise foi entender como fatores como a posição no Draft influenciam o desempenho dos jogadores da NFL, em termos de seleções All-Pro, e identificar as universidades e franquias que mais contribuem para o talento da liga.

- **Draft e Seleções All-Pro**: Investiguei se existe uma correlação entre a posição em que os jogadores são selecionados no Draft e o número de seleções All-Pro que conseguem ao longo de suas carreiras.
  
- **Impacto das Universidades**: Estudei quais universidades mais contribuem com jogadores para a NFL e como elas têm dominado a produção de talentos, destacando o impacto da SEC, com destaque para Alabama e LSU.

- **Franquias de Destaque**: Analisei a evolução de franquias, como os Detroit Lions, que, apesar de um histórico de dificuldades, têm se destacado por sua capacidade de identificar futuros talentos.

## Tecnologias Utilizadas

- **Python**: Para análise de dados e execução de modelos estatísticos.
- **Pandas**: Para manipulação de dados.
- **Matplotlib e Seaborn**: Para visualizações dos dados.

## Como Funciona a Análise

A análise foi dividida em várias etapas:

1. **Coleta e Preparação dos Dados**: Utilizando dados históricos de Draft e seleções All-Pro de diversas fontes confiáveis, principalmente o [Pro Football Reference](https://www.pro-football-reference.com), os dados foram organizados e limpos para garantir que fossem consistentes e prontos para análise.

2. **Análise Estatística**: Realizei uma análise de regressão linear para verificar a correlação entre a posição no Draft e o número de seleções All-Pro. Também calculei os valores de R² e p-valor para testar a força da correlação.

3. **Visualizações**: Criei gráficos para ilustrar as distribuições das seleções All-Pro, destacando as posições mais valiosas, como wide receivers, cornerbacks e safeties. Também fiz uma análise das universidades que mais contribuíram para a NFL e das franquias que mais identificaram talentos de elite.

4. **Conclusões**: A análise mostrou que, embora haja uma tendência negativa entre a posição no Draft e o número de seleções All-Pro, essa correlação é fraca, sugerindo que o Draft nem sempre define o futuro sucesso de um jogador. Além disso, a SEC continua sendo uma potência na produção de talentos para a NFL.

## Conclusões Principais

- **Aaron Donald** se destacou como o modelo de consistência e excelência, acumulando 9 seleções All-Pro ao longo da última década.
  
- **Zack Martin, Joel Bitonio e Chris Jones** também se destacaram, com 8 e 7 seleções All-Pro, respectivamente, e consolidaram seu lugar entre os melhores da liga.

- **Padrões de Draft**: A posição no Draft tem um impacto mínimo nas seleções All-Pro, com apenas 5% da variação explicada pela posição em que o jogador foi selecionado.

- **Universidades**: Alabama segue firme como a principal fornecedora de talentos para a NFL, com 20 seleções All-Pro, enquanto LSU também tem mostrado sua força, com 12,5 seleções.

- **Franquias em Ascensão**: Os **Detroit Lions**, que por muito tempo foram uma franquia de baixo desempenho, se destacaram por sua capacidade de identificar jogadores All-Pro através do Draft, liderando essa métrica.
