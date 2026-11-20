# ILS Sound Packs

Runtime sound packs for **ILS – Infinite Lab Studio**, served over a CDN so the
studio can carry the full sample set without shipping it inside the site bundle.

Generated: 2026-11-20

## Packs

| Pack | Instruments | Size | License | Source |
|---|---|---|---|---|
| `core` — Core Instruments | 12 | 4.39 MB | CC BY 3.0 / CC0 — see Credits | Subset of FluidR3 GM (CC BY 3.0, gleitz/midi-js-soundfonts) re-packaged for the hosted build |
| `salamander` — Salamander Grand Piano | 1 | 1.99 MB | CC BY 3.0 | https://github.com/sfzinstruments/SalamanderGrandPiano |
| `fluidr3` — FluidR3 General MIDI | 27 | 46.53 MB | CC BY 3.0 | https://github.com/gleitz/midi-js-soundfonts |
| `vsco2` — VSCO 2 Community Edition | 8 | 89.54 MB | CC0 1.0 | https://github.com/sgossner/VSCO-2-CE |
| `drums` — Drum Machines | 3 | 2.37 MB | CC0 1.0 / Public Domain | https://github.com/tidalcycles/sounds-tr808-fischer |
| `acoustic` — Acoustic Kit | 1 | 2.87 MB | CC0 1.0 | https://github.com/tidalcycles/Dirt-Samples |
| `hiphop` — Hip Hop & Club Kits | 5 | 4.38 MB | CC0 1.0 | https://github.com/tidalcycles/Dirt-Samples |
| `keys2` — Pianos & Keys | 4 | 15.40 MB | CC BY 3.0 | https://github.com/gleitz/midi-js-soundfonts |
| `synths` — Sampled Synths | 12 | 2.37 MB | CC BY 3.0 | https://github.com/gleitz/midi-js-soundfonts |
| `fx` — FX & Textures | 7 | 0.18 MB | CC BY 3.0 / CC0 | https://github.com/gleitz/midi-js-soundfonts |
| `loops` — Real Loops | 0 | 4.26 MB | CC0 1.0 / CC BY 3.0 | https://github.com/tidalcycles/Dirt-Samples |
| `guitars` — Guitars & Bass | 4 | 16.15 MB | CC BY 3.0 | https://github.com/nbrosowsky/tonejs-instruments |
| `sso` — Sonatina Symphonic Orchestra | 5 | 8.31 MB | CC Sampling Plus 1.0 | https://github.com/peastman/sso |

## Licenses

Every pack here is redistributable under the license named above, including
commercial use. Original authors and projects:

- **Core Instruments** — ILS (assembled from the credited open libraries) · CC BY 3.0 / CC0 — see Credits · https://creativecommons.org/licenses/by/3.0/
- **Salamander Grand Piano** — Alexander Holm · CC BY 3.0 · https://creativecommons.org/licenses/by/3.0/
- **FluidR3 General MIDI** — Frank Wen / gleitz MIDI.js soundfonts · CC BY 3.0 · https://creativecommons.org/licenses/by/3.0/
- **VSCO 2 Community Edition** — Versilian Studios (Sam Gossner, Simon Dalzell) · CC0 1.0 · https://creativecommons.org/publicdomain/zero/1.0/
- **Drum Machines** — Michael Fischer (TR-808), enoe/oramics (LinnDrum), open 909 pack · CC0 1.0 / Public Domain · https://creativecommons.org/publicdomain/zero/1.0/
- **Acoustic Kit** — Tidalcycles Dirt-Samples · Philharmonia toms · CC0 1.0 · https://creativecommons.org/publicdomain/zero/1.0/
- **Hip Hop & Club Kits** — Tidalcycles Dirt-Samples contributors · CC0 1.0 · https://creativecommons.org/publicdomain/zero/1.0/
- **Pianos & Keys** — FluidR3 (Frank Wen) · nbrosowsky tonejs-instruments · CC BY 3.0 · https://creativecommons.org/licenses/by/3.0/
- **Sampled Synths** — FluidR3 (Frank Wen) · CC BY 3.0 · https://creativecommons.org/licenses/by/3.0/
- **FX & Textures** — FluidR3 (Frank Wen) · Dirt-Samples · CC BY 3.0 / CC0 · https://creativecommons.org/licenses/by/3.0/
- **Real Loops** — ILS loop lab from CC0/CC-BY recordings · CC0 1.0 / CC BY 3.0 · https://creativecommons.org/publicdomain/zero/1.0/
- **Guitars & Bass** — nbrosowsky / tonejs-instruments (Philharmonia samples) · CC BY 3.0 · https://creativecommons.org/licenses/by/3.0/
- **Sonatina Symphonic Orchestra** — Mattias Westlund, Peter Eastman · CC Sampling Plus 1.0 · https://creativecommons.org/licenses/sampling+/1.0/

Audio files are unmodified except for trimming, format conversion (WAV),
and per-zone normalisation needed for playback.

## Layout

```
packs/index.json          catalogue: packs, files, instrument zone maps
packs/<pack-id>/...       the audio each pack manifest references
```

Fetch a file at a pinned version:

```
https://cdn.jsdelivr.net/gh/irblcoin/ils-sound-packs@v1/packs/core/…
```
