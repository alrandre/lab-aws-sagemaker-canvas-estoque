# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

### 1. Selecionar Dataset
- O dataset selecionado para o upload no SageMaker Canvas foi o "dataset-500-curso-sagemaker-canvas-dio.csv" da pastas "datasets".

### 2. Construir/Treinar

-   No SageMaker Canvas, após a importação do dataset, o modelo foi configurado com o seguinte parâmetro:
-   Target Columns: QUANTIDADE_ESTOQUE

### 3. Analisar
Métricas do modelo:
- avg wql = 0.086
- mape = 0.045
- wape = 0.151
- rmse = 1.423
- mase = 0.000

### 4. Prever
O modelo gerou previsões que podem ser rotuladas da seguinte maneira:
- Pessimistas (Percentil 10)
- Normais (Percentil 50)
- Otimistas (Percentil 90)
O item 25 foi rpevisro como um produto sem demanda devido ao seu esgotamento de estoque sem reposição por um longo período de tempo. 
