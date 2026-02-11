# 🇩🇪 Deutsch – README.md

# 📄🔎 LLM Dokumenten-Suchmaschine (RAG)
### Stelle Fragen in natürlicher Sprache – erhalte Antworten aus deinen Dokumenten.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)
![LangChain](https://img.shields.io/badge/Framework-LangChain-green)
![OpenAI](https://img.shields.io/badge/LLM-OpenAI-black)
![Vector DB](https://img.shields.io/badge/VectorStore-FAISS-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

[English](../EN/README.md) | [German](README.md)

---

## ✨ Projektvision

Informationen in langen, unstrukturierten Dokumenten zu finden ist langsam und teuer.

Dieses Projekt zeigt, wie **Large Language Models + Retrieval Augmented Generation (RAG)** statische Dateien in ein **interaktives Wissenssystem** verwandeln.

Statt suchen → lesen → interpretieren,  
kann der Nutzer einfach **fragen**.

> „Welche Rechte habe ich als ausländischer Bürger in Deutschland?“  
> „Welche Risiken nennt dieser Bericht?“  
> „Fasse die Kernergebnisse zusammen.“

---

## 💡 Auslöser des Projekts

Während meines Aufenthalts in Deutschland wollte ich Inhalte des **Grundgesetzes** verstehen, ohne hunderte Seiten lesen zu müssen.

Also entwickelte ich eine Lösung, bei der:

➡️ Dokumente zu Wissen werden  
➡️ Fragen frei formuliert werden können  
➡️ Antworten aus realen Quellen entstehen  

Aus einem persönlichen Helfer wurde ein **Baukasten für Enterprise-Knowledge-Systeme**.

---

## 🚀 Funktionen der Anwendung

Dokument hochladen → Embeddings erzeugen → im Vektorindex speichern → relevante Passagen abrufen → Antwort durch das LLM generieren.

Eine einfache Oberfläche macht komplexe KI für jeden nutzbar.

---

## 🧠 Funktionsweise (Architektur)

```

Frage des Nutzers
↓
Ähnlichkeitssuche (FAISS)
↓
Top-K Textstellen
↓
LLM (OpenAI / GPT)
↓
Kontextbasierte Antwort

```

### Pipeline

1. PDF / DOCX / TXT hochladen  
2. Inhalte werden extrahiert  
3. Embeddings via OpenAI erzeugt  
4. Speicherung im FAISS Index  
5. Semantische Suche  
6. Antwortgenerierung durch GPT

---

## 🛠 Technologien

- **Streamlit** → Benutzeroberfläche  
- **LangChain** → Orchestrierung & Retrieval  
- **OpenAI Modelle** → Analyse & Generierung  
- **Embeddings** → Bedeutungsverständnis  
- **FAISS** → schnelle Vektorsuche  
- **Python** → Integration

Ein typischer **State-of-the-Art RAG Stack**.

---

## 🎯 Relevanz für Unternehmen

Organisationen kämpfen mit:

❌ Wissenssilos  
❌ langen Dokumenten  
❌ Abhängigkeit von Experten  
❌ langsamer Einarbeitung  
❌ wiederkehrenden Fragen  

Dieses System wird zu einem **digitalen Experten rund um die Uhr**.

### Beispiele

- Recht → Klauselsuche  
- Medizin → Leitlinienabfrage  
- IT → Dokumentation  
- Strategie → KPI Extraktion  
- Forschung → Literaturrecherche  

---

## 📸 Demo

*(Screenshots oder GIF einfügen)*

```

/img/demo_1.png
/img/demo_2.png

````

---

## 🔍 Beispiel-Fragen

- Was sagt dieses Gesetz zur Besteuerung?
- Welche Pflichten haben Behörden?
- Wo wird DSGVO erwähnt?
- Erkläre die Inhalte einfach.

---

## 🧩 Erweiterbarkeit

Gleiche Architektur ermöglicht:

- Enterprise Suchmaschinen  
- AI Copilots  
- Vertragsanalyse  
- HR Assistenten  
- Research Helfer  
- natürliche Sprachschnittstellen  
- agentische Systeme  

---

## 🏆 Aussagekraft für Recruiter

Beweist Kompetenz in:

✔ End-to-End LLM Anwendungen  
✔ RAG Design  
✔ Vektordatenbanken  
✔ semantischer Suche  
✔ AI Produktdenken  
✔ schneller Prototypisierung  
✔ Übertragung in Business Nutzen  

---

## ⚙️ Lokal starten

```bash
pip install -r requirement.txt
streamlit run app.py
````

API Key in der Sidebar eintragen.

---

## 📜 Lizenz

MIT

```

---


