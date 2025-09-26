# Sitio PythonistaMX

Sitio web oficial de la comunidad PythonistaMX, construido con [Quarto](https://quarto.org).

## 🚀 Desarrollo Local

### Prerrequisitos

- [Quarto](https://quarto.org/docs/get-started/) instalado
- Python 3.7+ (opcional, para ejecutar código)

### Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/PythonistaMX/sitio-quarto.git
cd sitio-quarto
```

2. Previsualiza el sitio localmente:
```bash
quarto preview
```

3. Construye el sitio para producción:
```bash
quarto render
```

## 📁 Estructura del Proyecto

```
sitio-quarto/
├── _quarto.yml          # Configuración del proyecto
├── index.qmd            # Página principal
├── about.qmd            # Página "Acerca de"
├── styles.css           # Estilos personalizados
├── blog/
│   ├── index.qmd        # Índice del blog
│   └── posts/           # Artículos del blog
│       └── *.qmd
└── _site/               # Sitio generado (ignorado en git)
```

## ✍️ Contribuir

¿Quieres contribuir con contenido? ¡Excelente!

1. Haz fork del repositorio
2. Crea una rama para tu contribución
3. Agrega tu contenido en formato `.qmd`
4. Envía un Pull Request

### Crear un nuevo artículo

Para crear un nuevo artículo del blog:

1. Crea un archivo `.qmd` en `blog/posts/`
2. Usa el siguiente formato de header:

```yaml
---
title: "Título del artículo"
author: "Tu nombre"
date: "YYYY-MM-DD"
categories: [python, tutorial]
description: "Breve descripción"
---
```

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🌐 Enlaces

- [Comunidad en GitHub](https://github.com/PythonistaMX)
- [Quarto Documentation](https://quarto.org/docs/)
