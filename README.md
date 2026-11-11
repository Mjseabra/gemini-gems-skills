# 💎 Gemini Gems & AI Skills Catalog

> Coleção curada de **skills especializadas, personas avançadas e instruções de sistema** prontas para uso em **Google Gemini (Gems)**, **Claude Projects**, **Antigravity CLI / IDE** e **Custom GPTs**.

Cada skill foi desenhada com personas, restrições operacionais e fluxos metodológicos específicos para atuar como assistente de alto rendimento em diferentes contextos técnicos, analíticos e de negócio.

---

## 📂 Estrutura do Repositório

```text
gemini-gems-skills/
├── README.md              # Guia geral e contexto das skills
└── skills/                # Instruções e prompts de cada skill/gem
    ├── brainstorming.md
    ├── business-analyst.md
    ├── Caveman.md
    ├── documentation-and-adrs.md
    ├── EduGuide AI.md
    ├── generate-fresh-ideas.md
    ├── get-more-perspectives.md
    ├── humanizer-pt-br.md
    ├── i-have-adhd.MD
    ├── jde92.md
    ├── Prompmaster.md
    ├── Skill Creator.md
    └── sysaid.md
```

---

## 📌 Índice Rápido das Skills

| # | Skill | Arquivo | Domínio Principal | Foco / Aplicação |
|---|---|---|---|---|
| 1 | **Brainstorming Ideas Into Designs** | [`brainstorming.md`](skills/brainstorming.md) | Design & Arquitetura | Converte ideias brutas em especificações e arquiteturas validadas antes de codificar. |
| 2 | **Business Analyst** | [`business-analyst.md`](skills/business-analyst.md) | Negócios & Analytics | Análise de negócios, criação de KPIs, dashboards e recomendações baseadas em dados. |
| 3 | **Caveman Mode** | [`Caveman.md`](skills/Caveman.md) | Produtividade & Sintaxe | Respostas ultraconcisas e econômicas que eliminam enrolação, preservando 100% dos fatos técnicos. |
| 4 | **Documentation and ADRs** | [`documentation-and-adrs.md`](skills/documentation-and-adrs.md) | Engenharia de Software | Documentação de decisões de arquitetura (ADRs), focando no "porquê" e trade-offs. |
| 5 | **EduGuide AI** | [`EduGuide AI.md`](skills/EduGuide%20AI.md) | Educação & Carreiras | Orientador educacional socrático que mapeia habilidades e recomenda trilhas de cursos. |
| 6 | **Generate Fresh Ideas** | [`generate-fresh-ideas.md`](skills/generate-fresh-ideas.md) | Criação de Conteúdo | Cria 5 ângulos inéditos (remixes) a partir de notas, artigos ou transcrições de entrada. |
| 7 | **Get More Perspectives** | [`get-more-perspectives.md`](skills/get-more-perspectives.md) | Tomada de Decisão | Teste de estresse para decisões estratégicas através de um comitê de 5 consultores virtuais. |
| 8 | **Humanizer PT-BR** | [`humanizer-pt-br.md`](skills/humanizer-pt-br.md) | Redação & Edição | Elimina marcas e vícios de escrita de IA em português brasileiro, garantindo voz natural e fluida. |
| 9 | **i-have-adhd (Modo TDAH)** | [`i-have-adhd.MD`](skills/i-have-adhd.MD) | Acessibilidade & Foco | Respostas estruturadas para atenção de TDAH: foco na próxima ação imediata, sem distrações e passos numerados. |
| 10 | **Arquiteto JDE 9.2 Enterprise** | [`jde92.md`](skills/jde92.md) | ERP Oracle JD Edwards | Arquiteto sênior funcional/técnico em JDE 9.2 com domínio estrito da Localização Brasil e normas fiscais. |
| 11 | **Promptmaster** | [`Prompmaster.md`](skills/Prompmaster.md) | Engenharia de Prompt | Arquiteto de prompts que realiza entrevista diagnóstica reversa para construir prompts seguros e de alta performance. |
| 12 | **Skill Creator** | [`Skill Creator.md`](skills/Skill%20Creator.md) | Meta-Engenharia de IA | Metodologia completa para criar, testar, iterar e otimizar novas skills e benchmarks de IA. |
| 13 | **SysAid (Reescrita de Chamados JDE)** | [`sysaid.md`](skills/sysaid.md) | Suporte & Atendimento | Transforma diagnósticos técnicos do JDE em respostas humanas, empáticas e resolutivas para chamados. |

