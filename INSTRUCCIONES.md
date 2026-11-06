# Perfil GitHub — Eber Pauccara Huancara

Este paquete está preparado para el repositorio especial de perfil de GitHub: `Eber-123`.

## Contenido
- `README.md`: presentación que aparece en la página principal de tu perfil.
- `assets/profile-banner.svg`: banner tipo editor de código con animación SVG y tu fotografía.
- `assets/logo-ep.svg`: logo EP creado con tus iniciales porque no se adjuntó un archivo de logo personal independiente.
- `assets/`: fotografía, proyecto Fishmon 365, certificados y constancia.

## Publicar en GitHub
1. Entra a https://github.com/Eber-123
2. Crea un repositorio público llamado exactamente `Eber-123` si todavía no existe.
3. Marca la opción de agregar README solo si el repositorio está vacío; si ya existe, descarga o clona primero su contenido.
4. Descomprime este ZIP.
5. Sube `README.md` y la carpeta `assets` a la raíz del repositorio.
6. Confirma el commit. Tu presentación aparecerá en `https://github.com/Eber-123`.

## Si trabajas con Git en la carpeta descomprimida
Si el repositorio remoto está vacío:
```powershell
git init -b main
git add .
git commit -m "Create Eber profile README"
git remote add origin https://github.com/Eber-123/Eber-123.git
git push -u origin main
```

Si GitHub ya tiene contenido o un commit inicial, primero clona el repositorio y copia dentro los archivos de este paquete. No uses `--force`.

## Personalización pendiente
El logo EP es una propuesta original basada en tus iniciales, no un logotipo oficial que hayas proporcionado. Si tienes un logo propio, se puede reemplazar `assets/logo-ep.svg`.
La URL del portafolio web se deja pendiente hasta que publiques la página.
