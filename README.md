# kt-scoop-bucket

Personal [Scoop](https://scoop.sh) bucket maintained by [kytrun](https://github.com/kytrun).

## Usage

```powershell
scoop bucket add kt https://github.com/kytrun/kt-scoop-bucket
scoop install kt/ai-memory
```

## Apps

| App | Source | Description |
| --- | --- | --- |
| `ai-memory` | [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) | Long-term memory for agent coding CLIs and handoff between different agent vendors. |

Each manifest uses `checkver` + `autoupdate`, so new upstream releases are picked up automatically by the scheduled Excavator workflow (`.github/workflows/excavator.yml`).
