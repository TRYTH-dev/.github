![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24&height=160&section=header&text=TRYTH-dev&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38)

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+JP&weight=500&size=18&pause=1500&color=38BDF8&center=true&vCenter=true&width=650&lines=%E8%A6%B3%E5%85%89%C3%97%E8%AC%8E%E8%A7%A3%E3%81%8DPWA%E3%82%A2%E3%83%97%E3%83%AA%E3%80%8Cmap-riddle%E3%80%8D%E9%96%8B%E7%99%BA%E4%B8%AD%EF%BC%81;5%E4%BA%BA%E3%81%AE%E5%AD%A6%E7%94%9F%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%AB%E3%82%88%E3%82%8B%E4%BD%93%E9%A8%93%E5%9E%8B%E3%83%97%E3%83%AD%E3%83%80%E3%82%AF%E3%83%88;%E3%82%AB%E3%83%95%E3%82%A7%E3%82%A4%E3%83%B3%E9%A7%86%E5%8B%95%E9%96%8B%E7%99%BA%E3%81%A7%E3%83%90%E3%82%B0%E3%81%A8%E4%BA%A4%E6%88%A6%E4%B8%AD...;%E6%9C%AC%E7%95%AA%E3%83%87%E3%83%97%E3%83%AD%E3%82%A4%E3%81%AF%E6%89%BF%E8%AA%8D%E3%83%9C%E3%82%BF%E3%83%B31%E3%81%A4%E3%81%A7%E5%AE%89%E5%85%A8%E7%A8%80%E5%83%8D%E4%B8%AD%EF%BC%81" alt="Typing SVG" />
</div>

# 🧭 TRYTH-dev

観光×クイズ×バッジ収集PWAアプリケーション **「map-riddle」** をはじめとする、体験型Webプロダクトを開発する学生プロジェクトチームです。

---

### 🚀 Active Projects

#### 🗺️ [map-riddle](https://github.com/TRYTH-dev/map-riddle)

> **「訪れて、解いて、集める。街をめぐるデジタルバッジラリー。」**

`map-riddle` は、実際の観光地や観光施設に足を運び、その場所にちなんだクイズに正解することで限定デジタルバッジを獲得できる**観光周遊コレクションPWA（Progressive Web Apps）**です。  
駅スタンプアプリ「エキタグ」のように、観光地を巡りながらコレクションを集める楽しさと、ご当地クイズを通じて地域の魅力に深く触れる体験を提供します。

[![CI/CD Pipeline](https://github.com/TRYTH-dev/map-riddle/actions/workflows/deploy.yml/badge.svg)](https://github.com/TRYTH-dev/map-riddle/actions/workflows/deploy.yml)
![Status](https://img.shields.io/badge/Status-In_Development-blue?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Mobile_PWA-green?style=flat-square)

- 🧪 **Staging (テスト環境)**: [stage-map-riddle.zyuuuukak1n.dev](https://stage-map-riddle.zyuuuukak1n.dev/)
- 🌐 **Production (本番環境)**: [map-riddle.zyuuuukak1n.dev](https://map-riddle.zyuuuukak1n.dev/)
- 📖 **開発マニュアル**: [Google Docs ドキュメント](https://docs.google.com/document/d/1xdL6iOhfSZYEafGdGJoucmnR6xisjbKjX2IZee9JIZU/edit)

#### 🎯 Core Gameplay & Concept (体験の流れ)

```text
[1. マップで気になる観光地・施設を探す]
        │
        ▼
[2. 現地の観光スポットへ実際に足を運ぶ]
        │
        ▼
[3. その場所限定の「ご当地クイズ」に挑戦]
        │
        ▼
[4. 正解してオリジナル「限定デジタルバッジ」を獲得・コレクション]
```

- **📍 スポット連動 (Check-in & Location)**  
  GPS等の位置情報をもとに現地の観光スポットへ実際に訪れることで、対象スポット限定のクイズがアンロックされます。
- **❓ ご当地クイズ挑戦 (Local Quiz Challenge)**  
  名所・史跡の歴史や展示物のディテールなど、実際にその場所を訪れて観察しなければ解けないクイズを出題し、地域の魅力を深く知るきっかけを作ります。
- **🏅 デジタルバッジ収集 (Badge Collection)**  
  クイズに正解すると、その場所ならではのオリジナルデザインバッジを獲得。「エキタグ」のように旅の思い出や踏破記録としてコレクションできます。
- **⚡ インストール不要の快適性 (Lightweight PWA)**  
  アプリストアからのダウンロード不要で、ブラウザから即座に起動。旅行中でもストレージを圧迫せず手軽に楽しめます。

---

### 🛠️ Tech Stack

#### Application & UI
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

#### Infrastructure & Pipeline
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-24292F?style=for-the-badge&logo=tailscale&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

---

### 👥 Team Members

<table>
  <tr>
    <td align="center" width="160">
      <a href="https://github.com/zyuuuukak1n">
        <img src="https://images.weserv.nl/?url=github.com/zyuuuukak1n.png&mask=circle" width="80" height="80" alt="zyuuuukak1n" />
        <br />
        <sub><b>矢野 倖也</b></sub>
      </a>
      <br />
      <sub>Project Manager / Lead</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/MixJuice01">
        <img src="https://images.weserv.nl/?url=github.com/MixJuice01.png&mask=circle" width="80" height="80" alt="田中 宏樹" />
        <br />
        <sub><b>田中 宏樹</b></sub>
      </a>
      <br />
      <sub>UI/UX Designer / Frontend Engineer（Lead）</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/ri055">
        <img src="https://images.weserv.nl/?url=github.com/ri055.png&mask=circle" width="80" height="80" alt="李 朝暘" />
        <br />
        <sub><b>李 朝暘</b></sub>
      </a>
      <br />
      <sub>UI/UX Designer / Frontend Engineer</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="160">
      <a href="https://github.com/j549zkamn-commits">
        <img src="https://images.weserv.nl/?url=github.com/j549zkamn-commits.png&mask=circle" width="80" height="80" alt="田中 一樹" />
        <br />
        <sub><b>田中 一樹</b></sub>
      </a>
      <br />
      <sub>Backend Engineer（Lead）</sub>
    </td>
    <td align="center" width="160">
      <a href="https://github.com/kan713">
        <img src="https://images.weserv.nl/?url=github.com/kan713.png&mask=circle" width="80" height="80" alt="橋本 奏音" />
        <br />
        <sub><b>橋本 奏音</b></sub>
      </a>
      <br />
      <sub>Backend Engineer</sub>
    </td>
    <!-- 3列レイアウトのため空セル -->
    <td align="center" width="160"></td>
  </tr>
</table>
