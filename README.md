<h1>VS Code: configuration for the Iron Spring PL/I compiler</h1>

The core of this configuration is a JSON task which enables following funcionalities for the compiler:

- Compile  
- Link edit  
- Execute
  
Further funcionality: if the compile produces error(s), the next steps will not be executed, and the compile listing will be shown.

The structure of the directory:

```
├── .vscode
│   ├── tasks.json
│   └── tasks.json.old
├── SPEC.md
└── src
    ├── benchmark.exe
    ├── benchmark.lst
    ├── benchmark.obj
    ├── benchmark.pli
    ├── leven.exe
    ├── leven.lst
    ├── leven.obj
    └── leven.pli
```

In .vscode only "tasks.json" is relevant. 
"src" contains some samples. 
"SPEC.md" is an AI-generated help for the sample programs (not relevant for the project).
