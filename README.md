Here's the complete README content in a single copyable block. Just copy everything inside the code block and paste it directly into your `README.md` file.


# ROTATER – Satellite-Based Climate Intelligence & Early Warning System

**ROTATER** is a web-based climate intelligence platform that transforms satellite-derived Earth observation data into actionable insights. It enables users to explore historical climate patterns, monitor present conditions, and predict future climate risks for any global location.

## ✨ Features

- **🌍 Interactive 3D Globe** – Visualize global climate data on an immersive, interactive globe.
- **📊 Climate Data Visualization** – Generate dynamic charts and graphs to analyze climate trends over time.
- **🗺️ Map Visualization** – Explore geographic climate patterns with interactive mapping tools.
- **🤖 AI-Powered Insights** – Get intelligent, conversational climate analysis powered by Google's Gemini AI.
- **⚠️ Major Alerts** – Receive notifications about significant climate events and risks.
- **📈 Dashboard** – Centralized view of all climate metrics and insights at a glance.

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | React 19, TypeScript, Vite |
| **Styling** | Tailwind CSS (CDN) |
| **Charts & Visualization** | Recharts, D3.js, TopoJSON Client |
| **Animations** | Framer Motion |
| **AI Integration** | Google Gemini API (`@google/genai`) |
| **Mapping** | world-atlas |
| **Icons** | Lucide React |

## 📁 Project Structure

```
ROTATER/
├── components/
│   ├── ChatAssistant.tsx    # AI-powered chat interface
│   ├── ClimateCharts.tsx    # Climate data visualization charts
│   ├── Dashboard.tsx        # Main dashboard view
│   ├── IntroGlobe.tsx       # 3D interactive globe
│   ├── MajorAlerts.tsx      # Climate alerts and notifications
│   └── MapViz.tsx           # Geographic map visualization
├── services/
│   ├── geminiService.ts     # Google Gemini AI integration
│   └── nasaService.ts       # NASA satellite data retrieval
├── App.tsx                  # Main application component
├── constants.ts             # Application constants
├── types.ts                 # TypeScript type definitions
├── index.html               # Entry HTML file
├── index.tsx                # Application entry point
├── package.json             # Dependencies and scripts
├── vite.config.ts           # Vite build configuration
└── tsconfig.json            # TypeScript configuration
```


## 🚀 Getting Started

### Prerequisites

- **Node.js** (Latest LTS version recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vishnu-1324/ROTATER.git
   cd ROTATER
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env.local` file in the root directory and add your Gemini API key:
   ```
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   npm run preview
   ```

## 🔑 API Keys Required

- **Google Gemini API Key** – For AI-powered climate insights and conversational analysis

## 📦 Key Dependencies

- `react` & `react-dom` – UI framework
- `@google/genai` – Google Gemini AI SDK
- `recharts` – Charting library for data visualization
- `d3` & `topojson-client` – Data manipulation and geographic mapping
- `framer-motion` – Smooth animations and transitions
- `lucide-react` – Icon library

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the platform.

## 📄 License

This project is private and not currently licensed for public distribution.
```
