# Caracterização do Discurso Falado em Conteúdo Publicitário de Influenciadores Mirins

Repositório oficial do projeto da disciplina de Ciência de Dados. O estudo analisa padrões lexicais, n-gramas e eixos discursivos a partir da transcrição automática de áudio de vídeos publicitários.

## Estrutura do Repositório

- `notebooks/`: Notebooks Jupyter/Colab com o pipeline de transcrição (`01_transcricao_whisper.ipynb`) e limpeza/análise lexical (`02_analise_lexical_eixos.ipynb`).
- `data/raw/`: Dataset bruto com as 254 transcrições extraídas via Whisper (`transcrições.csv`).
- `data/processed/`: Corpus limpo e filtrado com 212 vídeos válidos (`transcricoes_limpas.csv`).
- `results/`: Tabelas de frequência (`tables/`) e gráficos em 300 DPI (`figures/`).
- `docs/`: Relatórios parciais e finais em PDF.

## Origem e Acesso aos Dados

Os vídeos pertencem ao recorte publicitário (`yes publi`, N = 254) coletado a partir de perfis indicados ao *Nickelodeon Kids' Choice Awards 2024*. Por restrições de armazenamento do GitHub e direitos de imagem, os arquivos `.mp4` originais não estão hospedados neste repositório. No entanto, o arquivo `data/raw/transcrições.csv` contém todas as transcrições brutas extraídas na Etapa 1, permitindo reproduzir integralmente a Etapa 2.

## Como Reproduzir

1. Clone o repositório e instale as dependências:
   ```bash
   git clone <URL_DO_SEU_REPOSITORIO>
   cd projeto-ds-discurso-publicitario
   pip install -r requirements.txt