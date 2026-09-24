# 🔥 Free Fire Info API — OB55

A high-performance **Free Fire Player Information API** built with **Flask** and **Protocol Buffers**, supporting multiple regions with automatic fallback and token caching.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-3.0.2-green?style=flat-square&logo=flask)
![Protobuf](https://img.shields.io/badge/Protobuf-4.25.1-orange?style=flat-square&logo=protobuf)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Version](https://img.shields.io/badge/OB-55-red?style=flat-square)

---

## 👨💻 Author

<table>
  <tr>
    <td align="center">
      <b>HS MUJAHID YT</b><br>
      <i>Full-Stack Developer & API Architect</i>
    </td>
  </tr>
</table>

| Platform | Link |
|----------|------|
| 🌐 **Website / Profile** | [https://great.mujahid.xyz](https://great.mujahid.xyz) |
| 📢 **Telegram** | [@suiiiiiiii0007](https://t.me/suiiiiiiii0007) |
| 💬 **Discord** | `@mujahid.py` |
| ▶️ **YouTube** | [HS MUJAHID YT](https://youtube.com/@TH_MIHAWK) |
| 🐙 **GitHub** | [@hsmujahid](https://github.com/HS-DEVS07) |

> 💡 **Follow me** for more Free Fire tools, APIs, and open-source projects!

---

## 📖 Overview

**Free Fire Info API** is a RESTful API that fetches detailed player information from Garena Free Fire servers using the official **Protocol Buffer** protocol. It supports multiple regions (**BD**, **IND**, **BR**) with **parallel requests**, **automatic fallback**, and **in-memory token caching** for optimal performance.

This project is built on top of the reverse-engineered Free Fire client protocol and uses a secure **JWT-based authentication** system with guest account credentials.

---

## ✨ Features

- 🌍 **Multi-Region Support** — BD (Bangladesh), IND (India), BR (Brazil)
- ⚡ **Parallel Region Fetching** — Tries all regions simultaneously for fastest response
- 🔁 **Automatic Fallback** — If one region fails, others are tried automatically
- 🔐 **JWT Token Caching** — Tokens cached in-memory to reduce API calls
- 🛡️ **Dual Authentication** — JWT API + Backup MajorLogin flow
- 📊 **Rich Player Data** — Basic info, rank, clan, pet, leaderboard titles, credit score & more
- 🚫 **Ban Detection** — Detects banned accounts automatically
- 🎨 **Item Name Resolution** — Fetches readable item names for titles, pets, skins
- ☁️ **Vercel Ready** — Deployable to Vercel with included `vercel.json`

---

## 🚀 Quick Start

### Prerequisites

- Python **3.10+**
- pip
- (Optional) Vercel account for deployment

### Installation

```bash
# Clone the repository
git clone https://github.com/hsmujahid/freefire-info-api.git
cd freefire-info-api

# Create a virtual environment
python -m venv venv
source venv/bin/activate      # Linux / macOS
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt
