# Green Score: A Dashboard for NYC Building Sustainability

This tool assigns a simple “green score” to buildings in New York City based on public energy benchmarking data. The score helps identify high- and low-performing buildings across the city and explore retrofit potential.

## Features
- Score calculated from energy use intensity and GHG emissions
- Filter by borough, property type, size
- Downloadable data table
- Interactive dashboard (Streamlit)

## Data Sources
- [NYC Energy Benchmarking](https://data.cityofnewyork.us/)
- [NYC DOB Energy Grades](https://data.cityofnewyork.us/)

## Tech Stack
- Python (pandas, numpy, Streamlit)
- Data visualization (Plotly or Matplotlib)
- Optional: Map visualization using Folium

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
