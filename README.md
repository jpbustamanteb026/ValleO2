# ValleO2

Real-time weather and air quality dashboard for Cali, Colombia.

![Preview](./preview.png)

## Stack

- **React 18** + **TypeScript**
- **Vite** — build tool
- **Tailwind CSS v4** — styling with CSS variables
- **shadcn/ui** — UI components
- **Recharts** — data charts
- **TanStack Query** — async state management
- **Open-Meteo API** — weather data (no API key required)
- **OpenAQ API** — air quality data (no API key required)
- **next-themes** — dark/light mode toggle

## Features

- Current temperature, humidity, wind speed and UV index
- 7-day temperature forecast chart
- Weekly precipitation chart
- Air quality index (AQI) with PM2.5 history
- Dark / light mode toggle
- Responsive layout

## Getting Started

**Requirements:** Node.js 18+ and pnpm

```bash
# Clone the repository
git clone https://github.com/jpbustamanteb026/ValleO2.git
cd ValleO2

# Install dependencies
pnpm install

# Start the development server
pnpm dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Data Sources

- [Open-Meteo](https://open-meteo.com/) — free weather API, no key required
- [OpenAQ](https://openaq.org/) — open air quality data
