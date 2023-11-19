# Projeto Final - Predição de Rotatividade de Clientes para a Interconnect

## Descrição do Projeto

A Interconnect, uma operadora de comunicações, está empenhada em prever a rotatividade de seus clientes para tomar medidas proativas e estratégicas. A ameaça de perder clientes impacta diretamente a receita e a lucratividade da empresa. O objetivo é desenvolver modelos preditivos que identifiquem padrões ou sinais de alerta indicando que um cliente está considerando cancelar seus serviços. Ao detectar esses sinais, a Interconnect pretende oferecer incentivos personalizados, como códigos promocionais e opções de plano especiais, para manter os clientes satisfeitos e engajados.

## "Dor" a Ser Resolvida

A principal "dor" que a Interconnect busca resolver é a ameaça de rotatividade de clientes. A perda de clientes não apenas impacta a receita imediata, mas também implica custos significativos na aquisição de novos clientes. Ao antecipar a intenção de um cliente de trocar de operadora, a Interconnect planeja agir proativamente, oferecendo soluções personalizadas para manter a base de clientes existente.

## Objetivo

O objetivo central do projeto é desenvolver modelos preditivos robustos que permitam à Interconnect identificar antecipadamente clientes propensos à rotatividade. Isso envolve a análise de dados pessoais, informações contratuais e detalhes sobre os serviços utilizados pelos clientes. Ao compreender os padrões que precedem a decisão de cancelamento, a empresa pode implementar estratégias preventivas para aumentar a satisfação do cliente e, consequentemente, reter clientes, impulsionando a receita e a lucratividade.

## Serviços da Interconnect

A Interconnect oferece uma variedade de serviços, incluindo:

1. **Telefonia Fixa:** Conexão a várias linhas simultaneamente.
2. **Internet:** Estabelecida através de DSL (*Digital Subscriber Line*) ou fibra óptica.
3. **Segurança na Internet:** Antivírus (*DeviceProtection*) e bloqueador de sites maliciosos (*OnlineSecurity*).
4. **Suporte Técnico Dedicado:** (*TechSupport*).
5. **Armazenamento de Dados na Nuvem e Backup:** (*OnlineBackup*).
6. **Streaming de TV:** (*StreamingTV*) e um diretório de filmes (*StreamingMovies*).

Os clientes têm a opção de escolher entre pagamento mensal e contratos de 1 ou 2 anos, com diversos métodos de pagamento disponíveis.

## Condições da Tarefa Principal

Os dados para análise foram coletados de fontes diferentes e incluem:

- `contract.csv` — Informação contratual.
- `personal.csv` — Dados pessoais do cliente.
- `internet.csv` — Informação sobre serviços de Internet.
- `phone.csv` — Informação sobre serviços de telefonia.

Cada cliente é identificado pelo código único `customerID`, e a informação contratual é válida a partir de 1 de fevereiro de 2020.

## Procedimentos do Projeto

Para atingir o objetivo, o projeto seguirá as seguintes etapas:

1. **Exploração de Dados:** Análise inicial dos conjuntos de dados para compreender a estrutura e identificar padrões preliminares.

2. **Pré-processamento de Dados:** Limpeza e formatação dos dados para prepará-los para análise. Tratamento de valores ausentes, duplicatas e etc.

3. **Análise Descritiva:** Exploração mais aprofundada dos dados para identificar correlações e padrões relevantes.

4. **Desenvolvimento de Modelos Preditivos:** Utilização de técnicas de aprendizado de máquina para desenvolver modelos que prevejam a rotatividade de clientes.
