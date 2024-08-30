# Date Fruit Clustering Project

Este projeto aplica técnicas de clusterização para analisar um dataset de diferentes variedades de frutas (datas). Utilizando métodos como K-Means, DBSCAN e Agglomerative Clustering, o objetivo é identificar grupos (clusters) distintos dentro do dataset e avaliar a qualidade desses clusters.

## Introdução

Clusterização é uma técnica de aprendizado não supervisionado que visa agrupar dados semelhantes em clusters. Neste projeto, exploramos vários métodos de clusterização para identificar padrões no dataset de frutas. Os métodos testados incluem K-Means, DBSCAN e Agglomerative Clustering, sendo que o método que retornou o melhor Silhouette Score foi escolhido para a análise final.

## Dataset

O dataset utilizado neste projeto está no formato ARFF e contém diversas características morfológicas de diferentes tipos de datas (frutas). O arquivo `.arff` foi carregado e processado utilizando bibliotecas como `pandas` e `scikit-learn`.

- **Nome:** Date_Fruit_Datasets.arff
- **Fonte:** [Dataset de Frutas](https://www.muratkoklu.com/datasets/)
- **Número de Atributos:** 34
- **Número de Instâncias:** 898

## Uso

Para executar o notebook, siga os passos abaixo:

1. Abra o Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2. No Jupyter, abra o arquivo `Date_Fruit_Clustering.ipynb`.

3. Execute as células para carregar os dados, aplicar os métodos de clusterização e visualizar os resultados.

## Métodos de Clusterização

Os seguintes métodos de clusterização foram avaliados neste projeto:

- **K-Means:** Um método simples e rápido para encontrar clusters esféricos.
- **DBSCAN:** Um método baseado em densidade que detecta clusters de formas arbitrárias e é robusto a ruído.
- **Agglomerative Clustering:** Um método hierárquico que constrói uma árvore de clusters.

Após testar esses métodos, o que apresentou o melhor Silhouette Score foi selecionado para a análise final.

## Resultados

O melhor método de clusterização encontrado foi `Método Escolhido` com um Silhouette Score de `0.34`.


## Contribuições

Contribuições são bem-vindas! Se você tiver alguma ideia ou sugestão, sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
