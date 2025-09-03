# Análise de Sobrevivência no Titanic: Fatores Determinantes e Padrões Demográficos

## Resumo

Este artigo apresenta uma análise detalhada dos fatores que influenciaram a sobrevivência dos passageiros do RMS Titanic durante o trágico naufrágio de 1912. Utilizando técnicas de análise exploratória de dados, investigamos como variáveis demográficas, socioeconômicas e familiares impactaram as chances de sobrevivência, revelando padrões significativos que refletem as circunstâncias sociais da época e as condições do desastre.

## 1. Introdução

O naufrágio do Titanic em 15 de abril de 1912 representa uma das maiores tragédias marítimas da história, resultando na morte de mais de 1.500 pessoas. Além de seu impacto histórico, o desastre do Titanic oferece uma oportunidade única para análise de fatores de sobrevivência em situações extremas, permitindo examinar como características demográficas e socioeconômicas influenciaram as chances de vida ou morte.

Este estudo utiliza o dataset histórico dos passageiros do Titanic para identificar padrões de sobrevivência e compreender os fatores determinantes que influenciaram quem viveu ou morreu durante o naufrágio. A análise busca revelar não apenas aspectos estatísticos, mas também reflexões sobre a sociedade da época e as circunstâncias do desastre.

## 2. Metodologia

### 2.1 Fonte dos Dados

O dataset utilizado contém informações detalhadas de 891 passageiros do Titanic, incluindo dados demográficos, socioeconômicos e de sobrevivência. Os dados foram coletados de registros históricos e representam uma amostra significativa dos passageiros a bordo.

### 2.2 Variáveis Analisadas

As principais variáveis consideradas no estudo incluem:

- **Survived**: Indicador de sobrevivência (0 = não sobreviveu, 1 = sobreviveu)
- **Pclass**: Classe socioeconômica (1ª, 2ª ou 3ª classe)
- **Sex**: Gênero do passageiro
- **Age**: Idade do passageiro
- **SibSp**: Número de irmãos/cônjuges a bordo
- **Parch**: Número de pais/filhos a bordo
- **Fare**: Tarifa paga pela passagem
- **Embarked**: Porto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton)

### 2.3 Tratamento dos Dados

O processo de preparação incluiu:

- **Análise de valores ausentes**: Identificação e tratamento de dados faltantes nas variáveis idade, cabine e porto de embarque
- **Criação de variáveis derivadas**: Desenvolvimento de novos indicadores para enriquecer a análise
- **Tratamento de outliers**: Identificação e análise de valores extremos para garantir robustez analítica
- **Codificação de variáveis categóricas**: Transformação adequada para análise quantitativa

## 3. Análise Exploratória

### 3.1 Panorama Geral de Sobrevivência

A análise inicial revelou uma taxa de sobrevivência geral de aproximadamente 38,4% entre os passageiros analisados. Esta baixa taxa de sobrevivência reflete a magnitude da tragédia e serve como ponto de partida para investigar os fatores que determinaram quem teve maior probabilidade de sobreviver.

### 3.2 Análise por Gênero

#### 3.2.1 Impacto do Gênero na Sobrevivência

A análise por gênero revelou uma das diferenças mais marcantes nos padrões de sobrevivência:

- **Mulheres**: Taxa de sobrevivência significativamente superior, refletindo o protocolo marítimo "mulheres e crianças primeiro"
- **Homens**: Taxa de sobrevivência consideravelmente menor, demonstrando o sacrifício masculino durante o desastre

Este padrão confirma a implementação do código de conduta marítima da época e ilustra como normas sociais influenciaram as chances de sobrevivência.

#### 3.2.2 Interação entre Gênero e Classe Social

A análise combinada de gênero e classe social revelou nuances importantes:

- **Mulheres de primeira classe**: Taxa de sobrevivência próxima a 100%
- **Mulheres de segunda classe**: Alta taxa de sobrevivência, mas inferior à primeira classe
- **Mulheres de terceira classe**: Taxa ainda elevada, mas com redução notável comparada às classes superiores
- **Homens de primeira classe**: Maior taxa de sobrevivência entre os homens
- **Homens de classes inferiores**: Taxas progressivamente menores de sobrevivência

