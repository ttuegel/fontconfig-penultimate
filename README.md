# fontconfig-penultimate

fontconfig-penultimate is a collection of sensible defaults for Fontconfig that requires no configuration.
It is a minimalist fork of fontconfig-ultimate that retains the metric and family aliases, but eschews extensive substitutions and selective rendering.

## Requirements

- Fontconfig
- FreeType

No patches to FreeType are required, but FreeType 2.7 or later is recommended for best rendering.

## Installation

Clone this repository and add this to your existing `fonts.conf`:
```.xml
<include>path/to/cloned/repository</include>
```
