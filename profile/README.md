<p align="center">
  <img src="logo.png" alt="NineVoltNine" width="220" />
</p>

<h1 align="center">NineVoltNine</h1>

<p align="center">
  <strong>Terminal guitar pedals for Linux.</strong>
</p>

<p align="center">
  <a href="https://ninevoltnine.com"><img src="https://img.shields.io/badge/website-ninevoltnine.com-0A0B0E?style=flat-square&labelColor=0A0B0E&color=5DFF9A" alt="Website" /></a>
  <a href="https://ninevoltnine.com/install.html"><img src="https://img.shields.io/badge/install-apt%20%2F%20dnf-0A0B0E?style=flat-square&labelColor=0A0B0E&color=E88820" alt="Install" /></a>
  <a href="mailto:jon@ninevoltnine.com"><img src="https://img.shields.io/badge/email-jon%40ninevoltnine.com-0A0B0E?style=flat-square&labelColor=0A0B0E&color=F5C06A" alt="Email" /></a>
  <img src="https://img.shields.io/badge/home-Garner%2C%20NC-0A0B0E?style=flat-square&labelColor=0A0B0E&color=5DFF9A" alt="Garner, NC" />
</p>

NineVoltNine builds **Ninevolt** — real-time guitar effects that treat the terminal like a pedalboard: JACK in, JACK out, knobs in a TUI, and whole boards as YAML you can share and version.

```bash
# Fedora
sudo dnf install https://ninevoltnine.com/downloads/repo.rpm
sudo dnf install ninevolt

# Debian / Ubuntu
curl -fsSL -o /tmp/ninevolt-repo.deb https://ninevoltnine.com/downloads/repo.deb
sudo apt install /tmp/ninevolt-repo.deb && sudo apt update && sudo apt install ninevolt
```

---

### Pedals with faces

Every stomp has a TUI you can read from across the room.

<p align="center">
  <a href="https://ninevoltnine.com/pedals/crazy-tone.html"><img src="shots/crazy-tone.jpg" alt="Crazy Tone TUI" width="48%" /></a>
  <a href="https://ninevoltnine.com/pedals/black-rat.html"><img src="shots/black-rat.jpg" alt="Black Rat TUI" width="48%" /></a>
</p>
<p align="center">
  <a href="https://ninevoltnine.com/pedals/green-screamer.html"><img src="shots/green-screamer.jpg" alt="Green Screamer TUI" width="48%" /></a>
  <a href="https://ninevoltnine.com/pedals/ana-echo.html"><img src="shots/ana-echo.jpg" alt="Ana Echo TUI" width="48%" /></a>
</p>

<p align="center">
  <img src="shots/live-amp.jpg" alt="Ninevolt LIVE chain" width="92%" />
  <br />
  <sub>LIVE chain — Amp Push on a Blink-inspired board</sub>
</p>

<p align="center">
  <a href="https://ninevoltnine.com/pedals/">Browse the full library →</a>
</p>

---

### What we build

| | |
|---|---|
| **Ninevolt** | Linux package of guitar pedals over JACK (or PipeWire’s JACK bridge) |
| **Pedals with faces** | Every stomp has a TUI you can read from across the room |
| **Chains & profiles** | YAML boards you can edit, diff, and hand to a friend or an agent |
| **Local-first** | No license server, no account gate — play offline, including on a tour spare |

Built for the desk and the stage. Feature requests and bugs: [jon@ninevoltnine.com](mailto:jon@ninevoltnine.com).
