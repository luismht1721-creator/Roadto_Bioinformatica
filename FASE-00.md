# Fase 00 — Fundamentos de cómputo

**Duración:** 4 semanas · **Ritmo:** ~1 hora/día (5 días/semana)
**Punto de partida:** cero experiencia en terminal y Python.

> Meta de la fase: dejar de pelear con la computadora. Bash, Git, un entorno de Python
> funcional y los fundamentos del lenguaje. Todo lo demás del programa depende de esto.

---

## ⚠️ Antes de empezar: usa Git Bash, no PowerShell

Las lecciones de la terminal asumen comandos de Unix (`ls`, `pwd`, `cat`…), que **no** son
los de PowerShell (`dir`, `cls`…). Como ya instalaste Git para Windows, ya tienes **Git Bash**:
búscalo en el menú Inicio y úsalo para toda la Semana 1. (PowerShell guárdalo solo para Git.)

---

## Semana 1 — La terminal (Bash)

**Recurso:** Software Carpentry — The Unix Shell → https://swcarpentry.github.io/shell-novice/
**Objetivo:** moverte por el sistema de archivos sin miedo y entender qué pasa "por debajo".

| Día | Tema | Comandos clave |
|-----|------|----------------|
| 1 | Abrir Git Bash · navegación | `pwd`, `ls`, `cd` |
| 2 | Crear y mover archivos | `mkdir`, `touch`, `cp`, `mv`, `rm` (¡cuidado con `rm`!) |
| 3 | Ver contenido y comodines | `cat`, `less`, `head`, `tail`, `*` |
| 4 | Tuberías y filtros | `|`, `grep`, `wc`, `sort` |
| 5 | Repaso + mini-reto | Organizar una carpeta desordenada solo con la terminal |

**Hito:** terminar shell-novice de Carpentry.

---

## Semana 2 — Git de verdad

**Recurso:** Software Carpentry — Version Control with Git → https://swcarpentry.github.io/git-novice/
**Objetivo:** entender *qué hiciste* al subir tu repo, no solo repetir comandos.

| Día | Tema | Comandos clave |
|-----|------|----------------|
| 1 | Modelo mental: working dir → staging → commit | `git init`, `git status` |
| 2 | Guardar cambios + buenos mensajes | `git add`, `git commit`, `git log` |
| 3 | Ver diferencias, deshacer, ignorar | `git diff`, `git restore`, `.gitignore` |
| 4 | Remotos (lo que ya viviste) | `git remote`, `git push`, `git pull`, `git clone` |
| 5 | **Práctica real:** agregar este archivo al repo | (ver instrucciones abajo) |

**Hito:** tu segundo commit en el repo (este archivo `FASE-00.md`).

---

## Semana 3 — Python: primeros pasos

**Recurso:** Python for Everybody → https://www.py4e.com/ (capítulos 1–5)
**Objetivo:** instalar Python con conda y dominar variables, condicionales, funciones y bucles.

| Día | Tema |
|-----|------|
| 1 | Instalar **Miniforge**, crear y activar un entorno: `conda create -n bioinfo python` → `conda activate bioinfo` |
| 2 | py4e cap. 1–2: qué es un programa, expresiones, variables |
| 3 | py4e cap. 3: condicionales (`if` / `elif` / `else`) |
| 4 | py4e cap. 4: funciones |
| 5 | py4e cap. 5: iteración (`while`, `for`) + mini-ejercicio |

**Hito:** entorno conda funcional + tus primeros scripts corriendo.

---

## Semana 4 — Python: manejo de datos

**Recurso:** Python for Everybody (capítulos 6–10)
**Objetivo:** strings, listas, diccionarios y archivos — la base para manipular secuencias después.

| Día | Tema |
|-----|------|
| 1 | cap. 6: strings (clave: una secuencia de ADN *es* un string) |
| 2 | cap. 8: listas |
| 3 | cap. 9: diccionarios |
| 4 | cap. 7: leer y escribir archivos |
| 5 | **Proyecto de cierre:** script que lee un archivo de texto con una secuencia de ADN y cuenta cada nucleótido (A, T, G, C). Súbelo al repo. |

**Hito:** completar py4e cap. 1–10 + script final versionado en el repo.

---

## Cómo agregar este archivo al repo (tu práctica de la Semana 2)

Las credenciales ya están guardadas, así que esto funcionará sin pedirte nada:

```bash
git add FASE-00.md
git commit -m "Agregar plan de la Fase 00"
git push
```

Recarga GitHub y verás tu segundo commit en el historial. Eso es versionar de verdad.

---

## Carril paralelo: inglés (20 min/día, aparte de la hora técnica)

No forma parte de esta hora, pero corre en simultáneo desde ya. Esta semana: haz un
**examen diagnóstico de IELTS** para saber tu punto de partida.
