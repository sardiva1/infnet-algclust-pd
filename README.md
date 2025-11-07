# NutricionistAI


### 1-Criar novo ambiente python
python -m venv infnet_nutricionistai_3118

### 2-Ativar ambiente python
infnet_nutricionistai_3118\Scripts\activate 

### 3-Instalar pacotes
pip install -r requirements.txt

### 4-Configurar arquivo .env
Criar arquivo .env no path src/nutricionist_agent com o conteúdo:
GOOGLEAI_API_KEY="********"

### 5-Rodar dashboard
streamlit run src/nutricionist_agent/app.py