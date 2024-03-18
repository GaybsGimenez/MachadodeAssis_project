# Projeto MachadodeAssis

Este projeto de estudo que foca nas bibliotecas NLTK e spaCy utilizando o corpus das obras de Machado de Assis.

## Funcionalidades Implementadas:

1. **Pré-processamento do Texto:**
   - Limpeza do corpus com NLTK, incluindo:
     - Seleção apenas de caracteres não alfanuméricos e padronização para letras minúsculas.
     - Remoção de stopwords.
     - Junção dos tokens novamente em formato de texto.
   - Tokenização.
   - Contagem de frequência.
   - Plotagem do gráfico de frequência.

2. **Concordânciador Simples:**
   - Divisão com método split, gerando um array de strings.
   - Utilização da função concordance().

3. **Similaridade:**
   - Identificação de palavras que tendem a ocorrer no mesmo contexto.

4. **Bigramas:**
   - Análise da ocorrência de palavras ao longo de todo o texto, incluindo a posição na lista em que a palavra aparece.

5. **Comparação com Outra Obra do Mesmo Autor:**
   - Utilização de POS-tagging para a etiquetagem morfossintática de cada palavra do corpus.
   - Análise comparativa entre duas obras.

6. **Gráficos:**
   - Utilização da biblioteca matplotlib.pyplot para estatística descritiva.
   - Criação de gráficos de barras simples.
   - Criação de dicionário de ocorrência.
   - Identificação de entidades nomeadas (NER) com spaCy.

