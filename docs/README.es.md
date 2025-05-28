**Languages:** [English](../README.md) | [Español](README.es.md)

# Nombre del Proyecto

Una breve descripción de lo que hace este proyecto y para quién está dirigido.

## Tabla de Contenidos

- [Instalación](#installation)
- [uso](#usage)
- [Contribuciones](#contributing)
- [Licencia](#license)
- [Contacto](#contact)

## Instalación

Describe cómo instalar las dependencias utilizando las herramientas de tu stack (por ejemplo, `pip install -r requirements.txt` o `npm install`).

## Uso

Ejemplos de cómo utilizar el proyecto. Proporciona comandos básicos de uso o ejemplos de código.

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, consulta [CONTRIBUTING.md](../CONTRIBUTING.md) para ver las directrices.

## Formatos

- [Pull Request Template](../.github/PULL_REQUEST_TEMPLATE.md)
- **Issue Templates:**
  - [Bug Report](../.github/ISSUE_TEMPLATE/bug_report.md)
  - [Feature Request](../.github/ISSUE_TEMPLATE/feature_request.md)

---

## Licencia

Distribuido bajo la [MIT License](LICENSE).

## Contacto

Your Name — [your.email@example.com](mailto:your.email@example.com)

## Buenas Prácticas
> **Nota:**  
> Esta sección de "Buenas Prácticas" está destinada como una guía interna del equipo. No es necesario incluir esta sección en tu `README.md` público/privado en GitHub.

### 1. Convenciones de Nomenclatura

- **Nombre de proyecto:**  
  Usa solo minúsculas, con palabras separadas por guiones para mejorar la legibilidad.  
  Formato: `nombreproyecto-subnombre`  
  **Ejemplos:**  
  - `data-collector`
  - `procesador-images`
  - `drone-monitoring-tool`

- **Carpetas y Archivos:**  
  - Usa solo minúsculas y guiones o guiones bajos.  
    Ejemplo: `data_processing/`, `model-evaluation/`, `main.py`, `utils.js`

- **Variables (en código):**  
  - Usa `snake_case` para Python y `camelCase` para JavaScript/TypeScript.  
    Ejemplo: `image_path`, `userData`

- **Ramas:**  
  - Usa un patrón consistente:  
    - `feature/descripcion-corta`
    - `bugfix/descripcion-corta`
    - `hotfix/descripcion-corta`
    - `docs/descripcion-corta`
  - Ejemplos:  
    - `feature/login-authentication`
    - `bugfix/image-upload`

---

### 2. Mensajes de Commit

- **Formato:**  

**Tipos:**
- `feat`: Nueva funcionalidad
- `fix`: Corrección de errores
- `docs`: Cambios en la documentación
- `refactor`: Refactorización de código
- `test`: Agregar o actualizar pruebas
- `chore`: Tareas de mantenimiento

**Ejemplos:**
- `feat: add user login page`
- `fix: resolve crash on empty data input`
- `docs: update contributing guidelines`

- **Mejores Prácticas:**
- Usa el modo imperativo ("add", no "added" o "adds").
- Referencia issues o pull requests cuando sea relevante (`fixes #42`).
- Escribe resúmenes descriptivos y significativos.

---

### 3. Frecuencia de Commits

- Haz commits con frecuencia, con **commits pequeños y enfocados**.  
- Cada commit debe representar un único cambio lógico.  
- Evita commits grandes que mezclen varios cambios no relacionados.

---

### 4. Pull Requests

- Crea pull requests (PRs) para fusionar cambios en las ramas `main` o `develop`.
- Completa la plantilla de PR con explicaciones claras.
- Asegúrate de que tu branch esté actualizado con la rama de destino antes de abrir un PR.
- Solicita revisiones a los miembros del equipo relevantes.

---

### 5. Otras Prácticas Importantes

- **Estilo de Código:**  
  - Sigue la guía de estilo del lenguaje/framework. Usa herramientas de formateo (por ejemplo, `black` para Python, `prettier` para JavaScript).

- **Documentación:**  
  - Documenta todas las clases, funciones y módulos públicos.
  - Actualiza la documentación cuando realices cambios en el comportamiento del código.

- **Testing:**  
  - Escribe pruebas para todas las nuevas funcionalidades y correcciones de errores.
  - Asegúrate de que las pruebas pasen antes de hacer push o abrir PRs.

- **Issues:**  
  - Usa títulos claros y descripciones detalladas al crear issues.
  - Aplica las etiquetas y asignaciones adecuadas.

---

### 6. Gestión de Tareas y Flujos de Trabajo

- **Usa GitHub Projects (Kanban):**  
  Organiza tu trabajo usando el tablero Kanban de GitHub Projects:
  - Crea un **Project Board** para tu repositorio u organización.
  - Usa columnas como **To do**, **In progress** y **Done** para visualizar el estado de issues y pull requests.
  - Vincula issues y pull requests a las tarjetas del tablero para una trazabilidad clara.
  - Actualiza el tablero regularmente conforme avanza el trabajo para mantener al equipo alineado.
  - Prioriza y asigna tareas, establece plazos y usa etiquetas para un seguimiento eficaz del proyecto.

  **Recursos:**
  - [Documentación de GitHub Projects](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards)
  - [Cómo crear un tablero Kanban en GitHub](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/creating-a-project-board)

#### Tabla Resumen

| Elemento        | Formato/Mejor Práctica                        |
|-----------------|-----------------------------------------------|
| Project Name    | `lowercase-with-hyphens`                      |
| Branch Name     | `type/short-description`                      |
| Commit Message  | `[type]: short description` (imperativo)      |
| Commit Size     | Cambios pequeños, enfocados y lógicos         |
| Documentation   | Actualizar README, comentarios de código, docs|
| Testing         | Añadir/mantener pruebas automatizadas         |
| Task Management | Usar Kanban de GitHub Projects para el seguimiento de tareas |

---
