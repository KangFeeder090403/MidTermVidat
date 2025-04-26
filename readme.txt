# Steam Game Visualization 🎮📈

Proyek visualisasi interaktif berbasis Flask + Plotly.js + Pandas untuk mengeksplorasi dataset Steam Games.

##  Fitur Utama
- **Pie Chart**: Distribusi Top-15 Genre game terpopuler.
- **Bar Chart**: Genre paling populer berdasarkan tahun rilis.
- **Line Chart**: Tren pertumbuhan genre sepanjang tahun.
- **Scatter Chart**: Hubungan harga game dan diskon yang diberikan.
- **Growth Chart + AI Insight**: Grafik pertumbuhan jumlah game dengan auto-insight AI.
- **AI Game Recommendation**: Rekomendasi game terbaik berbasis genre, tahun rilis, dan minimal rating!

##  Tech Stack
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS (SteamDB Inspired), JavaScript (AJAX), Plotly.js
- **Data Handling**: Pandas
- **Deployment**: GitHub Pages / Render / Vercel (opsional)

##  Struktur Proyek

```
steam-visualization/
│
├── app.py               # Flask backend utama
├── steam_viz.ipynb       # Notebook pembersihan dan pembuatan chart
├── templates/
│    ├── index_embed.html # Layout HTML utama (SteamDB style)
│    ├── bar_chart_*.html # Bar Chart per tahun
│    ├── pie_chart.html   # Pie Chart
│    ├── line_chart.html  # Line Chart
│    ├── scatter_chart.html # Scatter Chart
│    └── growth_chart.html  # Growth Chart
├── static/
│    └── favicon.ico      # Favicon kecil untuk tab website
├── steam_games.csv       # Dataset Steam original



## 🚀 Cara Menjalankan
1. Clone repo ini:
   ```bash
   git clone https://github.com/username/steam-visualization.git
   cd steam-visualization
   ```

2. Install dependencies:
   ```bash
   pip install flask pandas plotly
   ```

3. Jalankan Flask server:
   ```bash
   python app.py
   ```

4. Buka di browser:
   ```
   http://localhost:5000/
   ```

## Fitur Interaktif
- Dropdown filter tahun (tanpa reload halaman)
- Form AI Recommendation (genre + tahun + minimal rating)
- Submit Recommendation tanpa reload (AJAX smooth)
- Reset Form tombol merah ✖️
- Fade-in animation setiap hasil baru muncul

## Bonus Styling
- Layout terinspirasi SteamDB
- Responsive Design
- Soft card shadow + hover effect
- Table hover highlight
- Modern fonts (Open Sans)

## Catatan
- Data Steam dibatasi hanya sampai tahun 2024 untuk menjaga akurasi.
- Untuk visualisasi optimal, gunakan browser modern seperti Chrome atau Edge.



---
