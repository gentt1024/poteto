# poteto

A compact cartoon companion inspired by Lauren Tan / poteto, with round glasses, dark-brown hair, dark clothes and a roasted sweet potato. Kitchen helpers appear in selected states. The character's name is always **poteto**. The work loop depicts thought, a short cue and a helper response.

Publisher and creator credit: [gentt1024](https://github.com/gentt1024).

![All animation states and look directions](previews/all-states.gif)

![Chief work loop](previews/work.gif)

## Downloads

- [v1.0.0 Release](https://github.com/gentt1024/poteto/releases/tag/v1.0.0)
- [Latest poteto.zip](https://github.com/gentt1024/poteto/releases/latest/download/poteto.zip)
- [Latest spritesheet.png](https://github.com/gentt1024/poteto/releases/latest/download/spritesheet.png)

The ZIP contains only `pet.json` and `spritesheet.png` at its root. The first public release is **v1.0.0**. `spriteVersionNumber: 2` identifies the atlas layout version.

## Outfit skins

These four completed October 13, 2026 skins keep the original actions and helper crew. Each package has its own identity and contains only `pet.json` and `spritesheet.png` at the ZIP root. The original **v1.0.0** release remains available above.

| Outfit | Skin | Install package | Animation preview |
| --- | --- | --- | --- |
| B | Green hoodie | [Download ZIP](https://raw.githubusercontent.com/gentt1024/poteto/main/skins/green-hoodie/poteto-green-hoodie.zip) | [Preview](skins/green-hoodie/preview.gif) |
| C | Yellow raincoat | [Download ZIP](https://raw.githubusercontent.com/gentt1024/poteto/main/skins/yellow-raincoat/poteto-yellow-raincoat.zip) | [Preview](skins/yellow-raincoat/preview.gif) |
| D | Cream chef | [Download ZIP](https://raw.githubusercontent.com/gentt1024/poteto/main/skins/cream-chef/poteto-cream-chef.zip) | [Preview](skins/cream-chef/preview.gif) |
| E | Greige sleeveless | [Download ZIP](https://raw.githubusercontent.com/gentt1024/poteto/main/skins/greige-sleeveless/poteto-greige-sleeveless.zip) | [Preview](skins/greige-sleeveless/preview.gif) |

To install a skin, download its ZIP, extract the two files, and place them together in `~/.codex/pets/<skin-id>/`, where `<skin-id>` matches the `id` in its `pet.json` (for example, `poteto-green-hoodie`). Back up an existing folder first, then reopen Codex. Compatibility with your Codex version should be checked as described below.

## Contents

- Nine standard animation states plus sixteen look directions, 73 valid frames.
- Transparent RGBA PNG, 1536 × 2288, an 8 × 11 grid with 192 × 208 cells.
- The work loop is about 0.82 seconds, brisk and stepped. Some older states retain color/style differences; fine details are weaker at 64px.

## Local installation

1. Download and extract `poteto.zip` to obtain the two root files.
2. Following the [community format reference](https://codexpet.xyz/spec/), place both files in `~/.codex/pets/poteto/`; back up an existing folder first.
3. Reopen Codex and look for `poteto` in the pet interface available in your version.

JSON, image decoding, transparency, dimensions, consecutive populated frames and package contents have been checked locally. Official manifest schema compatibility and an actual Codex desktop import have not been independently verified; check these with your target version.

## Sources and rights

This is an unofficial, AI-assisted fan-inspired work. No endorsement from Lauren Tan, OpenAI or the reference artists is claimed. Rights holders, likeness permissions and redistribution permissions for the helper references remain unconfirmed. Public availability does not mean third-party rights have been cleared, and no MIT, CC BY or other open asset license is granted. See [CREDITS.md](CREDITS.md).
