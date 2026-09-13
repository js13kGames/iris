---
directors_cut: https://sirius-iris.netlify.app/
# See github.com/js13kGames/hello-world for supported frontmatter
---

**IRIS**

The earth split open and Samanta was left on the far side of the chasm. Sergio
wants to go after her. On the way a shadow follows him: a unicorn who lost her
colours. Sergio will help her.

Seven levels, one colour each.

### Controls

| Key | Action |
|---|---|
| **A** / **D** or arrows | Move |
| **W** or space | Jump |
| **M** | Shoot |
| **N** | Mute |
| **R** | Restart level |
| **Enter** | Continue |

### Details

- **Generated levels:** the generator derives from the physics (gravity, jump
  impulse, speed) the real distance a jump covers, and never creates a gap
  wider than that.
- **No asset files:** no images, no sounds, no libraries. The sprites are text
  strings and the background hills are sums of sines.
- **Audio generated with Web Audio.**
- Iris follows your exact path, jumps included.