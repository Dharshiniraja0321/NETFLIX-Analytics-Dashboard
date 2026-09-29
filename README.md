# Netflix Analytics Dashboard

An interactive Power BI-style dashboard that explores the Netflix catalog by content type, genre, geography, and release trends.

## Key Metrics (KPI Cards)
- **Total Title**: total number of titles in the catalog (~10K)
- **TV Shows**: count of TV show titles
- **Movies**: count of movie titles (~7K)
- **TV Shows %**: TV shows as a share of all titles (30.81%)

## Visuals
- **Top 5 Genre**: table of the genres with the most titles (Action & Adventure, Anime, Documentaries, LGBTQ+, Romance, Sports), with a total row.
- **Content Added Over Time**: area/line chart of titles added per year, rising from 2018 to a peak of 1,456 before dropping to 1,030 in 2026.
- **Content Type Distribution**: pie chart of Movies (6.92K) vs TV Shows (3.08K).
- **Total Contents Breakdown by Continent**: bar chart of titles per continent. Asia leads (3.5K), followed by Europe (2.5K) and North America (1.5K).
- **Rating Evolution**: waterfall chart showing each genre's contribution to the running total (~68K), from Anime through Faith & Spirituality.

## Filters (Slicers)
| Filter | Purpose |
|---|---|
| Year | Limit all visuals to a specific year |
| Genre | Focus on one genre |
| Country | Focus on one country |
| Type | Switch between Movie and TV Show |

All filters default to "All" and apply across every visual.

## How to Use
1. Open the dashboard file in Power BI.
2. Pick values in the Year, Genre, Country, or Type slicers.
3. Watch the KPI cards and charts update together.
4. Reset a slicer to "All" to see the full catalog.

## Data Source
Netflix titles dataset (title, type, genre, country, year added, rating). Add the source name/link here.

## Author
Add your name and contact/GitHub link here.
