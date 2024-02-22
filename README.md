# Reto-3

### A continuación veremos el procedimiento matemático para hallar los números primos hasta n y raíces cuadradas en forma de algoritmo en pseudocódigo y en diagrama de flujo.

##### Números primos hasta n naturalez.


###### Pseudocódigo.

``` 
n : enteri
i : entero
x = i/n : donde x = 0
y = i/n : donde y = i + 1

Inicio
 ("Escribimos cualquier numero entero")
  i := 2
  mientras (i < n) se realiza todas las divisiones sin incluir la propia i
     Si
	     i/n = x donde (x = 0) ("i no es un numero primo")
		  ("Se descarta el  numero e ingresamos uno nuevo")
	 Sino
	     i/n = y donde (y = i + 1) ("i es un  numero primo")
		   ("Agregamos el numero a la lista de primos")
  Finaliza el proceso
  Fin del proceso y se agrega un nuevo numero
 Se repite el proceso
 Fin
``` 

###### Diagrama de flujo.

###### Pseudocódigo.

[![](https://mermaid.ink/img/pako:eNpVkctOAzEMRX_FygpEKx7LEUXqE7FgVVbMdGEStzXKJEMepaXtv-OZFgRRpFjWvT5X8V5pb0gVamn9p15jSPAyqRzIGZZPjjX7BfT7D4dp1IHfuPYRdEb7kZkCuFxT8EAuyXOA0QVDMYC7y9OAUWuE8b5mEQSMwHAPDgxv2HCAyA7YaZul5uPJMu5Ycz7ApORrBwPYgvHOEGwHN-KnCE2QEAuRzco5gaGoJTQCWfiNI2NXgSK2YbPz0qdNZxn9pzjJPD1zdmfObsBXt0IS21_YYzmUkatupKDOJAQrl6PwxdqJY6t-L2fs0PJXl6sJXlP0C9VT4qqRjfz3vo1SqbSmmipVSGloidmmSlXuKFLMyc93TqsihUw9lRuDiSaMq4C1KpZoo3TJcPLh-bTDbpU91aB79f5Hc_wGjoSgWA?type=png)](https://mermaid.live/edit#pako:eNpVkctOAzEMRX_FygpEKx7LEUXqE7FgVVbMdGEStzXKJEMepaXtv-OZFgRRpFjWvT5X8V5pb0gVamn9p15jSPAyqRzIGZZPjjX7BfT7D4dp1IHfuPYRdEb7kZkCuFxT8EAuyXOA0QVDMYC7y9OAUWuE8b5mEQSMwHAPDgxv2HCAyA7YaZul5uPJMu5Ycz7ApORrBwPYgvHOEGwHN-KnCE2QEAuRzco5gaGoJTQCWfiNI2NXgSK2YbPz0qdNZxn9pzjJPD1zdmfObsBXt0IS21_YYzmUkatupKDOJAQrl6PwxdqJY6t-L2fs0PJXl6sJXlP0C9VT4qqRjfz3vo1SqbSmmipVSGloidmmSlXuKFLMyc93TqsihUw9lRuDiSaMq4C1KpZoo3TJcPLh-bTDbpU91aB79f5Hc_wGjoSgWA)


##### Raices cuadradas hasta numero n

