# TVSeries Poster Page — Schema.org Microdata (Moroccan TV Series)

This project is a static HTML poster page for a Moroccan TV Series (**L’Couple**) enriched with **Schema.org Microdata** so that the content becomes machine-readable.

## ✅ What I built
- A single-page "TV series poster" layout using **Bootstrap 5**
- A structured metadata layer using **Schema.org Microdata**
- The page describes a `TVSeries` and related entities like:
  - `Country` (countryOfOrigin)
  - `Person` (director, musicBy, actor)
  - `Organization` (productionCompany)
  - `TVSeason` (containsSeason)
  - `TVEpisode` (episode)
  - `VideoObject` (trailer)

## 🧠 Schema.org concepts used (Microdata)
Microdata attributes:
- `itemscope` — starts a new structured entity
- `itemtype` — defines the Schema.org type (e.g., TVSeries)
- `itemprop` — binds a property to a value (e.g., name, startDate)

Main type:
- `https://schema.org/TVSeries`

Key properties implemented:
- `name`, `description`, `image`, `genre`
- `startDate`, `endDate`
- `countryOfOrigin`
- `director`, `musicBy`, `actor`
- `productionCompany`
- `numberOfSeasons`, `numberOfEpisodes`
- `containsSeason` (TVSeason)
- `episode` (TVEpisode)
- `trailer` (VideoObject)

## 📁 Project structure
```bash
tvseries-microdata-lcouple/
├─ index.html
├─ images/
│ └─ lcouple-poster.png
├─ docs/
│ └─ rapport.md
└─ README.md
```

## 🚀 How to run
Just open `index.html` in your browser.

## 📄 Report
See the full report (course-notes style) here:
- `docs/rapport.md`

## 🔎 How this makes the page machine-readable
By adding Schema.org Microdata, the HTML is no longer only visual content.  
It becomes structured data that machines can interpret as:
- “This page describes a TVSeries”
- “It has a director (Person)”
- “It contains seasons and episodes”
- “It has a trailer (VideoObject)”

## 👤 Author
Abdelilah BENCHINE