# yorksafeApp
🛡️ SafePath York
AI‑powered safe walking routes for York Region.
Built with Flutter, OSRM, OpenStreetMap, ArcGIS, and Gemini AI.
🚀 Overview
SafePath York generates three optimized walking routes — 🏃 Fastest, ⚖️ Balanced, 🛡️ Safest — using real crime data, lighting, safe spaces, collisions, and infrastructure.
Each route has:

A 0–100 safety score
Color‑coded risk segments
A Gemini-generated explanation
Plus an AI Safety Chat where users can ask “Is this area safe at night?”


✨ Features

Multi‑route safety scoring (crime, lighting, collisions, safe spaces, sidewalks)
Gemini AI summaries + conversational safety assistant
Dark OSM map, swipeable route cards
Turn‑by‑turn walking navigation
Safety alerts (“Low lighting ahead”)
SOS button (emergency call + location share)


🛠️ Tech Stack

Flutter 3.x, Dart
OSRM (routing)
Nominatim (geocoding)
ArcGIS (crime + lighting)
OpenStreetMap / Overpass (safe spaces)
Hive (offline caching)
Riverpod (state management)
Dio, Geolocator, flutter_gemini, flutter_tts


⚙️ Setup
1. Install & Run
Plain Textflutter pub getflutter run --dart-define=GEMINI_API_KEY=your_keyShow more lines
2. Required Services

Gemini API key → https://aistudio.google.com/apikey
OSRM, OSM, Nominatim, ArcGIS → no key needed


📦 Project Structure (Condensed)
lib/
  core/        # theme, constants, utils
  data/        # models, repositories, local cache
  domain/      # scoring, routing, AI, navigation
  providers/   # Riverpod state
  presentation/# screens + widgets


🧠 Safety Scoring
Crime 40%  
Lighting 25%  
Collisions 15%  
Safe spaces 10%  
Infrastructure 10%


🔑 Key Screens

Home map + search
Route comparison (3 routes)
AI safety chat
Active navigation
Arrival summary


🧪 Verified APIs

OSRM routing
Nominatim geocoding
ArcGIS crime + lighting
Overpass safe spaces


🎤 Demo Flow (3 Minutes)

Search → 3 routes appear
Show safety scores + AI summaries
Start navigation
AI gives safety alerts
AI chat: “Is this area safe?”
Arrival → safety stats


❤️ Built For
York Region Hackathon 2026
Making walking safer using AI + open data + thoughtful design.
