# TAREA-9-CAPITULO-23-24
## 1.OBJETIVOS
## 1.1  TRANSFORMADORES Y CIRCUITOS ACOPLADOS 
-  Describir cómo un transformador acopla energía desde su primario hasta su secundario a través de un campo magnético cambiante.
-  Describir la construcción de un transformador básico.
-  Usar la convención del punto para determinar las fases del transformador.
-  Determinar las relaciones de voltaje y corriente a partir de la relación de vueltas de los transformadores de núcleo de hierro.
-  Calcular el voltaje y la corriente en circuitos con transformadores con núcleo de hierro y núcleo de aire.
-  Usar transformadores para igualar la impedancia de las cargas.
-  Describir algunas de las aplicaciones básicas de los transformadores.
-  Determinar los circuitos equivalentes de los transformadores.
-  Calcular la eficiencia del transformador con núcleo de hierro.
-  Usar multisim y pspice para resolver circuitos con transformadores y circuitos acoplados.
## 1.2  SISTEMAS DE TRES FASES 
-  Describir la generación de voltaje de tres fases.
-  Representar los voltajes y corrientes trifásicos en forma de fasores.
-  Describir las conexiones estándar de carga de tres fases.
-  Analizar circuitos trifásicos balanceados.
-  Calcular potencia activa, potencia reactiva y potencia aparente en sistemas de tres fases.
-  Medir la potencia con el método de dos wattímetros y de tres wattímetros.
-  Analizar circuitos trifásicos desbalanceados simples
-  Aplicar Multisim y PSpice a problemas de tres fases.
##  2. MARCO TEÓRICO (RESUMEN)
## 2.1 TRANSFORMADORES Y CIRCUITOS ACOPLADOS
### 2.1.1 INTRODUCCIÓN 
### 2.1.2 TRANSFORMADORES DE NÚCLEO DE HIERRO: EL MODELO IDEAL 
### 2.1.3IMPEDANCIA REFLEJADA 
### 2.1.4 ESPECIFICACIONES DEL TRANSFORMADOR DE POTENCIA 
### 2.1.5 APLICACIONES DEL TRANSFORMADOR 
### 2.1.6 TRANSFORMADORES DE NÚCLEO DE HIERRO PRÁCTICOS 
### 2.1.7 PRUEBAS DE LOS TRANSFORMADORES 
### 2.1.8 EFECTOS DEL VOLTAJE Y LA FRECUENCIA 
### 2.1.9 CIRCUITOS DÉBILMENTE ACOPLADOS 
### 2.1.10 CIRCUITOS ACOPLADOS MAGNÉTICAMENTE CON EXCITACIÓN SINUSOIDAL 
### 2.1.11 IMPEDANCIA ACOPLADA 
### 2.1.12 ANÁLISIS DE CIRCUITOS POR COMPUTADORA 
## 2.2 SISTEMA DE TRES FASES
### 2.2.1 GENERACIÓN DE VOLTAJE TRIFÁSICO 
### 2.2.2 CONEXIONES BÁSICAS DE CIRCUITOS TRIFÁSICOS 
### 2.2.3 RELACIONES TRIFÁSICAS BÁSICAS 
### 2.2.4 EJEMPLOS 
### 2.2.5 POTENCIA EN SISTEMAS BALANCEADOS 
### 2.2.6 MEDICIÓN DE POTENCIA EN CIRCUITOS TRIFÁSICOS 
### 2.2.7 CARGAS DESBALANCEADAS 
### 2.2.8 CARGAS EN SISTEMAS DE POTENCIA 
### 2.2.9 ANÁLISIS DE CIRCUITOS POR COMPUTADORA
## 3. EXPLICACIÓN Y RESOLUCIÓN DE LOS EJERCICIOS
## 3.1 TRANSFORMADORES Y CIRCUITOS ACOPLADOS
### 3.1.1 INTRODUCCIÓN 
1. Para los transformadores de la figura 23-71, dibuje las formas de onda que faltan.

