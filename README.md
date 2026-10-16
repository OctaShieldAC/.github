# OctaShieldAC/.github

Organization-wide GitHub assets for [OCTA Shield](https://octashield.ac/en).

| Path | Purpose |
|:--|:--|
| `profile/README.md` | Rendered on <https://github.com/OctaShieldAC> as the organization profile. |
| `assets/hero.svg` | Animated hero banner: brand lockup, radar sweep, stats. |
| `assets/detections.svg` | Animated illustrative detection feed and pipeline. |
| `assets/footer.svg` | Closing CTA with watermark lockup. |
| `assets/divider.svg` | Section divider. |

## Publish

1. Create a **public** repository named exactly `.github` under the `OctaShieldAC` organization.
2. Push this directory to its default branch (`main`).
3. Open <https://github.com/OctaShieldAC>. GitHub renders `profile/README.md` automatically.

Image URLs in `profile/README.md` point to `https://raw.githubusercontent.com/OctaShieldAC/.github/main/assets/...`. If the default branch is not `main`, update those URLs.

## Brand tokens used

Extracted from `octashield.ac`.

| Token | Value |
|:--|:--|
| Primary | `#F43D16` (hover `#FF7658`, gradient `#F94C2B → #FF2B51`) |
| Text | `#F3F3F3` / muted `#8D8D8D` |
| Surfaces | `#000000` / `#0A0A0A` / `#1A1A1A` |
| Type | Unageo (sans), PP Editorial Old (serif). SVGs fall back to system fonts because `<img>`-embedded SVG cannot load web fonts. |

The logo mark and the `SHIELD` wordmark are the vector paths from the site's `logo-footer.svg`, embedded verbatim.

## Notes

- All SVGs are self-contained (inline CSS + SMIL animations, no external resources), which GitHub's image proxy (camo) allows.
- Animations respect nothing beyond CSS/SMIL; GitHub's "reduce motion" setting does not affect `<img>` SVGs.
