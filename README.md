# fontconfig-penultimate

fontconfig-penultimate is a collection of sensible defaults for Fontconfig that requires no configuration.
It is a minimalist fork of fontconfig-ultimate that retains the metric and family aliases, but eschews extensive substitutions and selective rendering.

## Requirements

- Fontconfig
- FreeType

No patches to FreeType are required, but FreeType 2.7 or later is recommended for best rendering.

## Installation

```
# Clone this repository to ./fontconfig-penultimate first.

# Remove the existing Fontconfig settings (optional).
# Saves files matching 0*.conf that conventionally contain system-specific paths.
$ rm /etc/fonts/conf.d/[1-9]*.conf
# Install fontconfig-penultimate.
$ cp ./fontconfig-penultimate/*.conf /etc/fonts/conf.d
```
