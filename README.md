[![Board Status](https://dev.azure.com/Hyrule-Nexus/34d7e7bf-7b28-47e9-89f9-4c9feca13c2e/4641a0af-9862-4ad2-ae5b-964391b03f8e/_apis/work/boardbadge/eadee5f6-8cba-4870-b32b-470ab5d14df3)](https://dev.azure.com/Hyrule-Nexus/34d7e7bf-7b28-47e9-89f9-4c9feca13c2e/_boards/board/t/4641a0af-9862-4ad2-ae5b-964391b03f8e/Microsoft.RequirementCategory)
# BlazorApp-Training
Proyecto de práctica para aprender a usar Git y GitHub desde Windows y Visual Studio.

## 🎯 Propósito del proyecto
Este repositorio existe únicamente para:
- Practicar el flujo básico de Git.
- Entender cómo funcionan los commits, ramas y merges.
- Aprender a navegar en Git desde la terminal (PowerShell) y desde Visual Studio.
- Familiarizarse con los comandos más usados en el día a día.
- Subir, actualizar y versionar una Blazor App simple.

## 🧰 Requisitos
- Windows 10/11
- Visual Studio 2022 (con el workload de ASP.NET y Blazor)
- Git para Windows instalado
- Cuenta de GitHub (opcional pero recomendado)

## 📁 Estructura del proyecto
Este es un proyecto base de Blazor (WebAssembly o Server, según la plantilla usada).
No tiene lógica avanzada: solo sirve como entorno para practicar Git.

## 🚀 Flujo básico de trabajo con Git

### 1. Inicializar repositorio (si no existe)
```
git init
```

### 2. Ver el estado del repositorio
```
git status
```

### 3. Agregar archivos al área de preparación (staging)
```
git add .
```

### 4. Crear un commit
```
git commit -m "Descripción del cambio"
```

### 5. Agregar un repositorio remoto (solo la primera vez)
```
git remote add origin `https://github.com/usuario/repositorio.git` [(github.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fgithub.com%2Fusuario%2Frepositorio.git")
```

### 6. Subir cambios por primera vez (configurando upstream)
```
git push --set-upstream origin main
```

### 7. Subir cambios después de la primera vez
```
git push
```

### 8. Descargar cambios del remoto
```
git pull
```

## 🌿 Trabajo con ramas

### Crear una rama nueva
```
git branch nombre-rama
```

### Cambiar de rama
```
git checkout nombre-rama
```

### Crear y cambiar en un solo paso
```
git checkout -b nombre-rama
```

### Fusionar una rama a main
```
git checkout main
git merge nombre-rama
```

## 🔍 Comandos útiles para navegar en Git

### Ver historial de commits
```
git log
```

### Ver historial resumido
```
git log --oneline --graph --decorate
```

### Ver diferencias entre archivos
```
git diff
```

### Ver ramas existentes
```
git branch
```

## 🖥️ Uso desde Visual Studio
Visual Studio permite:
- Ver cambios pendientes
- Crear commits
- Crear ramas
- Hacer merge
- Resolver conflictos
- Sincronizar con GitHub

Todo desde **View → Git Changes** y **Git → Branches**.

## 🧪 Objetivo final
Dominar el flujo:
1. Editar código
2. `git add`
3. `git commit`
4. `git push`
5. Crear ramas
6. Hacer merge
7. Resolver conflictos
8. Mantener el repo limpio y ordenado

Este proyecto es solo un campo de entrenamiento para eso.

## 📄 Licencia
Uso libre para práctica personal.
```
