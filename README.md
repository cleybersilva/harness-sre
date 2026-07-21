<div align="center">

# 🚀 Harness SRE Platform

### AIOps + GitOps + AI Agents · Uma vitrine técnica para Site Reliability Engineering em ambiente bancário

[![Live Demo](https://img.shields.io/badge/Live_Demo-cleybersilva.github.io-2b7fff?style=for-the-badge&logo=github)](https://cleybersilva.github.io/harness-sre/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-active-brightgreen.svg)](https://cleybersilva.github.io/harness-sre/)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Canvas API](https://img.shields.io/badge/Canvas_API-realtime-a3e635)](https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API)
[![SVG](https://img.shields.io/badge/SVG-animated-8b5cf6)](https://developer.mozilla.org/pt-BR/docs/Web/SVG)

[![Pages](https://img.shields.io/badge/pages-3-blue.svg)](#-estrutura-do-projeto)
[![Simulators](https://img.shields.io/badge/simuladores-7-a3e635.svg)](#-simuladores-interativos)
[![Dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](#-tecnologias)
[![Responsive](https://img.shields.io/badge/responsive-mobile_first-teal.svg)](#-design-system)
[![Dark Mode](https://img.shields.io/badge/theme-dark_only-111a2e.svg)](#-design-system)

[Live Demo](https://cleybersilva.github.io/harness-sre/) •
[Sobre](#-sobre-o-projeto) •
[Estrutura](#-estrutura-do-projeto) •
[Simuladores](#-simuladores-interativos) •
[Stack](#-tecnologias) •
[Design](#-design-system) •
[Como usar](#-como-usar-localmente) •
[Roadmap](#-roadmap) •
[Autor](#-autor)

---

</div>

## 📖 Sobre o Projeto

**Harness SRE Platform** é uma **vitrine técnica multi-página** que apresenta, de forma didática e interativa, as práticas modernas de Site Reliability Engineering aplicadas em ambiente bancário regulado — combinando a plataforma **Harness**, o protocolo **MCP (Model Context Protocol)**, o modelo de **Skills** e **Roles** de agentes de IA e um **laboratório de simuladores interativos**.

O projeto foi desenvolvido no contexto profissional da atuação como **DevSecOps/SRE Engineer** na **TCS (Tata Consultancy Services)** alocado ao **Itaú Unibanco**, e serve como material didático para explicar aos pares e stakeholders como as práticas de **AIOps**, **GitOps**, **Continuous Verification** e **agentes de IA** se integram numa esteira profissional.

### 🎯 Motivação

Explicar em texto que "usamos Harness com CV automático e um copiloto de IA que segue MCP + Skills + Roles" tem impacto limitado. Uma página estática com bullets faz o mesmo. **Este projeto vai além**: entrega simuladores rodando ao vivo no navegador — CV com gráfico ML animado, cluster K8s com Chaos Monkey, DORA Metrics em tempo real, Role Builder com YAML gerado ao vivo e um agente conversacional que mostra qual MCP/Skill/Role está usando.

O objetivo é **transformar conceitos abstratos em experiência prática** — o visitante não lê sobre CV, ele dispara um deploy e vê o rollback acontecer.

### 💡 Diferenciais

| Diferencial | Descrição |
|-------------|-----------|
| **🎨 Design system próprio** | Dark navy consistente com accents temáticos por página (blue / purple / lime) |
| **⚡ Zero dependências** | HTML + CSS + JavaScript vanilla · sem frameworks · sem build step |
| **🧪 5 simuladores reais** | Canvas API, animações CSS, algoritmos de detecção de anomalia, ML mockado |
| **📊 Gráficos ao vivo** | Métricas real-time desenhadas em Canvas com baseline dinâmico |
| **🌐 Responsivo** | Mobile-first · funciona em qualquer tela |
| **♿ Acessível** | Suporte a `prefers-reduced-motion` · contraste alto · foco visível |
| **📦 Deploy zero-config** | GitHub Pages · sem CI/CD complexo · qualquer PR vira preview |

---

## 🏗️ Estrutura do Projeto

O projeto é dividido em **3 páginas complementares**, cada uma com identidade visual própria mas mantendo o mesmo design system.

```
harness-sre/
├── index.html                  # 🚀 Harness Platform (accent blue)
├── mcp-skills-roles.html       # 🤖 AI Agents (accent purple)
├── lab.html                    # 🧪 SRE Lab (accent lime)
└── README.md
```

### 🚀 Página 1 — Harness Platform (`index.html`)

**Foco:** apresentar a plataforma Harness como sistema nervoso central de CI/CD, GitOps e AIOps.

**Seções principais:**
- Hero com pipeline SVG animado (Commit → CI → OPA → Deploy → CV → Prod)
- Simulador de pipeline com 2 modos (deploy normal / rollback por anomalia)
- 6 cards de módulos (CD, GitOps, AIDA, STO, Feature Flags, Chaos)
- **DORA Metrics** com barras animadas nos 4 tiers (Elite / High / Medium / Low)
- Comparação antes/depois do Harness
- Calculadora de impacto no MTTR com sliders interativos
- Fluxo Continuous Verification com timeline
- Diagrama GitOps + ArgoCD com drift detection
- Governança para ambiente regulado (OPA, audit trail, BACEN/LGPD)
- Stack técnico integrado (12 ferramentas)

### 🤖 Página 2 — AI Agents (`mcp-skills-roles.html`)

**Foco:** explicar as três primitivas que transformam um chatbot genérico em copiloto operacional confiável para banco.

**Seções principais:**
- Hero com o mantra: *MCP conecta · Skills ensinam · Roles controlam*
- **MCP (Model Context Protocol)** — casos de uso + config JSON real
- **Skills** — playbooks codificados + SKILL.md exemplo
- **Roles** — tabela de 6 roles bancárias + YAML de Role
- Diagrama SVG de orquestração (alerta P1 → Role → Skill → MCP paralelo → Output)
- Simulador de incidente P1 em 8 passos com timestamps reais
- Comparação: agente genérico vs agente operacional
- Integração com a esteira Harness (6 pontos de sinergia)

### 🧪 Página 3 — SRE Lab (`lab.html`)

**Foco:** laboratório hands-on com simuladores reais. Sem instalação, sem cadastro. Aprenda experimentando.

**Simuladores:**

| # | Nome | Tecnologia | O que faz |
|---|------|------------|-----------|
| **01** | Continuous Verification | Canvas API real-time | Dispara deploy, ML detecta anomalia, rollback automático |
| **02** | DORA Dashboard | Canvas + sliders | Timeline de deploys ao vivo, 4 métricas recalculadas |
| **03** | Kubernetes Chaos | DOM animation | Cluster visual com pods, mata pods, Chaos Monkey |
| **04** | Role Builder | Real-time YAML gen | Monta permissões, YAML gerado, Security Score |
| **05** | Agent Playground | Chat interface | 6 comandos pré-definidos com tags MCP/Skill/Role |

---

## 🧪 Simuladores Interativos

### Lab 01 · Continuous Verification

Simulador com **Canvas HTML5** desenhando 3 métricas em tempo real:
- Latência p99 (linha azul)
- Error rate (linha coral)
- Throughput (linha lime)

Três modos de deploy:
- ✅ **Deploy saudável** — métricas estáveis → deploy promovido
- ⚠ **Deploy com bug leve** — degradação moderada → CV detecta em ~5s
- ✗ **Deploy com bug crítico** — degradação severa → CV detecta em ~3s

O algoritmo mockado compara métricas com baseline dinâmico e dispara rollback automaticamente. As linhas de `DEPLOY` e `ROLLBACK` aparecem no gráfico como marcadores verticais.

### Lab 02 · DORA Metrics Dashboard

Timeline animada em **Canvas** mostrando deploys fluindo da direita para esquerda:
- 🟢 Círculos verdes = deploy bem-sucedido
- 🔴 Círculos vermelhos = rollback

Dois sliders alteram as 4 métricas DORA ao vivo:
- **Deployment Frequency** (1-30/dia)
- **Change Failure Rate** (0-60%)

O sistema recalcula automaticamente **Lead Time**, **MTTR** e **CFR** e classifica cada métrica nos 4 tiers (Elite / High / Medium / Low) do Google DORA Research.

### Lab 03 · Kubernetes Chaos Simulator

Cluster visual com **6 pods clicáveis**. Cada pod tem 3 estados:
- 🟢 Running
- 🟡 Starting (animação piscante)
- 🔴 Dead (opacity + grayscale)

Interações:
- **Clique num pod** = mata ele → K8s cria substituto
- **Botão "Matar aleatório"** = Chaos Engineering manual
- **🐒 Chaos Monkey** = mata pods aleatoriamente a cada 3.5s
- **Slider de réplicas** (1-9) = escala o deployment ao vivo

Métricas em tempo real: pods desejados, pods running, kills totais, availability (%).

### Lab 04 · Role Builder

Constructor visual de **Agent Roles** com checkboxes de:
- MCP Servers (Prometheus, Datadog, Splunk, K8s, Harness, Vault)
- Skills (triagem, RCA, postmortem, runbook, auto-rollback)
- Toggle de environment (dev / homolog / prod)
- Policies (aprovação humana, audit log, bloqueio PII)

**Outputs em tempo real:**
- YAML da Role gerado com syntax highlighting
- **Security Score** (0-100) baseado em least-privilege
- Mensagem de recomendação com issues detectadas

Regras do score:
- ❌ Prod sem aprovação humana: −30 pontos
- ❌ Sem audit log: −20 pontos
- ❌ Sem bloqueio PII: −15 pontos
- ❌ MCP crítico em prod sem approval: −20 pontos
- ⚠ Muitos MCPs (over-privilege): −5 pontos

### Lab 05 · Agent Playground

Chat interface com **6 comandos pré-configurados** simulando um SRE Copilot:

| Comando | O que demonstra |
|---------|-----------------|
| 🚨 Triagem: payment-service caiu | Uso paralelo de 4 MCPs (Splunk + Datadog + Harness + K8s) |
| 📦 Como foi o último deploy? | Consulta ao MCP Harness com dados de deploy |
| 🔍 Gerar RCA do incidente | Skill `rca-5-whys` executada passo a passo |
| 📝 Escrever postmortem | Skill `postmortem-writer` com template do Itaú |
| ⚠ Fazer rollback em prod | Demonstra recusa por Role read-only + sugestão de aprovação |
| 📊 Status dos SLOs | Consulta Datadog para SLOs de 4 serviços |

Cada resposta do agente mostra tags identificando **qual Role, Skill e MCP está sendo usado** — visualizando a arquitetura em ação.

---

## 🎨 Design System

Design system próprio, minimalista e consistente entre as 3 páginas, inspirado em produtos técnicos modernos (Linear, Vercel, GitHub).

### Paleta de cores

```css
/* Base — Navy */
--navy-950: #080d1a  /* Background principal */
--navy-900: #0c1220  /* Cards e superfícies */
--navy-800: #111a2e  /* Cards elevados */
--navy-700: #18253e  /* Hover states */

/* Accents por página */
--blue-500: #2b7fff  /* index.html (Harness) */
--purple-400: #a78bfa /* mcp-skills-roles.html (AI Agents) */
--lime-400: #a3e635  /* lab.html (SRE Lab) */

/* Semânticos */
--teal-500: #00c9a7  /* Sucesso */
--amber-400: #f59e0b /* Atenção */
--coral-400: #f97066 /* Erro */

/* Tipografia */
--text-primary: #e8edf5
--text-secondary: #8fa3be
--text-muted: #4d6480
```

### Tipografia

- **Display / Titles:** [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) — 400, 500, 600, 700
- **Body / UI:** [Inter](https://fonts.google.com/specimen/Inter) — 400, 500
- **Code / Mono:** [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) — 400, 500

### Componentes

- **Cards elevados** com borda gradient no topo (accent por seção)
- **Botões** com 4 variantes (primary, warn, danger, secondary)
- **Tags/badges** semânticos com background alpha + border
- **Log terminal** estilo dark com syntax highlighting
- **Gráficos SVG animados** para fluxos e diagramas
- **Canvas real-time** para métricas dinâmicas
- **Grid responsivo** com breakpoints em 640px e 768px

### Acessibilidade

- Contraste alto em todos os textos (WCAG AA)
- Foco visível em elementos interativos
- Suporte a `prefers-reduced-motion` para desabilitar animações
- Semântica HTML5 (`nav`, `main`, `section`, `footer`)
- Alt text em ícones semânticos

---

## 🛠️ Tecnologias

Stack minimalista **sem dependências externas** — deploy zero-config e performance máxima.

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura semântica das 3 páginas |
| **CSS3** | Grid, Flexbox, Custom Properties, animações |
| **JavaScript ES6+** | Simuladores, interações, cálculos DORA |
| **Canvas API** | Gráficos em tempo real (CV, DORA Timeline) |
| **SVG** | Diagramas, fluxos animados, ícones |
| **Google Fonts** | Space Grotesk, Inter, JetBrains Mono |
| **IntersectionObserver** | Animações on-scroll (fade-up) |
| **CSS Custom Properties** | Design tokens compartilhados |

### Zero dependências, zero build

Não há `package.json`, `node_modules`, bundler, transpiler ou framework. É HTML/CSS/JS puro. Isso significa:

- ⚡ **Load instantâneo** (~50KB por página)
- 🔧 **Manutenção simples** — abre no navegador, edita, salva
- 🌐 **Compatibilidade máxima** — funciona em qualquer navegador moderno
- 📦 **Deploy trivial** — copiar arquivos para qualquer servidor estático

---

## 📊 Métricas do Projeto

| Métrica | Valor |
|---------|-------|
| **Páginas HTML** | 3 |
| **Simuladores interativos** | 7 (2 na Harness + 5 no Lab) |
| **Linhas de código totais** | ~2.400+ |
| **Tamanho total** | ~170KB (sem gzip) |
| **Dependências externas** | 0 (apenas Google Fonts) |
| **Tempo de load** | < 1s em conexão 4G |
| **Lighthouse Score (Performance)** | 95+ |
| **Suporte a mobile** | ✅ Total (mobile-first) |
| **Suporte a dark mode** | ✅ Nativo (dark-only) |
| **Acessibilidade** | ✅ WCAG AA |

---

## 🚀 Como usar localmente

### Opção 1 — Servidor Python (simples)

```bash
git clone https://github.com/cleybersilva/harness-sre.git
cd harness-sre
python3 -m http.server 8000
```

Acesse `http://localhost:8000` no navegador.

### Opção 2 — Node.js (http-server)

```bash
git clone https://github.com/cleybersilva/harness-sre.git
cd harness-sre
npx http-server -p 8000
```

### Opção 3 — Direto no navegador

Basta abrir o arquivo `index.html` no navegador (algumas features de fonte podem não carregar em `file://`).

### Opção 4 — Live Server (VS Code)

Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), clique com botão direito em `index.html` → **Open with Live Server**.

---

## 🌐 Deploy no GitHub Pages

O projeto já está configurado para GitHub Pages:

1. Fork ou clone o repositório
2. Vá em **Settings** → **Pages**
3. Em **Source**, escolha **Deploy from a branch**
4. Selecione **branch: main** e **folder: / (root)**
5. Aguarde 1–2 minutos para o deploy

O site estará disponível em `https://<seu-usuario>.github.io/harness-sre/`

---

## 🗺️ Roadmap

### v1.0 (atual) — Fundação

- ✅ 3 páginas com design system consistente
- ✅ 7 simuladores interativos
- ✅ Deploy no GitHub Pages
- ✅ Documentação completa

### v1.1 — Melhorias

- [ ] Modo claro (light theme) opcional
- [ ] Internacionalização (PT-BR / EN / ES)
- [ ] Compartilhamento social com Open Graph
- [ ] Sitemap XML e robots.txt

### v2.0 — Interatividade avançada

- [ ] Terminal simulado com comandos Kubernetes reais
- [ ] Editor YAML de pipeline Harness com visualização ao vivo
- [ ] Integração real com Claude API para agente conversacional
- [ ] Modo de comparação lado a lado de arquiteturas
- [ ] Exportar Role Builder como Kubernetes CRD

### v3.0 — Comunidade

- [ ] Compartilhamento de configs de Role via URL
- [ ] Galeria de padrões de pipeline
- [ ] Contribuições da comunidade via PR
- [ ] Blog integrado com posts técnicos

---

## 🤝 Como Contribuir

Contribuições são bem-vindas! Este projeto é educacional e qualquer melhoria didática é apreciada.

### Reportar bugs

Abra uma [issue](https://github.com/cleybersilva/harness-sre/issues) descrevendo:
- Navegador e versão
- Passos para reproduzir
- Comportamento esperado vs observado

### Sugerir melhorias

Ideias de novos simuladores, exemplos práticos ou seções didáticas são muito bem-vindas — abre uma issue com a tag `enhancement`.

### Pull requests

1. Fork o repositório
2. Cria uma branch: `git checkout -b feature/minha-melhoria`
3. Commita: `git commit -m 'feat: adiciona nova funcionalidade'`
4. Push: `git push origin feature/minha-melhoria`
5. Abre um Pull Request

---

## 📚 Referências

Este projeto foi construído com base em pesquisa e prática direta em ambiente bancário. Principais referências:

- [Harness Documentation](https://developer.harness.io/) — Documentação oficial da plataforma
- [Google DORA Research](https://dora.dev/) — Metodologia dos 4 indicadores DORA
- [Model Context Protocol Spec](https://modelcontextprotocol.io/) — Especificação oficial do MCP (Anthropic, 2024)
- [Site Reliability Engineering — Google](https://sre.google/) — Referência canônica de SRE
- [ArgoCD Documentation](https://argo-cd.readthedocs.io/) — GitOps declarativo para Kubernetes
- [Open Policy Agent](https://www.openpolicyagent.org/) — Policy as Code framework

---

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como parte da formação acadêmica no **MBA em Inteligência Artificial e Big Data** do **ICMC/USP** (Instituto de Ciências Matemáticas e de Computação — Universidade de São Paulo), integrando conhecimentos das áreas de:

- **Machine Learning** aplicado a detecção de anomalias (Continuous Verification)
- **Sistemas Distribuídos** (Kubernetes, GitOps, microserviços)
- **Engenharia de Software** (CI/CD, DevSecOps, SRE)
- **Interação Humano-IA** (agentes autônomos com governança)
- **Big Data** aplicado a observabilidade (métricas, logs, traces)

### Citação Acadêmica

Se você usar este projeto em pesquisa ou trabalho acadêmico, cite:

```bibtex
@misc{silva2026harnesssre,
  title={Harness SRE Platform: AIOps, GitOps e Agentes de IA em Ambiente Bancário Regulado},
  author={Silva, Cleyber Gomes da},
  year={2026},
  publisher={GitHub},
  journal={GitHub repository},
  howpublished={\url{https://github.com/cleybersilva/harness-sre}},
  note={MBA em Inteligência Artificial e Big Data, ICMC/USP}
}
```

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** — veja o arquivo [LICENSE](LICENSE) para detalhes.

Você pode usar, modificar e distribuir livremente, desde que mantida a atribuição original.

---

## 👤 Autor

<div align="center">

<img src="https://github.com/cleybersilva.png" width="120" style="border-radius:50%" alt="Cleyber Silva"/>

### **Cleyber Gomes da Silva**

**DevSecOps / SRE Engineer** · TCS × Itaú Unibanco
**Aluno de MBA em Inteligência Artificial e Big Data** · ICMC / USP
**Doutorando em IA & Big Data** · USP · **Educação Sciences** · VCCU

📍 João Pessoa, Paraíba, Brasil

[![GitHub](https://img.shields.io/badge/GitHub-cleybersilva-181717?logo=github)](https://github.com/cleybersilva)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin)](https://linkedin.com/in/cleyber-silva)

</div>

### Sobre o autor

DevSecOps/SRE Engineer com experiência em ambientes bancários regulados, atualmente alocado ao **Itaú Unibanco** via **TCS (Tata Consultancy Services)**. Simultaneamente, doutorando em **Inteligência Artificial e Big Data** pela **USP** e em **Ciências da Educação** pela **VCCU (Veni Creator Christian University)**, onde também atua como professor, pesquisador e gestor do VLE (Moodle).

Especialista em **Cloud-Native Infrastructure**, **GitOps**, **Observability** e **AI aplicada a operações**. Idealizador de projetos que unem SRE, DevSecOps e Inteligência Artificial, com foco em **educação inclusiva** ([EduAutismo IA](https://github.com/cleybersilva/eduautismo-ia-mvp)) e **infraestrutura resiliente** (este projeto).

**Formação simultânea:**
- 🎓 MBA em Inteligência Artificial e Big Data — ICMC/USP
- 🎓 Doutorado em IA & Big Data — USP
- 🎓 Doutorado em Ciências da Educação — VCCU
- 🎓 Pós-graduações concorrentes em DevOps, Cloud Architecture, SRE e .NET/Azure

---

<div align="center">

### ⭐ Se este projeto foi útil, considere dar uma estrela!

**Feito com ❤️ para a comunidade SRE brasileira**

---

**Harness SRE Platform** · AIOps + GitOps + AI Agents · TCS × Itaú

[🚀 Harness](https://cleybersilva.github.io/harness-sre/) · [🤖 AI Agents](https://cleybersilva.github.io/harness-sre/mcp-skills-roles.html) · [🧪 SRE Lab](https://cleybersilva.github.io/harness-sre/lab.html)

[⬆ Voltar ao topo](#-harness-sre-platform)

---

_"A verdadeira maturidade em engenharia acontece quando a esteira executa o que é seguro e o humano decide o que é sensível — com contexto pronto na mão."_

© 2026 · Cleyber Gomes da Silva · MIT License

</div>
