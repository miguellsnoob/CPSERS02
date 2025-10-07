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

## Datasets sugeridos nas instruções originais
- Solar Radiation Prediction Dataset — Kaggle: https://www.kaggle.com/datasets/dronio/SolarEnergy
- Wind Turbine SCADA Dataset — Kaggle: https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset

## Como transformar isso em um repositório GitHub
1. Inicialize git:
   ```bash
   cd deliverable_repo
   git init
   git add .
   git commit -m "Entrega: notebooks e dados iniciais"
   ```
2. Crie um repositório no GitHub (via web) e conecte o remoto:
   ```bash
   git remote add origin git@github.com:SEU_USUARIO/NOME_DO_REPO.git
   git branch -M main
   git push -u origin main
   ```

## Observações finais
- Os notebooks fornecidos são *prontos para uso*, mas podem precisar de ajustes de nomes de colunas dependendo do CSV exato.
- Se quiser, eu posso:
  - Executar o notebook aqui (se me autorizar a instalar dependências e executar treinos).
  - Gerar relatórios gráficos (ex.: comparação de modelos).
  - Ajudar a criar o repositório remoto no GitHub (preciso que você me dê permissão/OAuth e me instrua — eu **não** posso subir direto sem credenciais**).

