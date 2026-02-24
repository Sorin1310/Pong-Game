# Pong Game - Proiect Python

Acest proiect implementează jocul clasic **Pong** folosind biblioteca **Pygame**[cite: 2, 3, 9]. [cite_start]Este o aplicație interactivă concepută pentru doi jucători care concurează în timp real[cite: 24].

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

---

## 🛠️ 3) Tehnologii utilizate
* [cite_start]**Python** - limbajul principal utilizat pentru implementarea logicii jocului. [cite: 18]
* [cite_start]**Pygame** - bibliotecă utilizată pentru crearea interacțiunilor grafice și gestionarea evenimentelor. [cite: 18, 19]
* [cite_start]**Sys** - bibliotecă pentru ieșirea din aplicație. [cite: 20]
* [cite_start]Această combinație asigură o implementare fluidă și interactivă. [cite: 21]

---

## 📂 4) Descrierea aplicației
[cite_start]Aplicația constă într-o fereastră principală în care sunt desenate elementele jocului: paletele, mingea, scorurile și meniul de pauză. [cite: 23] [cite_start]Jocul este actualizat în timp real și permite o experiență competitivă pentru doi jucători. [cite: 24]

---

## 🖼️ 5) Interfața jocului
* [cite_start]**Elemente principale:** Două palete colorate (roșie și albastră), o minge albă și o linie centrală pentru separarea terenului. [cite: 27, 28, 29]
* [cite_start]**Meniu interactiv:** Două butoane funcționale: **Pauză** (oprește temporar jocul) și **Ieșire** (închide aplicația). [cite: 33, 34, 35]

---

## 🕹️ 6) Prezentare funcționalități

### Mișcarea paletelor:
* [cite_start]**Jucătorul 1:** Tastele `W` (sus) și `S` (jos). [cite: 43]
* [cite_start]**Jucătorul 2:** Tastele `Săgeată sus` și `Săgeată jos`. [cite: 44]

### Mișcarea mingii și coliziuni:
* [cite_start]Mingea se deplasează în linie dreaptă până la coliziunea cu o margine sau o paletă. [cite: 49]
* [cite_start]Coliziunile determină inversarea direcției mingii. [cite: 51]

### Sistemul de scor:
* [cite_start]Fiecare jucător primește **1 punct** atunci când mingea trece de paleta adversară. [cite: 54]
* [cite_start]Scorurile sunt afișate vizibil în partea de sus a ecranului. [cite: 55]

---

## 💻 7) Codul principal
Implementarea acoperă trei etape esențiale:
1. [cite_start]**Inițializarea jocului:** Definirea dimensiunilor ferestrei, culorilor și pozițiilor inițiale. [cite: 67, 68]
2. [cite_start]**Actualizarea jocului:** Gestionarea evenimentelor de tastatură, actualizarea pozițiilor și verificarea coliziunilor. [cite: 122, 123, 124, 125]
3. [cite_start]**Interfața grafică:** Desenarea elementelor la fiecare cadru (60 FPS) și afișarea meniului. [cite: 163, 172, 203]

---

## 👤 Autor
[cite_start]**Chirițoiu Constantin-Sorin** [cite: 6]  
[cite_start]**Grupa: 423E** [cite: 7]  
[cite_start]**Facultatea de Electronică, Telecomunicații și Tehnologia Informației** [cite: 1]  
[cite_start]**Universitatea Națională de Știință și Tehnologie Politehnica din București** [cite: 1]
