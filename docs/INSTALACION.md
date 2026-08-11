# Instalación y Uso - Aplicación BHD Desktop

## Requisitos Previos

- Node.js (v14 o superior)
- npm (incluido con Node.js)
- Git

## Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/Willianmateo/BHD-.git
   cd BHD-
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar la aplicación en desarrollo**
   ```bash
   npm start
   ```

## Compilar para Producción

Para crear un ejecutable standalone:

```bash
npm run build
```

Esto generará los instaladores en la carpeta `dist/`

## Estructura del Proyecto

```
BHD-/
├── src/
│   ├── main.js          # Punto de entrada de Electron
│   ├── index.html       # Interfaz HTML
│   ├── styles.css       # Estilos CSS
│   └── app.js          # Lógica de la aplicación
├── assets/
│   └── icons/
│       └── logo.svg    # Logo SVG
├── package.json        # Dependencias
└── README.md          # Este archivo
```

## Características

✅ Interfaz moderna y atractiva
✅ Logo BHD integrado
✅ Botones de participación
✅ Responsive design
✅ Multiplataforma (Windows, Mac, Linux)

## Desarrollo

- Para abrir DevTools, descomenta la línea en `src/main.js`:
  ```javascript
  mainWindow.webContents.openDevTools();
  ```

## Licencia

GNU General Public License v3.0
