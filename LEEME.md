# Plataforma del taller - Tu manuscrito, tu revista

Archivos: index.html (participantes), tallerista.html (consola), config.js (ajustes).

## 1. Supabase (5 minutos)
1. Crea un proyecto en supabase.com (no necesitas tablas).
2. Project Settings > API: copia Project URL y la clave pública (anon o publishable).
3. Pégalas en config.js (SUPABASE_URL y SUPABASE_KEY). No uses la clave service_role.
4. Cambia CODE (código de entrada) y SALT (frase secreta para los códigos de etapa).

## 2. GitHub Pages
1. Crea un repositorio (por ejemplo, taller-manuscrito) y sube los 3 archivos.
2. Settings > Pages > Deploy from a branch > main / root.
3. Participantes: https://fvargasj1.github.io/taller-manuscrito/
   Consola: https://fvargasj1.github.io/taller-manuscrito/tallerista.html

## 3. Antes del taller
- Abre la consola y una ventana de participante (modo incógnito) y prueba: entrar, habilitar etapas, votar.
- Modo demo sin servidor: index.html?demo=1

## Durante el taller
- Etapa nueva: botón "Habilitar siguiente etapa". Comparte el enlace de participantes y el código de entrada en el chat al inicio.
- Si alguien no se conecta: "Copiar mensaje para el chat" trae el código de esa etapa.
- No cierres la pestaña de la consola: reenvía la etapa cada 8 segundos para quienes entren tarde.
