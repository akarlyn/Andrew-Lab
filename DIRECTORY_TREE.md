---
id: andrew-lab-directory-tree
title: Andrew Lab Directory Tree
type: architecture
status: canonical
confidence: high
owner: Andrew S. Karlyn
created: 2026-07-20
updated: 2026-07-20
version: 0.1.0
---

# Directory Tree

```text
Andrew-Lab/
├── README.md
├── MANIFEST.md
├── REPOSITORY_RULES.md
├── DIRECTORY_TREE.md
├── VALIDATION_CHECKLIST.md
├── CHANGELOG.md
├── .gitignore
├── experiments/
│   ├── active/
│   ├── validated/
│   └── archived/
├── prototypes/
│   ├── agents/
│   ├── workflows/
│   ├── prompts/
│   └── applications/
├── research/
│   ├── notes/
│   ├── syntheses/
│   └── open-data/
├── publications/
│   ├── articles/
│   ├── presentations/
│   └── public-frameworks/
├── datasets/
│   ├── synthetic/
│   └── open/
├── notebooks/
├── templates/
├── governance/
├── build-ledger/
└── archive/
```

## Boundary rule

Andrew Lab stores only public-safe experimentation and released outputs. Private source material remains in Andrew OS or Kindora OS.

## Git directory rule

Git does not track empty folders. Add a `.gitkeep` file when an empty directory needs to appear before its first substantive asset is added.