---

## 🚀 Como Utilizar

### 1. No Google Gemini (Gemini Gems)
1. Acesse o **Google Gemini** e clique em **Gerenciador de Gems** (ou *Gems* no menu lateral).
2. Clique em **Novo Gem**.
3. Defina o nome do Gem (ex.: `Promptmaster` ou `Humanizer PT-BR`).
4. Abra o arquivo correspondente na pasta [`skills/`](skills/) deste repositório, copie todo o seu conteúdo e cole no campo **Instruções**.
5. Salve e comece a conversar diretamente com a gema especializada!

### 2. No Claude (Claude Projects) ou Custom GPTs
- Adicione as instruções do arquivo `.md` correspondente na seção **System Prompt / Custom Instructions** do seu projeto ou assistente.

### 3. Em Ferramentas CLI / Agentes Autônomos (Antigravity, Cursor, Claude Code)
- Clone ou copie o arquivo da skill desejada diretamente para o diretório de skills configurado no seu ambiente (ex.: `~/.gemini/config/skills/<skill-name>/SKILL.md`).

---

## 🔍 Detalhamento das Skills

---

### 1. [`skills/brainstorming.md`](skills/brainstorming.md) — Brainstorming Ideas Into Designs
- **Categoria:** Engenharia de Software / Concepção de Produto
- **Objetivo:** Transformar conceitos vagos ou ideias brutas em especificações funcionais e designs robustos antes de qualquer implementação de código.
- **Quando usar:** Antes de iniciar novas funcionalidades, refatorações amplas ou mudanças arquiteturais.
- **Destaques:** 
  - Bloqueia explicitamente a escrita prematura de código enquanto o design não for validado.
  - Conduz diálogo estruturado para revelar suposições ocultas, requisitos não funcionais e potenciais armadilhas de arquitetura.

---

### 2. [`skills/business-analyst.md`](skills/business-analyst.md) — Business Analyst
- **Categoria:** Análise de Negócios / Estratégia de Dados
- **Objetivo:** Atuar como um analista de negócios sênior orientado a IA, focado em tomada de decisões data-driven.
- **Quando usar:** Ao estruturar projetos de negócios, modelar processos operacionais ou desenhar estratégias baseadas em métricas.
- **Destaques:**
  - Auxilia na construção de matrizes de KPIs, métricas de sucesso e dashboards em tempo real.
  - Provê modelos preditivos e recomendações acionáveis alinhadas aos objetivos estratégicos da organização.

---

### 3. [`skills/Caveman.md`](skills/Caveman.md) — Caveman Mode
- **Categoria:** Estilo de Resposta / Otimização de Leitura
- **Objetivo:** Entregar respostas técnicas com o menor número possível de tokens, eliminando saudações, enrolações e clichês conversacionais ("fale como um homem das cavernas inteligente").
- **Quando usar:** Leitura em terminais, depurações rápidas ou quando o usuário desejar máxima velocidade e menor custo de leitura.
- **Destaques:**
  - Mantém 100% da precisão técnica, comandos e dados.
  - Elimina artigos, floreios e cordialidades vazias, focando diretamente na resposta.

---

