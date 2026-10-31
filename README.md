# 🌌 HoYoverse Waifu Tiermaker (Octubre 2026)

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-success?style=flat&logo=github)](https://iadamn.github.io/hoyoverse-waifu-tiermaker/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HoYoverse](https://img.shields.io/badge/Games-GI%20%7C%20HSR%20%7C%20ZZZ-ff2a85.svg)](#)

Una aplicación web interactiva y fluida estilo **Tiermaker** con **256 waifus** de **Genshin Impact (7.1)**, **Honkai: Star Rail (4.6)** y **Zenless Zone Zero (3.4)** hasta el 31 de octubre de 2026 (sin HI3rd).

---

## ✨ Características Principales

* **7 Tiers Personalizables:** `EX / GOD WAIFU`, `S`, `A`, `B`, `C`, `D`, `F` con etiquetas *sticky* y editor de nombres y colores en tiempo real.
* **256 Waifus Completas (0 Duplicados, 0 Placeholders):**
  * **Genshin Impact (107 waifus):** Jugables desde la 1.0 hasta Nod-Krai (Columbina, Lauma, Aino, Nefer, Jahoda, Zibai, Nicole Reeyn, Prune, Sandrone, Linnea, Skirk, Ineffa) y Snezhnaya 7.0–7.1 (Odette, Vodyanitsa, Vesna), además de la Zarina (Anastasya), Danica, Alice, Rhinedottir, Ronova, Asmoday, Istaroth, Barbeloth, Signora, Focalors, Rukkhadevata, Guizhong, Makoto, Kitsune Saiguu, Fujin e Indarias.
  * **Honkai: Star Rail (82 waifus):** Jugables hasta la 4.6 (Castorice, Aglaea, Tribbie, Cipher, Hyacine, Hysilens, Cerydra, Cyrene, The Dahlia/Constance, Yao Guang, Evanescia, Rin Tohsaka, Saber, Pearl), **todas las variantes SP** (The Herta, Tingyun Fugue, March 7th Evernight / The Hunt, Sparxie / Sparkle SP, Silver Wolf LV.999, Himeko Nova, Robin Summeretto, Firefly Spring Missive, y las 5 vías de Stelle) y filtraciones/lore (Obsidian, Celenova, Polka Kakamond, Yu Qingtu, Dan Shu, Cocona, Baiheng, Phantylia, Cocolia).
  * **Zenless Zone Zero (67 waifus):** Agentes de la Temporada 1, 2 y 3 (Sunbringer, Phoenix Reffaella, Norma Hollowell, Velina Airgid, Sigrid de L'Azur, Roxy Ifrita Pryce, Claret Flint, Promeia, Remielle Dan, grupo idol Angels of Delusion, Yixuan, Ju Fufu, Alice Thymefield, Orphie & Magus, Seed, Vivian, Trigger), variantes SP y crossovers (Soldier 0 - Anby, Aria Robot Form, Kafka y Robin ZZZ) y NPCs de Nueva Eridu (Belle, Fairy, Sarah Floren, Isolde, Carole Arna, Lady in White, Venus, Sweety, Orchidea, Elfy, Asha, Coco, Sjal, Rain, Ray).
* **Diseño Anti-Overflow Verificado:** Contenedores elásticos (`flex-wrap: wrap`) que permiten apilar las 256 tarjetas en un mismo Tier sin desbordar el contenedor ni romper la cuadrícula en móvil o escritorio.
* **Visualización Dual:** Alterna entre **Avatar Oficial 1:1** y **Retrato / Splash Vertical** en 3 tamaños (Compacto, Normal, Grande HD).
* **Detector Anti-Placeholder Automático:** Detección en vivo de imágenes borrador de Fandom con salto a respaldos de alta resolución.
* **Atajos de Teclado y Selección Múltiple:** Pulsa teclas `1` a `7` para mover selecciones masivas a cualquier Tier al instante.
* **Exportación:** Descarga de póster en imagen PNG HD y guardado/restauración de estados mediante JSON.

---

## 🚀 Despliegue en GitHub Pages (en 2 minutos)

1. Crea un nuevo repositorio en tu cuenta de GitHub (por ejemplo: `hoyoverse-waifu-tiermaker`).
2. Sube los archivos de este proyecto:
   ```bash
   git init
   git add .
   git commit -m "feat: HoYoverse Waifu Tiermaker (256 waifus)"
   git branch -M main
   git remote add origin https://github.com/iAdamn/hoyoverse-waifu-tiermaker.git
   git push -u origin main
   ```
3. En GitHub, ve a **Settings** > **Pages**.
4. En **Build and deployment** > **Source**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`, luego pulsa **Save**.
6. ¡Listo! Tu web quedará publicada gratis en:
   `https://iadamn.github.io/hoyoverse-waifu-tiermaker/`

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
