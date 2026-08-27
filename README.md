# 🌿 Proyecto Equipo

Repositorio de práctica creado como parte del **Taller Práctico Colaborativo de Git y GitHub**, usado por el equipo para ejercitar el flujo de trabajo con ramas, `push`/`pull`, resolución de conflictos de merge y `.gitignore`.

Este proyecto es intencionalmente simple: sirve como base común sobre la cual cada integrante crea su propia rama, modifica `index.html` y practica la sincronización con el repositorio remoto.

## 📁 Contenido del proyecto

```
proyecto-equipo/
├── index.html      # Estructura HTML base usada para practicar ramas y merges
├── styles.css       # Hoja de estilos del proyecto
└── .gitignore       # Archivos ignorados por Git (hola.env, debug.log)
```

## ⚠️ Notas sobre el estado actual

- `index.html` tiene una estructura incompleta: contiene etiquetas `<h1>` y `<h2>` fuera de cualquier documento HTML, seguidas de un segundo bloque `<html>` con un `<h1>` y un `<nav>` vacíos. Debe reescribirse como un único documento HTML válido (con `<!DOCTYPE html>`, `<head>` y `<body>`).
- `styles.css` está vacío; aún no contiene estilos.
- El archivo `.gitignore` está configurado para ignorar `hola.env` y `debug.log`, en línea con las buenas prácticas trabajadas en el taller (no subir archivos con credenciales o logs temporales).

## 🚀 Cómo usarlo

Este proyecto es un archivo estático simple (HTML + CSS), no requiere backend ni instalación de dependencias.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/yondermaldonado/proyecto-equipo.git
   cd proyecto-equipo
   ```

2. Abre `index.html` directamente en tu navegador.

## 👥 Equipo

- Yonder Daniel Maldonado Pabón
- Kleiderson Jesús Salcedo Rico
- Ricardo José Vargas Gamboa

## 📄 Licencia

Este proyecto se distribuye con fines educativos. Puedes usarlo y adaptarlo libremente citando la fuente.
