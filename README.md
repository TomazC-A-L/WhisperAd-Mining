# Caracterização do Discurso Falado em Conteúdo Publicitário de Influenciadores Mirins
## Estrutura do Repositório

- `notebooks/`: Notebooks Jupyter/Colab com o pipeline de transcrição (`01_transcricao_whisper.ipynb`) e limpeza/análise lexical (`02_analise_lexical_eixos.ipynb`).
- `data/raw/`: Dataset bruto com as 254 transcrições extraídas via Whisper (`transcrições.csv`).
- `data/processed/`: Corpus limpo e filtrado com 212 vídeos válidos (`transcricoes_limpas.csv`).
- `results/`: Tabelas de frequência (`tables/`) e gráficos em 300 DPI (`figures/`).

## Origem e Acesso aos Dados

Os vídeos pertencem ao recorte publicitário (`yes publi`, N = 254) coletado a partir de perfis indicados ao *Nickelodeon Kids' Choice Awards 2024*. Por restrições de armazenamento do GitHub e direitos de imagem, os arquivos `.mp4` originais não estão hospedados neste repositório. No entanto, o arquivo `data/raw/transcrições.csv` contém todas as transcrições brutas extraídas.

## Como Reproduzir

1. Clone o repositório e instale as dependências:
   ```bash
   git clone <WhisperAd-Mining>
   cd projeto-ds-discurso-publicitario
   pip install -r requirements.txt
