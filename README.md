# KmeansUnidade10Trilha3
# Projeto: Análise de Agrupamento de Atividades Humanas Usando K-means

## Objetivo do Projeto
Este projeto tem como objetivo explorar e analisar o conjunto de dados **Human Activity Recognition Using Smartphones**, aplicando o algoritmo de agrupamento K-means para identificar padrões e categorizar atividades humanas. O projeto inclui:

- Análise exploratória dos dados;
- Redução de dimensionalidade para visualização e eficiência computacional;
- Escolha do número ideal de clusters utilizando os métodos do cotovelo (*Elbow Method*) e *Silhouette Score*;
- Avaliação e interpretação dos clusters formados.

---

## Instruções para Executar o Código

### Pré-requisitos
Certifique-se de ter o ambiente Python configurado com as seguintes bibliotecas instaladas:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tqdm`

Para instalar as dependências, execute:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tqdm

Passo a Passo
Obtenha o Dataset: Baixe o conjunto de dados diretamente do repositório UCI Machine Learning:

Link do Dataset
Extraia o conteúdo do arquivo e salve no diretório de trabalho.
Configure o Google Colab:

Carregue o notebook .ipynb fornecido no repositório.
Faça o upload dos arquivos extraídos para o ambiente do Colab.
Execute o Notebook:

Siga as células do notebook, certificando-se de que os arquivos de dados estão no local correto.
O código irá realizar:
Pré-processamento e análise exploratória.
Redução de dimensionalidade com PCA.
Treinamento e avaliação do K-means.

Principais Conclusões e Considerações
Redução de Dimensionalidade:

A aplicação de PCA mostrou-se essencial para tornar os dados mais manejáveis e para facilitar a visualização dos clusters.
Com 50 componentes principais, foi possível preservar a maior parte da variância do conjunto de dados original.
Número Ideal de Clusters:

O método do cotovelo indicou que o número ideal de clusters é próximo de 6, o que reflete as atividades registradas no dataset.
O Silhouette Score corroborou essa análise, sugerindo boa separação entre os clusters.
Interpretação dos Clusters:

Cada cluster formado pelo K-means representou um grupo de atividades humanas com características semelhantes.
Foi possível identificar padrões nos dados que correspondem às atividades realizadas, como caminhar, ficar em pé e subir escadas.
Considerações:

A normalização dos dados foi fundamental para garantir que todas as variáveis contribuíssem igualmente para o agrupamento.
Embora o K-means tenha apresentado resultados satisfatórios, técnicas adicionais, como agrupamento hierárquico, podem ser exploradas em estudos futuros.

Observações Finais
Este projeto demonstrou a aplicação prática do K-means em dados reais de alta dimensionalidade. Ele também destacou a importância de metodologias robustas, como normalização e redução de dimensionalidade, para melhorar a eficiência e a qualidade dos resultados.

Sinta-se à vontade para contribuir ou reportar qualquer problema no repositório.
