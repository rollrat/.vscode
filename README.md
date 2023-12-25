# .vscode

`ctrl + shift + p => key json`

```json
// 키 바인딩을 이 파일에 넣어서 기본값 재정의
[
  {
    "key": "ctrl+n",
    "command": "explorer.newFile",
    "when": "!editorFocus"
  },
  {
    "key": "ctrl+shift+n",
    "command": "explorer.newFolder",
    "when": "!editorFocus"
  },
  {
    "key": "ctrl+`",
    "command": "workbench.action.terminal.focus"
  },
  {
    "key": "ctrl+`",
    "command": "workbench.action.focusActiveEditorGroup",
    "when": "terminalFocus"
  },
    {
        "key": "ctrl+tab",
        "command": "workbench.action.nextEditor"
    },
    {
        "key": "ctrl+shift+tab",
        "command": "workbench.action.previousEditor"
    },
{ "key" : "ctrl+a", "command" : "editor.action.selectAll",
"when" : "editorTextFocus && !inDebugRepl" },
{ "key" : "ctrl+c", "command" : "editor.action.clipboardCopyAction",
"when" : "editorTextFocus && !inDebugRepl && vim.mode != 'Insert'" },
{ "key" : "ctrl+v", "command" : "editor.action.clipboardPasteAction",
"when" : "editorTextFocus && !inDebugRepl && vim.mode == 'Insert'" },
{ "key" : "ctrl+x", "command" : "editor.action.clipboardCutAction",
"when" : "editorTextFocus && !inDebugRepl" },
{
  "key": "ctrl+p",
  "command": "workbench.action.quickOpen"
},
]
```
