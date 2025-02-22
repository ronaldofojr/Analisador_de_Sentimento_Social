# Analisador_de_Sentimento_Social

## Descrição
É um projeto que realiza a coleta de tweets relacionados a um termo específico, seguido por uma análise de sentimentos para determinar se os tweets possuem tom **positivo**, **negativo** ou **neutro**. Além disso, os resultados são visualizados por meio de gráficos para facilitar a interpretação.

## Funcionalidades
- Coleta de tweets utilizando a API do Twitter.
- Análise de sentimentos com classificação em positivo, negativo e neutro.
- Visualização de resultados com gráficos interativos.

## Tecnologias Utilizadas
- **Python**: Linguagem principal do projeto.
- **Tweepy**: Biblioteca para acessar a API do Twitter.
- **TextBlob**: Biblioteca para processamento de linguagem natural (NLP).
- **Pandas**: Manipulação e análise de dados.
- **Matplotlib/Seaborn**: Visualização de dados.

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/ronaldofojr/Analisador_de_Sentimento_Social.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd Analisador_de_Sentimento_Social
   ```
3. Crie um ambiente virtual e ative-o:
   ```bash
   python -m venv venv
   source venv/bin/activate # Linux/Mac
   venv\Scripts\activate   # Windows
   ```
4. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Uso
1. Configure as chaves de acesso da API do Twitter no arquivo `config.py`:
   ```python
   api_key = "SUA_API_KEY"
   api_secret = "SEU_API_SECRET"
   access_token = "SEU_ACCESS_TOKEN"
   access_token_secret = "SEU_ACCESS_TOKEN_SECRET"
   ```

2. Execute o script principal:
   ```bash
   python main.py
   ```

3. Insira o termo de busca e veja os resultados da análise de sentimentos.



