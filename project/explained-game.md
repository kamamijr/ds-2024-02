# Explained: Smart Decisions Game

## Overview
O Smart Decisions Game é uma simulação que auxilia equipes a aprenderem sobre design arquitetural em Big Data. Ele oferece cenários baseados em problemas reais, onde jogadores devem tomar decisões arquiteturais em diferentes iterações.

## How It Works:
1. **Setup**: O time baixa os materiais do jogo, como cartas azuis (design) e vermelhas (tecnologias), e estuda o cenário.
2. **Iterations**:
   - Cada iteração apresenta um problema (ex.: processamento em lote, análise em tempo real).
   - Os jogadores escolhem soluções arquiteturais (cartas azuis) e tecnologias associadas (cartas vermelhas).
   - Pontos são atribuídos com base na adequação da solução aos drivers do problema.
3. **Final Score**: A pontuação total é calculada, mostrando a eficácia das decisões tomadas.

## Academic Applications
- **Aprendizado Prático**: Estudantes compreendem os trade-offs de decisões arquiteturais em Big Data.
- **Colaboração**: Enfatiza o trabalho em equipe e a tomada de decisões baseadas em dados.
- **Simulação Realista**: Oferece experiência prática em cenários reais de design de sistemas.

## Business Applications
- **Treinamento Corporativo**: Empresas podem usar o jogo para treinar equipes em design de sistemas complexos.
- **Prototipagem de Soluções**: Testar ideias arquiteturais antes de implementá-las em sistemas reais.
- **Avaliação de Competências**: Identificar pontos fortes e áreas de melhoria em equipes de arquitetura e desenvolvimento.

## Advantages in Business
- **Custo-efetivo**: Permite simulações sem riscos financeiros reais.
- **Decisões Informadas**: Equipes aprendem a priorizar drivers como custo, escalabilidade e performance.
- **Inovação**: Estimula criatividade ao explorar diferentes combinações de designs e tecnologias.

## Scoring System: How Points Are Assigned
O sistema de pontuação do jogo é baseado em três categorias principais:

1. **Design Points** (Blue Cards):
   - Representam o impacto positivo do conceito de design arquitetural escolhido.
   - Cada carta azul possui estrelas que indicam a relevância para os drivers de qualidade definidos na iteração.
   - Exemplo: Um design com ★★★ em "Scalability" e "Ad-hoc Analysis" contribui com mais pontos se esses drivers forem prioritários.

2. **Technology Points** (Red Cards):
   - Avaliam as tecnologias selecionadas para implementar o design.
   - Assim como as cartas azuis, as cartas vermelhas possuem estrelas que refletem o impacto em atributos como performance, custo e confiabilidade.
   - Exemplo: O uso de "Fluentd" pode aumentar a pontuação em "Reliability" devido à sua robustez.

3. **Bonus Points** (Analysis):
   - Pontos extras são atribuídos com base na justificativa estratégica das escolhas.
   - Times que apresentam uma análise clara e alinhada ao problema recebem pontos adicionais de bônus.

### Fórmula Final:
A pontuação final de cada iteração é calculada como:

Iteration Total = (Design Points + Technology Points) + Bonus Points