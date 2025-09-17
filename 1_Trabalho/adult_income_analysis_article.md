# Análise Exploratória do Dataset Adult Income: Fatores Determinantes da Renda Individual

## Resumo

Este artigo apresenta uma análise exploratória abrangente do dataset Adult Income, com o objetivo de identificar e compreender os principais fatores que influenciam a renda individual. Através de técnicas de análise de dados e visualização, investigamos a relação entre variáveis demográficas, educacionais e profissionais com os níveis de renda, fornecendo insights valiosos sobre os determinantes socioeconômicos da renda na sociedade.

## 1. Introdução

O dataset Adult Income, também conhecido como Census Income dataset, é uma base de dados amplamente utilizada em estudos de ciência de dados e machine learning. Originado do censo americano de 1994, este conjunto de dados contém informações demográficas e socioeconômicas de indivíduos, incluindo idade, educação, ocupação, estado civil, entre outras variáveis, com o objetivo de prever se uma pessoa ganha mais ou menos de $50,000 por ano.

A compreensão dos fatores que influenciam a renda individual é fundamental para diversos aspectos da política pública e planejamento econômico. Este estudo busca identificar padrões e correlações entre as variáveis disponíveis, oferecendo uma visão analítica dos determinantes da renda.

## 2. Metodologia

### 2.1 Preparação dos Dados

O dataset original foi submetido a um processo de limpeza e preparação, que incluiu:

- **Remoção de variáveis redundantes**: As colunas 'fnlwgt' (peso final), 'capital-gain' e 'capital-loss' foram removidas para focar nas variáveis demográficas e profissionais principais.
- **Tratamento de valores ausentes**: Identificação e tratamento adequado de dados faltantes para garantir a integridade da análise.
- **Padronização de categorias**: Normalização das variáveis categóricas para consistência analítica.

### 2.2 Variáveis Analisadas

As principais variáveis consideradas no estudo incluem:

- **age**: Idade do indivíduo
- **workclass**: Classe de trabalho (privado, governo, autônomo, etc.)
- **education**: Nível educacional
- **education-num**: Número de anos de educação
- **marital-status**: Estado civil
- **occupation**: Ocupação profissional
- **relationship**: Tipo de relacionamento familiar
- **race**: Raça
- **sex**: Gênero
- **hours-per-week**: Horas trabalhadas por semana
- **native-country**: País de origem
- **income**: Variável target (≤50K ou >50K)

## 3. Análise Exploratória

### 3.1 Estrutura dos Dados

O dataset apresenta características equilibradas em termos de distribuição das variáveis categóricas, permitindo uma análise robusta dos padrões de renda. A análise inicial revelou a presença de valores ausentes em algumas variáveis, que foram tratados de acordo com as melhores práticas de preparação de dados.

### 3.2 Distribuição de Renda

A análise da distribuição da variável target revelou um desequilíbrio característico, onde a maioria dos indivíduos (aproximadamente 75%) possui renda igual ou inferior a $50,000 anuais. Esta distribuição reflete a realidade socioeconômica da época e serve como base para as análises subsequentes.

### 3.3 Análise por Variáveis Demográficas

#### 3.3.1 Idade
A análise por faixa etária demonstrou uma correlação positiva entre idade e renda, com indivíduos na faixa de 35-55 anos apresentando maior probabilidade de renda superior a $50,000. Este padrão sugere a importância da experiência profissional e maturidade na carreira como fatores determinantes da renda.

#### 3.3.2 Gênero
Os resultados evidenciaram uma disparidade significativa entre gêneros, com homens apresentando maior proporção de indivíduos na categoria de renda superior. Esta observação aponta para questões estruturais de equidade salarial que merecem atenção especial em políticas públicas.

#### 3.3.3 Raça
A análise racial revelou diferenças notáveis na distribuição de renda entre diferentes grupos étnicos, com algumas raças apresentando maior representação nas faixas de renda mais altas, indicando possíveis desigualdades sistêmicas.

### 3.4 Análise por Variáveis Educacionais

O nível educacional emergiu como um dos fatores mais determinantes da renda. Indivíduos com educação superior (Bachelors, Masters, Doctorate) apresentaram significativamente maior probabilidade de renda superior a $50,000, demonstrando o valor do investimento em educação para a mobilidade socioeconômica.

A correlação entre anos de educação e renda foi consistentemente positiva, reforçando a importância da educação formal como mecanismo de ascensão social.

### 3.5 Análise por Variáveis Profissionais

#### 3.5.1 Classe de Trabalho
A análise por classe de trabalho mostrou que trabalhadores do setor privado e autônomos incorporados apresentaram maior probabilidade de renda elevada, enquanto trabalhadores do governo federal mostraram distribuição mais uniforme entre as categorias de renda.

#### 3.5.2 Ocupação
Certas ocupações, particularmente nas áreas de gestão executiva, profissões especializadas e vendas, demonstraram forte associação com renda superior, refletindo a valorização de diferentes tipos de habilidades no mercado de trabalho.

#### 3.5.3 Horas Trabalhadas
A análise das horas trabalhadas por semana revelou uma correlação positiva com a renda, indicando que maior dedicação temporal ao trabalho está associada a maior remuneração.

### 3.6 Análise por Estado Civil e Relacionamento

O estado civil mostrou-se um fator relevante, com indivíduos casados apresentando maior probabilidade de renda superior. A análise por tipo de relacionamento complementou esta observação, mostrando que indivíduos em posição de "marido" ou "esposa" têm maior associação com renda elevada.

## 4. Principais Achados

1. **Educação como principal determinante**: O nível educacional demonstrou ser o fator mais fortemente correlacionado com renda superior, destacando a importância do investimento em educação.

2. **Disparidades de gênero**: Observou-se diferenças significativas na distribuição de renda entre gêneros, indicando necessidade de políticas de equidade salarial.

3. **Influência da idade e experiência**: A faixa etária intermediária (35-55 anos) apresentou maior concentração de indivíduos com renda superior, sugerindo o valor da experiência profissional.

4. **Impacto das variáveis profissionais**: Ocupação, classe de trabalho e horas trabalhadas mostraram correlações significativas com os níveis de renda.

5. **Fatores familiares**: Estado civil e tipo de relacionamento familiar influenciam a distribuição de renda, possivelmente relacionados à estabilidade e responsabilidades familiares.

## 5. Conclusões

Esta análise exploratória do dataset Adult Income forneceu insights valiosos sobre os determinantes da renda individual. Os resultados confirmam a importância multifatorial da renda, onde educação, experiência profissional, características demográficas e estrutura familiar interagem para determinar os níveis de renda.

Os achados têm implicações importantes para o desenvolvimento de políticas públicas voltadas à redução de desigualdades e promoção da mobilidade socioeconômica. Particularmente, destacam-se a necessidade de:

- Investimento em educação como mecanismo de ascensão social
- Políticas de equidade de gênero no mercado de trabalho
- Programas de desenvolvimento profissional para grupos sub-representados
- Iniciativas de inclusão racial e étnica

As limitações deste estudo incluem a natureza observacional dos dados e a necessidade de análises mais aprofundadas para estabelecer relações causais. Estudos futuros podem beneficiar-se da aplicação de técnicas de machine learning para modelagem preditiva e análise de importância de variáveis.

## 6. Referências

- Dataset Adult Income disponível em: UCI Machine Learning Repository
- Análise baseada no censo americano de 1994
- Técnicas de análise exploratória de dados aplicadas com Python e bibliotecas de visualização