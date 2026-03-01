# MiPsTeX

*by Conde Lucento, 2026*

---

# Español (ES)

**MiPsTeX** es un paquete de LaTeX diseñado para facilitar la escritura y presentación de código MIPS en tus apuntes o documentos. Permite resaltar instrucciones, registros y comentarios con colores personalizados, añadir títulos estilo pixel, y generar un índice automático de bloques de código.

## Características principales

- Títulos y subtítulos estilo "pixel" (`\mipstitle`, `\submipstitle`)  
- Entorno de código MIPS con:
  - Colores por tipo de instrucción
  - Comentarios en verde
  - Fondo gris
  - Numeración de líneas
- Bloques de código opcionalmente titulados con entrada automática en el **Code Index**
- Bloques de código sin título que mantienen el formato pero no aparecen en el índice

## Instalación

1. Copia el archivo `MiPsTeX.sty` en el mismo directorio que tu documento `.tex`, o en una carpeta reconocida por LaTeX (local `texmf`).  
2. Incluye el paquete en tu documento:

```latex
\usepackage{MiPsTeX}
```
---

# English (ENG)

**MiPsTeX** is a LaTeX package designed to make writing and presenting MIPS code in your notes or documents easier. It allows you to highlight instructions, registers, and comments with custom colors, add pixel-style titles, and generate an automatic index of code blocks.

## Main Features

- Pixel-style titles and subtitles (`\mipstitle`, `\submipstitle`)  
- MIPS code environment with:
  - Colors by instruction type
  - Green comments
  - Gray background
  - Line numbering
- Optionally titled code blocks that are automatically added to the **Code Index**
- Untitled code blocks that keep the formatting but do not appear in the index

## Installation

1. Copy the `MiPsTeX.sty` file to the same directory as your `.tex` document, or to a folder recognized by LaTeX (local `texmf`).  
2. Include the package in your document:

```latex
\usepackage{MiPsTeX}
```
