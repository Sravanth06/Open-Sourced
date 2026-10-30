# Open-Sourced: The Web-Port & Clone Tracker

## 🛑 What is this repository?
This repository is a centralized, community-driven database tracking active URLs that host unauthorized, browser-based ports of proprietary heavy games and commercial software. 

With the rapid rise of AI-assisted reverse-engineering tools (such as REA) and WebAssembly, fully playable AAA games and complete software suites are being illegally ported and hosted directly in web browsers. This repository catalogs where these clones are being hosted in real-time.

## 🎯 Why does this exist?
The primary goal of this project is to assist copyright holders, original developers, and publishers. 

By crowd-sourcing the discovery of these unauthorized web-ports and organizing them into a public directory, we make it significantly easier for corporate legal teams and automated DMCA bots to:
1. Identify unauthorized distributions of their intellectual property.
2. Locate the hosting providers (Cloudflare, Vercel, AWS, etc.) keeping these sites online.
3. Issue swift and targeted DMCA takedown notices to protect their products.

**Disclaimer:** This repository does NOT host, promote, or encourage piracy. We do not provide source code, game assets, or tutorials on how to reverse-engineer software. This is strictly a reporting tool for rightsholders.

## 📂 Repository Structure
To keep tracking organized and scalable, this repository is divided into specific folders based on the type of media and the specific title. Inside each folder, you will find a dedicated `README.md` containing the tracked URLs for that specific title.

```text
Open-Sourced/
├── README.md                (You are here)
├── Games/
│   ├── GTA-V/
│   │   └── README.md        (Tracked URLs for GTA V ports)
│   └── RDR2/
│       └── README.md        (Tracked URLs for Red Dead Redemption 2 ports)
└── Software/
    ├── Adobe-Photoshop/
    │   └── README.md        (Tracked URLs for Photoshop web clones)
    └── Adobe-Premiere/
        └── README.md        (Tracked URLs for Premiere web clones)
