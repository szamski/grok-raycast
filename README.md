<div align="center">

# Grok Theme for Raycast

Themes for [Raycast](https://raycast.com) based on the **Grok Night** and **Grok Day** color schemes from [iTerm2 Color Schemes](https://iterm2colorschemes.com/).

</div>

## Installation

> [!NOTE]
> Custom themes require [Raycast Pro](https://raycast.com/pro).

| Theme | Install | Preview |
|---|---|---|
| **Grok Night** | [**Add to Raycast →**](https://ray.so/themes?author=Maciej%20Szamowski&authorUsername=szamski&version=1&name=Grok%20Night&appearance=dark&colors=%23141414,%23242424,%23E1E1E1,%23E0AF68,%23E0AF68,%23F7768E,%23EC927B,%23E0AF68,%239ECE6A,%237AA2F7,%23BB9AF7,%23D988C2&addToRaycast) | [ray.so/themes](https://ray.so/themes?author=Maciej%20Szamowski&authorUsername=szamski&version=1&name=Grok%20Night&appearance=dark&colors=%23141414,%23242424,%23E1E1E1,%23E0AF68,%23E0AF68,%23F7768E,%23EC927B,%23E0AF68,%239ECE6A,%237AA2F7,%23BB9AF7,%23D988C2) |
| **Grok Day** | [**Add to Raycast →**](https://ray.so/themes?author=Maciej%20Szamowski&authorUsername=szamski&version=1&name=Grok%20Day&appearance=light&colors=%23F5F5F5,%23DEDEDE,%23262626,%237D4BC6,%237D4BC6,%23CD3048,%23B8532D,%23A27612,%23378E23,%232F64D2,%237D4BC6,%23A53E87&addToRaycast) | [ray.so/themes](https://ray.so/themes?author=Maciej%20Szamowski&authorUsername=szamski&version=1&name=Grok%20Day&appearance=light&colors=%23F5F5F5,%23DEDEDE,%23262626,%237D4BC6,%237D4BC6,%23CD3048,%23B8532D,%23A27612,%23378E23,%232F64D2,%237D4BC6,%23A53E87) |

After importing, pick the theme in **Raycast → Settings → Appearance → Theme** or with the **Switch Theme** command.

<details>
<summary>Install without a browser (deeplink)</summary>

**Grok Night**

```sh
open 'raycast://theme?author=Maciej%20Szamowski&authorUsername=szamski&version=1&name=Grok%20Night&appearance=dark&colors=%23141414,%23242424,%23E1E1E1,%23E0AF68,%23E0AF68,%23F7768E,%23EC927B,%23E0AF68,%239ECE6A,%237AA2F7,%23BB9AF7,%23D988C2'
```

**Grok Day**

```sh
open 'raycast://theme?author=Maciej%20Szamowski&authorUsername=szamski&version=1&name=Grok%20Day&appearance=light&colors=%23F5F5F5,%23DEDEDE,%23262626,%237D4BC6,%237D4BC6,%23CD3048,%23B8532D,%23A27612,%23378E23,%232F64D2,%237D4BC6,%23A53E87'
```

</details>

## Palette

Colors come from the iTerm2 [Grok Night](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/ghostty/Grok%20Night) and [Grok Day](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/ghostty/Grok%20Day) schemes: `background`, `foreground`, `selection-background` → `backgroundSecondary`, `cursor-color` → `selection`/`loader`, ANSI colors → accents. The schemes have no orange or separate magenta, so `orange` is a mix of red and yellow, and `magenta` a mix of red and ANSI magenta.

### Grok Night

| Role | Color |
|---|---|
| `background` | <img src="https://placehold.co/14x14/141414/141414.png" /> `#141414` |
| `backgroundSecondary` | <img src="https://placehold.co/14x14/242424/242424.png" /> `#242424` |
| `text` | <img src="https://placehold.co/14x14/E1E1E1/E1E1E1.png" /> `#E1E1E1` |
| `selection` | <img src="https://placehold.co/14x14/E0AF68/E0AF68.png" /> `#E0AF68` |
| `loader` | <img src="https://placehold.co/14x14/E0AF68/E0AF68.png" /> `#E0AF68` |
| `red` | <img src="https://placehold.co/14x14/F7768E/F7768E.png" /> `#F7768E` |
| `orange` | <img src="https://placehold.co/14x14/EC927B/EC927B.png" /> `#EC927B` |
| `yellow` | <img src="https://placehold.co/14x14/E0AF68/E0AF68.png" /> `#E0AF68` |
| `green` | <img src="https://placehold.co/14x14/9ECE6A/9ECE6A.png" /> `#9ECE6A` |
| `blue` | <img src="https://placehold.co/14x14/7AA2F7/7AA2F7.png" /> `#7AA2F7` |
| `purple` | <img src="https://placehold.co/14x14/BB9AF7/BB9AF7.png" /> `#BB9AF7` |
| `magenta` | <img src="https://placehold.co/14x14/D988C2/D988C2.png" /> `#D988C2` |

Source: [`grok-night.json`](grok-night.json)

### Grok Day

| Role | Color |
|---|---|
| `background` | <img src="https://placehold.co/14x14/F5F5F5/F5F5F5.png" /> `#F5F5F5` |
| `backgroundSecondary` | <img src="https://placehold.co/14x14/DEDEDE/DEDEDE.png" /> `#DEDEDE` |
| `text` | <img src="https://placehold.co/14x14/262626/262626.png" /> `#262626` |
| `selection` | <img src="https://placehold.co/14x14/7D4BC6/7D4BC6.png" /> `#7D4BC6` |
| `loader` | <img src="https://placehold.co/14x14/7D4BC6/7D4BC6.png" /> `#7D4BC6` |
| `red` | <img src="https://placehold.co/14x14/CD3048/CD3048.png" /> `#CD3048` |
| `orange` | <img src="https://placehold.co/14x14/B8532D/B8532D.png" /> `#B8532D` |
| `yellow` | <img src="https://placehold.co/14x14/A27612/A27612.png" /> `#A27612` |
| `green` | <img src="https://placehold.co/14x14/378E23/378E23.png" /> `#378E23` |
| `blue` | <img src="https://placehold.co/14x14/2F64D2/2F64D2.png" /> `#2F64D2` |
| `purple` | <img src="https://placehold.co/14x14/7D4BC6/7D4BC6.png" /> `#7D4BC6` |
| `magenta` | <img src="https://placehold.co/14x14/A53E87/A53E87.png" /> `#A53E87` |

Source: [`grok-day.json`](grok-day.json)

## License

[MIT](LICENSE). Unofficial project, not affiliated with xAI or Raycast. Color schemes from [iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes) (MIT).
