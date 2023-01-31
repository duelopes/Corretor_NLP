# **Corretor_NLP**

Com a ajuda da **Plataforma Alura**, foi feito um corretor ortográfico utilizando técnicas de tokenização de texto com o NLTK, uma das principais bibliotecas Python para NLP.

A ideia do primeiro corretor é corrigir os seguintes casos:
- Casos com uma letra a menos;
- Casos com letra a mais;
- Casos que precisam de trocas de letras;
- Caso de letras invertidas;

Depois foi codificado um segundo corretor para casos que se encaixam em mais de uma situação acima, como no caso de ter uma letra a mais e invertida por exemplo.

Foi feita a avaliaçâo de desempenho dos dois corretores com base nos arquivos de palavras. E o resultado foi melhor no primeiro corretor.
<img src="https://github.com/duelopes/Corretor_NLP/blob/main/Resultado.png" alt="Resultado"/>
O motivo desse resultado é que o segundo corretor acaba criando novas palavras que existem no vocabulário e que pode ser mais frequente, corrigindo de forma equivocada. 

## Diferença desempenho:
### *Primeiro corretor - 75.81% de 186 palavras*
<img src="https://github.com/duelopes/Corretor_NLP/blob/main/Desempenho_primeiro_corretor.png" alt="Primeiro_Resultado"/>

### *Segundo corretor - 55.38% de 186 palavras*
<img src="https://github.com/duelopes/Corretor_NLP/blob/main/Desempenho_segundo_corretor.png" alt="Segundo_Resultado"/>

