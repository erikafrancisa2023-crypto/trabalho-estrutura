# Comparação entre Insertion Sort e Merge Sort

Neste trabalho foi feita uma comparação entre os algoritmos **Insertion Sort** e **Merge Sort**.

Foram testados vetores de:

* 1.000
* 2.000
* 4.000
* 8.000
* 16.000 elementos

Os testes foram feitos com dados **aleatórios** e **ordenados**. Cada teste foi executado 3 vezes, descartando a primeira execução.

## Resultados

Os tempos dos testes foram salvos em:

dados/tempos.csv

O gráfico da comparação está em:

graficos/comparacao.png

Nos testes, o **Insertion Sort** apresentou um aumento maior de tempo com dados aleatórios. Já com os dados ordenados, seu tempo foi bem menor.

O **Merge Sort** apresentou um crescimento mais estável nos dois tipos de entrada, sendo compatível com **O(n log n)**.

## Como executar

Na pasta do projeto, execute:

```bash
python src/comparacao.py
```

O programa realiza os testes, salva os tempos no CSV e gera o gráfico.

## Estrutura

```text
trabalho estrutura/
├── README.md
├── DIARIO.md
├── src/
│   └── comparacao.py
├── dados/
│   └── tempos.csv
└── graficos/
    └── comparacao.png
```
