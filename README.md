# REAPER JSFX Syntax Highlighter

Syntax highlighting for REAPER JSFX / EEL2 effects scripting language.

## Features

Covers the full JSFX / EEL2 surface:

- **Section markers** — `@init`, `@slider`, `@block`, `@sample`, `@gfx`, `@serialize`
- **Header directives** — `desc:`, `slider1:`, `options:`, `in_pin:`, `out_pin:`, etc.
- **Keywords** — `function`, `while`, `loop`, `local`, `instance`, `global`, `this`
- **Built-in functions** — math, memory, stack, atomic, FFT/MDCT, MIDI, file I/O, string, GFX, host (~90 functions)
- **GFX / mouse variables** — `gfx_r`, `gfx_x`, `mouse_cap`, etc.
- **Special variables** — `spl0`–`spl63`, `srate`, `num_ch`, `tempo`, `play_state`, transport, PDC, `ext_*`, `reg00`–`reg99`
- **Literal formats** — `$pi`, `$phi`, `$e`, `$xFF`, `$'c'`, `$~n`, `0xFF`
- **Operators** — arithmetic, bitwise, comparison, logical, ternary, assignment
- **Preprocessor blocks** — `<? ?>`
- **String variables** — `#name` prefix
- **Namespace access** — `_global.*`, `this.*`
- **Comments** — `//` and `/* */`

## Usage

Files with the `.jsfx` extension are automatically detected. You can also set the language mode manually via the status bar.
