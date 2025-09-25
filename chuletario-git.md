# 🚀 Chuletario Git Bash – Flujo Profesional

## 🔹 Navegación de carpetas
```bash
cd ~/Documents/Proyectos         # ir a la carpeta Proyectos
cd Python/proyecto-prueba        # entrar a tu repo
ls                               # listar archivos
pwd                              # mostrar la ruta actual
Configuración inicial (solo una vez en tu PC)
git config --global user.name "Tu Nombre"
git config --global user.email "tu_correo@ejemplo.com"

🔹 Flujo básico
git status
git add .
git commit -m "Mensaje claro"
git push origin main

🔹 Actualizar cambios desde GitHub
git pull origin main

🔹 Ramas (trabajo en features)
git checkout -b nueva-rama
git checkout main
git merge nueva-rama

🔹 Subir proyecto nuevo a GitHub
git init
git remote add origin URL_DEL_REPO
touch README.md
git add .
git commit -m "Proyecto nuevo iniciado"
git push -u origin main