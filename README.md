# 📊 Análise de Comunidades e Estruturas em Grafos

Este projeto foi desenvolvido como parte da disciplina **TAG - Projeto 1**, com o objetivo de resolver os exercícios do capítulo 7 (_Components, Communities and Cliques_) do livro [_ONA - Online Network Analysis_](https://ona-book.org/index.html).

O projeto implementa algoritmos de análise de grafos para explorar propriedades como **componentes conectados, comunidades, modularidade, cliques** e visualizações gráficas de redes.

---

## 🚀 Funcionalidades

O código implementa soluções para os seguintes itens (cap. 7.5.2 - _Data Exercises_):

1. **Questão 4** → Determinação dos componentes conectados e identificação do maior componente.
2. **Questão 5** → Aplicação do algoritmo de **Louvain** para detecção de comunidades e cálculo da modularidade.
3. **Questão 6** → Comparação da modularidade de Louvain com a partição de referência (_ground truth_, baseada nos departamentos).
4. **Questão 7** → Visualização do grafo colorido por comunidades de Louvain e por departamentos.
5. **Questão 8** → Construção de _dataframe_ relacionando comunidades e departamentos, com visualização via _heatmap_.
6. **Questão 9** → Identificação do maior clique e contagem de cliques maximais no grafo.
7. **Questão 10** → Visualização dos maiores cliques no contexto do grafo completo.

---

## 🛠️ Tecnologias Utilizadas

As principais bibliotecas utilizadas foram:

- [NetworkX](https://networkx.org/) → Criação e análise de grafos
- [Pandas](https://pandas.pydata.org/) → Manipulação de dados
- [Seaborn](https://seaborn.pydata.org/) → Visualizações estatísticas
- [Matplotlib](https://matplotlib.org/) → Geração de gráficos e imagens
- [Community (python-louvain)](https://python-louvain.readthedocs.io/) → Algoritmo de Louvain para detecção de comunidades
- [NumPy](https://numpy.org/) → Operações matemáticas

---

## 📂 Estrutura do Projeto

```
📦 Projeto-Redes
 ┣ 📄 main.py                # Código principal com as funções de cada exercício
 ┣ 📄 docs.pdf               # Relatório com explicações e resultados
 ┣ 📄 email_vertices.csv     # Arquivo de vértices (ID e departamento)
 ┣ 📄 email_edgelist.csv     # Arquivo de arestas (ligações entre IDs)
 ┣ 📄 README.md              # Descrição do projeto
 ┗ 📂 resultados/            # Imagens PNG geradas (componentes, comunidades, cliques, etc.)

```

## ▶️ Como Executar

### 1. Instalar dependências

Certifique-se de ter o Python 3 instalado.  
Clone o repositório e, dentro da pasta do projeto, instale as dependências:

```bash
pip install -r requirements.txt
```

### 2. Escolher a questão

No final do arquivo main.py, descomente a chamada da função desejada:

```
#questao4(grafo)
#questao5(grafo)
#questao6(grafo)
#questao7(grafo)
#questao8(grafo)
#questao9(grafo)
#questao10(grafo)
```

### 3. Executar o script

Na raiz do projeto, rode:

```
python main.py
```
