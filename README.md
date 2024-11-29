# Formulario de Inscripción a Carrera

Este proyecto es un formulario de inscripción moderno desarrollado con React, TypeScript y Tailwind CSS.

## Requisitos Previos

- Node.js (versión 16 o superior)
- npm (viene incluido con Node.js)
- Visual Studio Code

## Pasos para Ejecutar el Proyecto en Visual Studio Code

1. Clona el repositorio o descarga los archivos del proyecto

2. Abre Visual Studio Code y abre la carpeta del proyecto

3. Abre la terminal en Visual Studio Code:
   - Presiona `Ctrl + ñ` (Windows/Linux) o `Cmd + ñ` (Mac)
   - O ve a `Ver -> Terminal`

4. Instala las dependencias:
   ```bash
   npm install
   ```

5. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

6. El proyecto se abrirá automáticamente en tu navegador predeterminado.
   - Si no se abre automáticamente, abre [http://localhost:5173](http://localhost:5173) en tu navegador

## Estructura del Proyecto

```
src/
  ├── components/
  │   └── CareerForm/
  │       ├── CareerSelect.tsx
  │       ├── PersonalInfo.tsx
  │       ├── ContactInfo.tsx
  │       └── PersonalSurvey.tsx
  ├── App.tsx
  └── main.tsx
```

## Scripts Disponibles

- `npm run dev`: Inicia el servidor de desarrollo
- `npm run build`: Construye la aplicación para producción
- `npm run preview`: Previsualiza la versión de producción localmente