# scoop-cookwala

Scoop bucket for [cookwala-samples](https://github.com/amado2k5/cookwala) — the Cookwala sample
clients, agents, orchestrators, gates, recovery and reporting (simulated devices, or any Cookwala
hub).

```powershell
scoop bucket add cookwala https://github.com/amado2k5/scoop-cookwala
scoop install cookwala-samples
cookwala-samples demo
```

The manifest is generated from `samples/packaging/scoop/cookwala-samples.json.in` in the main
repository; Excavator updates `version` and `hash` on every `samples-v*` release via `checkver` /
`autoupdate`.