### 3.3 Análise por Classe Socioeconômica

A classe social emergiu como um fator determinante crucial na sobrevivência:

#### 3.3.1 Primeira Classe
Passageiros de primeira classe apresentaram as maiores taxas de sobrevivência, beneficiando-se de:
- Localização privilegiada nos conveses superiores
- Acesso prioritário aos botes salva-vidas
- Melhor conhecimento da situação de emergência

#### 3.3.2 Segunda Classe
Taxas intermediárias de sobrevivência, refletindo uma posição média em termos de acesso aos recursos de emergência.

#### 3.3.3 Terceira Classe
Menores taxas de sobrevivência, resultantes de:
- Localização nos conveses inferiores
- Barreiras físicas ao acesso aos botes salva-vidas
- Menor informação sobre a gravidade da situação

### 3.4 Análise por Idade

#### 3.4.1 Padrões Etários de Sobrevivência

A análise etária revelou padrões complexos:

- **Crianças (0-12 anos)**: Taxa de sobrevivência elevada, consistente com o protocolo "mulheres e crianças primeiro"
- **Adultos jovens (13-30 anos)**: Variabilidade significativa dependente de outros fatores
- **Adultos maduros (31-60 anos)**: Taxas intermediárias com influência forte do gênero e classe
- **Idosos (60+ anos)**: Taxas reduzidas, possivelmente relacionadas à mobilidade limitada

#### 3.4.2 Interação Idade-Gênero

A combinação de idade e gênero mostrou que:
- Mulheres de todas as idades mantiveram vantagem de sobrevivência
- O efeito protetor da idade infantil foi mais pronunciado entre meninos
- Homens idosos apresentaram as menores taxas de sobrevivência

### 3.5 Análise de Estrutura Familiar

#### 3.5.1 Viajantes com Irmãos/Cônjuges (SibSp)

A presença de familiares mostrou padrões interessantes:
- **Viajantes sozinhos**: Taxas de sobrevivência intermediárias
- **Com 1-2 acompanhantes**: Melhores taxas de sobrevivência, sugerindo benefício do suporte familiar
- **Famílias grandes**: Redução nas taxas de sobrevivência, possivelmente devido à dificuldade de coordenação em emergências

#### 3.5.2 Viajantes com Pais/Filhos (Parch)

Padrões similares foram observados:
- Presença moderada de familiares correlacionou-se com maior sobrevivência
- Famílias muito grandes enfrentaram desafios adicionais durante a evacuação

### 3.6 Análise por Porto de Embarque

O porto de embarque mostrou correlações interessantes com sobrevivência:

- **Cherbourg (C)**: Maior taxa de sobrevivência, correlacionada com maior proporção de passageiros de primeira classe
- **Queenstown (Q)**: Taxa intermediária
- **Southampton (S)**: Menor taxa de sobrevivência, com maior proporção de passageiros de terceira classe

### 3.7 Análise de Tarifa

A tarifa paga pela passagem serviu como proxy adicional para status socioeconômico, mostrando correlação positiva com sobrevivência, confirmando o impacto da posição social nas chances de salvamento.

## 4. Correlações e Padrões Multivariados

A análise de correlações revelou interações complexas entre as variáveis:

1. **Correlação forte**: Classe social e tarifa (confirmando consistência dos dados)
2. **Correlação moderada**: Gênero feminino e sobrevivência
3. **Correlação negativa**: Terceira classe e sobrevivência
4. **Padrões complexos**: Idade com múltiplos fatores interagindo

## 5. Principais Achados

### 5.1 Fatores Determinantes Primários

1. **Gênero**: O fator mais determinante, com mulheres tendo 4 vezes mais chances de sobreviver
2. **Classe Social**: Impacto significativo, com primeira classe tendo 3 vezes mais chances que terceira classe
3. **Idade**: Efeito moderado, com vantagem para crianças e desvantagem para idosos

