# GitHub Profile Visual Assets

This directory contains the visuals used in [Kaelinda's profile README](../README.md).

| File | Description |
| --- | --- |
| `hero-dark.svg` | Dark-mode banner (1200 × 420) |
| `hero-light.svg` | Light-mode banner (1200 × 420) |
| `aicoder-mark.svg` | AICoder's approved A symbol, reproduced from the owner's brand source |

## Design decisions

- Static, self-hosted SVG; no analytics, third-party statistics endpoint, script or remote font dependency.
- GitHub `<picture>` switches the banner with the viewer's color scheme.
- The AICoder mark is the approved **A** brand symbol, not the experimental conversation-bubble icon.
- All repositories featured in the README were verified public when authored. Do not add private repository names or personal contact details without checking publication intent.
- The SVG has an accessible title/description, while the README keeps identity and project descriptions available as text outside the image.
- The identity lockup follows **AICoder / AI 码人士** naming and the brand motto **用 AI，把想法变成作品。**
- If a rendering issue appears, `hero-light.svg` serves as the image fallback.

Changes should maintain readable contrast in both themes and keep the headline clear at GitHub profile widths.
