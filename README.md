# Projeto de Visualização de Ferramentas em Matriz 2x2

Este projeto contém os arquivos necessários para visualizar ferramentas em uma matriz 2x2 utilizando um arquivo CSV como fonte de dados.

## Arquivos

### `ferramentas.csv`
Arquivo contendo os dados das ferramentas que serão plotadas na matriz 2x2.

O CSV é utilizado como entrada pelo arquivo HTML e deve conter as informações necessárias para posicionar cada ferramenta na matriz.

---

### `justificativas.pdf`
Documento com as justificativas das notas atribuídas a todas as ferramentas avaliadas.

O PDF detalha os critérios e motivos utilizados para definir as pontuações presentes no dataset.

---

### `matriz_figura_1.html`
Arquivo HTML responsável por gerar a visualização da matriz 2x2.

O sistema lê os dados do arquivo `ferramentas.csv` e plota automaticamente as ferramentas no gráfico.

## Como usar

1. Certifique-se de que o arquivo `ferramentas.csv` esteja na mesma pasta do arquivo `matriz_figura_1.html`.
2. Abra o arquivo `matriz_figura_1.html` no navegador.
3. A matriz será gerada automaticamente com base nos dados do CSV.

## Estrutura esperada

```text
.
├── ferramentas.csv
├── justificativas.pdf
└── matriz_figura_1.html
```

## Objetivo

O objetivo deste projeto é permitir:

- Visualização comparativa das ferramentas em uma matriz 2x2;
- Organização visual baseada nas notas atribuídas;
- Transparência na avaliação através do documento de justificativas.
