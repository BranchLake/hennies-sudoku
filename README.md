# Hennie's sudokulösare

En sudokulösare i webbläsaren som lär dig tänka steg för steg.

- Skriv in ett pussel eller importera ett foto/en skärmbild (sifferigenkänning med Tesseract.js)
- **Ledtråd** förklarar nästa drag steg för steg (gömd singel, ensam kandidat, pekande par, rad/box-låsning, nakna par)
- **Lös** visar hela lösningen, **Kontrollera** markerar fel

Allt ligger i `index.html` – inget byggsteg behövs.

## Köra lokalt (Windows)

Dubbelklicka på `start.bat`, eller kör:

```
powershell -ExecutionPolicy Bypass -File server.ps1
```

Öppna sedan http://localhost:8080
