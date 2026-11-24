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
| `duckle` | [slothflowlabs/duckle](https://github.com/slothflowlabs/duckle) | An open-source ETL platform for authoring pipelines on a canvas, in Python, or SQL and running them on your own infrastructure. |
| `mayoi` | [sorrycc/Mayoi](https://github.com/sorrycc/Mayoi) | A small, fast code editor written in Go with a native GPU UI. |
| `mdnote` | [Lahai-Roi/MDNote](https://github.com/Lahai-Roi/MDNote) | A fast, lightweight Markdown and TXT editor for Windows. |
| `rustrest` | [SojebSikder/rustrest](https://github.com/SojebSikder/rustrest) | An open-source, cross-platform native API testing platform written in Rust. |
| `zpad` | [helloxz/zpad](https://github.com/helloxz/zpad) | A cross-platform, natively rendered text editor without Git, AI, or WebView. |

Each manifest uses `checkver` + `autoupdate`, so new upstream releases are picked up automatically by the scheduled Excavator workflow (`.github/workflows/excavator.yml`).
