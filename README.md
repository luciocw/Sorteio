# Sorteio de Grupos

Random group draw + league schedule generator as a single-file PWA.

---

## English

### What it does

- **Group Draw**: Enter participant names, choose number of groups, and randomly assign everyone
- **League Schedule**: When drawing 12 teams into 4 groups of 3, generates a full 14-round schedule following a structured league format

### League Format

12 teams split into 4 groups of 3, paired (A-B, C-D):

| Phase | Rounds | Games per team |
|-------|--------|---------------|
| Intra-group (3x each rival) | 1-12 | 6 |
| Cross-group paired (2x each) | 1-12 | 6 |
| Cross-pair by standing | 13-14 | 2 |
| **Total** | **14** | **14** |

84 total games, 6 per round, no byes. Playoffs start at round 15.

### Features

- Single `index.html` file — no build, no dependencies
- PWA: installable, works offline
- Light/dark theme (auto-detects system preference)
- Bulk import names via paste (comma, semicolon, or line-separated)
- Copy or share results via Web Share API
- Responsive design (mobile, tablet, desktop)

### How to use

1. Open `index.html` in any modern browser
2. Set number of participants and groups
3. Enter names (or paste a list)
4. Click **Sortear** to draw
5. If 4 groups of 3 → click **Gerar Calendario** for the full schedule

### Tech

HTML + CSS + JavaScript — everything in one file. No frameworks, no bundler, no server required.

---

## Portugues

### O que faz

- **Sorteio de Grupos**: Insira nomes dos participantes, escolha o numero de grupos e distribua aleatoriamente
- **Calendario da Liga**: Ao sortear 12 times em 4 grupos de 3, gera o calendario completo de 14 rodadas seguindo formato estruturado de liga

### Formato da Liga

12 times divididos em 4 grupos de 3, pareados (A-B, C-D):

| Fase | Rodadas | Jogos por time |
|------|---------|---------------|
| Intra-grupo (3x cada rival) | 1-12 | 6 |
| Cross-grupo pareado (2x cada) | 1-12 | 6 |
| Cross-par por classificacao | 13-14 | 2 |
| **Total** | **14** | **14** |

84 jogos totais, 6 por rodada, sem folgas. Playoffs comecam na rodada 15.

### Funcionalidades

- Arquivo unico `index.html` — sem build, sem dependencias
- PWA: instalavel, funciona offline
- Tema claro/escuro (detecta preferencia do sistema)
- Importacao em massa via colar lista (virgula, ponto-e-virgula ou por linha)
- Copiar ou compartilhar resultados via Web Share API
- Design responsivo (mobile, tablet, desktop)

### Como usar

1. Abra `index.html` em qualquer navegador moderno
2. Configure numero de participantes e grupos
3. Insira os nomes (ou cole uma lista)
4. Clique em **Sortear** para sortear
5. Se 4 grupos de 3 → clique em **Gerar Calendario** para o calendario completo

### Tecnologia

HTML + CSS + JavaScript — tudo em um arquivo. Sem frameworks, sem bundler, sem servidor.
