# Slatehollow

A theme that gets out of the way. Clean surfaces, minimal yet subtle border lines, five syntax colours. Enough to tell your code apart, not enough to distract you from it. Ships with a light variant — Slatehollow Light.

## Slatehollow Dark OLED

Same surfaces, same five colours — tuned for OLED panels. Wide-gamut displays and deep blacks make the original accents feel vivid, so this variant pulls accent saturation back by about a fifth and dims the body text a touch. Hues stay put, so every colour still means the same thing.

Reach for it when Slatehollow Dark looks oversaturated — typically wide-gamut OLED laptops on Windows without colour management. On colour-managed screens (macOS, or Windows with automatic colour management), the original Dark already renders as intended.

## Philosophy

Borders (separator lines) only appear where colour can't do the job alone. Everything else relies on surface depth — each zone (editor, sidebar, tabs, status bar) sits at its own distinct level. You know where you are without being told.

Syntax colours are intentional and minimal:

- **Blue** — functions, constructors
- **Sage green** — strings
- **Amber** — constants, numbers
- **Purple** — keywords
- **Dusty rose** — properties (the "pay attention" colour, used sparingly)

Everything else — variables, punctuation, namespaces — fades into the background. Structural, not semantic.

Five colours is a constraint, not a limitation. When every token is a different colour, your brain stops using colour as signal. We'd rather you read the code.

## Install

Open the Command Palette:

**macOS**

```text
cmd + shift + p → Extensions: Install Extensions → search "Slatehollow"
```

**Windows/Linux**

```text
ctrl + shift + p → Extensions: Install Extensions → search "Slatehollow"
```

Or install directly from the Extensions sidebar.

Configure your theme:

```json
{
  "workbench.colorTheme": "Slatehollow Dark" // or "Slatehollow Dark OLED"
}
```

---

Made by [Amsh](https://github.com/ams-sth)
