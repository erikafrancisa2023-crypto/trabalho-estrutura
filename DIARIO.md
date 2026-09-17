# Diário do Trabalho

## Antes dos testes

Antes de começar os testes, eu esperava que o **Insertion Sort** fosse mais lento com vetores maiores, principalmente com dados aleatórios, por ter complexidade O(n²).

Também esperava que o **Merge Sort** apresentasse um crescimento mais estável, por ter complexidade O(n log n).

## Durante os testes

Foram realizados testes com vetores de 1.000 até 16.000 elementos, usando dados aleatórios e ordenados.

No início, ocorreu um erro porque as pastas `dados` e `graficos` ainda não existiam. Depois de criar as pastas, o programa conseguiu salvar os resultados e gerar o gráfico normalmente.

## Depois dos testes

Os resultados confirmaram o que era esperado. O **Insertion Sort** teve um aumento grande de tempo com dados aleatórios, enquanto com dados ordenados foi bem mais rápido.

O **Merge Sort** apresentou tempos mais estáveis nos dois tipos de entrada.

Os resultados foram salvos no arquivo `tempos.csv` e o gráfico foi gerado na pasta `graficos`.
