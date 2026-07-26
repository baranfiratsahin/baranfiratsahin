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

## ⬢ Calisma alanlari — tam kapsam

2024 ortasindan bugune suren calisma; kisisel arsivde bu doneme ait **126 ayri teknik konu** kayitli (en yogun donem 2025). 60+ acik depo; bazi sistemler operasyonel guvenlik veya ticari gizlilik geregi kapali.

**Siber guvenlik.** Kali Linux uzerinde penetrasyon testi ve zafiyet taramasi, Nuclei tabanli tarama akislari ve raporlama otomasyonu, bug bounty amacli arac gelistirme, ag seviyesinde DPI ve engelleme mekanizmalarinin analizi, sifreleme uygulamalari, bulut guvenligi ve kimlik dogrulama yapilandirmasi (MFA, erisim politikalari), gizlilik sertlestirme. Yalnizca yetkili degerlendirmeler kapsaminda.

**Canli veri altyapilari.** [fsahin.com](https://fsahin.com) World Terminal — 16 canli akis (USGS/AFAD deprem, NASA EONET yangin, toplulukADS-B ucuslari, ISS, RainViewer yagis radari, NOAA Kp uzay havasi, Open-Meteo hava/AQI, TR + dunya haberleri, IODA internet kesintileri, piyasa verileri, Wikimedia olay akisi) tek Cloudflare Worker + KV uzerinde, cercevesiz saf JavaScript + Leaflet ile. Kaynak duserse veri uydurulmaz, panel `SIGNAL LOST` durumuna gecer. Oncesinde ilk nesil canli harita denemeleri, uydu/hava goruntusu ve tile isleme hatti.

**Uygulamali yapay zeka, RAG ve ajan sistemleri.** Tamamen cevrimdisi yerel LLM (GLM-4-9B) tabanli akil yurutme; elle kurulmus RAG hatti: BM25 indeks, hibrit skor fuzyonuyla yeniden siralama, baglamsal parca oneki, parca siniri skorlama, erisim benchmark kosucusu; cok-personali konsey mimarisi; otonom ajan modlari ve gorev donguleri, ajan istem muhendisligi, model ailesi karsilastirma/secimi, MCP sunuculari, beceri ve is akisi otomasyonu, terminal HUD araclari, sesli asistan, sohbet arsivi denetim ve ozetleme sistemleri.

**Veri kurtarma ve korpus muhendisligi.** Uc yillik arsivin kurtarilmasi — yuzlerce konusmanin tek sorgulanabilir JSON korpusuna donusturulmesi, ayristirma/dogrulama scriptleri, zaman cizelgesi ve profil cikarimi, konu bazli ozetleme; varlik-kavram-kaynak yapisinda Obsidian bilgi kasasi; JSON sema duzeltme, CSV/UTF-8 donusum ve toplu katalog uretimi.

**Piyasa altyapilari ve otonom ticaret.** Tahmin piyasasi (Polymarket) tarama/arbitraj/yurutme catisi, kaldiracli kripto ticaret cekirdegi (Binance, Hyperliquid), MetaTrader 5 uzerinde XAUUSD/NAS100 algoritmik ticaret. Bilesenler: sinyal motoru, yurutme daemon servisi, risk motoru (pozisyon limiti, drawdown, kill-switch), bar replay backtest, emir akisi analitigi, funding/carry takibi, momentum siralama ve sepet kurgusu, kesitsel analitik, volatilite rejim siniflandirici, piyasa verisi kaydedici, equity/PnL gunlugu, canli ogrenme dongusu, bilesik getiri regulatoru, canli izleme panelleri; teknik gosterge arastirmasi ve madencilik/kontrol yazilimi kurulumu. Strateji ve parametreler private.

**E-ticaret ve is otomasyonu.** Shopify magaza operasyonlari: toplu urun katalogu uretimi (CSV/UTF-8 hatlari), script destekli magaza yonetimi, uluslararasi satis plani, urun gorunurlugu ve operasyon akisi duzeltmeleri; otomatik B2B kazanc sistemi tasarimi; kurumsal iletisim ve marka altyapisi.

**Web, arayuz ve tasarim sistemleri.** Kimlik ve platform sitelerinin birden cok nesli, tasarim token setleri (renk/tipografi/durum), yeniden kullanilabilir arayuz kitleri, React arayuz duzeltmeleri, SQL panel duzenlemeleri, Streamlit ic araclar, erisilebilirlik ve azaltilmis hareket destegi, Cloudflare Workers/Pages dagitimi, teknik SEO.

**3B uretim ve gorsel tasarim.** Blender'da Python ile pipeline otomasyonu (sahne, materyal/doku, scriptli uretim, disa aktarma), otomotiv gorsellestirme ve render calismalari, poster/kapak tasarimi, logo ve marka kimligi setleri, fotograf duzenleme ve stil aktarimi.

**Masaustu araclar ve sistem otomasyonu.** Windows pencere/sekme aktivite izleyicisi, PowerShell ve Python otomasyon scriptleri, surec ve kaynak izleme, belge isleme (e-fatura/e-arsiv PDF), veri cekme araclari.

Detayli teknik arsiv: **[baranfiratsahin.github.io](https://baranfiratsahin.github.io/)**

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
