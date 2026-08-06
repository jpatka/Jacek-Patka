md_content = """# Cześć, jestem Jacek Patka! 👋

Programista Python z pasją do astronomii, obróbki grafiki oraz wizualizacji danych naukowych.

---

### 🚀 O mnie
* 🐍 **Główny stos technologiczny:** Python (środowisko PyCharm)
* 🌌 **Zainteresowania naukowe:** Astronomia, nauki o kosmosie, zjawiska solarne oraz supernowe
* 🎨 **Grafika i multimedia:** Cyfrowa obróbka obrazu, wektoryzacja oraz edycja graficzna
* 📍 **Lokalizacja:** Żagań, Polska

---

### 🔭 Aktualne projekty
* **Wizualizacja zaćmień słońca:** Tworzenie skryptów w Pythonie do dokładnego obliczania oraz mapowania trajektorii i szerokości cienia zaćmień słonecznych.
* **Przetwarzanie danych astronomicznych:** Narzędzia do analizy i wizualizacji danych kosmicznych.

---

### 🛠️ Technologie i narzędzia
| Kategoria | Technologie / Narzędzia |
| :--- | :--- |
| **Języki programowania** | Python |
| **IDE & Narzędzia** | PyCharm, Git |
| **Specjalizacja** | Data Visualization, Image Processing, Astronomy & Space Science Data |

---

### 📬 Kontakt i profile
* **GitHub:** [@JacekPatka](https://github.com/)
* **Email:** *twój.email@example.com*
"""

filename = "README.md"
with open(filename, "w", encoding="utf-8") as f:
    f.write(md_content)

print(f"File saved successfully as {filename}")