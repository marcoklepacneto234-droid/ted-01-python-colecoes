# ted-01-python-colecoes
Ted 1 - Processamento de dados com Python

# DOCUMENTAÇÃO DO PROGRAMA

## 1. Nome dos integrantes da dupla

* Integrante 1: Marco Antonio Klepac Neto 
* Integrante 2: Thulio Augusto Sousa Barros

## 2. Cenário recebido

O cenário recebido apresenta dados relacionados a conteúdos e suas respectivas visualizações. Os dados foram disponibilizados em dois arquivos CSV: um contendo informações dos conteúdos e outro contendo informações sobre as visualizações realizadas pelos usuários.

Os conteúdos possuem informações como título, gênero e duração. Já os registros de visualizações possuem informações como usuário, conteúdo assistido, quantidade de visualizações e avaliação.

## 3. Descrição resumida da solução

Foi desenvolvido um programa em Python para realizar a leitura, organização, tratamento e análise dos dados fornecidos.

O programa lê os dois arquivos CSV, organiza as informações utilizando diferentes estruturas de dados e relaciona os conteúdos às suas respectivas visualizações.

Também são realizados tratamentos de dados duplicados utilizando conjuntos (`set`) e operações de conjuntos. O programa utiliza List Comprehension e Dict Comprehension para realizar filtragens e transformações.

Por fim, são realizadas diversas análises e os resultados são apresentados de forma organizada no terminal.

## 4. Estruturas de dados utilizadas

Foram utilizadas as seguintes estruturas:

* **Listas:** utilizadas para armazenar os conteúdos e os registros de visualizações.
* **Tuplas:** utilizadas para armazenar os gêneros dos conteúdos.
* **Dicionários:** utilizados para representar as informações de cada conteúdo e cada registro de visualização.
* **Estruturas aninhadas:** utilizadas para relacionar cada conteúdo às suas respectivas visualizações.
* **Sets:** utilizados para identificar e eliminar dados duplicados e realizar operações de interseção.
* **List Comprehension:** utilizadas para filtrar conteúdos com duração superior a 100 minutos e criar uma lista contendo os títulos.
* **Dict Comprehension:** utilizada para criar um dicionário relacionando o ID dos conteúdos aos seus respectivos títulos.

## 5. Principais análises realizadas

O programa realiza diferentes análises sobre os dados, entre elas:

1. Quantidade total de conteúdos cadastrados.
2. Quantidade total de registros de visualizações.
3. Quantidade de usuários diferentes.
4. Total de visualizações.
5. Identificação do conteúdo mais visualizado.
6. Média das avaliações realizadas pelos usuários.
7. Identificação dos conteúdos com duração superior a 100 minutos.
8. Filtragem dos conteúdos por gênero.
9. Identificação da quantidade de registros duplicados.
10. Identificação de usuários em comum através da operação de interseção de conjuntos.

## 6. Instruções para executar o programa

Para executar o programa, é necessário ter o Python instalado no computador.

Os arquivos devem estar organizados na mesma pasta:

* `streaming.py`
* `conteudos.csv`
* `visualizacoes.csv`

Depois, abra o terminal na pasta onde os arquivos estão localizados e execute:

```bash
python streaming.py
```

Após a execução, os resultados das análises serão apresentados diretamente no terminal de forma organizada.

## 7. Funções utilizadas

O programa possui quatro funções principais:

* `calcular_total_visualizacoes()` — calcula o total de visualizações.
* `calcular_media_avaliacoes()` — calcula a média das avaliações.
* `encontrar_mais_visualizado()` — identifica o conteúdo com maior número de visualizações.
* `filtrar_por_genero()` — filtra os conteúdos de acordo com o gênero escolhido.

Essas funções foram utilizadas para organizar o processamento e facilitar a realização das análises.
