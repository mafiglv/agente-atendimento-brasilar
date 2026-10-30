# Agente de Atendimento Virtual — Brasilar Construção

## Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático de **Engenharia de Prompts**, realizado durante o **Bootcamp Bradesco, na plataforma DIO (Digital Innovation One)**.

O desafio consiste em elaborar um prompt capaz de definir o comportamento de um agente de Inteligência Artificial voltado ao atendimento ao cliente, estabelecendo suas responsabilidades, limites de atuação, regras de comunicação e critérios para encaminhamento ao atendimento humano.

Como cenário de aplicação, foi escolhida a **Brasilar Construção**, uma loja de materiais de construção, com o objetivo de propor uma solução para otimizar o atendimento aos clientes por meio do WhatsApp.

## Objetivo

Desenvolver um prompt estruturado para um agente virtual capaz de oferecer atendimento rápido, cordial e eficiente, auxiliando clientes em dúvidas frequentes sobre produtos, marcas, preços e disponibilidade.

A proposta busca reduzir o tempo de espera por informações simples, permitindo que os funcionários da loja concentrem seus esforços em situações que exigem intervenção humana.

## Funcionalidades Propostas

O agente foi projetado para:

- Consultar preços de produtos cadastrados.
- Informar marcas e produtos comercializados.
- Consultar disponibilidade de estoque, quando houver integração.
- Informar localização e horário de funcionamento.
- Esclarecer dúvidas básicas sobre características de produtos.
- Auxiliar na identificação de materiais conforme a necessidade do cliente.
- Sugerir alternativas disponíveis no catálogo.
- Organizar solicitações de orçamento.
- Identificar situações que exigem atendimento humano.

## Regras e Limitações

Para garantir um atendimento confiável, o prompt estabelece diretrizes como:

- Não inventar informações sobre preços, produtos ou estoque.
- Não solicitar dados pessoais sensíveis ou informações bancárias.
- Não oferecer descontos ou condições comerciais sem autorização.
- Não confirmar pedidos, pagamentos ou entregas.
- Utilizar informações oficiais fornecidas pela empresa.
- Reconhecer quando não possui informações suficientes.
- Encaminhar solicitações complexas para atendimento humano.
- Manter uma comunicação cordial, objetiva e acessível.

## Estrutura do Prompt

O prompt foi organizado considerando os seguintes elementos:

| Elemento | Descrição |
|---|---|
| Identidade | Define o papel e o ambiente de atuação do agente. |
| Público-alvo | Identifica os perfis de clientes atendidos. |
| Responsabilidades | Estabelece quais solicitações o agente pode resolver. |
| Objetivo | Determina o resultado esperado em cada atendimento. |
| Tom e formato | Padroniza a linguagem e a apresentação das respostas. |
| Regras | Define restrições e comportamentos obrigatórios. |
| Encaminhamento | Identifica situações que exigem intervenção humana. |
| Tratamento de incertezas | Orienta o agente a solicitar esclarecimentos e não inventar informações. |

## Acesse o Prompt

O prompt completo, com todas as instruções de comportamento e atendimento, está disponível no arquivo:

**[prompt-agente-atendimento-brasilar.md](./prompt-agente-atendimento-brasilar.md)**

## Tecnologias e Conceitos

- **Engenharia de Prompts:** estruturação de instruções para modelos de Inteligência Artificial.
- **Inteligência Artificial Generativa:** aplicação de modelos de linguagem ao atendimento ao cliente.
- **Markdown:** documentação técnica do projeto.
- **Git e GitHub:** versionamento e publicação do projeto.
- **Atendimento Conversacional:** definição de fluxos de interação e critérios de encaminhamento.

## Possibilidades de Evolução

Embora o projeto tenha como foco a construção do prompt, sua estrutura permite futuras evoluções, como:

- Integração com a API oficial do WhatsApp Business.
- Consulta de produtos e preços em banco de dados.
- Integração com sistemas de estoque e gestão comercial.
- Automação de fluxos de atendimento utilizando ferramentas como n8n.
- Implementação de uma base de conhecimento para consultas do agente.
- Desenvolvimento de testes para avaliar a qualidade e a precisão das respostas.

## Status do Projeto

**Concluído — Etapa de Engenharia de Prompts.**

O escopo atual contempla a elaboração e a documentação das instruções do agente. Não foram implementadas integrações externas nem realizado o desenvolvimento de um chatbot funcional.

## Considerações Finais

O desenvolvimento deste projeto permitiu aplicar conceitos fundamentais de Engenharia de Prompts, principalmente na definição de contexto, responsabilidades, limitações e regras de comportamento de um agente de IA.

A atividade demonstra como instruções claras e bem estruturadas podem contribuir para a construção de soluções de atendimento mais consistentes, seguras e alinhadas às necessidades de um negócio.

---

**Projeto desenvolvido para fins educacionais como parte de um desafio da DIO — Bootcamp Bradesco.**