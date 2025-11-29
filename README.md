# proyecto-copilot

Blog técnico sobre Arquitectura de Software para la actividad. Contiene tres publicaciones y está implementado con HTML y CSS.

Cómo probar localmente
1. Abrir `index.html` en un navegador o ejecutar:

```powershell
python -m http.server 8000
# y abrir http://localhost:8000
```

Despliegue en GitHub Pages
1. Subir este repositorio a GitHub (crear repo y push a `main`).
2. En la página del repositorio en GitHub, Settings → Pages y elegir la rama `main` como fuente. El sitio estará disponible en `https://<usuario>.github.io/<repo>`.

Comandos útiles (PowerShell):

```powershell
git add -A
git commit -m "Añade blog técnico con 3 posts sobre Arquitectura de Software"
git push origin main
```

Si prefieres crear y publicar con la CLI de GitHub (`gh`):

```powershell
gh repo create <owner>/<repo> --public --source . --remote origin --push
gh repo view --web
```

Si quieres, puedo crear el commit y/o empujar los cambios al remoto — dime si autorizas.
Proyecto de prueba para Estructura de Datos 2
