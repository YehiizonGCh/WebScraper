# 🕷️ Web Scraper de Noticias

Scraper que extrae titulares, URLs y puntuaciones de **Hacker News** y exporta los resultados a CSV y JSON automáticamente.

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)
![requests](https://img.shields.io/badge/requests-2.x-FF6B35?style=flat)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup4-parsing-4CAF50?style=flat)
![License](https://img.shields.io/badge/license-MIT-green?style=flat)

---

## 📌 ¿Qué hace este proyecto?

- Descarga la página principal de Hacker News
- Extrae título, URL y puntuación de cada artículo
- Guarda los resultados en `noticias.csv` y `noticias.json`
- Muestra el **Top 5** de artículos más votados en consola

---

## 🖥️ Demo

```
🔍 Iniciando scraping de https://news.ycombinator.com ...
📰 30 artículos extraídos.
✅ CSV guardado: noticias.csv (30 artículos)
✅ JSON guardado: noticias.json (30 artículos)

🔥 TOP 5 ARTÍCULOS MÁS VOTADOS
============================================================
1. [842 pts] Show HN: I built a terminal emulator in Python
   https://github.com/...

2. [761 pts] The Return of the 90s Web
   https://manuelmoreale.com/...
```

---

## 🛠️ Tecnologías

| Librería | Uso |
|---|---|
| `requests` | Peticiones HTTP a la web |
| `BeautifulSoup4` | Parseo del HTML |
| `csv` | Exportación en formato tabla |
| `json` | Exportación en formato JSON |
| `datetime` | Fecha y hora de extracción |

---

## 🚀 Instalación y uso

### 1. Clona el repositorio
```bash
git clone https://github.com/YehiizonGCh/WebScraper.git
cd WebScraper
```

### 2. Instala las dependencias
```bash
pip install requests beautifulsoup4
```

### 3. Ejecuta el scraper
```bash
python scraper.py
```

### 4. Archivos generados
```
📁 web-scraper-noticias/
├── noticias.csv     ← exportación en tabla
└── noticias.json    ← exportación en JSON
```

---

## 📂 Estructura del proyecto

```
web-scraper-noticias/
├── scraper.py       # Script principal
├── .gitignore
└── README.md
```

---

## 💡 Posibles mejoras

- [ ] Scraping de múltiples páginas con paginación
- [ ] Almacenamiento en base de datos SQLite
- [ ] Ejecución automática programada con `schedule`
- [ ] Envío de resumen diario por email
- [ ] Adaptar a otros sitios (LaRepublica.pe, ElComercio.pe)

---

## 👤 Autor

**Luis Garro**
- GitHub: [@YehiizonGCh](https://github.com/YehiizonGCh)
