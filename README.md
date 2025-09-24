# Evaluación - Primer Parcial

Este proyecto es una aplicación **Angular** que muestra una tarjeta con el texto:

**EVALUACIÓN - PRIMER PARCIAL**  
**Lía Jazmín**

Incluye un input para cambiar el nombre dinámicamente.

---

## Requisitos
- Node.js v16+ y npm
- Angular CLI instalado globalmente (`npm install -g @angular/cli`)
- Git configurado

---

## Pasos para ejecutar el proyecto

```bash
# 1. Clonar el repositorio (si lo tienes en GitHub)
git clone <url-del-repo>
cd evaluacion-app

# 2. Instalar dependencias
npm install

# 3. Ejecutar servidor de desarrollo
ng serve --open
```

Abrirá automáticamente en: [http://localhost:4200](http://localhost:4200)

---

## Flujo Git recomendado

```bash
# inicializar repositorio
git init

# añadir todos los archivos
git add .

# primer commit
git commit -m "chore: initial angular app - student card"

# crear nueva rama de feature
git switch -c feature/student-name-ui

# tras realizar cambios
git add .
git commit -m "feat: improve student card styles"

# volver a main y hacer merge
git checkout main
git merge feature/student-name-ui --no-ff -m "merge: feature student card"

# agregar remoto y subir
git remote add origin https://github.com/TU_USUARIO/evaluacion-app.git
git branch -M main
git push -u origin main

# trabajar con ramas adicionales
git push -u origin feature/student-name-ui
```

---

## Comandos útiles

```
git status
git log --oneline --graph
git diff
git stash
git revert <commit-id>
git tag -a v1.0 -m "Versión inicial"
git push origin --tags
```

---

## Autor
**Estudiante:** Lía Jazmín
