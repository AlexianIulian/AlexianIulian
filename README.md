<picture>
  <source media="(prefers-color-scheme: dark)" srcset="header.svg">
  <source media="(prefers-color-scheme: light)" srcset="header.svg">
  <img src="header.svg" width="100%" alt="PROALEXIANS">
</picture>

<br/>

<div align="center">

![](https://img.shields.io/badge/Higgsfield_Ultra-soul__2_·_FLUX.2_Pro-0e0e0e?style=flat-square&labelColor=0e0e0e&color=c8a96e)
![](https://img.shields.io/badge/Seedance_2.5-cinematic_video-0e0e0e?style=flat-square&labelColor=0e0e0e&color=9c7ec8)
![](https://img.shields.io/badge/Claude_Code-Sonnet_4.6-0e0e0e?style=flat-square&labelColor=0e0e0e&color=7eb8c8)
![](https://img.shields.io/badge/Paris_·_Provence-studio-0e0e0e?style=flat-square&labelColor=0e0e0e&color=444)

</div>

<br/>

---

### `01` — Output

*What this system actually produces. Not renders — content indiscernible from studio work.*

<table>
<tr>
<td width="50%" align="center">
<img src="generated/lazy-morning.png" width="100%" alt="Lazy Morning — Maison Margiela Replica register">
<br/><sub><code>soul_2</code> &nbsp;·&nbsp; Maison Margiela Replica register &nbsp;·&nbsp; 1536×2048 &nbsp;·&nbsp; seed 793656</sub>
</td>
<td width="50%" align="center">
<img src="generated/saffron.png" width="100%" alt="Saffron stigmas — botanical macro">
<br/><sub><code>soul_2</code> &nbsp;·&nbsp; saffron stigmas on black &nbsp;·&nbsp; editorial botanical macro</sub>
</td>
</tr>
</table>

<br/>

---

### `02` — Model stack

*Four models. Each with a specific use case. None interchangeable.*

<img src="cards/soul2.svg" width="100%" alt="soul_2">

<br/>

<img src="cards/flux2.svg" width="100%" alt="FLUX.2 Pro">

<br/>

<img src="cards/seedance.svg" width="100%" alt="Seedance 2.5">

<br/>

<img src="cards/recraft.svg" width="100%" alt="Recraft V4.1">

<br/>

---

### `03` — Methodology

*Two open repositories. The complete production system, documented.*

<table>
<tr>
<td width="50%" valign="top">

**[`higgsfield-luxury-prompts`](https://github.com/Alexian/higgsfield-luxury-prompts)**

The core production system. Surface taxonomy, lighting models, prompt architecture, Seedance 2.5 motion rules. Built during real brand productions, not theory.

```
editorial/  reels/  supplements/
SYSTEM.md   CHANGELOG.md
v0.1.0
```

</td>
<td width="50%" valign="top">

**[`higgsfield-fragrance-prompts`](https://github.com/Alexian/higgsfield-fragrance-prompts)**

Fragrance-specific. Three registers — intimate morning, dark opulent, botanical raw. Prompt kits per maison. Tested on Replica, Byredo.

```
editorial/  reels/  maisons/
Maison Margiela · Byredo
v0.1.0
```

</td>
</tr>
</table>

<br/>

---

### `04` — Prompt anatomy

*The formula that runs through everything.*

```
[SUBJECT + STATE]  on/against  [SURFACE],
[LIGHT DIRECTION + KELVIN],    [COMPOSITION],
[PUBLICATION REFERENCE]  aesthetic,
[CAMERA + SPECS],
[EXCLUSIONS]
```

> **Name the reference. Never describe the quality.**
>
> `"Wallpaper* magazine editorial"` activates a complete visual register.  
> `"luxury"` activates whatever the internet thinks that means.

<br/>

---

### `05` — What fails and why

| Failure | Cause | Fix |
|:---|:---|:---|
| Generic "luxury" look | Descriptive adjective, no distribution target | Name the publication reference |
| Wrong surface register | Surface chosen after subject | Surface first — everything follows |
| Shadow fill where none wanted | Model three-point default | Explicit exclusion: `no ambient fill` |
| Video artifacts past 120° | Seedance 2.5 geometry limit | Max 90° rotation, single axis only |
| Label text unreadable | No model renders accurate packaging | Describe bottle form — not the label |

<br/>

---

### `06` — Pipeline

```
brief  →  surface decision  →  prompt build  →  Higgsfield Ultra
      →  review  →  upscale 4K  →  @alexianiulian
```

Orchestration: Claude Code (Sonnet 4.6) &nbsp;·&nbsp; Publishing: Upload-Post API

<br/>

---

<div align="center">
<sub>production work → <a href="https://instagram.com/alexianiulian">@alexianiulian</a></sub>
</div>
