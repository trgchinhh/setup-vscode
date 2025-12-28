# My VSCode Setup

## I. Extension 
- Python, Java, C++ tải exensions của Microsoft - RedHat
- HTML, Markdown tải extension live-server và Markdown Preview
- Theme: Atom One Dark, One Dark Pro, Dracula, ...
- Gợi ý:
  + C++: dùng Clangd tắt gợi ý mặc định của VSCode
  + Ngôn ngữ khác tự động có gợi ý nhanh
- Icon folder/ file: Material Icon Theme
- Chạy code: Runner Code
- Terminal mở nhanh trong VSCode: Terminal (Jun Han) 

## II. Setting User Json
### 1) Setting mặc định cơ bản 
```
"code-runner.runInTerminal": true,
"C_Cpp.default.compilerPath": "C:\\msys64\\ucrt64\\bin\\gcc.exe",
"python.defaultInterpreterPath": "C:\\Users\\ADMIN\\AppData\\Local\\Programs\\Python\\Python313\\python.exe",
"debug.onTaskErrorss": "debugAnyway",
"explorer.confirmDelete": false,
"grunt.autoDetect": "on",
"window.customTitleBarVisibility": "windowed",
"workbench.layoutControl.enabled": false,
"redhat.telemetry.enabled": true,
"workbench.editorAssociations": {
    "*.exe": "default",
    "*.class": "decompiled.javaClass"
},
"codesnap.pixelRatio": 3, // theme file 
"terminal.integrated.fontFamily": "JetBrains Mono, Consolas, 'Courier New', monospace", 
"terminal.integrated.fontSize": 14, // size chữ terminal
"terminal.integrated.cursorStyle": "line",
"editor.parameterHints.enabled": false,
"editor.fontWeight": "300",
"terminal.integrated.defaultProfile.windows": "Windows PowerShell",
"editor.fontFamily": "JetBrains Mono, Consolas, 'Courier New', monospace",
"editor.fontSize": 14, // size chữ code
"code-runner.saveFileBeforeRun": true,
"terminal.external.windowsExec": "C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
"workbench.iconTheme": "material-icon-theme",
```

### 2) Setting tắt gợi ý mặc định của VSCode
```
"C_Cpp.intelliSenseEngine": "disabled",
```

### 3) Setting tắt tự động update extension
```
"extensions.autoUpdate": false,
```

### 4) Setting scroll và code mượt hơn (kể cả máy yếu)
```
"editor.smoothScrolling": true,
"terminal.integrated.smoothScrolling": true,
"editor.mouseWheelScrollSensitivity": 2.0,
"editor.fastScrollSensitivity": 4,
"editor.scrollBeyondLastLine": true,
"editor.cursorSmoothCaretAnimation": "on",
```

### 5) Setting custom màu biến xanh -> trắng (theme mặc định) 
```
"editor.tokenColorCustomizations": {
    "[Default Dark Modern]": {
        "textMateRules": [
            {
                "scope": [
                    "variable",
                    "variable.other.readwrite",
                    "variable.other.constant"
                ],
                "settings": {
                    "foreground": "#cccccc",
                }
            }
        ]
    }
},
```

## III. Screenshot

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/966e9bee-f2f5-487f-b3c3-513a4a2e628e" />
