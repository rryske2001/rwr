# 🥽 Godot VR – Meta Quest Hand Controllers

## 📌 Opis projektu
Projekt przedstawia **prostą aplikację VR** stworzoną w silniku **Godot**, umożliwiającą **uruchomienie wirtualnej rzeczywistości** oraz **sterowanie rękami za pomocą kontrolerów Meta Quest**.  
Aplikacja pozwala na podstawową interakcję w środowisku 3D i została przygotowana jako demonstracja konfiguracji VR w Godot.

🌐 **Wersja online (WebXR):**  
👉 https://rryske2001.github.io/rwr/

---

## 🛠 Technologie
- **Godot Engine (3D / VR)**
- **OpenXR**
- **Meta Quest Controllers**
- **WebXR / HTML5 / WebAssembly**

---

## 🎮 Funkcjonalności
- Uruchomienie środowiska **VR**
- Obsługa **kontrolerów Meta Quest**
- Ruch rąk w przestrzeni 3D
- Podstawowa scena 3D
- Uruchamianie aplikacji bezpośrednio w przeglądarce (WebXR)

---

## 📂 Struktura projektu

### 🔹 Foldery
- `assets/models/`  
  Modele 3D wykorzystywane w scenie

---

### 🔹 Pliki konfiguracyjne
- `.gitignore` – ignorowane pliki Git  
- `.gitattributes` – konfiguracja repozytorium  
- `project.godot` – główny plik projektu Godot  
- `export_presets.cfg` – ustawienia eksportu projektu

---

### 🔹 Sceny i skrypty Godot
- `node_3d.tscn` – **główna scena projektu (VR)**
- `node_3d.gd` – skrypt sterujący sceną 3D
- `node_3d.gd.uid` – identyfikator skryptu
- `node_3d.tscn*.tmp` – pliki tymczasowe (mogą zostać usunięte)

---

### 🔹 Pliki eksportu Web (HTML5 / WebXR)
- `index.html` – punkt wejścia aplikacji
- `index.js` – logika JavaScript
- `index.wasm` – WebAssembly
- `index.pck` – zasoby projektu
- `index.audio.worklet.js` – obsługa dźwięku
- `index.png` – ekran ładowania
- `index.icon.png` – ikona aplikacji
- `index.apple-touch-icon.png` – ikona dla urządzeń Apple

---

### 🔹 Ikony
- `icon.svg` – ikona projektu
- `icon.svg.import` – plik importu Godot

---

## ▶️ Uruchomienie projektu

### 🌐 W przeglądarce (zalecane)
1. Wejdź na stronę:  
   👉 https://rryske2001.github.io/rwr/
2. Uruchom tryb **VR** w przeglądarce
3. Załóż headset **Meta Quest**
4. Użyj kontrolerów do poruszania rękami

> Wymagana przeglądarka obsługująca **WebXR** (np. Meta Quest Browser)

---

## 🎯 Wymagania
- Meta Quest
- Kontrolery Meta Quest
- Przeglądarka obsługująca **WebXR**
- (opcjonalnie) Godot Engine do edycji projektu

---

## 📌 Status projektu
✔️ Finalna wersja  
✔️ Obsługa VR i kontrolerów  
✔️ Publiczna wersja WebXR  

---

## 📄 Licencja
Projekt edukacyjny / demonstracyjny – do dowolnego użytku.
