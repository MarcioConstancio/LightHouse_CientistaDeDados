Este repositório faz parte do desafio Cientista de Dados do programa _Lighthouse_ da Indicium. Para conseguir rodar estes arquivos em seu computador, clone este repositório para sua máquina e, para evitar problemas com compatibilidade de versões, crie um ambiente virtual em seu computador. As instruções para a criação e a ativação de um ambiente virtual pode ser encontrada neste [link](https://docs.python.org/pt-br/3/library/venv.html).

Com o ambiente instalado e ativado, Instale as bibliotecas necessárias apresentadas no arquivo `requirements.txt`. Para isso, use o seguinte comando:

`pip install -r requirements.txt`

Neste projeto estão disponíveis os seguintes arquivos:

* `teste_indicium_precificacao.csv`: Arquivo fornecido pela Indicium para que fosse realizada a análise pedida. 
* `EDA.ipynb`: Análise exploratória dos dados fornecidos acima. Ao longo do arquivo vou discutindo os testes que foram feitos, mas os resultados principais já encontram-se resumidos no início da apresentação. 
* `Regressão.ipynb`: Arquivo onde testo diferentes métodos de regressão em busca de minimizar o erro. As métricas usadas aqui foram MAE e RMSE.  Neste arquivo, os diferentes modelos são testados por meio de _pipelines_, além da tunagem de hiperparâmetros dos modelos que apresentaram melhor resultado. 
*  `modelo.pkl`: O modelo final escolhido foi salvo por meio da biblioteca pickle.
*  `predict.ipynb`: Arquivo usado para carregar o modelo final e rodar o teste de estimativa de preço. 

Para rodar este modelo, basta abrir o arquivo `predict.ipynb` e fazer as alterações no campo identificado. 