### 5.2 Fatores Secundários

1. **Estrutura Familiar**: Famílias pequenas tiveram vantagem sobre indivíduos sozinhos e famílias grandes
2. **Porto de Embarque**: Reflexo indireto da composição socioeconômica dos passageiros
3. **Tarifa**: Confirmação adicional do impacto do status socioeconômico

### 5.3 Interações Complexas

A análise revelou que os fatores não atuaram independentemente, mas em combinações que amplificaram ou reduziram as chances de sobrevivência:

- **Mulher + Primeira Classe**: Combinação quase garantidora de sobrevivência
- **Homem + Terceira Classe**: Combinação com menores chances de sobrevivência
- **Criança + Família Pequena**: Vantagem significativa independente da classe

## 6. Implicações Históricas e Sociais

### 6.1 Reflexo da Sociedade Edwardiana

Os padrões de sobrevivência refletem claramente a estrutura social da época:

- **Hierarquia de classes**: Diferenças marcantes no acesso a recursos de salvamento
- **Normas de gênero**: Implementação do código "mulheres e crianças primeiro"
- **Desigualdade social**: Manifestação extrema em situação de vida ou morte

### 6.2 Lições para Gestão de Emergências

O estudo oferece insights para protocolos modernos de emergência:

- **Importância do acesso equitativo**: Necessidade de garantir acesso igual aos recursos de salvamento
- **Planejamento familiar**: Consideração especial para famílias em evacuações
- **Treinamento e informação**: Garantir que todos os grupos tenham conhecimento adequado sobre procedimentos de emergência

## 7. Limitações do Estudo

### 7.1 Limitações dos Dados

- **Dados ausentes**: Informações incompletas para algumas variáveis
- **Viés de sobrevivência**: Dados podem estar enviesados para sobreviventes
- **Representatividade**: Amostra pode não representar perfeitamente toda a população a bordo

### 7.2 Limitações Metodológicas

- **Análise observacional**: Impossibilidade de estabelecer causalidade definitiva
- **Variáveis não observadas**: Fatores como posição no navio no momento do impacto não foram considerados

## 8. Conclusões

A análise de sobrevivência no Titanic revelou padrões claros e significativos que refletem tanto as circunstâncias específicas do desastre quanto a estrutura social da época. Os principais determinantes de sobrevivência foram gênero, classe social e idade, atuando em combinações complexas que amplificaram desigualdades sociais existentes.

### 8.1 Principais Conclusões

1. **Desigualdade extrema**: O desastre ampliou drasticamente as consequências das desigualdades sociais
2. **Efetividade de protocolos**: O código "mulheres e crianças primeiro" foi amplamente implementado
3. **Impacto da estrutura social**: A posição socioeconômica foi determinante nas chances de sobrevivência
4. **Complexidade dos fatores**: Múltiplas variáveis interagiram para determinar os resultados

### 8.2 Relevância Contemporânea

Os achados deste estudo mantêm relevância para:

- **Gestão de emergências modernas**: Desenvolvimento de protocolos mais equitativos
- **Estudos sociológicos**: Compreensão de como desigualdades se manifestam em crises
- **Análise histórica**: Entendimento da sociedade do início do século XX

### 8.3 Direções Futuras

Pesquisas futuras podem beneficiar-se de:

- **Modelos preditivos avançados**: Aplicação de machine learning para modelagem de sobrevivência
- **Análise comparativa**: Estudos com outros desastres históricos
- **Simulações**: Modelagem de cenários alternativos para compreender impactos de diferentes protocolos

O estudo do Titanic oferece uma janela única para compreender como fatores sociais, demográficos e circunstanciais interagem em situações extremas, fornecendo lições valiosas tanto para a compreensão histórica quanto para o planejamento moderno de gestão de emergências.

## 9. Referências

- Dataset Titanic disponível em: Kaggle Titanic Competition
- Registros históricos do RMS Titanic
- Técnicas de análise exploratória de dados aplicadas com Python
- Literatura sobre análise de sobrevivência em desastres marítimos