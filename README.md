# Sentinel

FaulMor Labs — local runtime extraction / deobfuscation harness.

## v2.1.1
- More extraction (24 stages, higher HTTP/remote/runtime caps)
- Live stage-hop files: `extracts/stage_NN.txt` + `stage_hops.txt`
- Unclassified traffic → `unknown.txt`
- **All artifacts are `.txt`** (no `.json` / `.lua` outputs)

### Load
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/FaulMor-Labs/Sentinel/main/lua.txt"))()
```

Replace `lua.txt` on this branch with the v2.1.1 build if raw still shows 2.1.0.
