# Actividad de GitHub Classroom: Propuesta de Práctica Temática Pequeña

## 1) Título
**Diseña tu propio:** **“Asistente de Estudio en Terminal”**

> También puedes proponer un título equivalente, claro y específico, por ejemplo:
> - “Mini Toolkit en ARM64”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general
En esta actividad **no vas a construir un sistema grande**; vas a diseñar y documentar una **propuesta de proyecto pequeño** que pueda desarrollarse de forma realista en este curso.

Tu propuesta debe enfocarse en:
- definir una idea clara y útil,
- justificar su valor académico o práctico,
- planear la estructura del repositorio,
- describir pruebas básicas,
- y solo después considerar una implementación mínima.

### Lenguaje principal (elige uno)
Debes elegir **un solo lenguaje principal** para tu propuesta:
- ARM64 Assembly
- C
- Python
- Bash

> **Recomendación importante:** si eliges **ARM64 Assembly**, tu alcance debe ser **muy pequeño** (programas cortos, rutinas simples o utilidades mínimas).

### Restricciones de alcance
Para mantener la práctica viable con herramientas gratuitas (Codex u otras IAs con límites):
- mantén el proyecto en tamaño pequeño;
- evita frameworks pesados;
- evita APIs pagadas;
- evita bases de datos;
- evita servicios en la nube;
- evita contenedores;
- evita dependencias complejas.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir **como mínimo** los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Elementos opcionales (si aplican a tu propuesta):
- `src/`
- `scripts/`
- `tests/`

### Contenido esperado por archivo

#### `README.md`
Incluye:
- nombre de la práctica;
- objetivo general (3–6 líneas);
- lenguaje principal elegido;
- descripción breve de la idea;
- instrucciones mínimas para ejecutar (si ya existe prototipo);
- estructura del repositorio (resumen).

#### `docs/propuesta.md`
Incluye:
- tema del proyecto;
- problema que resuelve;
- alcance pequeño y delimitado;
- funcionalidades mínimas (MVP);
- límites explícitos (qué **no** hará el proyecto);
- recursos requeridos (solo herramientas básicas).

#### `docs/caso_de_uso.md`
Incluye:
- escenario realista de uso;
- tipo de usuario;
- flujo principal paso a paso;
- entrada esperada y salida esperada;
- ejemplo concreto de ejecución o interacción.

#### `docs/estructura_repositorio.md`
Incluye:
- árbol de carpetas propuesto;
- propósito de cada carpeta/archivo;
- convención de nombres;
- estrategia básica de versionamiento (commits claros y pequeños).

#### `docs/plan_de_pruebas.md`
Incluye:
- al menos 5 casos de prueba;
- formato: ID, objetivo, entrada, pasos, resultado esperado;
- al menos 1 caso de error;
- criterios de aceptación mínimos.

---

## 4) Estructura recomendada del repositorio
Usa como base esta estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `main.<ext>` debe coincidir con tu lenguaje principal:
> - `.s` para ARM64 Assembly
> - `.c` para C
> - `.py` para Python
> - `.sh` para Bash

---

## Criterios de evaluación sugeridos

1. **Claridad de la propuesta (30%)**
   - Idea bien definida, realista y acotada.

2. **Calidad de documentación (30%)**
   - Documentos completos, ordenados y fáciles de seguir.

3. **Coherencia técnica (20%)**
   - Lenguaje elegido, estructura y pruebas alineadas con el objetivo.

4. **Viabilidad del alcance (20%)**
   - Proyecto pequeño, ejecutable en entorno local, sin complejidad innecesaria.

---

## Formato de entrega
- Repositorio en GitHub Classroom con los archivos solicitados.
- Redacción en español.
- Markdown limpio y legible.
- Commits descriptivos (por ejemplo: `docs: agrega propuesta inicial`).

---

## Sugerencias finales para estudiantes
- Empieza por delimitar el problema en una sola frase.
- Si dudas entre lenguajes, elige Python o Bash para avanzar más rápido.
- Si eliges ARM64, reduce el objetivo a una utilidad mínima.
- Prioriza documentación de calidad sobre cantidad de código.
