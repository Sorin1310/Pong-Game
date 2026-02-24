# Pong Game - Proiect Python

[cite_start]Acest proiect implementează jocul clasic **Pong** folosind biblioteca **Pygame**[cite: 2, 3, 9]. [cite_start]Este o aplicație interactivă concepută pentru doi jucători care concurează în timp real[cite: 24].

## 🎮 Caracteristici
* [cite_start]**Interfață Grafică:** Două palete colorate (roșu și albastru) și o minge albă[cite: 27, 28].
* [cite_start]**Sistem de Scor:** Scorurile sunt afișate într-un format mare în partea de sus a ecranului[cite: 55].
* [cite_start]**Meniu Interactiv:** Include butoane funcționale pentru **Pauză** și **Ieșire**[cite: 16, 33].
* [cite_start]**Mecanică de Joc:** Mingea își schimbă direcția la contactul cu marginile sau paletele[cite: 15, 49].



---

## 🛠️ Tehnologii Utilizate
* [cite_start]**Python:** Limbajul principal de programare[cite: 18].
* [cite_start]**Pygame:** Bibliotecă pentru grafică și gestionarea evenimentelor[cite: 19].
* [cite_start]**Sys:** Bibliotecă pentru închiderea sigură a aplicației[cite: 20].

---

## 🕹️ Cum se joacă

### Comenzi Tastatură
| Jucător | Sus | Jos |
| :--- | :--- | :--- |
| **Jucător 1 (Stânga - Roșu)** | [cite_start]`W` [cite: 43] | [cite_start]`S` [cite: 43] |
| **Jucător 2 (Dreapta - Albastru)** | [cite_start]`Săgeată Sus` [cite: 44] | [cite_start]`Săgeată Jos` [cite: 44] |

### Reguli
* [cite_start]Un jucător primește **1 punct** când mingea trece de paleta adversarului[cite: 54].
* [cite_start]Butonul **Pauză** oprește jocul și afișează mesajul „Joc Pauzat”[cite: 61].
* [cite_start]Butonul **Ieșire** închide complet aplicația[cite: 61].

---

## 🚀 Instalare și Rulare

1. **Asigură-te că ai Python instalat.**
2. **Instalează Pygame:**
   ```bash
   pip install pygame
