# CKP9011 - Introdução a Ciência de Dados
<img  src="https://img.shields.io/badge/UFC-CKP9011-000000?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAsAAAAOCAYAAAD5YeaVAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAAANgAAADYBsVpjYQAAABl0RVh0U29mdHdhcmUAd3d3Lmlua3NjYXBlLm9yZ5vuPBoAAAENSURBVCiRbdFBS9QBEAXw36y7Wq6IgUSGsixhJBpiRBB08XN7ETyIFyPYui2KBXsQTUphsbbx4Cz8E+cyw8ybN/NmQsMy8xO+YRkdXGA9Ig6g3QC+r/Ad/lS8hp9TTKtBvFB+Dt2qZXNyuxEnNnCORUQ1Xj8G/lX7trAfEVeZOYu3j63xDG8wg35mdiPiFpf/gTNzocZ+xQgv8KGYp3WRmTtYxQBPiv0Wh5W/wjaG7WI8K1HThlPsYowevmO+hZe4wfOImJTIV5jgafl/WInM3MBmMY5xXP41ltx/cgaDKAF999/q1L0/Yq9ygc8RMWxBRJzgN7bwF8PS0MNpRAwf3nlUAo/qdAf4gh9TwB2yEFM5Ddb+rgAAAABJRU5ErkJggg==" /> <img src="https://img.shields.io/badge/Jupyter-000000?style=for-the-badge&logo=jupyter&logoColor=white" /> <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white" />

## Scrapping

[Letras.com](https://www.letras.com/) é uma plataforma que disponibiliza letras e traduções de letras de diferentes gêneros musicais e línguas. A plataforma disponibiliza uma lista dinâmica das 1000 músicas mais populares.

<img src="./assets/img/banner.png" alt="banner" />

A qualquer instante a lista de músicas pode ser alterada. Um arquivo com a rotina de _scrapping_ está disponível neste repositório ([notebook](./scrapping/letras-com-scrapping.ipynb)).

## Dados

Até o momento os dados brutos contam com as seguinte colunas ([dados](./data/letras-com.csv)).

| # | Nome     | Tipo    | # | Nome     | Tipo    |
| - | -------- | ------- | - | -------- | ------- |
| 0 | `rank`   | int64   | 5 | `genre`  | object  |
| 1 | `singer` | object  | 6 | `lang`   | object  |
| 2 | `title`  | object  | 7 | `views`  | float64 |
| 3 | `url`    | object  | 8 | `lyrics` | object  |
| 4 | `album`  | object  |

## Notas
Este repositório foi criado para documentar o progresso nos trabalhos da disciplina _CKP9011 - Introdução a Ciência de Dados_ da Universidade Federal do Ceará.

