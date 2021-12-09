# taller8
## Diseño de la solución de problemas con pseudocódigo aplicando
 arreglos unidimensionales.
A. Revisar los ejercicios y problemáticas de la carpeta ejemplos. 
Plantear la mejor solución.


B. Generar una miniespecificación que permita ingresar los valor 
de ventas de un vendedor por cada día de la semana (lunes a viernes);
 donde día 0 es Lunes. 
Usar 2 arreglos.
```
(ventas(5),i[0-n])  // arreglo que debe ser llenado por el usuario


(dias(5), x(20)[{a-z}, {BS}])
dias[0]<-- "Lunes"
dias[1]<-- "Martes"
dias[2]<-- "Miércoles"
dias[3]<-- "Jueves"
dias[4]<-- "Viernes"
```

Luego presentar un reporte así
- Lunes $130
- Martes $200
- Miércoles $190
- Jueves $200
- Viernes $100

C. Dados un arreglo
```
arreglo(5), i[0-n]
arreglo[0] <-- 10
arreglo[1] <-- 9
arreglo[2] <-- 20
arreglo[3] <-- 29
arreglo[4] <-- 100
```
Imprimir todos los valores del arreglo cuyo valor sea impar

D. Dados un arreglo
```
arreglo(5), i[0-n]
arreglo[0] <-- 10
arreglo[1] <-- 9
arreglo[2] <-- 20
arreglo[3] <-- 29
arreglo[4] <-- 100
```
//Imprimir todos los valores del arreglo que pertencen a un índice par mayor o igual a 2

1.  Inicio
2.  ventas (5), i [0-n]
3.  indice, i [o-n]
4.  diasdeventa (5), i[0-n]
5.  (dias(5), x(20)[{a-z}, {BS}])
6.  dias[0]<-- "Lunes"
7.  dias[1]<-- "Martes"
8.  dias[2]<-- "Miércoles"
9.  dias[3]<-- "Jueves"
10. dias[4]<-- "Viernes" 
11. Para(inidice=0) haga
12.   diasdeventa <-- dias[indice] + 130
13. Fin para
14. Para(inidice=1) haga
15.   diasdeventa <-- dias[indice] + 200
16. Fin para
13. Fin para
14. Para(inidice=2) haga
15.   diasdeventa <-- dias[indice] + 190
16. Fin para
17. Para(inidice=3) haga
18.   diasdeventa <-- dias[indice] + 200
19. Fin para
20. Fin para
21. Para(inidice=4) haga
22.   diasdeventa <-- dias[indice] + 100
23. Fin para
24. 
24. escribir: "las ventas diarias son:\n" = diasdeventa 
