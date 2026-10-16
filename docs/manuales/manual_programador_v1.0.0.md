# Manual del Programador v1.0.0

## Compilación

```powershell
g++ -std=c++11 src/main.cpp -o src/piedrapapelotijera.exe
```

## Estructura del Proyecto

- `src/main.cpp` — Código fuente principal
- `src/historial_partidas.txt` — Archivo de persistencia (se genera automáticamente)

## Flujo de Datos

1. El usuario juega una partida desde el menú principal
2. Cada partida se almacena en una estructura `Partida`
3. La partida se persiste en `src/historial_partidas.txt` en formato CSV
4. El historial puede consultarse desde la opción 2 del menú
