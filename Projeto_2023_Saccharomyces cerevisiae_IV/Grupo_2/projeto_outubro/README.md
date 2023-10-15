# Projeto de Outubro - Simulação de Mutações e Predição de Genes na Saccharomyces cerevisiae

## Resumo

Este estudo investigou o impacto das mutações no cromossomo IV de Saccharomyces cerevisiae usando a ferramenta Mutation Simulator com taxas reduzidas de mutações (2% de inserção, seguidas por 2% de deleção). Em seguida, a predição de genes foi realizada utilizando a ferramenta Augustus. Os resultados revelaram que a sequência sem mutação apresentou uma predição de 707 genes, enquanto a sequência com 2% de inserções resultou em 460 genes e a sequência com 2% de deleções produziu 286 genes. Além disso, a reprodutibilidade dos experimentos foi testada por outro membro da equipe, demonstrando resultados ligeiramente diferentes. Portanto, concluímos que, devido à natureza aleatória das mutações geradas pela ferramenta, a reprodutibilidade pode ser afetada.

## Introdução

### Mutation-Simulator

Mutation-Simulator é uma ferramenta essencial neste projeto, projetada para simular SNPs e SVs (variações estruturais) em qualquer genoma de referência. Este software oferece três modos distintos para simular SNPs, inserções, exclusões, duplicações em tandem, inversões, translocações e translocações intercromossômicas. O Mutation-Simulator permite a simulação a partir da linha de comando ou com arquivos RMT altamente configuráveis, fornecendo flexibilidade na geração de mutações. Os modos incluem:

- **Command-line Arguments (ARGS):** Esse modo permite simular qualquer tipo de SV ou SNP para uma taxa e comprimento distribuídos uniformemente pelo genoma de referência.

- **Interchromosomal Translocations (IT):** Usado para simular translocações intercromossômicas em uma taxa especificada.

- **Random Mutation Table (RMT):** Este modo combina os recursos acima e permite definir intervalos de taxas de mutação mais altas ou mais baixas em sequências específicas usando um arquivo RMT. Isso permite criar padrões recriáveis específicos para gerar mutações em taxas e comprimentos desejados em sequências específicas.

### AUGUSTUS

AUGUSTUS é outra ferramenta crucial neste projeto, destinada a prever genes em sequências genômicas eucarióticas. O programa é baseado em um modelo oculto generalizado de Markov (GHMM) e define distribuições de probabilidade para várias seções de sequências genômicas. Essas seções incluem introns, exons e regiões intergênicas, e cada uma delas corresponde a estados no modelo. Acredita-se que cada estado crie sequências de DNA com probabilidades de emissão pré-definidas. O AUGUSTUS é usado para encontrar uma análise ideal de uma sequência genômica, segmentando as sequências em estados que são mais prováveis de acordo com o modelo estatístico subjacente.

O objetivo deste projeto é explorar o funcionamento dessas ferramentas e entender como as mutações afetam a predição de genes na Saccharomyces cerevisiae. A reprodutibilidade dos resultados também será investigada por meio de análises independentes, o que nos ajudará a entender melhor a aleatoriedade das mutações geradas pela ferramenta e seu impacto nas previsões de genes.

## Resultados

### Mutation-Simulator

Inserção: (inserir imagem) 

Deleção: (inserir imagem)

### Predição de Genes com Augustus

Inserção:460 genes
(inserir imagem)

Deleção: 286 genes
(inserir imagem)

### Comparação da Predição de Genes com Augustus
(inserir imagem com tabela)

### Alinhamento das sequências com Jawview
(inserir imagem)

## Referências

- [Link para a apresentação no Canva](https://www.canva.com/design/DAFwD3R4CX4/DYeZCxnMPaZbSSSkukWbog/edit)
- [Link para a documentação do Mutation-Simulator](https://github.com/mkpython3/Mutation-Simulator)


## Links Relevantes

- [Outros links relevantes para o projeto]

