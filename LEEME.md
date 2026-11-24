# Plataforma del taller - Tu manuscrito, tu revista

Archivos: index.html (participantes), tallerista.html (consola), config.js (ajustes), sage.css (diseño Sage), img/ (favicons y logo).

## Fuentes Sage Peak
Sage Peak es propietaria y no está en este repositorio. Para verla, crea la carpeta `fonts/` y sube
`SagePeak-Medium.otf` y `SagePeak-Bold.otf` (están en la carpeta fonts del sistema de diseño Sage).
Sin ellas, los titulares usan Open Sans automáticamente.

## Antes del taller
- Abre la consola y una ventana de participante (modo incógnito) y prueba: entrar, habilitar etapas, votar.
- Modo demo sin servidor: index.html?demo=1

## Durante el taller
- Etapa nueva: botón "Habilitar siguiente etapa". Comparte el enlace de participantes y el código de entrada (SAGE-UNAL) en el chat al inicio.
- Si alguien no se conecta: "Copiar mensaje para el chat" trae el código de esa etapa. Los códigos son nombres de recursos de Sage: JOURNALS, METHODS, BOOKS, BUSINESS, CAMPUS, SKILLS, VIDEO y DATA (se pueden cambiar en config.js, lista CODES).
- No cierres la pestaña de la consola: reenvía la etapa cada 8 segundos para quienes entren tarde.

## PDF de la guía
En la última etapa el participante marca una casilla de responsabilidad y descarga su guía en PDF con diseño Sage. El PDF se genera en su dispositivo con las librerías de la carpeta vendor/ (jsPDF y Open Sans). La plataforma no muestra la guía en pantalla ni guarda nada.
