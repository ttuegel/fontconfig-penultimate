# fontconfig-penultimate

fontconfig-penultimate is a minimalist fork of fontconfig-ultimate
providing metric and family aliases and a few font-specific selective rendering settings;
it does not provide font substitutions or detailed selective rendering configurations.
It has no configurable parts,
but it also will not override user configurations:
fontconfig-penultimate provides a sensible and complete set of defaults,
nothing more or less.

## Requirements

- Fontconfig
- FreeType

No patches to FreeType are required, but FreeType 2.7 or later is recommended for best rendering.

## Installation

Clone this repository and add this to your existing `fonts.conf`:
```
<include>path/to/cloned/repository</include>
```
