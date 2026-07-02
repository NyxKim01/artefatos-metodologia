# Artefatos da Metodologia

Este projeto contém os arquivos necessários para visualizar ferramentas em quatro quadrantes utilizando um arquivo CSV como fonte de dados, além das justificativas, cálculos de validação e geração do ranking das ferramentas avaliadas.

## Arquivos

### `ferramentas.csv`
Arquivo contendo os dados das ferramentas que serão plotadas no plano cartesiano.

O CSV é utilizado como entrada pelo arquivo HTML e deve conter as informações necessárias para posicionar cada ferramenta nos quadrantes.

---

### `justificativas.pdf`
Documento com as justificativas das notas atribuídas a todas as ferramentas avaliadas.

O PDF detalha os critérios e motivos utilizados para definir as pontuações presentes no dataset.

---

### `Calculos_ranking.xlsx`
Planilha contendo os cálculos utilizados para geração do ranking das ferramentas avaliadas.

---

### `Validacao_dos_resultados.xlsx`
Planilha utilizada para validação dos resultados obtidos na avaliação das ferramentas.

---

### `quadrantes_figura_1.html`
Arquivo HTML responsável por gerar a visualização dos quatro quadrantes.

O sistema lê os dados do arquivo `ferramentas.csv` e plota automaticamente as ferramentas no gráfico.

## Como usar

1. Abra o arquivo `matriz_figura_1.html` no navegador.
2. Selecione o arquivo de entrada: `ferramentas.csv`.
3. Os quadrantes serão gerados automaticamente com base nos dados do CSV.
