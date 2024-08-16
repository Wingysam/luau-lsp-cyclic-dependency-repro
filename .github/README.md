# Rojo Cyclic Dependency Repro

This project compiles to a valid Roblox game. Luau LSP throws this error:

![TypeError: Cyclic module dependency: Users/wingy/Documents/Code/Personal/luau-lsp-cyclic-dependency-repro/src/ServerScriptService/a.luau [game/ServerScriptService/a] -> Users/wingy/Documents/Code/Personal/luau-lsp-cyclic-dependency-repro/src/ServerScriptService/b.luau [game/ServerScriptService/b] Luau 1023](image.png)