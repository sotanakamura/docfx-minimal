# DocFX Minimal Template
DocFX Minimal Template is a minimal theme derived from default template.

## Features

* Full width (Container-fulid in Bootsrtap)
* Minimal white pages
* Simple interface without a breadcrumb
* Table of contents aligned left

## Installation

1. Download source files of DocFX minimal template as a zip file from [Here](https://github.com/sotanakamura/docfx-minimal/archive/refs/heads/main.zip) or [GitHub](https://github.com/sotanakamura/docfx-minimal).
1. Create `templates` folder in your docfx project folder.
1. Extract the zip file and copy `minimal` folder into the `templates` folder.
1. Apply minimal template by adding `minimal` in your `docfx.json`.
```
"build": {
    "template": [
      "default","templates/minimal"
    ],
}
```