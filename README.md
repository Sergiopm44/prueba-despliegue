# ¿Qué es Git y Git Flow?

## ¿Qué es Git?
**Git** es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en el código fuente y coordinar el trabajo en equipo. Es una herramienta fundamental para gestionar proyectos de software, ya que facilita:

- **Historial de cambios**: Registra cada modificación realizada en los archivos.
- **Trabajo colaborativo**: Permite que varios desarrolladores trabajen simultáneamente en el mismo proyecto.
- **Gestión de ramas**: Ayuda a desarrollar nuevas funcionalidades o corregir errores en ramas separadas sin afectar la rama principal.

Algunas de las ventajas de Git incluyen su velocidad, flexibilidad y capacidad de trabajar sin conexión, ya que es distribuido.

---

## ¿Qué es Git Flow?
**Git Flow** es una estrategia o flujo de trabajo para organizar y gestionar ramas en un repositorio de Git. Fue propuesto por *Vincent Driessen* y es especialmente útil en proyectos con ciclos de desarrollo estructurados, como los que incluyen lanzamientos periódicos.

### Principales ramas en Git Flow
1. **`main`**:
   - Es la rama principal y siempre debe estar lista para ser lanzada en producción.
   - Contiene el código estable.

2. **`develop`**:
   - Rama principal de desarrollo.
   - Aquí se integran las nuevas funcionalidades antes de ser lanzadas.

### Tipos de ramas en Git Flow
Además de `main` y `develop`, Git Flow utiliza otras ramas temporales para facilitar la gestión del ciclo de desarrollo:

1. **Feature branches (ramas de funcionalidad)**:
   - Se usan para desarrollar nuevas características.
   - Se crean a partir de `develop` y, una vez completadas, se fusionan de vuelta en `develop`.
   - Ejemplo: `feature/nueva-funcionalidad`.

   ```bash
   git checkout -b feature/nueva-funcionalidad develop
# ¿Qué es Git y Git Flow?

## ¿Qué es Git?
**Git** es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en el código fuente y coordinar el trabajo en equipo. Es una herramienta fundamental para gestionar proyectos de software, ya que facilita:

- **Historial de cambios**: Registra cada modificación realizada en los archivos.
- **Trabajo colaborativo**: Permite que varios desarrolladores trabajen simultáneamente en el mismo proyecto.
- **Gestión de ramas**: Ayuda a desarrollar nuevas funcionalidades o corregir errores en ramas separadas sin afectar la rama principal.

Algunas de las ventajas de Git incluyen su velocidad, flexibilidad y capacidad de trabajar sin conexión, ya que es distribuido.

---

## ¿Qué es Git Flow?
**Git Flow** es una estrategia o flujo de trabajo para organizar y gestionar ramas en un repositorio de Git. Fue propuesto por *Vincent Driessen* y es especialmente útil en proyectos con ciclos de desarrollo estructurados, como los que incluyen lanzamientos periódicos.

### Principales ramas en Git Flow
1. **`main`**:
   - Es la rama principal y siempre debe estar lista para ser lanzada en producción.
   - Contiene el código estable.

2. **`develop`**:
   - Rama principal de desarrollo.
   - Aquí se integran las nuevas funcionalidades antes de ser lanzadas.

### Tipos de ramas en Git Flow
Además de `main` y `develop`, Git Flow utiliza otras ramas temporales para facilitar la gestión del ciclo de desarrollo:

1. **Feature branches (ramas de funcionalidad)**:
   - Se usan para desarrollar nuevas características.
   - Se crean a partir de `develop` y, una vez completadas, se fusionan de vuelta en `develop`.
   - Ejemplo: `feature/nueva-funcionalidad`.

   ```bash
   git checkout -b feature/nueva-funcionalidad develop
