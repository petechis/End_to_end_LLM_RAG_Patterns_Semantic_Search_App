# 🇬🇧 English – README.md

# 📄🔎 LLM Document Search Engine (RAG)
### Ask questions in natural language – get answers from your documents.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)
![LangChain](https://img.shields.io/badge/Framework-LangChain-green)
![OpenAI](https://img.shields.io/badge/LLM-OpenAI-black)
![Vector DB](https://img.shields.io/badge/VectorStore-FAISS-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

[English](README.md) | [German](.README.md)

---

## ✨ Project Vision

Finding information inside long, unstructured documents is slow, manual and expensive.

This project demonstrates how **Large Language Models + Retrieval Augmented Generation (RAG)** can transform static files into an **interactive knowledge system**.

Instead of searching → reading → interpreting,  
users can simply **ask**.

> *“What rights do I have as a foreign resident in Germany?”*  
> *“Which risks are highlighted in this report?”*  
> *“Summarize the findings of this paper.”*

---

## 💡 What triggered the project?

While living in Germany, I wanted a simple way to understand regulations inside the **German constitution (Grundgesetz)** without reading hundreds of pages.

So I built a system where:

➡️ documents become searchable knowledge  
➡️ questions can be asked in plain English  
➡️ answers are generated from real sources  

What started as a personal helper evolved into a **blueprint for enterprise knowledge access**.

---

## 🚀 What the app does

Upload documents → convert them into embeddings → store them in a vector index → retrieve relevant passages → let the LLM generate a contextual answer.

A minimal UI makes advanced AI accessible to non-technical users.

---

## 🧠 How it works (Architecture)

```

User Question
↓
Similarity Search (FAISS)
↓
Top-K relevant chunks
↓
LLM (OpenAI / GPT)
↓
Context-aware Answer

```

### Pipeline Steps

1. **Upload** PDF, DOCX or TXT  
2. **Document loaders** parse content  
3. **Embeddings** are generated via OpenAI  
4. Stored in a **FAISS vector index**  
5. Retrieval finds semantically similar text  
6. GPT produces a natural language answer

---

## 🛠 Technologies (derived from the implementation)

- **Streamlit** → rapid AI application UI  
- **LangChain** → orchestration & RetrievalQA chain  
- **OpenAI / Chat Models** → reasoning & generation  
- **OpenAI Embeddings** → semantic understanding  
- **FAISS** → high-performance similarity search  
- **Python** → glue for the ecosystem

This is a classic **production-relevant RAG stack**.

---

## 🎯 Why this matters for industry

Every organization struggles with:

❌ knowledge silos  
❌ long documents  
❌ expert dependency  
❌ slow onboarding  
❌ repeated questions  

This system turns documents into a **24/7 expert assistant**.

### Impact examples

- Legal → clause discovery  
- Healthcare → guideline lookup  
- IT → documentation search  
- Strategy → KPI extraction  
- Research → literature navigation  

---

## 📸 Demo

*(add screenshots or gif here)*

```

/img/demo_1.png
/img/demo_2.png

````

---

## 🔍 Example Questions

- What does this law say about taxation?
- Summarize the responsibilities of authorities.
- Where are GDPR obligations mentioned?
- Explain the key ideas in simple language.

---

## 🧩 Expandability

The same workflow can power:

- Enterprise search engines  
- AI copilots  
- contract analytics  
- HR assistants  
- research companions  
- natural language interfaces to data  
- agentic automation systems  

---

## 🏆 Takeaways for recruiters & managers

This project proves capability in:

✔ building end-to-end LLM apps  
✔ applying RAG patterns  
✔ semantic search  
✔ vector databases  
✔ prompt-driven workflows  
✔ turning AI into business value  
✔ rapid prototyping  
✔ scalable architecture thinking  

---

## ⚙️ Run locally

```bash
pip install -r requirement.txt
streamlit run app.py
````

Add your OpenAI key in the sidebar.

---

````

## 📜 License MIT

````

---



# 🇩🇪 Deutsch – README.md


# 📄🔎 LLM Dokumenten-Suchmaschine (RAG)
### Stelle Fragen in natürlicher Sprache – erhalte Antworten aus deinen Dokumenten.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Streamlit](https://img.shields.io/badge/UI-Streamlit-red)
![LangChain](https://img.shields.io/badge/Framework-LangChain-green)
![OpenAI](https://img.shields.io/badge/LLM-OpenAI-black)
![Vector DB](https://img.shields.io/badge/VectorStore-FAISS-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

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

````

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


