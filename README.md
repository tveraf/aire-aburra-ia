# Agente de calidad del aire del Valle de Aburrá (SI3003 – Proyecto final)

MVP: modelo Naive Bayes propio (Parte 1) + agente LLM con RAG y herramientas (Parte 2) + dashboard en Streamlit.

## Estructura
- `src/probe_data.py`: verifica acceso a fuentes de datos (corre primero).
- `data/raw`: datos descargados (plan B en CSV).
- `docs/corpus`: documentos para el RAG (normativa, protocolos, recomendaciones de salud).
- `src/`: modelo, RAG, agente.
- `app/`: dashboard Streamlit.

## Ejecución (se completará al final)
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # y editar la clave
python src/probe_data.py
streamlit run app/app.py
```

## Fuentes de datos
(por documentar tras la verificación)

## Declaración de uso de IA generativa
(por completar: herramientas usadas y propósito)

## Limitaciones
No es consejo médico, legal ni de seguridad.
