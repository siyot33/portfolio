# Publicar este portfolio en GitHub

Este proyecto está preparado para subirlo a un repositorio de GitHub llamado
`portfolio`. Sigue estos pasos desde tu ordenador.

## 1. Crear el repositorio

1. Entra en https://github.com/new
2. En **Repository name**, escribe `portfolio`.
3. Selecciona **Public**.
4. No marques la opción de añadir un README, `.gitignore` o licencia: estos
   archivos ya están en esta carpeta.
5. Pulsa **Create repository**.

## 2. Subir el proyecto con Git

Abre una terminal dentro de esta carpeta y ejecuta:

```bash
git init
git branch -M main
git add .
git commit -m "Añadida la estructura inicial del portfolio"
git remote add origin https://github.com/TU-USUARIO/portfolio.git
git push -u origin main
```

Sustituye `TU-USUARIO` por tu nombre de usuario real de GitHub.

## 3. Continuar el historial de trabajo

Los commits deben registrar cambios reales a medida que trabajas. No inventes
fechas ni intentes hacer que parezca que trabajaste en días anteriores.
Cuando hagas una mejora real, guarda el cambio con un mensaje descriptivo:

```bash
git add .
git commit -m "Mejorada la ficha personal"
git push
```

Puedes usar mensajes como estos cuando hayas realizado esos cambios:

- `Mejorada la ficha personal`
- `Revisada la estructura HTML`
- `Ampliada la explicación del entorno de trabajo`
- `Actualizada la documentación del proyecto`

## 4. Entrega en Moodle

Cuando el repositorio esté publicado, copia su dirección, que tendrá este
formato:

`https://github.com/TU-USUARIO/portfolio`

Pega esa URL en la tarea de Moodle.

**Importante:** este ZIP incluye los archivos del proyecto y estas instrucciones,
pero no crea el repositorio remoto ni puede generar por sí solo los cinco
commits en distintos días. Eso debe hacerse desde tu cuenta de GitHub y
registrando tu trabajo real.
