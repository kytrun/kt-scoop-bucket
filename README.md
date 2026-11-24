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
| `duckle` | [slothflowlabs/duckle](https://github.com/slothflowlabs/duckle) | An open-source ETL platform for authoring pipelines on a canvas, in Python, or SQL and running them on your own infrastructure. |
| `google-java-format` | [google/google-java-format](https://github.com/google/google-java-format) | A Java formatter that reformats Java source code to comply with Google Java Style. |
| `leantoken` | [morluto/leantoken](https://github.com/morluto/leantoken) | Code intelligence for agents: find the code that matters and keep your context window and tokens lean. |
| `mayoi` | [sorrycc/Mayoi](https://github.com/sorrycc/Mayoi) | A small, fast code editor written in Go with a native GPU UI. |
| `mdnote` | [Lahai-Roi/MDNote](https://github.com/Lahai-Roi/MDNote) | A fast, lightweight Markdown and TXT editor for Windows. |
| `nomo-scholar` | [ZeroDevi1/nomo-mygo](https://github.com/ZeroDevi1/nomo-mygo) | A local-first academic writing editor for Markdown, LaTeX, and Typst. |
| `quiet-md` | [s1dashu/quiet-md](https://github.com/s1dashu/quiet-md) | Fast, quiet notes that live on your computer. A native notes app built with Rust + GPUI. |
| `rustrest` | [SojebSikder/rustrest](https://github.com/SojebSikder/rustrest) | An open-source, cross-platform native API testing platform written in Rust. |
| `zpad` | [helloxz/zpad](https://github.com/helloxz/zpad) | A cross-platform, natively rendered text editor without Git, AI, or WebView. |

Each manifest uses `checkver` + `autoupdate`, so new upstream releases are picked up automatically by the scheduled Excavator workflow (`.github/workflows/excavator.yml`).
