# Trabalho 1 - Análise Exploratória de Dados

## Visão Geral

Este diretório contém análises exploratórias de dados realizadas em dois datasets clássicos de ciência de dados: Adult Income Dataset e Titanic Dataset. O trabalho inclui tanto os notebooks originais com código Python quanto transcrições em formato de artigo acadêmico.

## Estrutura do Projeto

```
1_Trabalho/
├── main_adult.ipynb                           # Notebook original - Análise Adult Income
├── main_titanic.ipynb                         # Notebook original - Análise Titanic
├── adult_income_analysis_article.md           # Artigo transcrito - Adult Income
├── titanic_survival_analysis_article.md       # Artigo transcrito - Titanic
├── article_transcription_overview.md          # Visão geral da transcrição
├── readme.md                                  # Este arquivo
├── requirements.txt                           # Dependências Python
└── dataset/                                   # Datasets (criado automaticamente)
```

## Notebooks Jupyter

### 1. main_adult.ipynb - Análise do Dataset Adult Income

**Objetivo**: Analisar fatores que influenciam a renda individual (>$50K vs ≤$50K)

**Dataset**: Adult Income Dataset (Census Income) - dados do censo americano de 1994

**Principais Análises**:
- Distribuição de renda por características demográficas
- Impacto da educação na renda
- Análise por gênero, idade e raça
- Influência de variáveis profissionais
- Análise por estado civil e tipo de relacionamento

### 2. main_titanic.ipynb - Análise de Sobrevivência no Titanic

**Objetivo**: Identificar fatores que influenciaram a sobrevivência no naufrágio do Titanic

**Dataset**: Titanic Dataset - dados históricos dos passageiros do RMS Titanic

**Principais Análises**:
- Taxa de sobrevivência geral
- Análise por gênero e idade
- Impacto da classe socioeconômica
- Influência da estrutura familiar
- Análise por porto de embarque
- Correlações entre variáveis

## Artigos Transcritos

### Artigos Acadêmicos

Os notebooks foram transcritos para formato de artigo acadêmico, removendo código técnico e focando na análise e interpretação dos resultados:

1. **`adult_income_analysis_article.md`**
   - Análise completa dos determinantes da renda individual
   - Estrutura acadêmica com resumo, metodologia, resultados e conclusões
   - Foco em implicações socioeconômicas e políticas públicas

2. **`titanic_survival_analysis_article.md`**
   - Análise detalhada dos fatores de sobrevivência no Titanic
   - Contexto histórico e social do desastre
   - Discussão sobre desigualdades sociais e protocolos de emergência

3. **`article_transcription_overview.md`**
   - Documentação completa do processo de transcrição
   - Metodologia aplicada na conversão
   - Guia para utilização dos artigos

## Principais Achados

### Adult Income Dataset

- **Educação** é o fator mais determinante da renda
- **Disparidades de gênero** significativas na distribuição de renda
- **Idade e experiência** correlacionam positivamente com renda superior
- **Ocupação e classe de trabalho** têm impacto significativo
- **Estado civil** influencia os padrões de renda

### Titanic Dataset

- **Gênero** foi o fator mais determinante (protocolo "mulheres e crianças primeiro")
- **Classe social** teve impacto dramático na sobrevivência
- **Idade** mostrou padrões complexos com vantagem para crianças
- **Estrutura familiar** influenciou as chances de sobrevivência
- **Porto de embarque** refletiu composição socioeconômica dos passageiros

## Como Usar

1. **Para análise técnica**: Consulte os notebooks Jupyter originais
2. **Para uso acadêmico**: Utilize os artigos transcritos em formato Markdown
3. **Para documentação**: Consulte o arquivo de overview da transcrição

## Contato

Para dúvidas sobre implementação, metodologia ou resultados, consulte:
- Notebooks originais para detalhes técnicos
- Artigos transcritos para análise acadêmica
- Arquivo de overview para processo de transcrição