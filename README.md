# GLX Ridership Metro Map

Interactive metro-style visualization of MBTA Green Line Extension ridership data (2023-2025).

## Features

- **Metro-style map** showing all GLX stations in geographical order
- **Stacked circles** per station — one for each year (2023, 2024, 2025)
- **Circle size** proportional to average daily ridership
- **Color-coded by year** for easy comparison
- **Interactive dropdown** to switch between yearly averages and individual months
- **Hover tooltips** with detailed ridership data

## Quick Start

### Option 1: View on GitHub
Simply navigate to the [landing page](https://dtatarak.github.io/mbta_glx_ridership/index.html), and the plots will render!
### Option 2: Run Locally

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/glx-ridership-map.git
cd glx-ridership-map

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook glx_ridership_map.ipynb
```

### Option 3: Google Colab
Upload the notebook and CSV to Google Colab for instant interactive visualization.

## Files

| File | Description |
|------|-------------|
| `glx_ridership_map.ipynb` | Main Jupyter notebook with visualization |
| `GLX_Ridership_Total_Monthly_and_Avg_Daily__R001475-120525_.csv` | Source ridership data |
| `requirements.txt` | Python dependencies |

## Data

The visualization uses the **upperbound average daily ridership** (`highbound_avg_daily_ons`) from MBTA ridership data covering:

- **Years**: 2023, 2024, 2025
- **Stations**: 11 GLX stations from Government Center to Medford/Tufts
- **Granularity**: Monthly data with yearly aggregation option

## Station Layout

```
Science Park ─── Lechmere ─┬─ East Somerville ─── Gilman ─── Magoun ─── Ball ─── Medford/Tufts
                           │
                           └─ Union Square
```

## License

MIT License - feel free to use and modify!
