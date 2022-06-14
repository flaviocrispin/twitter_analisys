# Análise de tweets sobre os principais candidatos a eleições brasileiras em 2022
Esses notebooks incluem análises de tweets sobre os principais candidatos a presidência do Brasil em 2022.
ISão várias etapas que vão desde a extração dos dados no twitter até uso de deep learning para encontrar os sentimentos dos tweets. 

## Passos
1. Extração dos tweets
  - Extração dos dados usando o Twint (sem limites de tweets)
  - Salvar no google drive
2. Transformação e limpeza dos dados
  - Carregamento dos dados
  - Exclusão de caracteres especiais (@:// e etc)
  - Stopwords
  - Conversão de emojis e emoticons em sentimentos
  - Stemmed
  - Tokenização
  - Salvar o novo DATAFRAME no google drive
3. Análise de sentimentos
  - Carregamento dos dados
  - Análise de sentimentos usando TextBlob
  - Análise de sentimentos usando Vader Sentiment
