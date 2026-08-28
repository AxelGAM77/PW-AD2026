# Comandos Git

| Comando | Descripción | Ejemplo de caso de uso |
|---|---|---|
| `git init` | Inicializa un nuevo repositorio Git vacío en la carpeta actual. | `git init` |
| `git clone` | Crea una copia local de un repositorio remoto existente. | `git clone https://github.com/AxelGAM77/PW-AD2026.git` |
| `git status` | Muestra el estado actual de los archivos (modificados, en área de preparación, sin seguimiento). | `git status` |
| `git add` | Agrega cambios de archivos al área de preparación. | `git add index.html` |
| `git commit` | Guarda los cambios preparados como un nuevo punto en el historial del repositorio. | `git commit -m "Agrega página de inicio"` |
| `git push` | Envía los commits locales al repositorio remoto. | `git push origin main` |
| `git pull` | Descarga y fusiona los cambios del repositorio remoto con la rama local. | `git pull origin main` |
| `git fetch` | Descarga los cambios del repositorio remoto sin fusionarlos automáticamente. | `git fetch origin` |
| `git branch` | Lista las ramas existentes o crea una nueva. | `git branch feature-login` |
| `git checkout` | Cambia entre ramas o restaura archivos a un estado anterior. | `git checkout feature-login` |
| `git switch` | Cambia de rama de forma más simple y segura (comando moderno). | `git switch main` |
| `git merge` | Combina los cambios de una rama con la rama actual. | `git merge feature-login` |
| `git log` | Muestra el historial de commits del repositorio. | `git log --oneline` |
| `git diff` | Muestra las diferencias entre archivos, commits o ramas. | `git diff HEAD~1 HEAD` |
| `git remote` | Administra las conexiones a repositorios remotos. | `git remote add origin https://github.com/AxelGAM77/PW-AD2026.git` |
| `git reset` | Deshace cambios moviendo el puntero HEAD, con distintos niveles de impacto. | `git reset --hard HEAD~1` |
| `git revert` | Crea un nuevo commit que deshace los cambios de un commit anterior sin borrar el historial. | `git revert 3f2a1c9` |
| `git stash` | Guarda temporalmente los cambios no confirmados para volver a un estado limpio. | `git stash` |
| `git rm` | Elimina un archivo del repositorio y del directorio de trabajo. | `git rm archivo_obsoleto.txt` |
| `git tag` | Crea una etiqueta para marcar un punto específico del historial (ej. versiones). | `git tag v1.0.0` |
