# learning

Repositório organizacional que agrupa **projetos de aprendizado** (cursos, formações e estudos guiados) utilizando **Git submodules**.

Este repositório não concentra desenvolvimento ativo. Cada projeto possui **repositório próprio**, com histórico e commits independentes.

---

## Objetivo

- Organizar projetos de estudo por **plataforma** e **área**
- Evitar misturar estudos guiados com projetos autorais
- Manter histórico limpo e rastreável de cada projeto
- Facilitar navegação para fins de portfólio

---

## Estrutura

```
learning/
 ├─ dio/
 ├─ senai/
 └─ danki/
```

Cada pasta contém apenas **submodules**, representando projetos individuais.

---

## Plataformas

### DIO
Projetos de bootcamps, formações e laboratórios.

```
dio/
 ├─ aws/linux/iac
 └─ ifood-game-dev/game-dev-principles/open-source
```

### SENAI
Projetos do curso técnico e disciplinas práticas.

```
senai/
 ├─ programming-logic/portugol
 ├─ app-develop/invoice
 ├─ system-testing/webpage
 └─ system-develop/
    ├─ kanban
    └─ agenda
```

### Danki
Projetos de estudo focados em desenvolvimento de jogos.

```
danki/
 └─ game-develop/mini-games/zelda
```

---

## Submodules

Para clonar corretamente:

```bash
git clone --recurse-submodules https://github.com/siddigo/learning
```

Ou, após clonar:

```bash
git submodule update --init --recursive
```

---

## Observação

Este repositório contém **exclusivamente projetos de aprendizado**.  
Projetos autorais, conceituais ou produtos finais ficam em outros repositórios, como:

- `game-dev`
- `game-mods`

---

## Autor

Sidnei Rodrigo dos Santos
