# Contribuir a Supabase Local Self-Hosted

¡Gracias por querer ayudar a mejorar este repositorio! Aquí hay algunas pautas para que tus aportes sean claros y fáciles de revisar.

## 1. Reportar un problema

Si encuentras un error o tienes una idea de mejora:

1. Abre un issue en GitHub.
2. Describe el problema con claridad.
3. Incluye los pasos para reproducirlo, tu sistema operativo y la versión de Docker si aplican.

## 2. Proponer un cambio

Para cambios en el código o la documentación:

1. Haz un fork del repositorio.
2. Crea una rama con un nombre descriptivo, por ejemplo:

```bash
git checkout -b fix-readme-translation
```

3. Haz tus cambios en la rama.
4. Asegúrate de que la documentación se mantenga clara y precisa.
5. Envía un pull request con una breve descripción de lo que cambiaste.

## 3. Estilo de contribución

- Mantén cambios pequeños y enfocados.
- Usa un lenguaje claro y directo.
- En documentos, evita errores ortográficos y conserva el formato Markdown.
- No incluyas datos sensibles.

## 4. Archivos importantes

- `README.md`: guía principal de uso.
- `SUPABASE_HERRAMIENTAS.md`: explicación didáctica de los servicios.
- `docker-compose.yml`: configuración principal de Docker Compose.
- `kong.yml`: reglas de enrutamiento para Kong.
- `.env.example`: plantilla de variables de entorno.

## 5. Reglas básicas

- No subas el archivo `.env`.
- No agregues secretos reales al repositorio.
- Si agregas un servicio nuevo, documenta cómo se conecta al resto del stack.

---

¡Gracias por contribuir! Tu ayuda hace que este proyecto sea más útil para toda la comunidad.
