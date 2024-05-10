
<img width="223" alt="image" src="https://github.com/mstrulenque/imersao-ai_google-alura/assets/63933792/f707dbde-92ca-4906-8e94-561df7b3478e"> | <img width="232" alt="image" src="https://github.com/mstrulenque/imersao-ai_google-alura/assets/63933792/bb7ee96b-01e0-4b9e-b3a0-fa3eabb0d2cf">
---------|---------------
 
# DESAFIO


## Sobre o Desafio

Este desafio tem o objetivo de colocar em prática todos os aprendizados da `Imersão AI - Google e Alura`


## Sobre o Projeto

Ajudar a `locomoção no Rio Grande do Sul` através de `rotas alternativas` (estradas ainda trafegáveis) utilizando informações do Governo do Estado do Rio Grande do Sul/ Brigada Militar / Comando Rodoviário 

###OBS: Como é um projeto didático, as informações são parciais e os dados foram extraídos em 10/05/2024.


## Foram utilizados

- **Base Dados**: 
   - Arquivo CSV: Dados Governo Rio Grande do Sul / Brigada Militar / Comando Rodoviário
       
- **Google AI Generative**:
   - API Gemini, para:
      - Embedding - Dados
      - Embedding - Prompt
   - Model:
      - models/embedding-001
           - task-type:
               - RETRIEVAL_DOCUMENT
               - RETRIEVAL_QUERY
            
- **Bibliotecas**:
   - pandas: Importar e Tratar Dados CSV <br>
   - numpy: Produtos Escalares / Tratamento Embeds <br>
   - google.generativeai: Utilizacao do Gemini <br>
   - userdata: Recuperar Secrets do Google Colab <br>

---


- https://crbm.app.br/gestao-de-rotas/index.php?class=RotaCardList&method=onWhats&key=268
