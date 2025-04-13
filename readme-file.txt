# Agente de Clima com IA

Este aplicativo fornece informações de clima em tempo real e recomendações personalizadas usando GPT para sugerir roupas adequadas e configurações de temperatura para ar-condicionado com base nas condições climáticas atuais.

## Funcionalidades

- Busca de clima por CEP brasileiro
- Busca de clima por coordenadas (latitude e longitude)
- Visualização de dados meteorológicos atuais (temperatura, umidade, vento)
- Recomendações geradas por IA para:
  - Roupas adequadas para o clima atual
  - Temperatura ideal para o ar-condicionado em casa
  - Temperatura ideal para o ar-condicionado no carro

## Como usar

1. Digite seu CEP ou as coordenadas de latitude/longitude
2. Clique em "Buscar Clima"
3. Visualize as informações meteorológicas e recomendações da IA

## Tecnologias utilizadas

- Streamlit: Interface de usuário
- OpenAI API: Geração de recomendações personalizadas
- WeatherAPI: Dados meteorológicos em tempo real
- ViaCEP: Conversão de CEP para localidade

## Instalação local

Para executar este aplicativo localmente:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/agente-clima-ia.git
cd agente-clima-ia

# Instale as dependências
pip install -r requirements.txt

# Configure suas variáveis de ambiente
# Crie um arquivo .env com:
# OPENAI_API_KEY=sua_chave_openai
# WEATHER_API_KEY=sua_chave_weatherapi

# Execute o aplicativo
streamlit run app.py
```

## Licença

MIT
