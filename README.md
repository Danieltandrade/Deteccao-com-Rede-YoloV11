# Deteccao com Rede YoloV11
=====================================

## Resumo
--------

Este projeto visa criar um modelo personalizado com YoloV11 para detecção de objetos em imagens. O modelo é treinado com um conjunto de dados específico e pode ser utilizado para detecção de objetos em novas imagens.

## Introdução
------------

A detecção de objetos em imagens é uma tarefa fundamental em muitas aplicações de visão computacional, como vigilância, monitoramento de tráfego, detecção de anomalias, entre outras. Neste projeto, utilizamos a rede YoloV11, uma das mais eficientes e precisas redes de detecção de objetos disponíveis, para criar um modelo personalizado capaz de detectar objetos em imagens.

## Repositórios
--------------

* [GitHub EdgeOfAI](https://github.com/EdgeOfAI/oidv7-Toolkit)
* [GitHub Danieltandrade](https://github.com/Danieltandrade/Deteccao-com-Rede-YoloV11)

## Dependências
------------

* Python 3.10 >=
* Vide dependências nos arquivos `requirements.txt`, presentes nos repositórios acima
* Ultralytics 8.3.75

## Instalação
------------

0. Clone o repositório: `https://github.com/EdgeOfAI/oidv7-Toolkit.git` # Opcional
1. Clone o repositório: `https://github.com/Danieltandrade/Deteccao-com-Rede-YoloV11.git`
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o notebook Jupyter: `jupyter notebook Deteccao_com_Rede_YoloV11.ipynb`

>[!Note]
> O repositório __oidv7-Toolkit__ é opcional, e deve ser clonado apenas se for necessário para realizar o download das imagens do conjunto de dados OpenImages.

### Treinamento do Modelo

1. Abra o notebook Jupyter ou o Google Colab e execute as células para treinar o modelo.
2. O modelo será treinado com o conjunto de dados específico e salvará os pesos do modelo em um arquivo `best.py`, conforme estrutura abaixo:

    ```bash
    ├── weights
        ├── best.pt
        └── last.pt
    ```

## Conjunto de Dados
-----------------

O conjunto de dados utilizado para treinar o modelo é composto por imagens de objetos de diferentes classes que podem ser escolhidas pelo usuário. O conjunto de dados é dividido em treinamento e teste, com 90% das imagens utilizadas para treinamento e 10% para validação.

## Avaliação do Modelo
-------------------

O modelo é avaliado utilizando as métricas de precisão, recall e F1-score. Os resultados da avaliação são apresentados no notebook Jupyter.

## Contribuição
------------

Contribuições são bem-vindas! Se você tiver alguma sugestão ou correção, por favor, abra uma issue ou faça um pull request.

## Licença
-------

Este projeto é licenciado sob a licença MIT.

## Autores
--------

* Daniel Torres de Andrade : [e-mail](danieltorresandrade@gmail.com)