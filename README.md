# 🏆 Mundial 2026 — Simulador Interactivo

Simulador web del Mundial de Fútbol 2026 (USA · CAN · MEX). Permite simular toda la fase de grupos, las eliminatorias, comparar selecciones y compartir tu predicción en redes sociales.

**🔗 Demo en vivo:** [dbouzada.github.io/mundial-2026](https://dbouzada.github.io/mundial-2026)

---

## ✨ Funcionalidades

### 📊 Fase de Grupos
- Los **12 grupos** y **48 selecciones** oficiales del Mundial 2026
- Fixture real con **fecha y horario en hora Argentina** para cada partido
- Cálculo automático de **tabla de posiciones**: puntos, partidos jugados, goles a favor/en contra, diferencia de gol
- Sistema de desempate por DG y GF
- Visualización de clasificados (top 2 de cada grupo + 8 mejores terceros)

### 🥊 Bracket Eliminatorias
- Llaves completas: **16avos → Octavos → Cuartos → Semis → Final**
- Carga automática de los **clasificados** según los resultados de grupos
- Cálculo dinámico de los **8 mejores terceros** (regla FIFA)
- Click para avanzar ganadores; la siguiente ronda se actualiza sola
- Cruces oficiales (P73 a P88) según el sorteo FIFA

### 🔮 Predictor de Partidos
- Compará dos selecciones cualquiera
- Cálculo de probabilidad de victoria basado en rating histórico
- Comparativa visual: Rating FIFA, títulos mundiales, apariciones, goles históricos
- Resultado de cada selección en Qatar 2022

### 📚 Historia del Mundial
- KPIs: 22 ediciones, 8 campeones distintos, 2.548 goles totales
- Ranking de **títulos por país** (1930–2022)
- Tabla de las últimas 8 ediciones
- Top **goleadores históricos** del Mundial
- Selecciones con más participaciones

### 📤 Compartir Predicción
- **Descarga como imagen PNG** lista para redes sociales
- Botones directos a **Twitter / X**, **WhatsApp** y **LinkedIn**
- Copia al portapapeles
- Versión imprimible / exportable a PDF

### 💾 Otras features
- **Persistencia automática** en el navegador (localStorage) — el progreso se guarda solo
- **Diseño responsive** — funciona en mobile y desktop
- **100% client-side** — sin backend, sin tracking, sin cookies

---

## 🛠️ Stack Técnico

- **HTML5** + **CSS3** (Variables, Grid, Flexbox)
- **JavaScript ES6+** vanilla — sin frameworks
- **html2canvas** para generación de imágenes
- **Google Fonts**: DM Sans, DM Mono, DM Serif Display
- **GitHub Pages** para deploy

> Sin dependencias de instalación. Archivo único `index.html` deployable en cualquier hosting estático.

---

## 📦 Fuentes de Datos

- **FIFA** — Clasificación oficial de selecciones y fixture 2026
- **Wikipedia** — Datos históricos de mundiales (1930–2022)
- **RSSSF** — Estadísticas de goleadores históricos

---

## 🚀 Cómo usar localmente

```bash
git clone https://github.com/dbouzada/mundial-2026.git
cd mundial-2026
# Abrí index.html en cualquier navegador moderno
```

No requiere build, ni `npm install`, ni servidor local.

---

## 👤 Autor

**Diego Bouzada** — Data Analytics Engineer

- 💼 [LinkedIn](https://www.linkedin.com/in/bouzadadiego/)
- 🐙 [GitHub](https://github.com/dbouzada)

> Data Analytics Engineer con +4 años de experiencia. DP-600 certified. Stack: SQL · Python · Power BI · Microsoft Fabric · dbt · BigQuery · Azure. Formación en Comunicación Social — traduzco datos en decisiones de negocio.

---

## 📄 Licencia

MIT — usalo, modificalo y compartilo libremente.
