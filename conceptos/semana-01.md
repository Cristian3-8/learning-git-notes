# 📘 Semana 1 - Fundamentos de Git

## 1. ¿Qué es Git? (2025-12-01)
Git es un sistema de control de versiones distribuido que permite rastrear cambios en archivos y coordinar el trabajo entre múltiples personas.

## 2. Commit (2025-12-02)
Un commit es una instantánea del estado de tu proyecto en un momento específico. Cada commit tiene:
- Hash único (ej: `a1b2c3d`)
- Autor y fecha
- Mensaje descriptivo
- Referencia al commit anterior

## 3. Ramas (Branches) (2025-12-03)
Las ramas son líneas de desarrollo independientes que permiten trabajar en features, fixes o experimentos sin afectar la rama principal (`main`/`master`).

## 4. .gitignore (2025-12-04)
Archivo que especifica qué archivos/directorios Git debe ignorar. Ejemplos comunes:
- Archivos de entorno (`.env`)
- Logs (`*.log`)
- Dependencias (`node_modules/`)

## 5. Merge vs Rebase (2025-12-05)
- **Merge**: Crea un nuevo commit que une dos ramas, preservando toda la historia.
- **Rebase**: Reorganiza la historia moviendo commits de una rama a otra, creando una línea temporal lineal.

## 6. Stash (2025-12-06)
Guarda cambios no commitidos temporalmente, permitiendo cambiar de rama sin perder trabajo.
```bash
git stash        # Guardar cambios
git stash pop    # Recuperar cambios
