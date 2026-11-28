# kt-scoop-bucket

Personal [Scoop](https://scoop.sh) bucket maintained by [kytrun](https://github.com/kytrun).

## Usage

```powershell
scoop bucket add kt https://github.com/kytrun/kt-scoop-bucket
scoop install kt/<app>
```

## Apps

| App | Source | Description |
| --- | --- | --- |
| `ai-memory` | [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) | Long-term memory for agent coding CLIs and handoff between different agent vendors. |
| `bsk` | [Tencent/BrowserSkill](https://github.com/Tencent/BrowserSkill) | Connect your AI agent to the browser you already use. |
| `codedb` | [justrach/codedb](https://github.com/justrach/codedb) | Code intelligence for your coding agent, built in Zig and connected over MCP. |
| `codeg-server` | [spacering-net/codeg](https://github.com/spacering-net/codeg) | Self-hosted server for Codeg, a collaborative multi-agent AI coding workspace that aggregates sessions from Claude Code, Codex, OpenCode, and others. |
| `duckle` | [slothflowlabs/duckle](https://github.com/slothflowlabs/duckle) | An open-source ETL platform for authoring pipelines on a canvas, in Python, or SQL and running them on your own infrastructure. |
| `elyoffice` | [ELY-Open-Source/ElyOffice](https://github.com/ELY-Open-Source/ElyOffice) | An offline-first office suite (ElyMail, ElyDoc, ElyTable, ElyShow, ElyPDF, ElyMark, ElyTree) built in Rust and GPUI. |
| `google-java-format` | [google/google-java-format](https://github.com/google/google-java-format) | A Java formatter that reformats Java source code to comply with Google Java Style. |
| `kubeui` | [IvanJosipovic/KubeUI](https://github.com/IvanJosipovic/KubeUI) | A Kubernetes user interface for managing clusters and resources. |
| `leantoken` | [morluto/leantoken](https://github.com/morluto/leantoken) | Code intelligence for agents: find the code that matters and keep your context window and tokens lean. |
| `mayoi` | [sorrycc/Mayoi](https://github.com/sorrycc/Mayoi) | A small, fast code editor written in Go with a native GPU UI. |
| `mdnote` | [Lahai-Roi/MDNote](https://github.com/Lahai-Roi/MDNote) | A fast, lightweight Markdown and TXT editor for Windows. |
| `nomo-scholar` | [ZeroDevi1/nomo-mygo](https://github.com/ZeroDevi1/nomo-mygo) | A local-first academic writing editor for Markdown, LaTeX, and Typst. |
| `pay-respects` | [iffse/pay-respects](https://github.com/iffse/pay-respects) | A fast, rule-based command-line corrector that suggests and runs fixes for your failed commands. |
| `quiet-md` | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Fast, quiet notes that live on your computer. A native notes app built with Rust + GPUI. |
| `rustrest` | [SojebSikder/rustrest](https://github.com/SojebSikder/rustrest) | An open-source, cross-platform native API testing platform written in Rust. |
| `thinkterm` | [RoversX/ThinkTerm](https://github.com/RoversX/ThinkTerm) | A workspace-first terminal with a built-in multiplexer that keeps your sessions running after you close the window. |
| `tomoru` | [ACAne0320/Tomoru](https://github.com/ACAne0320/Tomoru) | Live bilingual subtitles for anything your computer plays: videos, streams, games, and meetings. |
| `wake` | [iAmCorey/Wake](https://github.com/iAmCorey/Wake) | A native desktop app that gathers every coding-agent session on your machine into one place. |

Each manifest uses `checkver` + `autoupdate`, so new upstream releases are picked up automatically by the scheduled Excavator workflow (`.github/workflows/excavator.yml`).
