# Desafio Criativo: Extraindo Insights de Feedbacks Bancários com IA

Projeto desenvolvido como parte do curso de **Generative AI** da [Digital Innovation One (DIO)](https://www.dio.me/).

## Sobre o Desafio
O objetivo deste desafio foi construir um **prompt estruturado de alta performance** para orientar modelos de Inteligência Artificial a analisarem feedbacks de clientes bancários. O foco principal é extrair gargalos operacionais, sentimentos e oportunidades de melhoria para apoiar a tomada de decisão das equipes de **Experiência do Cliente (CX)** e **Gestão de Produtos**.

A construção do comando seguiu uma metodologia em 3 passos:
1. **Definição da Intenção:** Objetivo, público-alvo e entrega esperada.
2. **Contexto e Restrições:** Definição dos dados disponíveis, critérios de análise e regras de segurança/LGPD.
3. **Prompt Final Estruturado:** Consolidação em um comando pronto para execução.

---

## Prompt Final Estruturado

> **Papel:** Atue como analista sênior de Dados e Experiência do Cliente (CX) em uma instituição bancária.
>
> **Tarefa:** Analisar a base de feedbacks de clientes sobre os serviços bancários (App, Pix, Cartões e Atendimento) para identificar padrões, principais dores e oportunidades de melhoria operacional e de produto.
>
> **Contexto:** A análise servirá de insumo direto para reuniões de priorização do time de Produto e CX. O objetivo central é transformar comentários brutos em decisões estratégicas de rápida execução.
>
> **Dados Disponíveis:** Registos contendo ID, Data, Canal, Produto, Nota (1 a 5) e Comentário do Cliente.
>
> **Instruções de Análise:**
> 1. Classifique cada feedback por **Tema** (ex: Usabilidade, Falha Técnica, Atendimento, Custos), **Sentimento** (Positivo, Neutro, Negativo) e **Urgência** (Baixa, Média, Alta).
> 2. Identifique os padrões mais críticos de reclamações e os pontos fortes elogiados.
> 3. Utilize trechos curtos dos comentários como evidências para validar cada ponto identificado.
> 4. Proponha ações práticas de melhoria indicando a área responsável (ex: TI, Produto, Operações/Atendimento).
>
> **Formato da Resposta:**
> - **Resumo Executivo:** Um parágrafo de até 5 linhas consolidando o cenário geral.
> - **Tabela de Diagnóstico:** Colunas para *Tema*, *Sentimento*, *Urgência*, *Evidência (Trecho do Comentário)* e *Ação Sugerida*.
> - **Top 3 Prioridades:** Lista final objetiva com as 3 ações mais urgentes que o banco deve tomar.
>
> **Restrições & Cuidados:**
> - Baseie-se estritamente nos dados fornecidos. Não invente estatísticas, motivos ou dados que não constem na base.
> - Preserve total sigilo e não solicite nem exiba dados pessoais sensíveis (PII / LGPD).
> - Caso o volume ou o teor dos dados seja insuficiente para um diagnóstico completo, aponte essa limitação na resposta.
> - Utilize linguagem clara, humanizada, objetiva e voltada para negócios.

---

## Tecnologias e Conceitos Utilizados
- **Engenharia de Prompt (Prompt Engineering)**
- **IAG / Generative AI**
- **Análise de Sentimento e Feedback de Clientes (CX)**
- **Markdown & Git/GitHub**
