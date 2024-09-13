# Manual de uso cannon.py

Se aumentó la velocidad de la pelota del cañon en la función tap.

## Eliminar restricción de borde

Se eliminaron las siguientes líneas de código dentro de la función move, responsables de terminar la simulación en caso de que alguna de las pelotas azules (targets) colisione con el borde del canvas:

```python
for target in targets:
    if not inside(target):
        return
```
