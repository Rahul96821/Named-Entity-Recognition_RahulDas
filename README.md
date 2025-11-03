## 🧠 Named Entity Recognition (NER) using SpaCy

This project demonstrates how **Natural Language Processing (NLP)** techniques can be used to automatically extract meaningful entities such as **persons, organizations, dates, and locations** from unstructured text data using **SpaCy**.

By leveraging SpaCy’s pre-trained English model (`en_core_web_sm`), the script processes real-world news content and identifies key entities efficiently. The extracted entities are then organized into a structured **Pandas DataFrame**, making it easier to analyze and visualize the information.

This project serves as a simple yet effective example of applying NLP for **information extraction**, **text analytics**, and **automated data understanding**. It can be extended for various applications such as **news monitoring**, **document classification**, **sentiment analysis**, or **knowledge graph generation**.

---

### 🔧 **Tech Stack**

* **Python 3.x**
* **SpaCy** (`en_core_web_sm` model)
* **Pandas**
* **BeautifulSoup4** *(optional – for web scraping)*

---

### 🚀 **Key Features**

* Extracts named entities (e.g., `PERSON`, `ORG`, `DATE`, `GPE`) from raw text
* Visualizes entities using SpaCy’s `displacy` renderer
* Converts extracted entities into a structured DataFrame
* Easily extendable for large-scale news or document analysis
