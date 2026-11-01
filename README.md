# 🌸 HoYoverse Waifu Tiermaker (2026 Edition)

Aplicación web interactiva y fluida estilo TierMaker con **256 waifus oficiales y anunciadas** de los tres principales universos de HoYoverse:
- ⚔️ **Genshin Impact** (107 personajes, hasta versión 7.1 Snezhnaya)
- 🚂 **Honkai: Star Rail** (82 personajes, hasta versión 4.6 e variantes SP)
- ⚡ **Zenless Zone Zero** (67 personajes, hasta versión 3.4 y Ángeles del Delirio)

*(Estrictamente excluye Honkai Impact 3rd por diseño).*

---

## 🚀 Despliegue con GitHub Pages

Este proyecto funciona 100% en el navegador (Vanilla JavaScript + Tailwind CSS CDN), sin necesidad de Node.js, compilación ni dependencias backend.

1. Sube `index.html` a la rama principal (`main`) de tu repositorio.
2. Ve a **Settings** > **Pages** en tu repositorio de GitHub.
3. En **Branch**, selecciona `main` y la carpeta `/(root)`.
4. Haz clic en **Save**. ¡Tu tiermaker estará en línea en pocos segundos!

---

## ✨ Características Principales

- **7 Tiers Personalizables:** S, A, B, C, D, E, F con nombres y colores configurables.
- **Drag & Drop Fluido:** Arrastra, reordena y apila todas las waifus en cualquier tier con ajuste automático y contenedor con scroll inteligente.
- **Exportación PNG de Alta Definición (1400px):** Renderizado infográfico nativo a prueba de fallos de CORS, con previsualización en vivo, descarga directa, apertura en nueva pestaña y copiado al portapapeles.
- **Modo Captura (Captura Limpia):** Oculta barras laterales, controles y pool de selección para realizar capturas de pantalla de alta fidelidad sin distracciones en PC y móvil.
- **Filtrado Avanzado:** Por juego (GI, HSR, ZZZ), elemento/vía, rareza (4★ / 5★) y búsqueda en tiempo real por nombre.
- **Persistencia Local:** Guarda automáticamente tu tierlist en el almacenamiento del navegador (`localStorage`) para que nunca pierdas tu progreso.
- **Doble Fallback de Imágenes:** Sistema multi-espejo que valida imágenes en tiempo real y detecta placeholders grises de wikis para mostrar siempre avatares limpios y nítidos.

---

## 📁 Estructura del Repositorio

```text
├── index.html       # Aplicación web completa autocontenida
├── README.md        # Documentación y guía de despliegue
├── LICENSE          # Licencia MIT
└── .gitignore       # Archivos ignorados por git
```

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Los nombres, artes e imágenes pertenecen a [HoYoverse / Cognosphere](https://www.hoyoverse.com/).
