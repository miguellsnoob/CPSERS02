# CP 02 Soluções em Energias Renováveis e Sustentáveis
# Miguel lima da silva RM:565141

## Estrutura do repositório
```
deliverable_repo/
├─ data/                      # datasets (coloque aqui os CSVs se não estiverem)
│  └─ appliances_extracted/    # conteúdo extraído do zip enviado
├─ notebooks/
│  ├─ regression_appliances.ipynb
│  └─ solar_wind_templates.ipynb
├─ README.md
└─ requirements.txt
```

## Como usar
1. Abra um terminal e navegue até a pasta `deliverable_repo`.
2. (Opcional) Crie um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate   # Windows
   ```
3. Instale dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   e rode `notebooks/regression_appliances.ipynb` e `notebooks/solar_wind_templates.ipynb`.

## Sobre o dataset (Appliances Energy Prediction)
- Arquivo fornecido: `energydata_complete.csv` (extraído para `data/appliances_extracted/`).
- Local de extração: `data/appliances_extracted/`
- A descrição e colunas variam conforme o CSV. Execute as primeiras células do notebook de regressão para inspecionar colunas e escolher o target (por exemplo, `Appliances`, `energy`, ou `Appliances energy (Wh)`).
- Métricas recomendadas para avaliação: **R²**, **RMSE**, **MAE**.



