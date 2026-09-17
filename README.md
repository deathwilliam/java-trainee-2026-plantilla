# Curso de Java y Spring Boot — Entregas

**Programa Digital Trainee 2026** · Banco Cuscatlán · Facilitador: Wilfredo Melgar

Este es **tu** repositorio del curso. Acá va todo lo que escribas durante los dos meses: los
ejercicios de cada clase, las tareas y el proyecto integrador que defendés el **16 de
noviembre**.

---

## Cómo se entrega

No hay que mandar archivos por chat ni comprimir nada. **Entregar es hacer push.**

```bash
git add .
git commit -m "ejercicio de la sesion 3"
git push
```

Eso es todo. Lo que está en GitHub es lo que se revisa.

---

## Hacé commit mientras trabajás, no al final

Esto es lo más importante de esta página, y no es por prolijidad.

Un solo commit gigante al final de la clase no dice nada de vos. Cinco commits repartidos
muestran **cómo pensaste**: por dónde empezaste, qué te costó, cómo lo resolviste. Cuando
revisamos tu entrega, el historial se lee tanto como el código.

Y hay una razón práctica: si algo se rompe, con commits podés volver atrás. Sin commits,
perdiste el trabajo.

**Regla simple: cada vez que algo te funcione, commit.** Aunque esté a medias.

### Mensajes de commit

| | |
| :--- | :--- |
| ✅ `agrego la clase Cuenta con sus getters` | Se entiende qué hiciste |
| ✅ `arreglo el error de super en ProductoFisico` | Mejor todavía: se ve que peleaste con algo |
| ❌ `asdasd` · `cambios` · `update` | No dice nada |

---

## Dónde va cada cosa

```
semana-01/    ← ejercicios de esa semana
semana-02/
...
proyecto/     ← el proyecto integrador, desde la semana 7
```

Dentro de cada semana, una carpeta por sesión: `sesion-03/`, `sesion-04/`…

---

## Si no compila, subilo igual

En serio. **No borres el código roto para que se vea mejor.**

Un archivo que no compila con un intento honesto vale muchísimo más que una carpeta vacía:
muestra dónde te trabaste, que es justo lo que hace falta saber para ayudarte. Si algo quedó a
medias, escribí un comentario arriba diciendo qué estabas intentando hacer. Se lee.

---

## Lo que NO se sube

El `.gitignore` ya los filtra, pero para que sepas por qué:

- `out/`, `target/`, `*.class` — son el resultado de compilar. Se regeneran solos
- `.idea/` — la configuración de tu IntelliJ. Solo sirve en tu máquina

**Al repositorio va el código fuente, nunca lo compilado.**

---

## Sobre el uso de IA

La política del curso es por etapas:

| Semanas | Para qué |
| :--- | :--- |
| 1 a 6 | Entender conceptos y traducir mensajes de error |
| 7 y 8 | Como asistente, con criterio propio |
| 9 y 10 | Como en el trabajo real |

La regla que gobierna todo: **si no podés explicar una línea, esa línea no cuenta.**

En la defensa del 16/11 se te va a preguntar por tu propio código.
