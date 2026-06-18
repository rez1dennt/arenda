# Suggested Commands

Run local server:
```powershell
python -m http.server 5173 --bind 127.0.0.1
```

Check server:
```powershell
Invoke-WebRequest -Uri 'http://127.0.0.1:5173/' -UseBasicParsing
```

List files:
```powershell
Get-ChildItem -Force
```

Fast search:
```powershell
rg "pattern" .
```

There are no configured npm scripts, tests, formatter, or linter in this static project.