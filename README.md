# aris-nina-plugin-assets

Public static assets for the ARIS NINA plugin. This repo exists because the main ARIS repo is private — NINA needs to fetch plugin images from a public HTTPS URL at runtime, so the logos live here.

## Contents

- `aris-logo-256.png` — ARIS logo, 256 px tall, transparent background, used as the `FeaturedImageURL` in the plugin's `AssemblyInfo.cs`
- `imaging-main.png` — the Imaging screen, used as the `ScreenshotURL`
- `sequencing-main.png` — the Sequence Builder, used as the `AltScreenshotURL`

## Usage

```csharp
[assembly: AssemblyMetadata("FeaturedImageURL", "https://raw.githubusercontent.com/arisastro/aris-nina-plugin-assets/main/aris-logo-256.png")]
```

## License

Same as the ARIS project.
