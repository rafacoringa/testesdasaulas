---
marp: true
title: "GitHub na prática — do perfil ao pull request (aula 2h)"
description: "Aula de 2h (Ensino Médio / Técnico em Informática): panorama completo de GitHub + prática guiada"
author: "Prof. Rafael Abade Ribeiro"
theme: default
class: invert
paginate: true
header: "🧑‍💻 Aula - GitHub na prática"
footer: "prof. Rafa Abade / CC-BY / ⏱️ 2h • 2026 / Gerado com aux. IA copilot"
---

# 🧑‍💻 Aula - GitHub na prática


**Objetivo:** sair da aula com um repo organizado, fluxo de trabalho claro e um PR feito do jeito “profissional”.


---

## 🧭 Regras rápidas da aula (logística)
- ✅ **Acesso remoto permitido** (quando funcionar bem)
- 🐢 **Se a internet estiver lenta:** você pode **só transmitir a tela** e guio passo a passo
- 🧩 Hoje vale errar: **conflito e bug são parte do jogo**

**Meta do final:** 1 repo + 1 projeto Kanban + 1 issue + 1 branch + 1 PR revisado.

---

## ⏱️ Roteiro (2h)
- **0:00–0:10** Aquecimento + check do ambiente
- **0:10–0:25** Perfil, repos, estrelas, pin, boas práticas
- **0:25–0:40** README.md e Markdown (rápido, mas caprichado)
- **0:40–0:55** Branches, commits e mensagens decentes
- **0:55–1:20** Forks + Pull Requests + Reviews
- **1:20–1:35** Issues + templates + labels (triagem)
- **1:35–1:50** Projects (Kanban) + automações leves
- **1:50–2:00** Licenças + tendências/IA + checklist final

---

## 🧪 Aquecimento (3 min)
**Pergunta relâmpago:**
- Qual foi o último projeto que você fez (mesmo pequeno)?
- O que você gostaria que ele tivesse: *documentação*, *organização*, *evolução*?

> 🎯 *A ideia:* GitHub não é só “guardar código”. É “**mostrar evolução e trabalhar em time**”.

---

## 🧰 Setup mínimo (sem sofrimento)
- Conta GitHub logada / add https://github.com/rafacoringa
- Editor VS Code opcional

---

## 👤 Perfil GitHub que “passa confiança”
✅ Checklist rápido:
- Foto + bio curta (1 linha)  
- 2–3 **repositórios fixados (pinned)**  
- README do perfil (opcional, mas legal)  
- Links: LinkedIn / portfólio / itch.io (se tiver jogos) 🎮

**Mini-desafio (Discussão, 4 min):**
> “Se um recrutador olhasse seu perfil por 30s, o que ele entenderia?”

---

## 📦 Repositórios: o básico que muita gente ignora
- Nome claro (ex: `api-tarefas-node`)
- `Topics` (tags)
- `Description` (1 frase)
- Releases (quando fizer sentido)
- `LICENSE` + `README` desde o começo

💡 **Curiosidade:** “repos abandonados” sem mantedores  
Um README bom = *changelog mental* pra quem chega depois.

---

## 📝 README.md: o “menu inicial” do seu projeto
Estrutura simples que funciona:
1. **O que é** (1–2 linhas)
2. **Como rodar**
3. **Tecnologias**
4. **Funcionalidades**
5. **Como contribuir**
6. **Licença**

