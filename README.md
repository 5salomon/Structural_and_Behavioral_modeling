# Structural_and_Behavioral_modeling
 sumador de 64bits

En este proceso del diseño de un sumador de x64 bits nos basamos en la hoja de asignacion , la cual indica que se debe empezar con un sumador completo (Fulladder) y partiendo de esta base se debe hacer un sumador de dos bits luego un sumador de 4 bits hasta llegar al sumador de x64 bits el cual debe de estar compuesto por instancias de un sumador de x32 bits. En las siguientes imagenes se ira describiendo la realizacion de todo el proceso.

![alt text](image.png)

primero de se realizo el sumador completo , el cual cuanta con tres entradas y dos salidas , las entradas seran A , B y Cin siendo Cin el acarreo de entrada , y las salidas van a ser Sout que sera la suma y Cout siendo el acarreo de salida.
![alt text](image-1.png)  ![alt text](image-2.png)

Luego tendremos el sumador de dos bits que esta conformado por dos intacias del fulladder, este sumador de dos bits tendra 5 entradas y 3 salidas. Las entradas seran A1 , A2 , B1 ,B2, Cin y las salidas son out 1 ,out 2 y Cout.

![alt text](image-3.png) ![alt text](image-4.png) ![alt text](image-5.png)

