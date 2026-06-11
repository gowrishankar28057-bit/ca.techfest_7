🪐 TECHFEST '26 — College Ambassador Portal

✨ Features

FeatureDescription🌀 Vortex Portal HeroTeal spiral with 3 counter-rotating layers — click ENTER to warp through the core🪐 Animated Planet BackgroundBreathing, parallax planet artwork visible across all 7 pages📄 No-Scroll NavigationClick-to-switch pages with 3D flip transitions, keyboard arrows & dot nav🪪 Animated ID CardSwinging lanyard card with shine sweep, 3D mouse tilt & floating avatar🗄️ Live Dummy DatabaseIn-memory DB object with users + tasks tables — complete tasks → points update in real-time🏆 Live LeaderboardAuto-ranks update as you complete tasks; your row re-positions live🎯 League ProgressionBronze → Silver → Gold → Diamond based on tasks completed🖱️ Blob CursorCustom two-layer lerp cursor with spring physics and hover scale🎆 Global Star Field110-star twinkling canvas with depth layers on every page📝 Register → DashboardForm insert creates a CA profile, generates ID, syncs to all pages


🗂️ Pages

P0  Hero Portal      — Animated vortex, warp-through-core ENTER transition
P1  About            — Techfest stats with animated counters
P2  Domains          — 6 domain cards with 3D mouse tilt
P3  Rewards          — League system + reward tiers
P4  Dashboard        — Ambassador profile, ID card, task rail, refer strip
P5  Leaderboard      — Live-ranked table driven by dummy DB
P6  Register         — Form → offer letter → dashboard redirect


🚀 Quick Start

Option 1 — Just open it

bash# No build step needed. Just open in any browser.
open index.html

Option 2 — Clone & run locally

bashgit clone https://github.com/YOUR-USERNAME/techfest26-portal.git
cd techfest26-portal
# open index.html in your browser

Option 3 — Deploy to GitHub Pages

bashgit init
git add index.html
git commit -m "🚀 initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/techfest26-portal.git
git push -u origin main
# Then: Settings → Pages → Branch: main / (root) → Save

Live at: https://YOUR-USERNAME.github.io/techfest26-portal/


🧱 Tech Stack

HTML5          — Single file, zero build tooling
CSS3           — Custom properties, 3D transforms, keyframe animations
Vanilla JS     — In-memory DB, lerp physics, IntersectionObserver
Satoshi Font   — Via fontshare.com CDN

No React. No Vue. No npm. No bundler. One .html file. 137 KB total.


🎮 Interactions to Try


Click ENTER on the hero — watch the vortex warp animation
Hover a domain card — 3D tilt toward cursor
Hover the ID card on the dashboard — pauses swing, tilts in 3D
Complete tasks on the dashboard → points animate up, league badge upgrades
Check the Leaderboard — your row moves up as points increase
Register on the last page — your name appears on the ID card instantly
Use ← → arrow keys to navigate pages



📁 Project Structure

techfest26-portal/
│
├── index.html        ← entire app (HTML + CSS + JS, all assets base64 embedded)
└── README.md

All images are base64-embedded inside the HTML — no external asset requests, works fully offline.


🖼️ Assets Used

AssetRolePlanet artworkAnimated background across all pagesTeal vortexHero portal animationBlue/orange wavesRegister page overlayBlob cursorCustom two-state cursorGold linesDecorative blend layer


👤 Author

Gowrishankar — ECE '29 · Team NOVACORE
St. Joseph's College of Engineering, Chennai

Show Image
Show Image


📄 License

MIT — free to use, modify and distribute.


<div align="center">
  <sub>Built for Techfest IIT Bombay · CA Program · Web Development Domain · Team NOVACORE</sub>
</div>
