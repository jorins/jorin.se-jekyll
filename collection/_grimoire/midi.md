---
title: MIDI
en: MIDI
sv: MIDI

tags:
  - protocol
  - connector
  - music-technology

further-reading:
  -
    name: A simplified guide to MIDI over TRS minijacks - minimidi.world
    link: 'https://minimidi.world'

images:
  - midi-din
---

MIDI is a protocol used to transmit data about musical events.

---

# Physical 

A MIDI connector uses three pins: ground, +5V, and a data sink. It can be
used over five-pin DIN, TRS, TS, or purely digitally. Although not standardised
for a long while, manufacturers have used MIDI over TRS (most commonly 3.5mm)
for a long time. There are three TRS variants.

| Pin function         | DIN connector pin[^din-conn] | TRS A **(standard)** | TRS B  | TS / TRS C |
|---------------------:|------------------------------|----------------------|--------|------------|
| Data (current sink)  |5                             | Tip                  | Ring   | Tip        |
| +5V (current source) |4                             | Ring                 | Tip    | Sleeve     |
| Ground               |2                             | Sleeve               | Sleeve | *None*     |

[^din-conn]: DIN connector does not use pin 1 or 5. Whack!

---

# Gallery

{% include img.html i='midi-din.svg' %}

---

# Footnotes
