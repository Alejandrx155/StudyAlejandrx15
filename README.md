# 📚 Study Alejandrx15

### 🚀 [Ver sitio](https://studyalejandrx-study-alejandrx15.vercel.app/)

Página web que usa Google Gemini para resumir, explicar, traducir, corregir y estudiar cualquier texto.

## Funciones

- 📝 Resumir
- 💡 Explicar (nivel simple)
- 🧠 Quiz (opción múltiple con puntuación interactiva)
- 🗂️ Flashcards (con flip)
- 🌐 Traducir (idioma configurable)
- ✅ Corregir gramática y ortografía
- 🎭 Cambiar tono (formal, informal, profesional, etc.)
- 🗺️ Mapa mental (esquema jerárquico visual)

## API Key (PRIVADA)

La página **no contiene ninguna API Key**. La key vive oculta en un servidor intermedio (Cloudflare Worker), en la variable de entorno `GEMINI_KEY`.

1. Crea un Worker en Cloudflare.
2. En **Settings → Variables and Secrets**, añade la variable secreta.
3. Pega el código del worker y copia su URL en `workerUrl` dentro de `index.html`.

Cualquier usuario puede además poner su propia key en **Ajustes** para usar su propia cuota.

Modelo configurado: `gemini-3.5-flash-lite`.

---
Desarrollado por Alejandrx.15
