# B2B Service Contract Intelligence

![Banner do Projeto](https://i.postimg.cc/J0Vn3gCw/Chat-GPT-Image-30-de-jun-de-2026-23-30-44.png)

> **Você assinaria um contrato de R$ 500.000 sem uma segunda opinião?**
>
> O projeto **B2B Service Contract Intelligence** explora o uso do Google NotebookLM como uma ferramenta de Inteligência Artificial aplicada à análise de contratos de prestação de serviços entre empresas (B2B), utilizando técnicas de **Retrieval-Augmented Generation (RAG)**, curadoria documental e engenharia de prompts para transformar documentos jurídicos complexos em conhecimento acionável.

---

# 📖 Contexto do Projeto

Contratos de prestação de serviços B2B frequentemente possuem:

- cláusulas complexas;
- obrigações assimétricas entre as partes;
- multas e penalidades elevadas;
- riscos operacionais e financeiros;
- SLAs mal definidos;
- responsabilidades jurídicas pouco claras;
- cláusulas de confidencialidade insuficientes;
- riscos relacionados à LGPD e proteção de dados.

Pequenas e médias empresas raramente possuem departamentos jurídicos internos capazes de revisar todos os contratos com profundidade antes da assinatura.

Este projeto investiga como o **Google NotebookLM** pode atuar como um **Assistente Inteligente de Análise Contratual**, permitindo identificar riscos, resumir documentos extensos e apoiar decisões estratégicas de forma rápida e eficiente.

---

# 🎯 Objetivos do Estudo

Os principais objetivos deste caderno temático foram:

- Estudar a aplicação de IA Generativa em análise documental jurídica;
- Explorar o uso do NotebookLM como ferramenta de aprendizagem ativa;
- Avaliar a capacidade do modelo em identificar riscos contratuais;
- Desenvolver prompts reutilizáveis para análise de contratos B2B;
- Construir uma base de conhecimento especializada em contratos empresariais;
- Demonstrar um caso de uso real e com potencial comercial para IA aplicada aos negócios;
- Investigar como RAG pode aumentar a confiabilidade das respostas em ambientes jurídicos.

---

# 🔗 Acesso ao Projeto

## Notebook Público

O notebook desenvolvido durante este estudo pode ser acessado através do link abaixo:

👉 https://notebooklm.google.com/notebook/a9c65735-5f63-4a84-a102-0ec29859f74b

---

# 📚 Curadoria de Fontes

Para construir a base de conhecimento do NotebookLM foram selecionadas fontes abertas e materiais jurídicos relacionados à gestão contratual empresarial.

## Gestão Contratual

- Gestão de Contratos Empresariais
- Auditoria contratual preventiva: checklist prático para reduzir riscos e evitar litígios
- Auditoria de contratos: o que é e como fazer passo a passo

## Contratos de Prestação de Serviços B2B

- Contrato de Prestação de Serviços entre empresas: cláusulas essenciais e riscos
- Contratos B2B: cláusulas essenciais para proteção empresarial
- Segurança jurídica em serviços digitais: como minimizar riscos e litígios em contratações entre empresas (B2B)

## Confidencialidade e Proteção de Informações

- Como elaborar um NDA eficiente e evitar erros comuns
- Modelo de acordo de confidencialidade
- Confidencialidade: princípio, NDA, cláusula e quebra
- Termo de confidencialidade: o que é e quando utilizar

## SLA e Governança Operacional

- Indicadores SLA: guia completo
- Indicadores de SLA: o que é e quais são os principais
- Tipos de métricas de SLA (IBM)

## Aspectos Jurídicos e Responsabilidade Civil

- Inadimplemento contratual: conceito, classificação e remédios
- O inadimplemento à luz do Código Civil
- O que é responsabilidade civil e quais seus reflexos em danos
- O que muda com a LGPD

## Materiais Complementares

- Renovação automática e seus contornos à luz da Lei do Contrato de Seguro
- Lei Geral de Proteção de Dados (LGPD)
- Manual jurídico do Tribunal de Justiça do Estado de São Paulo

---

# 🤖 Engenharia de Prompts

Um dos principais objetivos do projeto foi explorar como pequenas alterações nos prompts impactam significativamente a qualidade das respostas.

---

## Prompt 1 — Análise de Riscos Contratuais

### Prompt utilizado

```text
Identifique os principais riscos financeiros, jurídicos e operacionais presentes neste contrato de prestação de serviços B2B.
```

### Objetivo

Mapear rapidamente os pontos de maior exposição da empresa antes da assinatura do contrato.

### Resultado obtido

O NotebookLM foi capaz de:

- identificar cláusulas de risco;
- classificar obrigações críticas;
- apontar potenciais desequilíbrios contratuais;
- destacar riscos operacionais e jurídicos relevantes.

---

## Prompt 2 — Resumo Executivo

### Prompt utilizado

```text
Crie um resumo executivo deste contrato para um CEO que possui apenas 3 minutos para leitura.
```

### Objetivo

Transformar documentos extensos em informação estratégica para tomada de decisão.

### Resultado obtido

A IA sintetizou:

- prazo contratual;
- multas;
- obrigações principais;
- riscos críticos;
- pontos de atenção;
- possíveis impactos financeiros.

---

## Prompt 3 — Obrigações Contratuais

### Prompt utilizado

```text
Liste separadamente todas as obrigações da contratante e da contratada.
```

### Objetivo

Facilitar a compreensão operacional do contrato.

### Resultado obtido

Extração organizada das responsabilidades de cada parte envolvida.

---

## Prompt 4 — Penalidades e Rescisão

### Prompt utilizado

```text
Extraia todas as multas, penalidades e gatilhos de rescisão presentes neste contrato.
```

### Objetivo

Identificar rapidamente a exposição financeira da organização.

---

## Prompt 5 — NDA e Confidencialidade

### Prompt utilizado

```text
Como elaborar um NDA eficiente e quais erros devem ser evitados?
```

### Objetivo

Construir uma base de conhecimento sobre proteção de informações empresariais.

### Resultado obtido

Foram identificados:

- os principais elementos de um NDA;
- erros comuns em acordos de confidencialidade;
- boas práticas de governança da informação.

---

## Prompt 6 — SLA

### Prompt utilizado

```text
Quais indicadores de SLA devem ser monitorados em contratos de prestação de serviços?
```

### Objetivo

Melhorar governança operacional e gestão do fornecedor.

---

## Prompt 7 — Mudanças Regulatórias

### Prompt utilizado

```text
Quais as principais mudanças na renovação automática de seguros?
```

### Objetivo

Avaliar a capacidade do NotebookLM de identificar mudanças legislativas e regulatórias.

---

# ⚠️ Cicatrizes e Aprendizados

Durante a utilização do NotebookLM foram identificadas algumas limitações e oportunidades de melhoria.

## Problema 1 — Prompts Genéricos

### Prompt inicial

```text
Existe algum risco neste contrato?
```

### Resultado

Resposta superficial e pouco acionável.

### Solução adotada

```text
Identifique riscos financeiros, jurídicos e operacionais e classifique-os por severidade.
```

### Resultado após melhoria

- respostas mais objetivas;
- melhor organização das informações;
- maior utilidade prática para tomada de decisão.

---

## Problema 2 — Escopo Excessivamente Amplo

Ao incluir muitos temas jurídicos diferentes, algumas respostas se tornaram menos especializadas.

### Solução adotada

Organização das fontes em categorias:

- contratos B2B;
- SLA;
- NDA;
- LGPD;
- inadimplemento;
- responsabilidade civil.

---

## Problema 3 — Fontes Muito Genéricas

Alguns conteúdos da web apresentavam excesso de contextualização e pouca aplicação prática.

### Solução adotada

Priorização de:

- artigos jurídicos especializados;
- guias técnicos;
- materiais de escritórios de advocacia;
- documentação oficial.

---

# 📘 Miniguia de Estudo

## Contratos B2B

São acordos firmados entre empresas para fornecimento de produtos ou prestação de serviços.

---

## NDA

Documento responsável pela proteção de informações confidenciais e segredos comerciais.

---

## SLA

Acordo de Nível de Serviço responsável por definir métricas, indicadores e expectativas de desempenho.

---

## Inadimplemento

Ocorre quando uma das partes deixa de cumprir suas obrigações contratuais.

---

## LGPD

Lei responsável pela proteção de dados pessoais e privacidade.

---

## Responsabilidade Civil

Determina a obrigação de reparar danos causados pelo descumprimento contratual.

---

## Gestão Contratual

Conjunto de práticas voltadas ao acompanhamento da execução, renovação e encerramento dos contratos.

---

# 📖 Glossário

| Termo | Definição |
|------|-----------|
| B2B | Business to Business |
| NDA | Non-Disclosure Agreement |
| SLA | Service Level Agreement |
| LGPD | Lei Geral de Proteção de Dados |
| RAG | Retrieval-Augmented Generation |
| Inadimplemento | Descumprimento contratual |
| Compliance | Conformidade regulatória |
| Due Diligence | Processo de investigação prévia |
| CLM | Contract Lifecycle Management |
| KPI | Key Performance Indicator |

---

# 🔁 Prompts Reutilizáveis

```text
Identifique riscos financeiros, jurídicos e operacionais deste contrato.
```

```text
Crie um resumo executivo para a diretoria.
```

```text
Liste as obrigações da contratante e da contratada.
```

```text
Extraia todas as multas e penalidades previstas.
```

```text
Quais cláusulas deveriam ser renegociadas?
```

```text
Quais indicadores de SLA devem ser monitorados?
```

```text
Existe desequilíbrio contratual entre as partes?
```

```text
Qual é a exposição financeira máxima prevista neste contrato?
```

```text
Quais cláusulas podem gerar litígios futuros?
```

```text
Quais obrigações estão relacionadas à LGPD?
```

---

# 🛠️ Tecnologias Utilizadas

- Google NotebookLM
- Inteligência Artificial Generativa
- Retrieval-Augmented Generation (RAG)
- Engenharia de Prompts
- Curadoria de Conhecimento
- Gestão Documental

---

# 🚀 Aplicações Empresariais

Este tipo de solução pode ser aplicado em:

- departamentos jurídicos;
- empresas de tecnologia;
- consultorias;
- empresas de facilities;
- prestadores de serviços;
- gestão de fornecedores;
- compras e suprimentos;
- compliance corporativo;
- empresas de outsourcing.

---

# 📷 Recursos Utilizados no NotebookLM

Durante o desenvolvimento do projeto foram exploradas diversas funcionalidades da plataforma:

✅ Conversas contextuais com múltiplas fontes  
✅ Flashcards automáticos  
✅ Resumos inteligentes  
✅ Organização temática das fontes  
✅ Busca contextual baseada em RAG  
✅ Aprendizagem ativa utilizando IA

---

# 🏆 Conclusão

Este projeto demonstrou que ferramentas de IA generativa podem ir muito além da simples geração de texto, atuando como verdadeiros assistentes especializados capazes de apoiar decisões empresariais críticas.

Mais do que um exercício acadêmico, este projeto representa uma aplicação prática de IA em um problema real do mercado corporativo: a análise e mitigação de riscos em contratos de prestação de serviços B2B.

O resultado final foi a construção de uma base de conhecimento especializada capaz de transformar documentos jurídicos extensos em informações estratégicas para gestores, empresários e tomadores de decisão.

---

# 👨‍💻 Autor

**Jefferson Campina**

Projeto desenvolvido como parte do desafio prático da DIO sobre utilização do NotebookLM como ferramenta de aprendizagem ativa e construção de conhecimento especializado.

---

## ⭐ Se este projeto foi interessante para você, considere deixar uma estrela no repositório.