### 4. [`skills/documentation-and-adrs.md`](skills/documentation-and-adrs.md) — Documentation and ADRs
- **Categoria:** Governança Técnica / Documentação
- **Objetivo:** Registrar e padronizar Registros de Decisões de Arquitetura (ADRs) e documentação técnica crítica.
- **Quando usar:** Ao tomar decisões estruturais de arquitetura, escolher entre bibliotecas/frameworks concorrentes ou alterar APIs públicas.
- **Destaques:**
  - Foco primordial em documentar o "porquê" (contexto, restrições e alternativas descartadas) em vez de apenas o "o quê" (código).
  - Garante a preservação de contexto histórico tanto para novos engenheiros quanto para agentes de IA.

---

### 5. [`skills/EduGuide AI.md`](skills/EduGuide%20AI.md) — EduGuide AI
- **Categoria:** Educação / Orientação Profissional
- **Objetivo:** Atuar como orientador educacional e tutor socrático para auxiliar profissionais e estudantes a encontrar o curso ou trilha de aprendizado ideal.
- **Quando usar:** Diagnóstico de competências, planejamento de transição de carreira ou escolha de cursos.
- **Destaques:**
  - Conduz perguntas de diagnóstico simples (nível técnico, tempo disponível e objetivo profissional).
  - Cruza o perfil levantado com o catálogo de cursos disponível e gera recomendações fundamentadas com plano de ação.

---

### 6. [`skills/generate-fresh-ideas.md`](skills/generate-fresh-ideas.md) — Generate Fresh Ideas
- **Categoria:** Criatividade / Reposicionamento de Conteúdo
- **Objetivo:** Criar 5 variações e ângulos derivados (remixes) a partir de qualquer material bruto (artigos, transcrições, notas ou tweets).
- **Quando usar:** Ao produzir conteúdo, campanhas ou buscar novas abordagens para temas já existentes.
- **Destaques:**
  - Aplica 5 lentes criativas fixas:
    1. *Contrarian Take* (Visão Contrária ao senso comum);
    2. *Personal Story Hook* (Gancho narrativo/pessoal);
    3. *Data/Evidence Angle* (Foco em dados e evidências);
    4. *Practical Playbook* (Guia passo a passo prático);
    5. *What They Missed* (O que o conteúdo original ignorou).

---

### 7. [`skills/get-more-perspectives.md`](skills/get-more-perspectives.md) — Get More Perspectives
- **Categoria:** Tomada de Decisão / Análise Estratégica
- **Objetivo:** Submeter decisões difíceis a um comitê consultivo virtual com 5 perspectivas especializadas.
- **Quando usar:** Dilemas de produto, estratégia corporativa, contratações chave ou pivôs de projeto.
- **Destaques:**
  - Os 5 consultores assumem posições declaradas (*A Favor*, *Contra* ou *Condicional*):
    - 🔧 **Operator:** Viabilidade de execução e capacidade técnica.
    - ⚠️ **Skeptic:** Riscos, gargalos, falhas e hipóteses frágeis.
    - 🚀 **Visionary:** Oportunidades de crescimento e impacto a longo prazo.
    - 👤 **Customer Advocate:** Experiência do usuário e atrito com o cliente.
    - 💵 **Finance Mind:** ROI, custos, eficiência e alocação de capital.
  - Entrega veredito consolidado e divisão de votos já no primeiro turno.

---

### 8. [`skills/humanizer-pt-br.md`](skills/humanizer-pt-br.md) — Humanizer PT-BR
- **Categoria:** Edição Textual / Redação Humanizada
- **Objetivo:** Identificar e reescrever textos com vícios de escrita típicos de modelos de linguagem (IA) em português brasileiro.
- **Quando usar:** Na revisão de artigos, e-mails corporativos, posts para redes sociais ou roteiros audiovisuais.
- **Destaques:**
  - Remove aberturas bajuladoras, conectivos artificiais ("Vale ressaltar que", "Em suma"), análises com gerúndio vago e tríades forçadas.
  - Restaura a voz autoral, ritmo variado e vocabulário natural do cotidiano brasileiro sem perder a mensagem original.

---

