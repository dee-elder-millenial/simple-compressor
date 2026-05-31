# Contributing

Contributions are welcome.

## Good changes to propose

- Clear bug fixes
- Better default settings
- Compressor behavior improvements
- Metering improvements
- Documentation fixes
- Preset suggestions

## Development notes

This project is intentionally simple. The main plugin lives in:

```text
Effects/Simple Compressor.jsfx
```

Please keep the plugin dependency-free and readable. If a DSP change is subtle, include a short note explaining what changed and why.

## Testing

Before proposing changes:

1. Copy the JSFX file into REAPER's `Effects` folder.
2. Rescan plugins or restart REAPER.
3. Load `Simple Compressor` on a track.
4. Check that all sliders respond smoothly.
5. Test with drums, vocals, bass, and full-mix material.
6. Listen for clicks, pumping, silence, unexpected clipping, and zipper-like artifacts.

## Pull requests

Please include:

- A short summary of the change
- Any listening or compatibility notes
- Screenshots only if the change affects visible plugin UI
