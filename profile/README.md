![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24&height=160&section=header&text=TRYTH-dev&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38)

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+JP&weight=500&size=18&pause=1500&color=38BDF8&center=true&vCenter=true&width=650&lines=%E8%A6%B3%E5%85%89%C3%97%E8%AC%8E%E8%A7%A3%E3%81%8DPWA%E3%82%A2%E3%83%97%E3%83%AA%E3%80%8Cmap-riddle%E3%80%8D%E9%96%8B%E7%99%BA%E4%B8%AD%EF%BC%81;5%E4%BA%BA%E3%81%AE%E5%AD%A6%E7%94%9F%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%AB%E3%82%88%E3%82%8B%E4%BD%93%E9%A8%93%E5%9E%8B%E3%83%97%E3%83%AD%E3%83%80%E3%82%AF%E3%83%88;%E3%82%AB%E3%83%95%E3%82%A7%E3%82%A4%E3%83%B3%E9%A7%86%E5%8B%95%E9%96%8B%E7%99%BA%E3%81%A7%E3%83%90%E3%82%B0%E3%81%A8%E4%BA%A4%E6%88%A6%E4%B8%AD...;%E6%9C%AC%E7%95%AA%E3%83%87%E3%83%97%E3%83%AD%E3%82%A4%E3%81%AF%E6%89%BF%E8%AA%8D%E3%83%9C%E3%82%BF%E3%83%B31%E3%81%A4%E3%81%A7%E5%AE%89%E5%85%A8%E7%A8%80%E5%83%8D%E4%B8%AD%EF%BC%81" alt="Typing SVG" />
</div>

# 🧭 TRYTH-dev

観光×謎解きPWAアプリケーション **「map-riddle」** をはじめとする、体験型Webプロダクトを開発する学生プロジェクトチームです。

---

### 🚀 Active Projects

#### 🗺️ [map-riddle](https://github.com/TRYTH-dev/map-riddle)

> **「街そのものを、巨大な脱出ゲームのフィールドへ。」**

`map-riddle` は、スマートフォンの位置情報（GPS）とWebマップを活用し、実在する街や観光地を歩きながら謎を解き明かす**体験型観光周遊PWA（Progressive Web Apps）**です。  
紙のパンフレットや専用アプリインストールの手間をなくし、ブラウザを開いた瞬間から物語と探索が始まります。

[![CI/CD Pipeline](https://github.com/TRYTH-dev/map-riddle/actions/workflows/deploy.yml/badge.svg)](https://github.com/TRYTH-dev/map-riddle/actions/workflows/deploy.yml)
![Status](https://img.shields.io/badge/Status-In_Development-blue?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Mobile_PWA-green?style=flat-square)

- 🧪 **Staging (テスト環境)**: [stage-map-riddle.zyuuuukak1n.dev](https://stage-map-riddle.zyuuuukak1n.dev/)
- 🌐 **Production (本番環境)**: [map-riddle.zyuuuukak1n.dev](https://map-riddle.zyuuuukak1n.dev/)
- 📖 **開発マニュアル**: [Google Docs ドキュメント](https://docs.google.com/document/d/1xdL6iOhfSZYEafGdGJoucmnR6xisjbKjX2IZee9JIZU/edit)

#### 🎯 Core Gameplay & Concept (体験の流れ)

```text
[1. 地図上の異変・手がかりを察知]
        │
        ▼
[2. プレイヤー自身が実際の現地へ足を運ぶ]
        │
        ▼
[3. GPS範囲（ジオフェンス）到達で謎がアンロック]
        │
        ▼
[4. 現地の看板・史跡・風景のディテールから答えを導く]
```

- **📍 現地到達型トリガー (Geofencing)**  
  地図上に配置されたチェックポイントへ実際に移動し、一定の半径内に入ることで初めて次の謎やヒントが開示されます。
- **🏛️ 観光資源の再発見 (Sightseeing × Mystery)**  
  有名スポットだけでなく、歴史の息づく石碑や路地裏のレトロな建築物など、現地を歩いて観察しなければ気付けない要素を謎解きの手がかりとして組み込みます。
- **⚡ インストール不要の快適性 (Lightweight PWA)**  
  QRコードを読み取るだけで即座に開始可能。通信の不安定な屋外でもキャッシュを活用して軽快に動作します。

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
