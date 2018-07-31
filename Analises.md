# Análise 1: Perfil Viajante

## 1) Qual é a análise:
    
    Análise para suportar demanda de busca por perfil de viagens frequentes.
    
## 2) Motivação da análise
    
    Analisando o log com os dados e ao navegar no site para encontrar uma passagem, entendi como oportuno para usuários cadastrados, a sugestão de uma melhor alternativa para uma rota frenquente utilização.

## 3) Como executar
    
    * Analisar quantificadores mais buscados de lugares, companhias e horários.
    * Cruzar informações com as melhores sugestões que chamo de padrões(default do site).
    * Exibir resultado entre o cruzamento das informações anteriores.
   
# Análise 2: Férias Família

## 1) Qual é a análise:
    
    Análise para impulsionar buscas em períodos de férias escolares.
    
## 2) Motivação da análise
    
    O período de férias escolares é uma oportunidade para divulgar passagens para clientes. O log de dados, contém quantificadores para criação de um modelo preditivo, sobre quem poderia ser alvo de campanhas de divulgação de passagens a serem utilizadas em períodos de férias escolares.
    

## 3) Como executar
    
    * Análise terá como primeiro críterio coluna "qtd_criancas" tenha dados quantificados maiores que zero.
    * Análisar destinos mais procurados no período de férias escolares.
    
# Análise 3: Companhia Cool

## 1) Qual é a análise:
    
    Análise para minimizar os riscos com companhias aéreas e evitar turnovers de clientes.
    
## 2) Motivação da análise
    
    Com o propósito de evitar turnovers e criar um ranking criterioso para sugerir um determinada companhia, a criação de uma análise, que possibilite uma auditoria inicial das companhias em aspectos interessantes para o negócio. Partindo do pressuposto, que as companhias mais solicitadas devem estar sobe olhar constante, a fim de ter sua qualidade aferida frenquentemente.
    

## 3) Como executar
    
    * A análise deve ordenar as companhias a partir das mais solicitadas "qtd_voos_recebidos". 
    * Deve ser estabelecida uma granularidade diária para um acompanhamento mais acertivo.
    * O agrupamento por aeroporto deve ser considerado para identificação dos locais analisados. 
    * Considerar a menor razão do produto da subtração entre "qtd_voos_recebidos" e "qtd_voos" para como sendo a melhor escolha.
     