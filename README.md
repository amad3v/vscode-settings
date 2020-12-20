# VSCodium Settings

## Scope

Settings backup containing:

- List of extensions
- User settings
- Custom snippets


## Switch to MS Marketplace

file to change:

```bash
cd /usr/share/vscodium-bin/resources/app/product.json
```

section to replace:

```json
"extensionsGallery": {
    "serviceUrl": "https://open-vsx.org/vscode/gallery",
    "itemUrl": "https://open-vsx.org/vscode/item"
  }
```

with

```json
"extensionsGallery": {
   "serviceUrl": "https://marketplace.visualstudio.com/_apis/public/gallery",
   "itemUrl": "https://marketplace.visualstudio.com/items"
 }
```

## Links

<img src="https://github.com/VSCodium/vscodium/raw/master/src/resources/linux/code.png" style="zoom:4%;" />

[VSCodium keyboard shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf)

![](https://www.jetbrains.com/favicon-32x32.png)

[IntelliJ keyboard shortcuts](https://resources.jetbrains.com/storage/products/webstorm/docs/WebStorm_ReferenceCard_Windows_Linux.pdf)
