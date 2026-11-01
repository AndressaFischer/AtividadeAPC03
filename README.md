# Ordenação e arquivos em C

Trabalho final feito em C para praticar arquivos, vetores e algoritmos de ordenação.

O programa permite gravar números em `dados.txt`, escolher um algoritmo para ordenar esses números e salvar o resultado em `ordenado.txt`. Também dá para alterar um número pela posição e ordenar de novo.

## O que tem no programa

- Bubble Sort
- Insertion Sort
- Selection Sort
- Merge Sort
- Quick Sort
- Alteração de um número usando um arquivo temporário

O programa aceita até 100 números, pois usa um vetor com tamanho definido no código.

## Como compilar e executar

É necessário ter o GCC instalado. Na pasta do projeto, rode:

```bash
gcc -std=c99 atividade_final_ordenacao_arquivos.c -o trabalho
./trabalho
```

No Windows, execute `trabalho.exe` depois de compilar.

## Menu

1. Criar ou substituir `dados.txt`.
2. Mostrar os números de `dados.txt`.
3. Escolher um algoritmo e salvar em `ordenado.txt`.
4. Alterar um número em `dados.txt` e ordenar novamente.
5. Mostrar `ordenado.txt`.
0. Sair.

Os arquivos de dados são criados na mesma pasta em que o programa é executado.

## Teste

Com Python 3 e GCC instalados, execute:

```bash
python3 tests/test_integracao.py
```

O teste compila o programa e verifica os cinco algoritmos, a alteração de um valor e o aviso quando `dados.txt` ainda não foi criado.

## Arquivos do projeto

- `atividade_final_ordenacao_arquivos.c` — código do programa.
- `tests/test_integracao.py` — teste simples de execução.
- `.gitignore` — ignora o executável e os arquivos criados pelo programa.