![image](https://user-images.githubusercontent.com/84425276/132602284-83d3837a-4e14-4259-a51d-ec710c828481.png)

### 3.1.2 TRANSFORMADORES DE NÚCLEO DE HIERRO: EL MODELO IDEAL 
3. Un transformador ideal tiene Np = 1000 vueltas y Ns = 4000 vueltas.
a. ¿El voltaje se eleva o se reduce?
b. Si es = 100 sen t, ¿qué valor tiene ep cuando se devana como en la figura 23-7(a)?
c. Si Es = 24 volts, ¿qué valor tiene Ep?
d. Si Ep = 24 V∠0°, ¿qué valor tiene Es cuando se devana como en la figura 23-7(a)?
e. Si Ep = 800 V∠0°, ¿qué valor tiene Es cuando se devana como en la figura 23-7(b)?
5. Para la figura 23-72, determine las expresiones para v1, v2 y v3.

![image](https://user-images.githubusercontent.com/84425276/132602318-8f75b0c5-65a8-4525-af58-9e63f93548cc.png)

7. Si, para la figura 23-73, Eg = 240 V∠0°, a = 0.5, e Ig = 2 A∠20°, determine lo siguiente:
a. IL b. VL c. ZL

![image](https://user-images.githubusercontent.com/84425276/132602350-0d7da342-98f9-4b9a-b810-96a04aca624a.png)

9. Si, para la figura 23-73, a = 4, Ig = 4 A∠30°, y ZL = 6 Ω - j8 Ω, determine lo siguiente:
a. VL b. Eg

![image](https://user-images.githubusercontent.com/84425276/132602372-5a3a69b8-fc63-4b9e-a9a4-9e88d9c8c7b4.png)

### 3.1.3 IMPEDANCIA REFLEJADA 
11. Para cada circuito de la figura 23-74, determine Zp.

![image](https://user-images.githubusercontent.com/84425276/132602420-91c64969-4d1a-465a-b1a0-1e7e80a8ab6e.png)

13. Para la figura 23-74(a), ¿qué relación de vueltas se requiere para hacer que Zp = (62.5 - j125) Ω?


15. Para cada circuito de la figura 23-75, determine ZT.

![image](https://user-images.githubusercontent.com/84425276/132602430-61a3f3c5-539d-4447-9fef-1c7829e28c1d.png)

### 3.1.4 ESPECIFICACIONES DEL TRANSFORMADOR DE POTENCIA 
17. Un transformador tiene una especificación de voltaje primario de 7.2 kV, a = 0.2, y una especificación de corriente en el secundario de 3 A. ¿Cuál es la especificación de kVA?


### 3.1.5 APLICACIONES DEL TRANSFORMADOR 
19. El transformador de la figura 23-25 tiene un primario de 7200 V y un secundario de 240 V con terminal central. Si la carga 1 consiste en doce lámparas de 100 W, la carga 2 es un calentador de 1500 W y la carga 3 es una horno de
2400 W con Fp = 1.0, determine
a.	I1 b. I2 c. IN d. Ip

![image](https://user-images.githubusercontent.com/84425276/132602607-3430da81-0bb0-4803-a923-0946a9d5c00c.png)

21. Un amplificador con un equivalente de Thévenin de 10 V y RTh de 25 Ω manejan una bocina de 4 Ω a través de un transformador con una relación de vueltas de a = 5. ¿Cuánta potencia es suministrada a la bocina? ¿Qué relación de vueltas produce 1 W?


23. Para la figura 23-30(a), a2 = 2 y a3 = 5, Z2 = 20 Ω∠50°, Z3 = (12 + j4)  Ω y Eg = 120 V∠0°. Encuentre cada corriente de carga y la corriente del generador.


### 3.1.6 TRANSFORMADORES DE NÚCLEO DE HIERRO PRÁCTICOS 
25. Para la figura 23-77, Eg = 1220 V∠∠0°.
a. Dibuje el circuito equivalente.
b. Determine Ig, IL, y VL.

![image](https://user-images.githubusercontent.com/84425276/132602768-2db10859-0081-4dd9-a2fd-829ac52719ce.png)

27. Un transformador que entrega Psal = 48 kW tiene un perdida en el núcleo de 280 W y una perdida en el cobre de 450 W. ¿Cuál es su eficiencia a esta carga?

### 3.1.9 CIRCUITOS DÉBILMENTE ACOPLADOS 
29. Para la figura 23-78,

![image](https://user-images.githubusercontent.com/84425276/132602792-4c577744-e17f-4c77-8651-837950d8cc50.png)

Para cada circuito indique que signo usar con M, más o menos.
31. Para un conjunto de bobinas acopladas, L1 = 2 H, M = 0.8 H y el coeficiente de acoplamiento es de 0.6. Determine L2.


33. Todo igual que en el problema 32, excepto que i1 = 10 e^-500t A. Encuentre las ecuaciones de los voltajes del primario y el secundario. Calcule los a t = 1 ms.


35. Para la figura 23-80, determine LT.

![image](https://user-images.githubusercontent.com/84425276/132602810-23a25522-f3b3-496f-b175-587a39728706.png)

### 3.1.10 CIRCUITOS ACOPLADOS MAGNÉTICAMENTE CON EXCITACIÓN SINUSOIDAL 
### 3.1.12 ANÁLISIS DE CIRCUITOS POR COMPUTADORA 
## 3.2 SISTEMA DE TRES FASES
### 3.2.2CONEXIONES BÁSICAS DE CIRCUITOS TRIFÁSICOS 
### 3.2.3 RELACIONES TRIFÁSICAS BÁSICAS 
### 3.2.4 EJEMPLOS 
### 3.2.5 POTENCIA EN SISTEMAS BALANCEADOS 
### 3.2.6 MEDICIÓN DE POTENCIA EN CIRCUITOS TRIFÁSICOS 
### 3.2.7 CARGAS DESBALANCEADAS 
### 3.2.9 ANÁLISIS DE CIRCUITOS POR COMPUTADORA
## 4. VIDEO
## 5. CONCLUSIONES
### 5.1  TRANSFORMADORES Y CIRCUITOS ACOPLADOS 
### 5.2 SISTEMAS DE TRES FASES 
## 6. BIBLIOGRAFÍA
