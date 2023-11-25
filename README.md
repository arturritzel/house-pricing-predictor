# house-pricing-predictor
Este algoritmo realiza a previsão aproximada dos valores das casas em Boston com base em alguns fatores estruturais e sociais. Projeto utilizado como base para estudo de inteligência artificial, machine learning, deep learning, estrutura de dados, etc.
  

## arquivos

### tratamento
**1_tratamento_preprocessamento_testes.ipynb**
- Abre o arquivo contendo os dados das casas em Boston. Analisa informação por informação em busca de dados incondizentes que possam dificultar, fragilizar ou diminuir a eficácia do código, e trata os valores quando necessário.
- Pré-processa os dados. Separa os dados independentes/dependentes de diferentes formas e testa em aproximadamente 10 modelos de deep learning de aprendizado supervisionado (regressão), buscando o melhor modelo possível com o melhor formato de dados. Ao final, exporta os dados tratados.

**2_simulador.ipynb**
- Através do tratamento e análise dos códigos anteriores, esse código interpreta informações de novas casas fictícias e informa o preço aproximado da casa em US$ com (baseando-se na tabela de dados disponível) 83.15% de coeficiente de determinação médio.

**housing.csv**
- Dados para análise: imóveis em boston

**dependente.csv & independente.csv**
- Dados separados em dependentes e independentes
