# Contribuir a MiPsTeX 🚀

¡Hola! Gracias por interesarte en mejorar **MiPsTeX**. Este proyecto nació para hacer que los apuntes de arquitectura de computadores se vean geniales, y cualquier ayuda es bienvenida.

Puedes contribuir de muchas formas: reportando errores, sugiriendo nuevas instrucciones MIPS para resaltar o mejorando la documentación.

## 🛠 ¿Cómo puedo ayudar?

### 1. Reportar Errores (Bugs)
Si encuentras algo que no funciona o un comando de MIPS que no se colorea correctamente:
* Revisa si ya existe una **Issue** abierta sobre el tema.
* Si no, abre una nueva detallando qué versión de LaTeX usas y un ejemplo mínimo que falle.

### 2. Sugerir Mejoras
¿Te gustaría que el estilo "pixel" tuviera más colores? ¿Falta algún registro específico? 
* Abre una **Issue** con la etiqueta `enhancement`.

### 3. Enviar un Pull Request (PR)
Si quieres meter mano al código directamente:
1. Haz un **Fork** del repositorio.
2. Crea una rama para tu mejora: `git checkout -b feature/mejora-increible`.
3. Realiza tus cambios en `MiPsTeX.sty`.
4. **Prueba tus cambios**: Asegúrate de que `Example.tex` compila correctamente con tus modificaciones.
5. Haz un push de tu rama y abre un **Pull Request**.

## 🎨 Guía de Estilo (LaTeX)
Para mantener la coherencia en el código del paquete:
* **Comentarios:** Explica para qué sirve cada nueva definición de color o comando.
* **Compatibilidad:** Intenta no cargar paquetes muy pesados que puedan entrar en conflicto con otros (como `geometry` o `fancyhdr`).
* **Sintaxis MIPS:** Si añades instrucciones, agrúpalas por tipo (aritméticas, de salto, de memoria) para mantener el orden actual.

## 👾 Sobre el estilo Pixel
Si decides modificar los comandos `\mipstitle` o `\submipstitle`, intenta que mantengan la estética retro. Si conoces una fuente tipográfica "pixel" que sea libre y mejor que la actual, ¡coméntalo en una Issue!

---

¡Gracias por ayudar a que la arquitectura de computadores sea un poco más bonita! 
— **CondeLucento**
