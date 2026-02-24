# 🚀 InsightFlow - Planejamento de Produto Digital com IA

**Trabalho de Gestão de Projetos**  
**Tema:** Do Problema ao Produto: Planejamento de um Produto Digital com IA, MVP e Roadmap

---

## 📑 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Artefatos Criados](#-artefatos-criados)
- [Como Navegar](#-como-navegar)
- [Lógica do Planejamento](#-lógica-do-planejamento)
- [Metodologias Aplicadas](#-metodologias-aplicadas)
- [Estrutura dos Arquivos](#-estrutura-dos-arquivos)
- [Como Usar Cada Artefato](#-como-usar-cada-artefato)
- [Tecnologias e Ferramentas](#-tecnologias-e-ferramentas)
- [Referências](#-referências)
- [Contato](#-contato)

---

## 📋 Sobre o Projeto

### Contexto

Este projeto apresenta o **planejamento estratégico completo** de um produto digital chamado **InsightFlow**, uma plataforma SaaS que utiliza IA Generativa para transformar dados de atendimento ao cliente em insights acionáveis.

### Desafio

Empresas de tecnologia enfrentam um problema crítico: times de Customer Success/Suporte recebem volumes massivos de tickets (1.000+/dia) mas não conseguem:
- Priorizar temas críticos em tempo real
- Identificar padrões de insatisfação
- Gerar planos de ação rapidamente

### Solução Proposta

**InsightFlow** é uma plataforma de análise inteligente que utiliza IA Generativa (GPT-4/Claude) para:
- ✅ Detectar crises **72h mais rápido** que processos manuais
- ✅ Alcançar **90%+ de precisão** em priorização de urgência
- ✅ Gerar **planos de ação automáticos** para cada tema crítico

---

## 📦 Artefatos Criados

Este projeto contém **4 artefatos principais** desenvolvidos segundo as melhores práticas de gestão de projetos e produtos:

| # | Artefato | Formato | Descrição |
|---|----------|---------|-----------|
| 1️⃣ | **Lean Canvas** | HTML + PDF | Visão estratégica do produto em 9 blocos |
| 2️⃣ | **Documento de MVP** | HTML + CSV | 12 features priorizadas com critérios de aceitação |
| 3️⃣ | **Roadmap Visual** | HTML + Markdown | Timeline de 6 meses dividido em 3 fases |
| 4️⃣ | **Matriz de Riscos** | HTML + CSV | 9 riscos mapeados com planos de mitigação |

### Arquivos Disponíveis

```
/outputs/
├── InsightFlow_LeanCanvas.html          # Canvas visual interativo
├── insightflow_mvp_document.html        # Documento de MVP completo
├── insightflow_mvp_features.csv         # Features em formato planilha
├── insightflow_roadmap.html             # Roadmap visual com Gantt
├── insightflow_roadmap.md               # Roadmap em Markdown (Notion/Trello)
├── insightflow_risk_matrix.html         # Matriz de riscos visual
├── insightflow_risk_matrix.csv          # Riscos em formato planilha
└── README.md                            # Este arquivo
```

---

## 🧭 Como Navegar

### Fluxo de Leitura Recomendado

Para entender o planejamento completo, recomendamos seguir esta sequência:

```
1. Lean Canvas → Entenda o modelo de negócio e proposta de valor
2. Documento MVP → Veja quais features serão desenvolvidas primeiro
3. Roadmap → Compreenda a evolução do produto em 6 meses
4. Matriz de Riscos → Conheça os riscos e estratégias de mitigação
```

### Visualização Rápida (5 minutos)

Se você tem pouco tempo, abra apenas os **arquivos HTML** no navegador:
1. `InsightFlow_LeanCanvas.html` (2 min)
2. `insightflow_roadmap.html` - vá direto para o Gantt (2 min)
3. `insightflow_risk_matrix.html` - veja apenas a matriz visual (1 min)

### Análise Profunda (30-60 minutos)

Para análise detalhada:
1. Abra todos os HTMLs no navegador (em abas separadas)
2. Leia o documento de MVP completo
3. Importe os CSVs no Google Sheets para análise de dados
4. Leia o `roadmap.md` no Notion para visão estruturada

---

## 💡 Lógica do Planejamento

### Por Que Priorizamos Essas Features no MVP?

O MVP foi definido usando a **metodologia MoSCoW**:

#### ✅ Must Have (Entraram no MVP)
**Critérios:**
- Resolve a **dor #1** do cliente (identificar crises rápido)
- **Viável tecnicamente** em 6-8 semanas
- Gera **diferenciação competitiva** (não é apenas BI)
- Permite **validar hipótese** central (usuários confiam na IA?)

**Exemplos:**
- Motor de IA (Sentimento, Categorização, Urgência) → Core do produto
- Dashboard Top 5 Críticos → Visualização essencial
- Gerador de Planos de Ação → Diferencial competitivo

#### 🟡 Should Have / Could Have (Ficaram para Fase 2)
**Por quê?**
- **Gráfico de Sentimento:** Nice to have, mas não é bloqueante para validar valor
- **Tendências Históricas:** Alto esforço (80h), valor menor que features core
- **Integração Intercom:** Cliente piloto usa apenas Zendesk

#### 🔴 Won't Have (Fase 3 ou descartado)
**Por quê?**
- **Chatbot de Respostas:** Complexidade alta (120h), risco de distrair do core
- **Multi-idiomas:** Cliente foca em PT-BR inicialmente

### Por Que 3 Fases no Roadmap?

```
Fase 1 (8 sem)  → Provar valor rápido com MVP
Fase 2 (10 sem) → Adicionar diferenciais e preparar para escala
Fase 3 (8 sem)  → Arquitetura industrial para 50+ clientes
```

**Justificativa:**
- **Menos de 3 fases:** Muito arriscado (apostar tudo no MVP)
- **Mais de 3 fases:** Perde foco, roadmap vira "lista de desejos"
- **6 meses total:** Balanceia validação rápida + construção sólida

### Como Interpretamos os Riscos?

**Fórmula:** `Score = Probabilidade (1-5) × Impacto (1-5)`

**Classificação:**
- 🔴 **Crítico (16-25):** Ação imediata necessária
- 🟡 **Médio (8-15):** Plano de mitigação obrigatório
- 🟢 **Baixo (1-6):** Monitorar periodicamente

**Exemplo:**
- **R2 (IA Baixa Precisão):** Prob=4, Impacto=4 → Score=16 (Crítico)
  - **Por quê crítico?** Se IA falha, clientes perdem confiança e produto morre
  - **Mitigação:** Human-in-the-loop + Dashboard de precisão semanal

---

## 🔧 Metodologias Aplicadas

### Gestão de Produto
- **Lean Canvas:** Modelo de negócio em 1 página (Ash Maurya)
- **MoSCoW:** Priorização de features (Must/Should/Could/Won't)
- **OKRs:** Objetivos e Key Results para cada fase
- **Build-Measure-Learn:** Ciclo de validação contínua (Lean Startup)

### Gestão de Projetos
- **PMBOK 7th Edition:** Gestão de riscos e ciclo de vida
- **Scrum:** Sprints de 2 semanas, daily standups, retrospectives
- **Gantt Chart:** Timeline visual de 6 meses
- **Exit Criteria:** Gates de qualidade entre fases

### IA e Produto
- **Explainable AI:** Transparência nas classificações da IA
- **Human-in-the-Loop:** Supervisão humana para aumentar precisão
- **Fairness Auditing:** Auditoria de viés algorítmico
- **Continuous Learning:** Re-treinamento mensal com feedback

---

## 📂 Estrutura dos Arquivos

### 1️⃣ Lean Canvas (`InsightFlow_LeanCanvas.html`)

**O que contém:**
- 9 blocos do Lean Canvas preenchidos
- Proposta de valor destacada
- Modelo de receita (3 tiers de pricing)
- Estrutura de custos detalhada
- Métricas-chave de sucesso

**Como usar:**
- Abra no navegador para visualização
- Ctrl+P para salvar como PDF
- Use em apresentações para stakeholders
- Compartilhe com investidores ou clientes

**Insights-chave:**
- **Proposta de Valor:** "Da montanha de dados ao plano de ação em 5 minutos"
- **Receita (Mês 12):** R$ 225K MRR com 50 clientes
- **Margem Esperada:** 60% após otimização (Fase 3)

---

### 2️⃣ Documento de MVP (`insightflow_mvp_document.html` + `.csv`)

**O que contém:**
- 12 features mapeadas e priorizadas
- 5 Must Have (MVP core)
- Critérios de aceitação para cada feature
- Estimativas de esforço (em horas)
- Timeline de desenvolvimento (8 semanas)

**Como usar:**

**HTML:**
- Visualização completa com cards de features
- Estatísticas: 8 features MVP, 296h esforço total
- Justificativa de priorização incluída

**CSV:**
- Importe no Google Sheets ou Excel
- Crie filtros por prioridade ou responsável
- Adicione colunas customizadas (status, % progresso)
- Fórmulas de soma de esforço

**Como interpretar:**

| Prioridade | Cor | Significado | Vai no MVP? |
|------------|-----|-------------|-------------|
| Must Have | 🟢 Verde | Essencial para resolver dor principal | ✅ Sim |
| Should Have | 🔵 Azul | Importante mas não bloqueante | Se sobrar tempo |
| Could Have | 🟡 Amarelo | Nice to have | ❌ Fase 2 |
| Won't Have | 🔴 Vermelho | Complexidade alta ou valor incerto | ❌ Fase 2-3 |

**Exemplo de leitura:**

```
F1: Motor de IA - Análise de Sentimento
├─ Prioridade: Must Have (entra no MVP)
├─ Esforço: 40h
├─ Responsável: ML Engineer
├─ Critérios de Aceitação:
│  ✓ Precisão ≥ 85% validada com 500 tickets
│  ✓ Processar 100 tickets em < 5 minutos
│  ✓ API retorna JSON com sentimento + confidence
│  ✓ Logs de erro para tickets que falharem
└─ Status: Planejado (Fase 1)
```

---

### 3️⃣ Roadmap Visual (`insightflow_roadmap.html` + `.md`)

**O que contém:**

**HTML:**
- Timeline Gantt de 6 meses
- 3 fases com cards visuais de entregáveis
- Exit criteria para cada fase
- Milestone timeline vertical
- Tabela de evolução de métricas

**Markdown:**
- Formato texto estruturado
- Ideal para Notion, GitHub Projects ou Trello
- Checkboxes interativos
- Tabelas editáveis

**Como usar:**

**Para Apresentações:**
1. Abra o HTML no navegador
2. Dê scroll até o Gantt Chart
3. Screenshot ou Ctrl+P para PDF
4. Use em reuniões de kickoff ou board meetings

**Para Gestão Diária:**
1. Copie o `.md` para o Notion
2. Converta em timeline view
3. Adicione checkboxes interativos
4. Atribua responsáveis e datas

**Como interpretar as fases:**

#### Fase 1: Fundação (Semanas 1-8)
**Objetivo:** Validar que IA funciona e usuários confiam  
**Exit Criteria:**
- ✅ 3 clientes piloto usando diariamente
- ✅ NPS ≥ 40
- ✅ Tempo de crise reduzido 50%+

**Se NÃO passar:**
- ❌ NPS < 40 → Investigar causas, corrigir antes de escalar
- ❌ IA < 90% precisão → Pausar, melhorar modelo

#### Fase 2: Expansão (Semanas 9-18)
**Objetivo:** Adicionar diferenciais e preparar para escala  
**Exit Criteria:**
- ✅ 10 clientes pagantes
- ✅ Churn < 10%
- ✅ IA com 95%+ precisão

#### Fase 3: Escala (Semanas 19-26)
**Objetivo:** Arquitetura industrial para 50+ clientes  
**Exit Criteria:**
- ✅ 50+ clientes ativos
- ✅ ARR > $500K
- ✅ CAC Payback < 6 meses

**Milestones Principais:**

| Semana | Milestone | O Que Acontece |
|--------|-----------|----------------|
| Sem 0 | Kick-off | Setup inicial, onboarding de 3 pilotos |
| Sem 4 | Motor IA | Pipeline de IA com 85%+ precisão |
| Sem 8 | MVP Live | 3 pilotos ativos, Go/No-Go Fase 2 |
| Sem 12 | Pagantes | 5 clientes pagos, MRR R$ 22.5K |
| Sem 18 | PMF | 10 clientes, churn < 10% |
| Sem 26 | Escala | 50+ clientes, ARR $500K+ |

---

### 4️⃣ Matriz de Riscos (`insightflow_risk_matrix.html` + `.csv`)

**O que contém:**

**HTML:**
- Matriz 5×5 de Probabilidade × Impacto
- 9 riscos posicionados visualmente
- Cards detalhados com planos de mitigação
- Dashboard de estatísticas (3 críticos, 4 médios, 2 baixos)

**CSV:**
- Tabela estruturada para análise
- Importável no Excel/Sheets
- Colunas: ID, Risco, Categoria, Prob, Impacto, Score, Mitigação, Responsável

**Como usar:**

**Para Tomada de Decisão:**
1. Abra o HTML no navegador
2. Identifique os **3 riscos críticos** (vermelho)
3. Leia os planos de mitigação
4. Atribua responsáveis e prazos

**Para Acompanhamento Semanal:**
1. Importe CSV no Google Sheets
2. Crie coluna "Status" (Ativo/Mitigado/Materializado)
3. Filtro por responsável
4. Revise semanalmente em reunião de risco

**Como interpretar a matriz:**

```
      1       2       3       4       5
    ┌───────────────────────────────────┐
  5 │  🟢   🟡   🔴   🔴   🔴  │ Catastrófico
  4 │  🟢   🟢   🟡   🔴   🔴  │ Alto
  3 │  🟢   🟢   🟡   🟡   🔴  │ Moderado
  2 │  🟢   🟢   🟢   🟡   🟡  │ Menor
  1 │  🟢   🟢   🟢   🟢   🟡  │ Insignificante
    └───────────────────────────────────┘
     Raro  Improvável Possível Provável Quase Certo
```

**Riscos Críticos (Ação Imediata):**

| ID | Risco | Score | Ação Prioritária |
|----|-------|-------|------------------|
| R1 | Violação LGPD | 15 | Implementar criptografia + DPO review |
| R2 | IA Baixa Precisão | 16 | Human-in-the-loop + Dashboard de precisão |
| R3 | Dependência APIs | 15 | Fallback para 2 provedores (OpenAI + Anthropic) |

**Triggers de Ação:**
- **R1:** Qualquer incidente de acesso não autorizado → PAUSAR tudo, investigar
- **R2:** F1-score < 85% em qualquer semana → Revisão urgente do modelo
- **R3:** Downtime API > 1h → Ativar fallback imediatamente

---

## 🛠️ Tecnologias e Ferramentas

### Stack Técnico Proposto (MVP)

**Backend:**
- Python 3.11+ (FastAPI)
- PostgreSQL (dados estruturados)
- Redis (cache)

**IA/ML:**
- OpenAI GPT-4 API ou Anthropic Claude
- LangChain (orquestração)
- Scikit-learn (avaliação de modelos)

**Frontend:**
- React 18+ (Next.js)
- Tailwind CSS
- Recharts (visualizações)

**Infraestrutura:**
- AWS (ECS, RDS, S3)
- Datadog (monitoramento)
- GitHub Actions (CI/CD)

### Ferramentas de Gestão

**Planejamento:**
- Notion (roadmap e documentação)
- Miro (workshops e brainstorming)
- Figma (design de interfaces)

**Desenvolvimento:**
- GitHub (código)
- Jira (tracking de tarefas)
- Slack (comunicação)

**Métricas:**
- Mixpanel ou PostHog (product analytics)
- Google Sheets (análise de riscos)
- Looker (dashboards executivos)

---

## 📚 Referências

### Bibliográficas

1. **PMI** (2021). *A Guide to the Project Management Body of Knowledge (PMBOK Guide) – 7th Edition*.
   - Gestão de riscos, ciclo de vida, governança

2. **Schwaber, K., & Sutherland, J.** (2020). *The Scrum Guide*.
   - Frameworks ágeis, sprints, cerimônias
   - Disponível em: https://scrumguides.org

3. **Ries, E.** (2011). *The Lean Startup*.
   - Build-Measure-Learn, MVP, pivots

4. **Cagan, M.** (2018). *Inspired: How to Create Tech Products Customers Love*.
   - Gestão de produtos, discovery, validação

5. **Maurya, A.** (2012). *Running Lean: Iterate from Plan A to a Plan That Works*.
   - Lean Canvas, priorização, métricas

### Frameworks e Metodologias

- **MoSCoW Prioritization:** Dai Clegg (1994)
- **Lean Canvas:** Ash Maurya (adaptação do Business Model Canvas)
- **OKRs:** John Doerr (Google)
- **RICE Score:** Intercom (Reach × Impact × Confidence / Effort)

### Artigos e Recursos Online

- **Anthropic Documentation:** Melhores práticas com LLMs
  - https://docs.anthropic.com

- **Google People + AI Guidebook:** Design de produtos com IA
  - https://pair.withgoogle.com

- **IBM AI Fairness 360:** Auditoria de viés algorítmico
  - https://aif360.mybluemix.net

---

## 📊 Métricas de Sucesso do Projeto

### MVP (Fase 1)
- ✅ 3 clientes piloto usando diariamente por 2 semanas
- ✅ NPS ≥ 40
- ✅ Tempo de identificação de crises: 3 dias → 12h (80% redução)
- ✅ Precisão da IA: 90%+

### Product-Market Fit (Fase 2)
- ✅ 10 clientes pagantes
- ✅ Churn < 10%
- ✅ Feature adoption: 70% dos clientes usam ≥3 funcionalidades
- ✅ MRR: R$ 45K

### Escala (Fase 3)
- ✅ 50+ clientes ativos
- ✅ ARR > $500K
- ✅ CAC Payback < 6 meses
- ✅ NPS ≥ 50
- ✅ Uptime 99.5%+

---

## ❓ FAQ - Perguntas Frequentes

### 1. Por que usar IA Generativa e não modelos tradicionais de ML?

**Resposta:** Modelos tradicionais (ex: Random Forest, SVM) exigem:
- Centenas de milhares de tickets anotados manualmente (custo proibitivo)
- Re-treinamento complexo para cada cliente (taxonomias diferentes)

IA Generativa (GPT-4/Claude) permite:
- ✅ Few-shot learning (funciona com poucos exemplos)
- ✅ Adaptação rápida para taxonomias customizadas
- ✅ Explicabilidade natural (descreve o raciocínio em linguagem humana)

**Trade-off:** Custo de API mais alto → Mitigado com cache + migração futura para modelo próprio (Fase 3)

---

### 2. Como o MVP valida se o produto resolve o problema?

**Hipóteses que o MVP testa:**

| Hipótese | Como Validar | Métrica de Sucesso |
|----------|--------------|-------------------|
| H1: IA categoriza melhor que processo manual | Comparar precisão IA vs. humano em 1.000 tickets | Precisão IA ≥ 85% |
| H2: Alertas chegam antes de crises escalarem | Medir tempo de detecção (antes vs. depois) | 3 dias → 12h |
| H3: Planos de ação economizam tempo do time | Survey com usuários piloto | 80% consideram "úteis" |

**Se alguma hipótese falhar:** Pivotamos antes de gastar 6 meses construindo features erradas.

---

### 3. Por que Zendesk como primeira integração?

**Dados de mercado:**
- 40% das empresas B2B SaaS usam Zendesk (líder de mercado)
- API bem documentada e estável
- Clientes piloto já confirmados usam Zendesk

**Próximas integrações (Fase 2):**
- Intercom (15% do mercado)
- Freshdesk (10% do mercado)

---

### 4. Como garantir privacidade/LGPD se enviamos tickets para LLM?

**Estratégias de Segurança:**

1. **Tokenização de PII:** Antes de enviar para GPT-4, substituímos:
   - Emails → `[EMAIL_HASH_12345]`
   - CPF → `[CPF_HASH_67890]`
   - Nomes → `[NOME_HASH_ABCDE]`

2. **Contrato com OpenAI/Anthropic:**
   - Cláusula de não-treinamento com dados do cliente
   - Retenção de dados < 30 dias

3. **Auditoria:**
   - DPO (Data Protection Officer) revisa arquitetura
   - Pentest semestral
   - Certificação ISO 27001 (Fase 2)

---

### 5. E se a API do OpenAI aumentar o preço 10x?

**Plano de Contingência (R3):**

**Curto Prazo (Fase 1-2):**
- Fallback para Anthropic Claude (já implementado)
- Cache agressivo (40% dos tickets não precisam reprocessamento)
- Otimização de prompts (-30% tokens)

**Longo Prazo (Fase 3):**
- Migrar para modelo open-source fine-tunado (Llama 3, Mistral)
- Hospedar em AWS EC2 com GPUs
- Custo: $3K/mês (vs. $15K/mês com API)

---

## 🎯 Próximos Passos

### Para Implementação Real

Se este projeto for executado de verdade, os próximos passos são:

**Semana 0 (Preparação):**
- [ ] Montar time (1 PM, 2 Devs, 1 ML Engineer, 1 Designer)
- [ ] Setup de infraestrutura (AWS, GitHub, Jira)
- [ ] Onboarding de 3 clientes piloto
- [ ] Assinatura de contratos (OpenAI/Anthropic API, Zendesk)

**Semana 1-2 (Sprint 1):**
- [ ] Implementar integração Zendesk (OAuth2 + Sync)
- [ ] Criar estrutura de banco de dados
- [ ] Setup de ambiente de desenvolvimento

**Semana 3-4 (Sprint 2):**
- [ ] Desenvolver pipeline de IA (F1, F2, F3)
- [ ] Testes de precisão com 1.000 tickets históricos
- [ ] Beta interno com time de CS

**Semana 5-8 (Sprints 3-4):**
- [ ] Desenvolver dashboard MVP (F4)
- [ ] Implementar gerador de planos de ação (F6)
- [ ] Sistema de alertas (F8)
- [ ] QA + Security review
- [ ] Launch com 3 clientes piloto

---

## 📞 Contato

**Projeto Acadêmico:**
- Disciplina: Gestão de Projetos
- Instituição: Unifecaf
- Professor: PAULO LISBOA

**Autor:**
- Nome:Gabriel Barbosa Silva
- Email: gabriel.barbosa.avlis@gmail.com
- LinkedIn: https://www.linkedin.com/in/gabriel-barbosa-silva/
- GitHub: https://github.com/Gabriel-barbosa-silva

**Data:**
- Criação: Fevereiro 2026
- Última Atualização: [18/02/2026]

---

## 📄 Licença e Uso

Este projeto foi desenvolvido para fins acadêmicos como trabalho da disciplina de Gestão de Projetos.

**Uso Permitido:**
- ✅ Referência acadêmica (com citação)
- ✅ Estudo e aprendizado
- ✅ Portfolio pessoal

**Uso Restrito:**
- ❌ Comercialização sem autorização
- ❌ Cópia literal sem atribuição

---



## 📌 Notas Importantes

### Sobre a Viabilidade Técnica

Este planejamento foi baseado em:
- ✅ Experiências reais de produtos SaaS B2B
- ✅ Benchmarks de mercado (custos, prazos, precisão de IA)
- ✅ Melhores práticas de gestão de produtos e projetos

**Ressalvas:**
- Prazos podem variar conforme experiência do time
- Custos de IA dependem de volume real de tickets
- Precisão de modelos varia por domínio de dados

### Sobre as Métricas

Todas as métricas apresentadas (NPS, precisão de IA, churn, etc.) são:
- Baseadas em benchmarks reais da indústria
- Conservadoras (metas atingíveis)
- Validadas por casos de uso similares

---

## 🔄 Histórico de Revisões

| Versão | Data | Alterações |
|--------|------|------------|
| 1.0 | Fev/2026 | Versão inicial completa |
| - | - | - |

---

**🚀 Pronto para construir o futuro do Customer Success com IA!**

---

*README gerado como parte do Trabalho de Gestão de Projetos - Do Problema ao Produto*
