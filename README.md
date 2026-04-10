# Tres en raya

## Requisitos

El programa a resolver debe permitir a dos usuarios jugar el tic tac toe (tres en raya)

<div align=center>

<table>
  <tr><th>Inicio</th><th>Juego en desarrollo</th><th>Fin del juego</th></tr>
<tr>
<td>

```
_ _ _ 
_ _ _ 
_ _ _ 
> Fila? [1..3]
```
</td>
<td>

```
_ _ o 
x o x 
_ _ o 
> Fila? [1..3]
```
</td>
<td>

```
x _ o 
x o x 
o _ _ 
Hemos ganado los o
```    
</td>
</tr>
</table>

</div>

## Requisitos

- Inicialmente el tablero estará vacío.
- Los jugadores pondrán las fichas alternativamente, siendo posible alcanzar las "Tres en Raya" con la quinta puesta.
- En caso contrario, una vez puestas las 6 fichas, se moverán las fichas alternativamente.
- Tanto en las puestas como en los movimientos, se deben requerir las coordenadas a usuario validando la corrección de la puesta/movimiento.
- Se debe detectar automáticamente la finalización del juego al lograrse "Tres en Raya": tras la quinta y sexta puesta y tras cada movimiento.
