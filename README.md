# CLI-Anything on Windows Guide

Windows(WSL2) 환경에서 [CLI-Anything](https://github.com/HKUDS/CLI-Anything)을 사용하는 방법을 시각화한 인터랙티브 대시보드.

**Live:** https://cli-anything-windows-guide.vercel.app

## What is CLI-Anything?

GUI 소프트웨어(GIMP, Blender, LibreOffice 등)를 AI Agent가 제어할 수 있는 CLI로 자동 변환하는 도구. HKUDS(홍콩대 Data Intelligence Lab) 개발.

## Dashboard Features

| Section | Interaction |
|---------|-------------|
| KPI Metrics | Scroll-triggered count-up animation, circular progress ring |
| Workflow Pipeline | Sequential node activation with pulse animation |
| 7-Phase Pipeline | Gradient progress bar fills (blue to purple) |
| MECE Logic Tree | Click to expand/collapse 5 branches |
| Architecture Diagram | Layered visualization (Windows > WSL2 > Software) |
| Compatibility Matrix | Proportional animated bars for 10 software (1,508 tests) |
| Command Tabs | 5-tab terminal-style code windows |

## Tech

- Single self-contained `index.html` (zero external dependencies)
- Dark theme dashboard (GitHub/Linear/Vercel aesthetic)
- IntersectionObserver scroll animations
- Accessible: `aria-hidden` SVGs, typed buttons, semantic HTML
- Deployed on Vercel (static)

## MECE Structure

```
CLI-Anything Windows
├── 1. Environment  (WSL2, Python, Node.js)
├── 2. Installation (Claude Code, Plugin, Target Software)
├── 3. Generation   (/cli-anything 7-phase pipeline)
├── 4. Usage        (CLI, REPL, JSON output)
└── 5. Troubleshooting (paths, GUI, permissions)
```

## Credits

- [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) - Original project
- HKU Data Intelligence Lab
