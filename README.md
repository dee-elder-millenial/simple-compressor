# Simple Compressor

A simple stereo compressor for [REAPER](https://www.reaper.fm/), packaged as a native JSFX effect.

Simple Compressor is designed to be easy to use, easy to read, and easy to modify. It uses a stereo-linked feed-forward detector with threshold, ratio, attack, release, soft knee, makeup gain, and parallel mix controls.

## Features

- Native REAPER JSFX plugin, no VST/AU build step required
- Stereo-linked compression
- Threshold, ratio, attack, release, and soft knee controls
- Makeup gain, dry/wet mix, input trim, and output trim
- Custom gain-reduction meter
- Plain-text source that can be copied, modified, and shared
- MIT licensed

## Download

Download the plugin file directly:

[Effects/Simple Compressor.jsfx](Effects/Simple%20Compressor.jsfx)

Or download the repository as a ZIP from GitHub:

`Code > Download ZIP`

## Install

1. In REAPER, choose `Options > Show REAPER resource path in explorer/finder`.
2. Open the `Effects` folder.
3. Copy `Effects/Simple Compressor.jsfx` into that folder.
4. In REAPER, open the FX browser.
5. Choose `FX > Scan for new plugins`.
6. Search for `Simple Compressor` under `JS`.

Important: JSFX files go in REAPER's `Effects` folder, not `UserPlugins`. `UserPlugins` is for REAPER extension binaries.

More detailed installation notes are in [INSTALL.md](INSTALL.md).

## Controls

| Control | What it does |
| --- | --- |
| `Input` | Adjusts level before compression. |
| `Threshold` | Sets the level where compression begins. |
| `Ratio` | Sets how strongly levels above the threshold are reduced. |
| `Attack` | Controls how quickly compression reacts. |
| `Release` | Controls how quickly compression relaxes. |
| `Knee` | Smooths the transition around the threshold. |
| `Makeup` | Adds gain after compression. |
| `Mix` | Blends compressed and uncompressed signal for parallel compression. |
| `Output` | Final gain trim. |

## Development

The plugin is a single JSFX file:

`Effects/Simple Compressor.jsfx`

To edit it, change the file in your REAPER `Effects` folder or copy this repository version there after each edit. REAPER can reload JSFX from the FX window after rescanning or reopening the effect.

## License

MIT. See [LICENSE](LICENSE).
