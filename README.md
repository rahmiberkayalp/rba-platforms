# RBA Platforms

RBA Platforms, makroekonomik veriler için yeni nesil **endeksler**, **interaktif grafikler** ve **AI destekli makro analiz** üreten bir ekosistemdir.

> **Indices. Graphs. Intelligence.**

---

## 🏛️ Ürün Suite

RBA Platforms üç ana üründen oluşur:

### 🔹 RBA Backend
Makro veri ingestion, zaman serisi işleme, kompozit indeks hesaplama (RAI, RIPI, RFSI) ve API katmanı.  
Teknoloji: FastAPI, Python, pandas, SQL.

### 🔹 RBA MacroGraph
Makroekonomik göstergeleri ve RBA endekslerini interaktif grafiklerle sunan web arayüzü.  
Teknoloji: Next.js, React, Plotly.

### 🔹 RBA Index Lab
Yeni makroekonomik kompozit endekslerin (RBA Activity Index, Inflation Pressure Index, Financial Stress Index) üretildiği bağımsız Python paketi.

### 🔹 RBA Analyst AI
Makro veri + RBA endekslerini otomatik analiz eden yapay zekâ motoru.  
Trend, risk, senaryo, makro özet ve politika yorumları üretir.

### 🔹 RBA Shared Utils
Tüm sistemde ortak kullanılan yardımcı fonksiyonlar:  
logging, config, date helpers, error yapıları.

---

## 📦 Repository Ekosistemi

Bu ana repo, RBA Platforms’un şirket seviyesi dokümantasyon deposudur.

Aşağıdaki repolar ürün kodlarını içerir:

- **rba-backend** – API & data pipeline  
- **rba-macrograph** – frontend  
- **rba-index-lab** – indeks kütüphanesi  
- **rba-analyst-ai** – AI yorum motoru  
- **rba-shared-utils** – ortak modüller  

---

## 🧬 Mimari Genel Bakış

+------------------------+
|     RBA MacroGraph     |
|   (Next.js Frontend)   |
+-----------+------------+
            |
            v
+------------------------+
|       RBA Backend      |
|   (FastAPI / Python)   |
+-----------+------------+
            |
+-----------+---------------------------+
|                                       |
v                                       v
+--------------------+      +------------------------+
|    RBA Index Lab   |      |     RBA Analyst AI     |
|  (Python package)  |      | (LLM-based analysis)   |
+--------------------+      +------------------------+

             +-------------------------+
             |    RBA Shared Utils     |
             | (logging, config, etc.) |
             +-------------------------+



---

## 🚀 Roadmap (v1)

- [ ] `rba-backend` repo oluşturma  
- [ ] FastAPI iskelet kurulumu  
- [ ] Temel Türkiye makro veri ingestion  
- [ ] RBA Activity Index v1 formülü  
- [ ] RBA MacroGraph MVP dashboard  
- [ ] Analyst AI “Macro Brief v1” üretici  
- [ ] Shared Utils temel modülleri (logging & config)

---

## 📄 Lisans
TBD

---

## 👤 Author
**Rahmi Berkay Alp**  




