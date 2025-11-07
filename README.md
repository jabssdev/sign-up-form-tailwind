# 🚀 Formulario de Registro (Sign Up) con Tailwind CSS v4

Un proyecto de aprendizaje simple que implementa un formulario de **Registro de Usuario (Sign Up)**. Está construido con **HTML semántico** y estilizado completamente con las últimas utilidades de **Tailwind CSS v4**.

El enfoque de este proyecto es practicar la maquetación de componentes de interfaz complejos, como formularios, utilizando las clases de utilidad de Tailwind, junto con el flujo de trabajo de build optimizado mediante la CLI.

---

## 🚀 Tecnologías Utilizadas

- **HTML5**
- **Tailwind CSS v4** (Implementado mediante su herramienta de línea de comandos: `@tailwindcss/cli`).
- **npm** para la gestión de scripts y dependencias.

---

## ⚙️ Configuración e Instalación

Para poner en marcha el proyecto, solo necesitas instalar las dependencias de Node:

1. Clona el repositorio.
2. Abre la terminal en la raíz del proyecto.
3. Instala las dependencias:

   ```bash
   npm install
   ```

---

## ▶️ Uso y Scripts

Hemos configurado dos comandos clave en `package.json` para facilitar el trabajo:

### 1. Modo Desarrollo (`--watch`)

Este comando genera el CSS y se queda observando tus archivos HTML para regenerar el CSS automáticamente con cada cambio.

```bash
npm run tailwind
```

### 2. Modo Producción (`--minify`)

Este comando es crucial antes de subir a producción. Genera el CSS final, realizando la optimización (eliminando el CSS no utilizado, o Purge/Tree-Shaking) y minificando el archivo.

```bash
npm run tailwind:build
```
