# 📚 Distribuição por Quartil: Uma Análise Estatística de Oportunidades no Tesouro Direto
A teoria dos quartis foi descoberta por John Wilder Tukey, um estatístico americano que viveu de 1915 a 2000. J.W. Tukey foi um dos estatísticos mais influentes do século XX, e seus trabalhos tiveram um impacto significativo em muitas áreas da ciência, incluindo a medicina, a engenharia e a economia.
Autor de várias obras e de uma das frases mais importantes para amantes de análise de dados.
“Uma resposta aproximada para o problema certo vale muito mais do que uma resposta exata para um problema aproximado.”  John Wilder Tukey
# 📊 O Que São Quartis?
John Wilder Tukey desenvolveu a teoria dos quartis na década de 1960, como parte de seu trabalho sobre análise exploratória de dados. A análise exploratória de dados é um conjunto de técnicas usadas para entender e descrever conjuntos de dados, neste caso, os quartis são uma ferramenta importante para a análise exploratória de dados, pois permitem que os analistas identifiquem rapidamente a distribuição dos dados e as principais tendências.
Quartis dividem um conjunto de dados em quatro partes iguais, cada uma representando 25% dos dados.
•	O primeiro quartil (Q1) representa o limite entre os 25% menores valores e os 75% maiores valores.
•	O segundo quartil (Q2) é a mediana, dividindo os dados ao meio.
•	O terceiro quartil (Q3) separa os 75% menores valores dos 25% maiores valores.
# 📈 Importância na Análise Estatística Descritiva
Identificação de Outliers: Quartis ajudam a identificar valores extremos no conjunto de dados, os quais podemos a identificar valores atípicos que podem afetar negativamente um portfólio de investimentos.
Comparação entre Conjuntos: Comparar distribuições usando quartis revela diferenças significativas. Ao classificar fundos em quartis, é possível comparar seu desempenho relativo a outros fundos do mesmo grupo.
Tomada de Decisões: Auxiliam na compreensão da variabilidade dos dados, crucial para tomadas de decisões informadas.
Gestão de Riscos: Investidores usam quartis para entender a volatilidade dos investimentos, ajudando na gestão de riscos. Analisar investimentos através dos quartis proporciona uma base sólida para decisões informadas, contribuindo para estratégias de investimento bem fundamentadas.

# 💰 Análise Estatística Descritiva para o Tesouro Direto
Neste trabalho, foi criado códigos em python para tratamento dos dados dos títulos públicos brasileiros, com foco nas taxas e a avaliação de uma melhor compra com objetivo manter até o vencimento. Para isso, usamos quartis para avaliação da série histórica.
O código para análise foi construindo seguindo a sequência abaixo:
Instalação e importação de bibliotecas: Selecionamos as principais bibliotecas tanto para cálculos quanto para geração de gráficos.
Utilização da API do Tesouro Direto:  Com base no portal do Tesouro Direto, foi adaptado a busca automática através de uma API dos dados e cotações diárias dos títulos do tesouro. 
Organização do Dataframe: Após a recepção dos dados via API, organizamos os títulos com agrupamentos, seleção por vencimentos e tipo de títulos.
Limpeza e Tratamento dos Dados: Foi feito uma varredura em 134.862 linhas e 8 colunas para verificação de algum erro, valor nulo ou faltante e nada de anormal foi encontrado.
Seleção do Título: Em nosso estudo prático, foi selecionado o título TESOURO PREFIXADO, e com o vencimento em 2026. O foco desta análise foi buscar a melhor taxa de compra pela manhã, onde podemos entender que se o título foi adquirido com a maior taxa e mantido até o vencimento, trará bons ganhos a carteira do investidor. Sabemos que as taxas bem como o PU do título sofrem oscilações com a marcação a mercado e é neste sentido que a análise de quartis irá orientar o investidor no sentido de estar comprando um título “caro” ou “barato”, o que também podemos dizer como ativo descontado ou supervalorizado.
A taxa que estiver próxima a taxa máxima e/ou próxima ao Q3, trará melhor retorno a carteira do investidor.
Lembrando que este estudo pode ser feito para qualquer outro título e outro vencimento. Vale destacar também que não se trata de uma recomendação de compra ou de venda e rentabilidades passadas não garantem resultados futuros.
Criação de Gráfico: No período em questão, foi selecionado e plotado um gráfico onde podemos verificar a volatilidade do ativo no decorrer do tempo.
# ♟️ Calculando o melhor Quartil para melhor  compra: 
Quantidade analisada:	917
Média:	9,886423
Desvio Padrão:	2,301583
Taxa mínima:	5,810000
Q1:	7,450000
Q2:	10,300000
Q3	11,890000
Taxa Máxima:	13,840000
# 👍🏻 Agradecimentos
Por fim, agradeço a você que dedicou um tempo para conhecer este trabalho e deixo uma frase de Tuke.
“Uma resposta aproximada para o problema certo vale muito mais do que uma resposta exata para um problema aproximado.”  John Wilder Tukey
