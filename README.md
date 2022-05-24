<pre>
	<p align=center>

Tecnológico Nacional de México
Instituto Tecnológico de Tijuana

Departamento de Sistemas y Computación
Ingeniería en Sistemas Computacionales

Semestre:
Febrero - Junio 2022

Materia:
Lenguajes de interfaz

Docente:
M.C. Rene Solis Reyes 

Unidad:
3

Título del trabajo:
CIERRE Tema 3: Corra los programas de ARM Assembly entregados a su revisión.

Estudiante:
Leonardo Mercado Celis

	</p>
</pre>

Makefile utilizado:
```bash
compile:
        echo "Compiling... $(file)"
        as -o $(file).o $(file).s
        gcc -o $(file) $(file).o
        gdb $(file)
```

Corridas de pantalla en gdb y como ejecutable(si es posible):

# Delay.s <br>
![image](https://user-images.githubusercontent.com/81432796/169950192-d1f3923b-fa37-4670-be8a-f097435fc138.png)

# Div.s <br>
![image](https://user-images.githubusercontent.com/81432796/169950574-510296fc-0606-447a-a8e7-c6527e887487.png)

# Hanoi.s <br>
![image](https://user-images.githubusercontent.com/81432796/169950712-2934b0d1-4a34-4578-b094-8fbc7fcb390c.png)
<br>
![image](https://user-images.githubusercontent.com/81432796/169950945-66df6a8b-1104-4530-8371-ffe9347f1508.png)

# Sum2.s <br>
![image](https://user-images.githubusercontent.com/81432796/169950841-ec2361a2-3c77-44a0-ac52-bf6ac742c357.png)
<br>
![image](https://user-images.githubusercontent.com/81432796/169950909-b7d44dfa-c832-4aed-942d-c48ea92ed70d.png)

# Stack.s <br>
![image](https://user-images.githubusercontent.com/81432796/169948518-62ae184d-0567-48ec-b37c-5b8bf327e51a.png)

# Scanf.s <br>
![image](https://user-images.githubusercontent.com/81432796/169949524-2f2f3457-f327-4054-aa2d-ed4ada1cadd7.png)
<br>
![image](https://user-images.githubusercontent.com/81432796/169950997-bee2051d-f79e-4cd5-991d-f88878e29e78.png)

# Sum3.s <br>
![image](https://user-images.githubusercontent.com/81432796/169949924-22b533f6-7cbd-42c6-84dd-ee5da979f986.png)
<br>
![image](https://user-images.githubusercontent.com/81432796/169951022-370d08fd-770e-4c5b-827a-4ac56dcd5d80.png)

# Primero.s <br>
![image](https://user-images.githubusercontent.com/81432796/169948238-8511002a-d66a-468f-a3a7-a019d0328a00.png)
