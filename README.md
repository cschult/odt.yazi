# odt.yazi

Plugin for [Yazi](https://github.com/sxyazi/yazi) to preview libreoffice writer (.odt) files with [odt2txt](https://github.com/dstosberg/odt2txt).

To install, use vcsh repo yazi.

`~/.config/yazi/plugins/`:

```bash
git clone https://github.com/Reledia/glow.yazi.git
```

then include it in your `yazi.toml` to use:

```toml
[plugin]
prepend_previewers = [
  { mime = "application/vnd.oasis.opendocument.text", run = "odt" },
]
```
