# Cumberland County Northern Lights Forecast

**Real-time, accurate Aurora Borealis forecast for Cumberland County, Maine.**

Live data from the official NOAA Space Weather Prediction Center (SWPC):

- **Current Kp index** and geomagnetic storm scale
- **NOAA OVATION** 30–90 minute aurora probability map (Northern Hemisphere)
- **Location-specific probability** sampled near 43.78°N, 70.33°W
- **3-day Kp forecast** in 3-hour slots
- **27-day Space Weather Outlook** (daily max Kp, 10.7 cm flux, A-index)
- **Moon phase & illumination** for optimal dark-sky viewing
- Clear guidance on what Kp is needed from southern Maine and best viewing practices

## Live Site

Once GitHub Pages is enabled:

**https://aross197.github.io/cumberland-aurora-forecast/**

## Data Sources (all official & free)

| Product | Endpoint |
|---------|----------|
| OVATION Aurora JSON | `https://services.swpc.noaa.gov/json/ovation_aurora_latest.json` |
| OVATION Map Image | `https://services.swpc.noaa.gov/images/animations/ovation/north/latest.jpg` |
| Planetary K-index | `https://services.swpc.noaa.gov/products/noaa-planetary-k-index.json` |
| Kp Forecast | `https://services.swpc.noaa.gov/products/noaa-planetary-k-index-forecast.json` |
| 27-day Outlook | `https://services.swpc.noaa.gov/text/27-day-outlook.txt` |

No API keys required. The page fetches data client-side and refreshes every 5 minutes.

## Viewing Tips for Cumberland County, ME

- **Kp 5 (G1)** — possible faint aurora low on the northern horizon under dark, clear skies
- **Kp 6–7** — significantly better odds; stronger displays possible
- Best window: **10 pm – 2 am** local time
- Prefer nights near **New Moon**
- Get away from Portland light pollution; look for a dark northern horizon

## License

This project is open source. NOAA data is public domain / free for public use with attribution.

Not affiliated with NOAA or the National Weather Service.