### 9. [`skills/i-have-adhd.MD`](skills/i-have-adhd.MD) — Modo TDAH (i-have-adhd)
- **Categoria:** Acessibilidade / Formatação de Produtividade
- **Objetivo:** Adaptar a estrutura de saída para pessoas com Transtorno do Déficit de Atenção com Hiperatividade (TDAH).
- **Quando usar:** Sessões de trabalho longas, instruções técnicas ou tarefas com múltiplos passos onde a sobrecarga cognitiva precisa ser minimizada.
- **Destaques:**
  - Começa sempre pela próxima ação prática imediata (Next Action First).
  - Quebra etapas em passos curtos numerados com estimativas realistas de tempo (ex: 5 min, 15 min).
  - Elimina divagações e reitera o estado atual da tarefa para apoiar a memória de trabalho.

---

### 10. [`skills/jde92.md`](skills/jde92.md) — Arquiteto JDE 9.2 Enterprise
- **Categoria:** ERP / Oracle JD Edwards
- **Objetivo:** Atuar como arquiteto de soluções sênior para Oracle JD Edwards EnterpriseOne 9.2 com profunda especialização em Localização Brasileira.
- **Quando usar:** Parametrizações tributárias (NF-e, SPED, Reforma Tributária), finanças (AP, AR, GL), distribuição, orquestrações e desenvolvimento técnico no ERP.
- **Destaques:**
  - Domínio estrito de regras de negócio, tabelas do JDE, UDOs, Orchestrator e desenvolvimento em C/C++, ER e BSSV.
  - Proíbe inventar funções ou sintaxes inexistentes e veta customizações invasivas de código quando há alternativas nativas por Orchestrator ou UDOs.

---

### 11. [`skills/Prompmaster.md`](skills/Prompmaster.md) — Promptmaster
- **Categoria:** Engenharia de Prompt / Otimização de Instruções
- **Objetivo:** Transformar pedidos informais ou instruções brutas em prompts estruturados, didáticos e de alta previsibilidade técnica para LLMs.
- **Quando usar:** Na criação de instruções de sistema para novos agentes, chatbots corporativos ou automações com IA.
- **Destaques:**
  - Aplica o método de **Entrevista Reversa Ponto a Ponto**: faz uma única pergunta por turno antes de gerar qualquer instrução final.
  - Garante rigor técnico com especificação mecânica de restrições negativas, personas e formatos de saída padronizados.

---

### 12. [`skills/Skill Creator.md`](skills/Skill%20Creator.md) — Skill Creator
- **Categoria:** Desenvolvimento de IA / Meta-Habilidade
- **Objetivo:** Estruturar, aprimorar e validar o ciclo de vida completo de uma nova skill para assistentes de IA.
- **Quando usar:** Ao criar uma nova habilidade do zero, aprimorar o gatilho de disparo ou criar baterias de testes (evals).
- **Destaques:**
  - Fornece metodologia de ponta a ponta: concepção, rascunho de instruções, elaboração de casos de teste, avaliação qualitativa/quantitativa e refinamento iterativo.
  - Otimiza descrições para garantir precisão de disparo do agente sem falso-positivos.

---

### 13. [`skills/sysaid.md`](skills/sysaid.md) — SysAid (Reescrita de Chamados JDE)
- **Categoria:** Atendimento ao Cliente / Suporte Funcional JDE
- **Objetivo:** Converter notas técnicas brutas de consultores e diagnósticos internos do JD Edwards em respostas claras, empáticas e resolutivas para chamados e e-mails.
- **Quando usar:** No fechamento de tickets de suporte, esclarecimento de erros operacionais ou comunicação com analistas fiscais/contábeis.
- **Destaques:**
  - Tom colaborativo de consultor sênior parceiro: direto, sem burocracia ou termos robóticos ("Prezado", "Espero que encontre bem").
  - Explica a causa raiz funcional (status de lote, validações fiscais, telas do JDE) com clareza e sem jargões desnecessários de código.

---

## 📄 Licença

Este repositório é disponibilizado para a comunidade sob a licença [MIT](LICENSE).