✨ Markdown básico:
- `#` título, `##` seção  / - listas `-` / código ` ``` ` /   links e imagens
- Sintaxe básica https://commonmark.org/help/

---

## 🧩 Exercício 1 — README Sprint (10 min)
**Você vai criar/editar um README.md** com:
- título + descrição + print (se tiver)
- passos de instalação/execução
- “próximos passos” (roadmap curto)

💬 **Pergunta de revisão:**  
“O README responde as 3 dúvidas do visitante? (o que é / como roda / por que importa)”

---

## 🌿 Branches: suas “linhas do tempo”
- `main` = estável
- branch de feature = experimento com segurança
- nomes úteis:
  - `feature/login`
  - `fix/cadastro-null`
  - `docs/readme`

✅ Regra de ouro: **1 branch = 1 objetivo** (como uma missão).

---

## ✅ Commits: mensagens que ajudam você do futuro
Padrão simples:
- `feat: adiciona tela de login`
- `fix: corrige validação de email`
- `docs: melhora README`
- `refactor: organiza serviços`

💡 *Commit bom* = “o que mudou + por quê”.

---

## 🧯 Exercício 2 — 3 commits bons (8 min)
Faça **3 commits** (pode ser em mudanças pequenas):
1. docs (README)
2. feat (algo simples)
3. fix/refactor (organização ou correção)

📌 Depois, olhe o histórico e pergunte:
> “Dá pra entender o projeto só lendo os commits?”

---

## 🍴 Fork vs Clone (sem confusão)
- **Clone:** traz o repo pra sua máquina  
- **Fork:** cria uma cópia *no seu GitHub* (bom pra contribuir em projetos alheios)


---

## 🔀 Pull Request (PR): a ponte oficial das mudanças
PR serve para:
- comparar branch → main
- pedir revisão
- discutir
- rodar checks (CI)
- documentar decisões

---

**Partes do PR:**
- título + descrição
- commits
- arquivos alterados
- reviewers
- checks
- conversa

---

## 🧠 Tendência: PRs “gerados por IA” e o caos das revisões 🤖
- IA acelera código e docs ✅  
- mas pode gerar **muitos PRs pequenos** e “barulho” ❌  
- resultado: **fila de review** + mais tempo pra manter qualidade

**Boa prática:** PR pequeno, objetivo e com contexto.  
IA ajuda — mas **review humano continua obrigatório**.

---

## 🧩 Exercício 3 — Fork + PR (15–20 min)
Você vai:
1. **Fork** de um repo de exemplo (ou seu próprio repo via branch)
2. Criar branch `docs/melhoria-readme`
3. Alterar algo (README ou bug simples)
4. Subir e abrir **Pull Request**
5. Preencher um template simples (ver slide)

> Se não tivermos repo externo: fazemos no seu repositório mesmo (branch → main).

---

## ✅ Template curto de PR (copiar/colar)
- **O que mudou?** ...
- **Por que mudou?** ...
- **Como testar?**
     - passos…

**Checklist**
- [ ] Não quebrei nada
- [ ] Rodei/testei o básico
- [ ] Atualizei docs se necessário

---

## 🧑‍⚖️ Review: como revisar sem virar “polícia do código”
Foque em:
- clareza do código
- legibilidade
- risco (quebra?)
- testes
- consistência

**Frases úteis:**
- “Sugestão:” … / - “Dúvida:” …
- “Você pode explicar o porquê de…?”

🎯 A meta é melhorar o projeto, não “vencer discussão”.

---

## 🧨 Exercício 4 — Simulação de review (7 min)
Troca rápida:
- você abre o PR
- eu faço 2 comentários (1 elogio + 1 sugestão)
- você responde e ajusta

📌 Objetivo: praticar o “**ciclo**” PR → comentário → ajuste → merge.

---

## 🧩 Issues: o lugar das tarefas e bugs
Use Issues para:
- bug report
- feature request
- discussão técnica
- tarefas

Elementos úteis:
- labels (bug, feature, docs)
- assignees
- milestones
- templates

---

## 🧪 Exercício 5 — Triagem de Issue (8 min)
Crie **2 issues**:
1. 🐛 bug (mesmo que “fictício”, mas realista)
2. ✨ melhoria

Depois:
- aplicar labels
- descrever **passos para reproduzir** (bug)
- definir “critério de pronto” (melhoria)

---

## 🗂️ Projects (Kanban): do caos ao fluxo
GitHub Projects (Kanban) ajuda a ver:
- **Backlog** → **Em andamento** → **Em revisão** → **Feito**

Boas práticas:
- colunas simples
- limite de WIP (não abra 20 coisas)
- conectar cards em Issues/PRs

---

## 🧩 Exercício 6 — Kanban de 10 minutos (10 min)
Criar um Project com colunas:
- Backlog
- Doing
- Review
- Done

Adicionar:
- as 2 issues criadas
- o PR criado

**Bônus:** mover cards quando mudar o estado.

---

## 📄 Licenças: “pode usar meu código?”
Escolhas comuns:
- **MIT**: bem permissiva
- **Apache 2.0**: permissiva + patente
- **GPL**: exige que derivados também sejam GPL
- **Sem licença**: na prática, *ninguém tem permissão* clara
- Licenças CC - https://br.creativecommons.net/licencas/

🎯 Regra simples: projeto público sem licença = confuso pra quem quer contribuir.

---

## 🧩 Exercício 7 — Escolha de licença (5 min)
Para seu projeto atual, responda:
- Você quer que outras pessoas usem livremente?
- Você liga para atribuição?
- Você quer “obrigar” que melhorias continuem abertas?

✅ Ação: adicionar arquivo `LICENSE` (ou decidir conscientemente não usar, com justificativa).

---

## ➕ 5 temas extras (panorama rápido) 🌟
1. ⚙️ **GitHub Actions (CI/CD):** automatizar testes/build
2. 🔒 **Security/Dependabot:** alertas de dependências vulneráveis
3. 👥 **CODEOWNERS:** quem revisa o quê (regras de review)
4. 🏷️ **Releases/Tags + SemVer:** versionamento e “patch notes”
5. 🌐 **GitHub Pages:** site do projeto/portfólio direto do repo

> Se der tempo no final: demo rápida de 1 Action simples.

---

## ⚙️ Mini-demo (opcional) — Action “Hello CI”
Uma Action simples pode:
- rodar lint
- rodar testes
- impedir merge se falhar

**Ideia:** “main” só recebe PR quando checks passam ✅

*(Se o tempo apertar, fica como tarefa guiada pra próxima aula.)*

---

## 🤖 IA no GitHub: onde ajuda de verdade (e onde atrapalha)
Ajuda:
- rascunhar README
- explicar erros
- sugerir testes
- refatorar com cuidado

Atrapalha:
- PR gigante sem contexto
- código “parece certo”, mas não está
- excesso de PRs automáticos → review congestionado

✅ Regra: IA acelera, mas **você continua responsável**.

---

## 🎯 Checklist final (resultado da aula)
Você deve sair com:
- [ ] Perfil minimamente apresentável
- [ ] README decente
- [ ] Branch criada e usada
- [ ] 3 commits bons
- [ ] 1 PR aberto + revisado
- [ ] 2 issues triadas (labels + critérios)
- [ ] 1 Kanban com cards conectados
- [ ] Licença definida

---

## 🧠 Fechamento (2 min): reflexão rápida
1. Qual parte do fluxo foi mais “natural”?
2. Qual parte foi mais chata/difícil — e por quê?
3. Se isso fosse um projeto de game, qual seria o “próximo patch”?

🎮 *Missão bônus:* “tornar o repo ‘jogável’ em 2 minutos para alguém que nunca viu.”

---

## 📌 Tarefa opcional (se quiser evoluir)
- Criar um `CONTRIBUTING.md` curto
- Criar um template de Issue
- Criar uma Action simples de lint/test
- Criar uma Release `v0.1.0` com notas

> Na próxima aula, dá pra conectar isso com **portfólio** e **processo real de equipe**.
