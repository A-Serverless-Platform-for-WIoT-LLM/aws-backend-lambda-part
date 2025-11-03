# AWS Lambda export snapshot

## Structure
- `functions/<NAME>/` : get-function.json, config.json, versions.json, aliases.json, event-source-mappings.json, policy*.{json,txt}, code_sha256.txt
- `layers/<LAYER>/<VER>/` : meta.json, policy*.{json,txt}
> Large binaries (zip, jars, etc.) are excluded via `.gitignore`.
