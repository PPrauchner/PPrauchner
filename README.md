<div align="center">

# Pietro Prauchner

### Desenvolvedor full-stack com foco em backend Python e IA aplicada

**Buscando estágio em desenvolvimento — Alegrete/RS ou remoto · curso noturno**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pietroprauchner/)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pietro.mprauchner@gmail.com)
[![Lattes](https://img.shields.io/badge/Currículo_Lattes-0A5C9E?style=for-the-badge&logoColor=white)](http://lattes.cnpq.br/8153919281360932)

**[🇧🇷 Português](README.md) · [🇺🇸 English](README.en.md)**

</div>

Estudante de Engenharia de Software na **UNIPAMPA — campus Alegrete/RS**, no 4º de 9 semestres (conclusão prevista para 2029/1). Gosto de tirar uma ideia do papel e ver ela funcionando de ponta a ponta: levantar os requisitos, desenhar a arquitetura, escrever o código — e deixar o projeto organizado o suficiente para outra pessoa entrar nele no dia seguinte.

---

## 💼 Experiência

**Bolsista de extensão — AI Horizon Labs / UNIPAMPA** · 2026 – atual · 20h semanais

Projeto *Educador 5.0: Capacitação de Professores para o Uso de Inteligência Artificial na Educação Básica*. Atuo presencialmente na formação continuada de professores da Educação Básica, traduzindo ferramentas de IA em uso prático de sala de aula.

---

## 🚀 Projetos em destaque

### [SAGA — Sistema de Acompanhamento e Gestão Acadêmica](https://github.com/PPrauchner/SAGA-Sistema-de-Acompanhamento-e-Gestao-Academica)

Sistema de gestão para programas de pós-graduação: cadastro de discentes, plano de trabalho, validação de créditos, prorrogações e relatórios gerenciais. Projeto em equipe de 6 pessoas, com um **motor de inferência lógica construído do zero em Python** e **Programação Orientada a Aspectos** para autorização, auditoria e alertas.

> **Meu papel:** maior contribuidor do repositório (307 commits). Levantei os requisitos, organizei o trabalho da equipe e escrevi a maior parte das issues e da documentação. **Desenhei a arquitetura do motor de inferência** — a separação entre termos, unificação, substituição, resolvedor e base de conhecimento — e escrevi a **camada de regras declarativas (RL01–RL05)** e a **suíte de testes** contra a qual o time implementou. Revisei metade dos PRs e trabalhei no back-end, no front-end e no banco.

`Python` `FastAPI` `React` `TypeScript` `Firebase` `pytest`

### [ORÁCULO — auditoria de dependências Python](https://github.com/PPrauchner/Oraculo)

Ferramenta web que cruza o que um projeto **declara** depender (`pyproject.toml`, `requirements.txt`, `environment.yml`) com o que o código **realmente importa**, via análise de AST, e confronta os dois com o PyPI. Reporta *Zumbis* (declaradas e nunca usadas), *Fantasmas* (importadas e nunca declaradas) e desatualizadas, com métricas de tamanho, idade e um Índice de Saúde.

> **Meu papel:** 227 dos 238 commits do repositório — na prática, meu projeto. Núcleo desacoplado da interface, parsers registrados por decorador, suíte de testes, internacionalização (pt/en) e as decisões de arquitetura documentadas.

`Python` `Streamlit` `Plotly` `AST` `uv`

### [LazyPR — análise funcional de pull requests](https://github.com/PPrauchner/LazyPR-Grupo-06)

Plataforma que ingere datasets grandes de pull requests do GitHub de forma *lazy* e os classifica semanticamente via LLM (Groq/Llama): natureza da mudança, clareza da descrição e tipo de projeto. Pipeline inteiramente funcional — funções puras, composição, `map`/`filter`/`reduce` — com dashboards interativos.

> **Meu papel:** maior contribuidor do repositório (56 commits). Implementei a **camada de integração com o LLM** — engenharia de prompt, *retry* e tratamento do *rate limit* do Groq — e as funções de classificação de natureza, clareza e tipo de projeto, além do **cache multinível com persistência atômica em disco**. Escrevi metade dos testes e cuidei dos requisitos, da organização da equipe, das issues e da revisão dos PRs.

`Python` `LLM (Groq/Llama)` `Streamlit` `Programação Funcional`

---

## 📌 Outros projetos

- **[Site da Maria Dinoir — Terapeuta](https://github.com/PPrauchner/Site-de-terapeuta)** · **[🔗 no ar](https://maria-dinoir-terapeuta.com/)** — site profissional para uma cliente real, do briefing à entrega: páginas institucionais, FAQ interativa, modais e agendamento por WhatsApp. Comecei em HTML/CSS puro e migrei para Astro, reorganizando todo o CSS em um design system próprio. `Astro` `TypeScript` `CSS`
- **[mini-simulador-edge-cloud](https://github.com/PPrauchner/mini-simulador-edge-cloud)** — simulador de alocação de tarefas em infraestrutura Edge-Cloud, feito como desafio técnico para um processo de bolsa. `Python`

---

## ⚙️ Como eu trabalho

Trato projeto pequeno com o mesmo processo de projeto grande — é isso que faz outra pessoa (ou eu, três meses depois) conseguir entrar nele.

- **Issues e pull requests mesmo em projeto solo.** Nos últimos 12 meses: ~1.200 contribuições, 52 PRs e 205 issues.
- **Decisões escritas.** Cada projeto tem um `CONTEXT.md` com o modelo de domínio e ADRs em `docs/adr/` registrando as decisões e seus porquês — é a fonte da verdade antes de implementar.
- **Commits atômicos** e convenções de código versionadas junto do projeto.
- **Automação do próprio fluxo.** Mantenho em [`.claude-generica`](https://github.com/PPrauchner/.claude-generica) as skills, hooks e regras que uso para padronizar revisão de PR, abertura de issues e commits. Foi essa base que adaptei para organizar o trabalho da equipe no SAGA.

---

## 🛠️ Stack

**Backend**  Python · FastAPI · Firebase

**Front-end**  TypeScript · React · Astro · HTML/CSS

**Dados & IA**  integração com LLMs (Groq/Llama) · análise de AST · Streamlit · Plotly

**Práticas**  Git · issues e code review · pytest · uv · ADRs

---

## 📫 Contato

Buscando estágio em desenvolvimento, **em Alegrete/RS ou remoto**. Curso noturno — disponibilidade durante o dia.

**[LinkedIn](https://www.linkedin.com/in/pietroprauchner/)** · **[E-mail](mailto:pietro.mprauchner@gmail.com)** · **[Currículo Lattes](http://lattes.cnpq.br/8153919281360932)**
