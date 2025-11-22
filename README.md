# RBA Platforms

RBA Platforms is a next-generation ecosystem focused on **macroeconomic intelligence**.  
It integrates **composite macro indices**, **interactive visualizations**, and **AI-powered economic analysis** into a unified system.

> **Indices. Graphs. Intelligence.**

---

## 📌 Overview

- Composite macroeconomic indices (RAI, RIPI, RFSI)  
- Interactive dashboards with modern UI  
- AI-driven macro briefings & scenario analysis  
- Modular architecture with independent repositories  
- Built for clarity, transparency, and data-driven insights

---

## 🧩 Repository Structure

This repository (`rba-platforms`) acts as the **documentation & meta hub**.

Core codebases:

- `rba-backend` — API & data pipeline  
- `rba-macrograph` — interactive visualization UI  
- `rba-index-lab` — index computation library  
- `rba-analyst-ai` — AI macro analysis engine  
- `rba-shared-utils` — shared utility modules  

---

## 🧬 System Architecture

```
                    ┌──────────────────────────┐
                    │     RBA MacroGraph       │
                    │      (Next.js UI)        │
                    └───────────────┬──────────┘
                                    │
                                    ▼
                    ┌──────────────────────────┐
                    │       RBA Backend        │
                    │    (FastAPI / Python)    │
                    └───────────────┬──────────┘
                                    │
                   ┌────────────────┴────────────────┐
                   │                                 │
                   ▼                                 ▼
        ┌──────────────────────┐          ┌────────────────────────┐
        │    RBA Index Lab     │          │     RBA Analyst AI     │
        │    (Python pkg)      │          │   (LLM-based engine)   │
        └──────────────────────┘          └────────────────────────┘

                    ┌──────────────────────────────┐
                    │       RBA Shared Utils        │
                    │   (logging, config, tools)    │
                    └──────────────────────────────┘
```

---

## 📈 Roadmap (v1)

- [ ] Initialize `rba-backend` repository  
- [ ] Set up FastAPI project structure  
- [ ] Build macro data ingestion pipeline  
- [ ] Implement RBA Activity Index v1  
- [ ] Create MacroGraph UI (MVP)  
- [ ] Develop Analyst AI “Macro Brief v1”  
- [ ] Build Shared Utils module  

---

## 📄 License

TBD

---

## 👤 Author

**Rahmi Berkay Alp**  
