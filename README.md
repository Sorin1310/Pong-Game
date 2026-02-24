# Pong Game - Proiect Python

Acest proiect implementează jocul clasic **Pong** folosind biblioteca **Pygame**. Este o aplicație interactivă concepută pentru doi jucători care concurează în timp real.

## 🎮 Caracteristici
* **Interfață Grafică:** Două palete colorate (roșu și albastru) și o minge albă.
* **Sistem de Scor:** Scorurile sunt afișate într-un format mare în partea de sus a ecranului.
* **Meniu Interactiv:** Include butoane funcționale pentru **Pauză** și **Ieșire**.
* **Mecanică de Joc:** Mingea își schimbă direcția la contactul cu marginile sau paletele.

---

## 🕹️ 1) Cerința
Proiectul permite celor doi jucători să controleze paletele și să concureze pentru a marca puncte. Utilizatorii au posibilitatea de a pune pauză sau de a ieși din joc printr-un meniu grafic interactiv.

---

## 📝 2) Descriere generală
Jocul Pong este un joc clasic de reflexe în care mingea se deplasează într-o arenă dreptunghiulară și este respinsă de paletele controlate de jucători. Scopul fiecărui jucător este de a marca puncte prin trimiterea mingii în partea opusă a terenului.

Funcționalitățile includ:
* Controlul paletelor de către doi jucători, utilizând tastatura.
* O minge care își schimbă direcția la contactul cu marginea sau cu paletele.
* Sisteme de scor afișate pe ecran.
* Meniu cu butoane pentru pauză și ieșire.

---

## 🛠️ 3) Tehnologii utilizate
* **Python** - limbajul principal utilizat pentru implementarea logicii jocului.
* **Pygame** - bibliotecă utilizată pentru crearea interacțiunilor grafice și gestionarea evenimentelor.
* **Sys** - bibliotecă pentru ieșirea din aplicație.
* Această combinație asigură o implementare fluidă și interactivă a jocului Pong.

---

## 📂 4) Descrierea aplicației
Aplicația constă într-o fereastră principală în care sunt desenate elementele jocului: paletele, mingea, scorurile și meniul de pauză. Jocul este actualizat în timp real și permite o experiență competitivă pentru doi jucători.

---

## 🖼️ 5) Interfața jocului
* **Elemente principale:** Două palete colorate (roșie și albastră), controlate de jucătorii 1 și 2, o minge albă care se deplasează în arena de joc și o linie centrală albă pentru separarea terenului.
* **Meniu interactiv:** Două butoane funcționale: 
    * **Pauză**: oprește temporar jocul.
    * **Ieșire**: închide aplicația.

---

## 🕹️ 6) Prezentare funcționalități

### Mișcarea paletelor:
* **Jucătorul 1:** Controlată cu tastele `W` (sus) și `S` (jos).
* **Jucătorul 2:** Controlată cu tastele `Săgeată sus` și `Săgeată jos`.

### Mișcarea mingii și coliziuni:
* Mingea se deplasează în linie dreaptă până la coliziunea cu o margine, o paletă sau ieșirea din teren.
* Coliziunile determină inversarea direcției mingii.

### Sistemul de scor:
* Fiecare jucător primește **1 punct** atunci când mingea trece de paleta adversară.
* Scorurile sunt afișate într-un format mare, vizibil, în partea de sus a ecranului.

---

## 💻 7) Codul principal
Implementarea acoperă etapele esențiale:
1. **Inițializarea jocului:** Se definesc dimensiunile ferestrei, culorile, paletele, mingea și pozițiile lor inițiale.
2. **Actualizarea jocului:** Se gestionează evenimentele utilizatorului, se actualizează pozițiile și se verifică coliziunile pentru a modifica traiectoria sau scorul.
3. **Interfața grafică:** Se desenează elementele jocului la fiecare cadru și se afișează meniul interactiv.

---

## 👤 Autor
**Chirițoiu Constantin-Sorin** **Facultatea de Electronică, Telecomunicații și Tehnologia Informației** **Universitatea Națională de Știință și Tehnologie Politehnica din București**
