# Claro desafío v0.1

Prototipo web del juego de capacitación de productos y accesorios.

## Probar localmente

Por seguridad del navegador, `questions.json` debe servirse mediante un servidor local.

Con Python:

```bash
python -m http.server 8080
```

Luego abrir `http://localhost:8080`.

## Publicar en GitHub Pages

1. Crear un repositorio público.
2. Subir todos los archivos de esta carpeta a la raíz.
3. Abrir `Settings > Pages`.
4. En `Build and deployment`, elegir `Deploy from a branch`.
5. Seleccionar la rama `main` y la carpeta `/root`.
6. Guardar y esperar la publicación.

## Estado actual

- 120 preguntas curadas.
- 10 familias.
- Ruleta animada.
- Vidas, puntaje, racha e insignias.
- Ranking local mediante `localStorage`.
- Diseño adaptable a celular y computadora.

## Próxima etapa

Conectar Supabase para compartir jugadores, progreso y ranking entre dispositivos.
