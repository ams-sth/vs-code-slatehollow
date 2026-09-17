# Slatehollow

A theme that gets out of the way. Clean surfaces, minimal yet subtle border lines, five syntax colours. Enough to tell your code apart, not enough to distract you from it. Ships with a light variant — Slatehollow Light.

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
  "workbench.colorTheme": "Slatehollow Dark"
}
```

---

Made by [Amsh](https://github.com/ams-sth)
