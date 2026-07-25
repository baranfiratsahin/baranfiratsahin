<div align="center">

# Baran Fırat Şahin

**Offensive Security · Fullstack · Applied AI · Markets**

<a href="https://fsahin.com"><img src="https://img.shields.io/badge/%E2%97%89_LIVE-fsahin.com-39ff88?style=for-the-badge&labelColor=05070a"/></a>
<a href="https://tr.linkedin.com/in/barannn"><img src="https://img.shields.io/badge/LinkedIn-Baran_F%C4%B1rat_%C5%9Eahin-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=05070a"/></a>
<a href="https://baranfiratsahin.github.io/"><img src="https://img.shields.io/badge/SITE-baranfiratsahin.github.io-ffb000?style=for-the-badge&labelColor=05070a"/></a>
<img src="https://komarev.com/ghpvc/?username=baranfiratsahin&style=for-the-badge&color=ffb000&label=PROFILE+VIEWS&labelColor=05070a"/>

<br>

<img src="https://ghchart.rshah.org/39ff88/baranfiratsahin" alt="Baran Fırat Şahin — contribution graph" width="100%"/>

</div>

## ⬢ Sistemler / What's here

Bu profildeki depolar dört alanda toplanır: **canlı veri altyapıları**, **güvenlik araçları**, **çevrimdışı yapay zeka** ve **piyasa altyapıları**.

**[fsahin.com](https://fsahin.com) — World Terminal.** Tek ekranda 16 canlı veri akışını harita üzerinde birleştiren gerçek zamanlı terminal: deprem (USGS/AFAD), yangın ve doğa olayları (NASA EONET), uçuşlar (topluluk ADS-B ağları, 8 bölgelik ızgara + saniyelik ara değerleme), ISS, yağış radarı (RainViewer), uzay havası (NOAA Kp), hava ve hava kalitesi (Open-Meteo), TR + dünya haber akışı, internet kesintileri (IODA/Georgia Tech), piyasa verileri ve Wikimedia canlı olay akışı. Çerçeve, derleme adımı ve paketleyici kullanılmadan saf JavaScript + Leaflet ile yazıldı; tek bir Cloudflare Worker üzerinde çalışıyor, durum Workers KV'de tutuluyor. Tasarım ilkesi: her değer canlı bir kaynağa iner, kaynak düşerse veri uydurulmaz — panel `SIGNAL LOST` durumuna geçer. Haber başlığında geçen yer adı haritada işaretlenir.

**Güvenlik.** Kali Linux ekosistemi üzerine kurulu, yetkili değerlendirmeler için zafiyet taraması ve penetrasyon testi otomasyonu; sistem sertleştirme akışları.

**Çevrimdışı yapay zeka.** Buluta bağlanmadan çalışan akıl yürütme sistemi: yerel dil modeli (GLM-4-9B), kişisel arşiv üzerinde RAG (BM25 indeks, hibrit yeniden sıralama, bağlamsal parça sınırı skorlama) ve bir soruyu çok sesli tartışan panel mimarisi.

**Piyasa altyapısı.** Emir yaşam döngüsü, risk katmanı (pozisyon limitleri, drawdown koruması, acil durdurma), backtest iskeleti ve equity/PnL günlüğü. Strateji ve parametreler tasarım gereği private.

**Ayrıca:** afet anında altyapı çöktüğünde çalışan çevrimdışı mesh iletişim ağı konsepti, arşiv kurtarma araçları, harita/tile işleme, tasarım sistemi token setleri ve Blender pipeline otomasyonu.

Detaylı teknik arşiv: **[baranfiratsahin.github.io](https://baranfiratsahin.github.io/)**

## ⬢ Projeler / Featured

| Proje | Ne yapar |
|-------|----------|
| **[▸ fsahin.com — World Terminal](https://github.com/baranfiratsahin/baranfiratsahin-worldmap)** | Tam ekran, canlı veri dünya terminali · 13 gerçek akış · Cloudflare Worker + KV · **[CANLI ↗](https://fsahin.com)** |
| **[Deprem & Yangın Acil İletişim Ağı](https://github.com/baranfiratsahin/Deprem-yangin-acil-offline-iletisim-agi)** | Afette altyapı çökse bile çalışan çevrimdışı mesh iletişim konsepti |
| **[Systematic Trading Infrastructure](https://github.com/baranfiratsahin/Quantitive-trading-bot)** | Emir yaşam döngüsü · risk katmanı · backtest *(strateji private)* |
| **[Multi-Venue Crypto System](https://github.com/baranfiratsahin/Trading-bot-hyperliquid-and-all-cryptos)** | Sinyal motoru · yürütme daemon'u · backtester *(alpha private)* |
| **[Linux Security Toolkit](https://github.com/baranfiratsahin/DDOS-VULN-PENTEST-Linux-Bot-)** | Zafiyet taraması · pentest otomasyonu *(yetkili testler)* |
| **[Yerli & Milli Offline LLM](https://github.com/baranfiratsahin/Yerli-ve-milli-yapay-zeka-LLM)** | Tamamen çevrimdışı yerel LLM · RAG · çok-personalı konsey |

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=baranfiratsahin&show_icons=true&hide_border=true&bg_color=05070a&title_color=ffb000&icon_color=7cd5ff&text_color=c7ccd4&include_all_commits=true&count_private=true"/>
<img height="150" src="https://github-readme-streak-stats.herokuapp.com?user=baranfiratsahin&hide_border=true&background=05070a&ring=ffb000&fire=ff3355&currStreakLabel=ffb000&sideLabels=c7ccd4&dates=94a3b8&sideNums=7cd5ff&currStreakNum=ffb000"/>

</div>

---

```console
baran@firat-group:~$ whoami --full
  name      : Baran Fırat Şahin
  role      : IT Operations Manager · BEQW SYSTEMS [AR-GE]
  location  : Türkiye
  builds    : live systems · security tooling · trading infra · offline AI
  doctrine  : real data · honest failures · ships to production
  flagship  : https://fsahin.com  →  fullscreen live-data world terminal
```

<div align="center">

![Kali](https://img.shields.io/badge/Offensive_Security-Kali-7cd5ff?style=flat-square&logo=kalilinux&logoColor=7cd5ff&labelColor=0b0e14)
![JS](https://img.shields.io/badge/JavaScript-vanilla-ffb000?style=flat-square&logo=javascript&logoColor=ffb000&labelColor=0b0e14)
![Python](https://img.shields.io/badge/Python-3-39ff88?style=flat-square&logo=python&logoColor=39ff88&labelColor=0b0e14)
![Cloudflare](https://img.shields.io/badge/Cloudflare-Workers_·_KV-ffb000?style=flat-square&logo=cloudflare&logoColor=ffb000&labelColor=0b0e14)
![AI](https://img.shields.io/badge/LLM_·_RAG-offline-7cd5ff?style=flat-square&logo=openai&logoColor=7cd5ff&labelColor=0b0e14)
![MT5](https://img.shields.io/badge/MetaTrader_5-markets-ff3355?style=flat-square&labelColor=0b0e14)
![Linux](https://img.shields.io/badge/Linux-hardening-ffb000?style=flat-square&logo=linux&logoColor=ffb000&labelColor=0b0e14)

**[fsahin.com](https://fsahin.com)** · **[baranfiratsahin.github.io](https://baranfiratsahin.github.io/)** · `builds live systems`

</div>
