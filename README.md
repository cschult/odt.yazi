# odt.yazi

Plugin for [Yazi](https://github.com/sxyazi/yazi) to preview libreoffice
writer (.odt) files with [odt2txt](https://github.com/dstosberg/odt2txt).

To install, clone the repo inside your `~/.config/yazi/plugins/`

`~/.config/yazi/plugins/`:

```bash
git clone https://github.com:cschult/odt.yazi.git
```

or install with ya:

`~/.config/yazi/plugins/`:

```bash
ya pack --add cschult/odt
```

then include it in your `yazi.toml` to use:

```toml
[plugin]
prepend_previewers = [
  { mime = "application/vnd.oasis.opendocument.text", run = "odt" },
]
```
