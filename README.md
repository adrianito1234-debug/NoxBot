# NoxBot — canal de auto-update

Copia **funcional estable: 3.0.9**

## Qué hay aquí
- `update/latest.json` — versión actual del canal
- `update/files/` — launcher, bridge, updater, `nox_lua.zip`

Firmas LuaJIT (separado): https://github.com/adrianito1234-debug/NoxBot-Sigs

## 3.0.9 (estable)
- Modo híbrido: si el motor está en disco (`noxbot_data`), un solo contacto Lua (estilo 2.0.2). Sin empujar ~72 ranuras en el hilo UI.
- Sin fallback off-thread (no toca la VM desde el worker).
- Perfiles / motor viven en el pack; el cliente no se parchea en disco.

Tag: `v3.0.9-stable`
