I managed some of the libraries by myself instead of through npm to reduce the overall file size.

**Versions**

```json
{
  "font-awesome": "6.4.2", // Download from here: https://fontawesome.com/download
  // Fontawesome cheatsheet is available here: https://kapeli.com/cheat_sheets/Font_Awesome.docset/Contents/Resources/Documents/index
  "katex": "v0.16.22", // Only keep the css and fonts files.
  "mermaid": "11.9.0", // https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js
  "reveal": "4.6.0",
  "wavedrom": "3.3.0" // - https://cdn.jsdelivr.net/npm/wavedrom@3.3.0/wavedrom.min.js
}
```

_Attention_: Need to remove `font: inherit;` from `reveal.css`. Otherwise, `KaTeX` and `MathJax` will have trouble rendering. Also don't forget to add the empty file `none.css`.

_Attention_: Don't forget to modify the `dependentLibraryMaterials` variable in `markdown-engine.ts`

_Attention_: NOTE: We have to disable the `_self = window` line in `prism.js` to make it work with VSCode web extension.
