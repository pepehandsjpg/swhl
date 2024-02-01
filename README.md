i made this theme just for myself

there are no colors for textmate/semantic tokens b/c i prefer to customize them directly in my settings b/c usually i highlight only 4 groups (tokens): keywords, types, constants, strings

i might add some colors in future

it's pretty minimal and it might be broken for some of vsc ui elements

if you want you can leave an issue [here](https://github.com/hushyael/swhl/issues)

i personally recommend to disable all of the annoying "MODERN IDE" ui shit like activity bar, status bar, sidebar action icons, minimap, scrollbars, guides etc...
```
{
    "window.commandCenter": false,
    "workbench.layoutControl.enabled": false,
    "workbench.tree.renderIndentGuides": "none",
    "workbench.editor.showTabs": "single",
    "editor.minimap.enabled": false,
    "editor.unicodeHighlight.invisibleCharacters": false,
    "editor.unicodeHighlight.ambiguousCharacters": false,
    "editor.scrollbar.verticalScrollbarSize": 0,
    "editor.bracketPairColorization.enabled": false,
    "editor.folding": false,
    "editor.scrollbar.vertical": "hidden",
    "editor.scrollbar.horizontal": "hidden",
    "editor.guides.indentation": false,
}
```
