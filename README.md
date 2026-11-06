# IMPENNATA

A browser wheelie racing game by IGNITX Labs. Ride motorbikes or bicycles, hold long wheelies, fly off ramps and race rivals. Play with the keyboard, on a touch screen, or with your body through the webcam.

**▶ Play now: https://ignitx-labs.github.io/impennata/**

The game is in **English and Italian**. Use the **IT / EN** switch at the top right of the menu. Your choice is remembered.

---

## The menu

Pick one option in each of the four sections, then press **START**.

### 1 · Discipline
| | |
|---|---|
| **corsara** (motorbikes) | Throttle, wheelies, jumps and backflips. |
| **FRECCIA** (bicycles) | Pedal in rhythm, pull wheelies and bunny-hop off the ramps. |

### 2 · Model
Three bikes per discipline. Each card shows its **speed**, **wheelie** and **jump** ratings.

| Motorbikes | | Bicycles | |
|---|---|---|---|
| **SCIROCCO GP** | GP prototype, the fastest | **DARDO R** | Road bike, all-rounder |
| **MAESTRALE RR** | Superbike, balanced | **SAETTA TT** | Time-trial bike, top speed |
| **LIBECCIO V4** | Hyper-naked, best wheelies | **DARDO XC** | Mountain bike, best wheelies and jumps |

**GARAGE ▸** opens a 3D showroom where you can:
- spin each bike around (drag to rotate, scroll to zoom);
- switch between the 3/4, side, rear and detail views;
- choose a **livery** (paint scheme);
- show or hide the rider.

In 2-player mode, the garage lets each player pick their own bike.

### 3 · Track
| Track | Setting |
|---|---|
| **MILAN BY NIGHT** | Neon city circuit |
| **STELVIO PASS** | Alpine road at 2,758 m |
| **PISCINAS DUNES** | Sardinian sand dunes at sunset |

### 4 · Mode
| Mode | What happens |
|---|---|
| **GRAND PRIX** | A full circuit seen from behind the bike: 3 laps on a motorbike, 2 on a bicycle. Brake for corners and dodge cones, hay bales and oil against rivals. |
| **SPRINT** | A side-on straight with jumps and ramps against 3 rivals. The fastest time wins. |
| **FREESTYLE** | Endless scoring. Ride as far as you can and rack up points. One crash ends the run. |

At the top of this section you can also choose:
- **1 PLAYER** or **2 PLAYERS**. Two players race split-screen on one keyboard.
- **📷 BODY CONTROL**, to ride with your body through the webcam ([see below](#body-control-webcam)).

---

## How to play

### Motorbike (Sprint and Freestyle)
| Key | Action |
|---|---|
| **W** / **↑** | Throttle. Hold it to lift the front wheel, then feather it to stay balanced. |
| **S** / **↓** | Brake |
| **SPACE** | Jump |
| **SHIFT** | Turbo (charges while you wheelie) |
| **W** in the air | Backflip |

### Bicycle (Sprint and Freestyle)
| Key | Action |
|---|---|
| **A** + **D** (or **←** + **→**), alternating | Pedal. A steady rhythm means more speed. |
| **W** / **↑** | Pull the handlebars to wheelie |
| **S** | Brake |
| **SPACE** | Bunny hop |
| **SHIFT** | Sprint boost |

### Grand Prix
| Key | Action |
|---|---|
| **W** / **↑** | Throttle (motorbike) or pedal (bicycle) |
| **S** / **↓** | Brake. Slow down before corners. |
| **A** / **D** or **←** / **→** | Steer |
| **SPACE** | Wheelie (charges the turbo) |
| **SHIFT** | Turbo |

### Always available
- **P** or **Esc**: pause
- **M**: music on/off

### Two players (one keyboard)
| | Player 1 | Player 2 |
|---|---|---|
| Throttle / pedal | **W** | **↑** |
| Brake | **S** | **↓** |
| Steer or pedal | **A** / **D** | **←** / **→** |
| Jump / wheelie | **F** | **ENTER** |
| Turbo | **G** | **RIGHT CTRL** or **-** |

### Touch screens
On phones and tablets, on-screen buttons appear during a race (throttle, brake, jump, turbo and so on).

---

## Scoring tips
- **Wheelies score points every second.** The longer you hold one, the higher the **combo multiplier**, up to **x10**.
- **Sweet spot.** Keep the bike at a steep but safe angle; the **wheelie angle** gauge turns green. When the banner says **SWEET SPOT x2**, the points double and the turbo charges twice as fast.
- **Don't go too far.** If the bike tips past vertical, you flip over and crash.
- **Air time and flips.** Big jumps score bonus points. A full **backflip** or **frontflip** is worth 1,500, and more for multiple flips. Land on the back wheel for a **WHEELIE LANDING** bonus.
- **Orbs** floating over the track give points, multiplied by your combo, and refill the turbo.
- **Clearing obstacles** cleanly in Sprint, and **dodging** them in Grand Prix, earns small bonuses and some turbo.
- **Records.** Your best time on each track and your best Freestyle score are saved in your browser.

---

## Body control (webcam)
Press **📷 BODY CONTROL** in the menu, allow camera access, and follow the short calibration. Stand about 1 m from the webcam in good light, with your shoulders and hands in the picture.

| Movement | Action |
|---|---|
| Lean your shoulders | Steer |
| Roll your right wrist towards you, like a throttle grip | Throttle |
| Raise both hands | Wheelie |
| In Sprint: lean right / left | Push / brake |

**SPACE** still jumps, and the keyboard keeps working alongside the webcam. Body tracking runs in your browser using Google MediaPipe. Nothing is uploaded.

---

## Run it locally
Serve the folder with any static web server and open it in the browser:

```bash
python -m http.server 8000
```

Then go to http://localhost:8000. Opening the file directly may block the webcam.

---

Built with [Three.js](https://threejs.org/) and [MediaPipe](https://developers.google.com/mediapipe). All bikes, brands, teams and riders in the game are fictional.

© IGNITX Labs, an Ignite Strategies LLC product.
