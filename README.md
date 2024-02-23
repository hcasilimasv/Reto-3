# Reto-3

### A continuación veremos el procedimiento matemático para hallar los números primos hasta n y raíces cuadradas en forma de algoritmo en pseudocódigo y en diagrama de flujo.

##### Números primos hasta n naturalez.


###### Pseudocódigo.

``` 
n : entero
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


[![](https://mermaid.ink/img/pako:eNpVkctOAzEMRX_FygpEKx7LEUXqE7FgVVbMdGEStzXKJEMepaXtv-OZFgRRpFjWvT5X8V5pb0gVamn9p15jSPAyqRzIGZZPjjX7BfT7D4dp1IHfuPYRdEb7kZkCuFxT8EAuyXOA0QVDMYC7y9OAUWuE8b5mEQSMwHAPDgxv2HCAyA7YaZul5uPJMu5Ycz7ApORrBwPYgvHOEGwHN-KnCE2QEAuRzco5gaGoJTQCWfiNI2NXgSK2YbPz0qdNZxn9pzjJPD1zdmfObsBXt0IS21_YYzmUkatupKDOJAQrl6PwxdqJY6t-L2fs0PJXl6sJXlP0C9VT4qqRjfz3vo1SqbSmmipVSGloidmmSlXuKFLMyc93TqsihUw9lRuDiSaMq4C1KpZoo3TJcPLh-bTDbpU91aB79f5Hc_wGjoSgWA?type=png)](https://mermaid.live/edit#pako:eNpVkctOAzEMRX_FygpEKx7LEUXqE7FgVVbMdGEStzXKJEMepaXtv-OZFgRRpFjWvT5X8V5pb0gVamn9p15jSPAyqRzIGZZPjjX7BfT7D4dp1IHfuPYRdEb7kZkCuFxT8EAuyXOA0QVDMYC7y9OAUWuE8b5mEQSMwHAPDgxv2HCAyA7YaZul5uPJMu5Ycz7ApORrBwPYgvHOEGwHN-KnCE2QEAuRzco5gaGoJTQCWfiNI2NXgSK2YbPz0qdNZxn9pzjJPD1zdmfObsBXt0IS21_YYzmUkatupKDOJAQrl6PwxdqJY6t-L2fs0PJXl6sJXlP0C9VT4qqRjfz3vo1SqbSmmipVSGloidmmSlXuKFLMyc93TqsihUw9lRuDiSaMq4C1KpZoo3TJcPLh-bTDbpU91aB79f5Hc_wGjoSgWA)


##### Raices cuadradas hasta numero n

###### Pseudocódigo

```
n = Real
x = Real
 Inicio
  ("Esccribimos cualquier numero real")
  x = 16
    Si   x ≥ 0 entonces
	      x = n ^ 0.5
              El resultado es (la raiz cuadrada de "x" es "n")
    Sino El resultado es ("no se puede calcular la raiz")
             ("Se descarta el  numero e ingresamos uno nuevo")
 Finaliza el proceso
agregamos un nuevo numero y repetimos el proceso
```

###### Diagrama de flujo.

[![](https://mermaid.ink/img/pako:eNpVkUtOAzEMhq9iZQVSi4oELEYCqU-BBKuyYqZIJnHbSJmk5AFDHwfgIFyMk-DMtAuyipL___zb3gnpFIlCLI37lGv0EZ4nlQU-w_LBaqndAvr9u_00SK_fdO0CyITmPWnyYFNN3oEnNHsYnTVwC5c35519lG0w3o2dVRlTQAO_3z8wALLRWUnh0AnHLX-u9zApM8HCKwwurlkGir3ESH69amPMSpgarheSiagcUACD4FFvcyrlUSGwo8kfDD862XhfzrRFo7cIZGDjHdd3i_8BrNvDtHw88izTGx0i5SCG2-6aDW23FDIUVuWcuF6QPLcWfJoIgbYrjol5XolRNtGHy56h6AmW1KgVT32XE1QirqmmShR8VbREbq4SlT2wFFN08y8rRRF9op5IG4WRJhpXHmtRLNEEfiWlo_NP3SbbhfbEBu2LcyfN4Q-I7KA2?type=png)](https://mermaid.live/edit#pako:eNpVkUtOAzEMhq9iZQVSi4oELEYCqU-BBKuyYqZIJnHbSJmk5AFDHwfgIFyMk-DMtAuyipL___zb3gnpFIlCLI37lGv0EZ4nlQU-w_LBaqndAvr9u_00SK_fdO0CyITmPWnyYFNN3oEnNHsYnTVwC5c35519lG0w3o2dVRlTQAO_3z8wALLRWUnh0AnHLX-u9zApM8HCKwwurlkGir3ESH69amPMSpgarheSiagcUACD4FFvcyrlUSGwo8kfDD862XhfzrRFo7cIZGDjHdd3i_8BrNvDtHw88izTGx0i5SCG2-6aDW23FDIUVuWcuF6QPLcWfJoIgbYrjol5XolRNtGHy56h6AmW1KgVT32XE1QirqmmShR8VbREbq4SlT2wFFN08y8rRRF9op5IG4WRJhpXHmtRLNEEfiWlo_NP3SbbhfbEBu2LcyfN4Q-I7KA2)
