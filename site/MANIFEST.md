# Archive manifest - leader

Authority: `authorities/leader` @ 0.3.0-rc1 - generated 2026-10-11T09:53:09+00:00 UTC

| file | role | sha256 (first 16) | size |
|---|---|---|---|
| `.site-state.json` | refresh state (pack hash, version, artifact set) | `8128e9d92c8a938f` | 950 |
| `agent-brief.md` | asset | `7c67e64e266c5280` | 4517 |
| `audit.jsonl` | machine-recorded authority call trace | `f7da1d1de4e6142f` | 59041 |
| `brief.md` | build brief | `df3478fd0113ece0` | 2259 |
| `index.html` | page | `3b968a5ef19a20f0` | 35551 |
| `log.md` | build log (agent, 1:1 with audit.jsonl) | `fc60e498bf67f5f8` | 30662 |
| `refresh-log.md` | refresh log (generated layers vs pack) | `206c632f4af200e7` | 4084 |
| `run-authority` | audited runner (build-time tool) | `8c8eb36c2f2b22d7` | 1033 |
| `styles.css` | stylesheet | `9837a09e1ab90009` | 12665 |
| `fonts/ArchivoBlack-Regular.ttf` | brand font file | `dd9a89a019b4849f` | 90988 |
| `fonts/Gelasio-VF.ttf` | brand font file | `4daecea457258c9e` | 168556 |
| `fonts/Inter-VF.ttf` | brand font file | `29160a80ff49ddca` | 876576 |
| `.design-authority/gaps.jsonl` | gap store (filed gaps) | `cbf4c571d4c0c687` | 1915 |

External references: 1 (must be 0).

- `fonts/ArchivoBlack-Regular.ttf`: byte-identical to `docs/synthesis/leader/tile/fonts/ArchivoBlack-Regular.ttf` -> True
- `fonts/Inter-VF.ttf`: byte-identical to `docs/synthesis/leader/tile/fonts/Inter-VF.ttf` -> True
- `fonts/Gelasio-VF.ttf`: byte-identical to `docs/synthesis/leader/tile/fonts/Gelasio-VF.ttf` -> True

Verify: `python3 tools/archive_authority_assets.py --verify leader`
