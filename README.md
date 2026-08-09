# 🚁 [PROJEKTNAME]


<img src="Protector (by DTech).jpg" alt="localization_editor_interface" width="800">


[Deutsch](#deutsch) | [English](#english)

---

<a name="deutsch"></a>
# 🇩🇪 Deutsch

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Web Audio API](https://img.shields.io/badge/Audio-Web_Audio_API-00599C)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Multiplayer](https://img.shields.io/badge/Multiplayer-PeerJS_WebRTC-red)](https://peerjs.com/)

> Ein moderner, im Browser spielbarer Retro-Helikopter-Shooter im 16-Bit-Amiga-Stil – inklusive prozeduralem Chiptune-Sound und P2P-Multiplayer.

---

## 📖 Die Geschichte hinter dem Projekt

Der alte Amiga-Klassiker **[Protector (Virgin Mastertronic, 1989)](https://amiga.abime.net/games/view/protector-virgin-mastertronic#information)** hat mir damals als Kind unglaublich viel Spaß gemacht. Das einfache, aber anspruchsvolle Gameplay, die flüssige Helikopter-Steuerung und die spannenden Luftkämpfe sind mir über all die Jahre in Erinnerung geblieben.

Da es heute gar nicht mehr so einfach ist, den alten Klassiker spontan ohne Hürden wie Emulatoren oder alte Hardware zusammen mit dem eigenen Kind zu spielen, habe ich mich dazu entschlossen, das Spielgefühl von damals neu zu erschaffen. 

**Das Ergebnis:** Eine komplett eigenständige Web-Reimplementierung, die direkt im Browser läuft – ohne Installation, ohne Plugins, aber mit echtem Nostalgie-Faktor und modernem Peer-to-Peer-Multiplayer, um gemeinsam Erinnerungen neu aufleben zu lassen!

---

## ✨ Features

* 🎮 **Authentisches 16-Bit Arcade-Feeling:** Dual-Canvas Split-Screen mit toroidalem (endlos umlaufendem) Welt-System.
* 🎵 **Prozeduraler Chiptune-Sound (Web Audio API):** Der gesamte Soundtrack und alle Soundeffekte (Explosionen, Schüsse, Rotor-Sounds) werden live per Code synthetisiert – **0 KB externe MP3s/WAVs!**
* 🌐 **Serverloser P2P-Multiplayer:** Co-Op & Versus-Action über WebRTC (Powered by PeerJS). Einfach einen Raum-Code generieren und dem Mitspieler schicken.
* 🌍 **Zweisprachig (DE / EN):** Integrierte Sprachumschaltung direkt im Startmenü.
* 💻 **Zero Dependencies / Pure Web:** Geschrieben in reinem JavaScript (ES6+), HTML5 Canvas und CSS. Keine schwere Engine, kein Build-Step erforderlich.
* 🎨 **Retro-Typografie:** Authentische HUD-Visualisierung unter Verwendung der *Press Start 2P* Pixel-Schriftart.

---

## 🕹️ Steuerung

| Aktion | Spieler 1 (Keyboard) | Spieler 2 / Peer (Keyboard) |
| :--- | :--- | :--- |
| **Hoch / Runter** | `W` / `S` | `Pfeil oben` / `Pfeil unten` |
| **Links / Rechts** | `A` / `D` | `Pfeil links` / `Pfeil rechts` |
| **Schießen** | `Leertaste` | `Enter` / `Strg` |
| **Spezial / Bombe** | `Shift` | `M` |

*(Hinweis: Im P2P-Multiplayer-Modus steuert jeder Spieler auf seinem eigenen Bildschirmausschnitt.)*

---

## 🚀 Schnellstart / Installation

Da das Projekt ohne Build-Tools oder Abhängigkeiten auskommt, lässt es sich extrem einfach starten:

### Variante 1: Direkt im Browser
Öffne einfach die `index.html` direkt in deinem bevorzugten Webbrowser (Chrome, Firefox, Edge, Safari).

### Variante 2: Lokaler Webserver (Empfohlen für WebRTC / Audio)
1. Repository klonen:
   ```bash
   git clone [https://github.com/dtechniker/](https://github.com/dtechniker/)[PROJEKTNAME].git
   cd [PROJEKTNAME]


   # 🇬🇧 English README

# 🚁 [PROJEKTNAME] – Amiga Retro Helicopter Shooter

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Web Audio API](https://img.shields.io/badge/Audio-Web_Audio_API-00599C)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Multiplayer](https://img.shields.io/badge/Multiplayer-PeerJS_WebRTC-red)](https://peerjs.com/)

> A modern, browser-playable retro 16-bit Amiga-style helicopter shooter – featuring procedural chiptune audio and P2P multiplayer.

---

## 📖 The Story Behind the Project

As a child, I had an incredible amount of fun playing the classic Amiga game **[Protector (Virgin Mastertronic, 1989)](https://amiga.abime.net/games/view/protector-virgin-mastertronic#information)**. The simple yet challenging gameplay, smooth helicopter physics, and intense dogfights stayed in my memory over all these years.

Since setting up old hardware or dealing with emulators isn't ideal for a quick game session with my child today, I decided to recreate that classic gameplay experience from scratch using modern web technologies.

**The result:** A standalone web-based homage that runs directly in any modern browser – no installation, no plugins, pure nostalgic fun, and built-in Peer-to-Peer multiplayer to relive those gaming memories together!

---

## ✨ Features

* 🎮 **Authentic 16-Bit Arcade Vibe:** Dual-canvas split-screen featuring a toroidal (wrap-around) world system.
* 🎵 **Procedural Chiptune Audio (Web Audio API):** Complete soundtrack and sound effects (explosions, gunfire, rotor sound) generated live via code – **0 KB external audio files!**
* 🌐 **Serverless P2P Multiplayer:** Co-op & Versus action powered by WebRTC (PeerJS). Just generate a room code and share it with your co-player.
* 🌍 **Bilingual (DE / EN):** Built-in language switch directly in the main menu.
* 💻 **Zero Dependencies / Pure Web:** Built with pure JavaScript (ES6+), HTML5 Canvas, and CSS. No heavy engines or build steps required.
* 🎨 **Retro Typography:** Authentic HUD rendering using the *Press Start 2P* pixel font.

---

## 🕹️ Controls

| Action | Player 1 (Keyboard) | Player 2 / Peer (Keyboard) |
| :--- | :--- | :--- |
| **Up / Down** | `W` / `S` | `Up Arrow` / `Down Arrow` |
| **Left / Right** | `A` / `D` | `Left Arrow` / `Right Arrow` |
| **Shoot** | `Space` | `Enter` / `Ctrl` |
| **Special / Bomb** | `Shift` | `M` |

*(Note: In P2P Multiplayer mode, each player controls their helicopter on their own screen viewport.)*

---

## 🚀 Quick Start / Installation

Since this project has zero external build tools or runtime dependencies, running it is straightforward:

### Option 1: Directly in Browser
Simply open `index.html` in your favorite web browser (Chrome, Firefox, Edge, Safari).

### Option 2: Local Web Server (Recommended for WebRTC / Audio)
1. Clone the repository:
   ```bash
   git clone [https://github.com/dtechniker/](https://github.com/dtechniker/)[PROJEKTNAME].git
   cd [PROJEKTNAME]
