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

a) es se encuentra en fase con ep
b) ep se encuentra 180° fuera de fase cos es
### 3.1.2 TRANSFORMADORES DE NÚCLEO DE HIERRO: EL MODELO IDEAL 
3. Un transformador ideal tiene Np = 1000 vueltas y Ns = 4000 vueltas.
a. ¿El voltaje se eleva o se reduce?
b. Si es = 100 sen t, ¿qué valor tiene ep cuando se devana como en la figura 23-7(a)?
c. Si Es = 24 volts, ¿qué valor tiene Ep?
d. Si Ep = 24 V∠0°, ¿qué valor tiene Es cuando se devana como en la figura 23-7(a)?
e. Si Ep = 800 V∠0°, ¿qué valor tiene Es cuando se devana como en la figura 23-7(b)?

![image](https://user-images.githubusercontent.com/84425276/132606326-4af4f556-0494-4ad5-95b1-eb4a39efa00a.png)

![image](https://user-images.githubusercontent.com/84425276/132608753-fa966985-b5b6-4527-a5c1-de6362c496c9.png)

5. Para la figura 23-72, determine las expresiones para v1, v2 y v3.

![image](https://user-images.githubusercontent.com/84425276/132602318-8f75b0c5-65a8-4525-af58-9e63f93548cc.png)

![image](https://user-images.githubusercontent.com/84425276/132608777-1312067b-a085-4489-beff-cef33911da51.png)

7. Si, para la figura 23-73, Eg = 240 V∠0°, a = 0.5, e Ig = 2 A∠20°, determine lo siguiente:
a. IL b. VL c. ZL

![image](https://user-images.githubusercontent.com/84425276/132602350-0d7da342-98f9-4b9a-b810-96a04aca624a.png)

![image](https://user-images.githubusercontent.com/84425276/132608797-d56260f9-097b-494a-b334-e952b271a0ad.png)

9. Si, para la figura 23-73, a = 4, Ig = 4 A∠30°, y ZL = 6 Ω - j8 Ω, determine lo siguiente:
a. VL b. Eg

![image](https://user-images.githubusercontent.com/84425276/132602372-5a3a69b8-fc63-4b9e-a9a4-9e88d9c8c7b4.png)

![image](https://user-images.githubusercontent.com/84425276/132608875-548a0722-29a8-440a-bb99-eeb9f311a451.png)

### 3.1.3 IMPEDANCIA REFLEJADA 
11. Para cada circuito de la figura 23-74, determine Zp.

![image](https://user-images.githubusercontent.com/84425276/132602420-91c64969-4d1a-465a-b1a0-1e7e80a8ab6e.png)

![image](https://user-images.githubusercontent.com/84425276/132608907-2b94dbc7-eff6-4ff6-aff9-5778ea9b2723.png)

13. Para la figura 23-74(a), ¿qué relación de vueltas se requiere para hacer que Zp = (62.5 - j125) Ω?

![image](https://user-images.githubusercontent.com/84425276/132606366-82504d0d-7e2c-4bc8-8919-9f1dad240aa5.png)

![image](https://user-images.githubusercontent.com/84425276/132608938-d0ab1ac2-5167-4964-a523-e572e51e4e23.png)

15. Para cada circuito de la figura 23-75, determine ZT.

![image](https://user-images.githubusercontent.com/84425276/132602430-61a3f3c5-539d-4447-9fef-1c7829e28c1d.png)

![image](https://user-images.githubusercontent.com/84425276/132608990-da30c349-196a-4cf9-87e6-5b7492b52450.png)

![image](https://user-images.githubusercontent.com/84425276/132609013-a3b91f17-82d9-4a73-beda-b1aeb8f017d4.png)

![image](https://user-images.githubusercontent.com/84425276/132609033-5541c3f3-a76a-45b5-babe-05163cffcea1.png)

### 3.1.4 ESPECIFICACIONES DEL TRANSFORMADOR DE POTENCIA 
17. Un transformador tiene una especificación de voltaje primario de 7.2 kV, a = 0.2, y una especificación de corriente en el secundario de 3 A. ¿Cuál es la especificación de kVA?

![image](https://user-images.githubusercontent.com/84425276/132609079-e77c53ae-211c-4272-a789-5cbfac43a762.png)

### 3.1.5 APLICACIONES DEL TRANSFORMADOR 
19. El transformador de la figura 23-25 tiene un primario de 7200 V y un secundario de 240 V con terminal central. Si la carga 1 consiste en doce lámparas de 100 W, la carga 2 es un calentador de 1500 W y la carga 3 es una horno de
2400 W con Fp = 1.0, determine
a.	I1 b. I2 c. IN d. Ip

![image](https://user-images.githubusercontent.com/84425276/132602607-3430da81-0bb0-4803-a923-0946a9d5c00c.png)

![image](https://user-images.githubusercontent.com/84425276/132609157-dfcc38f7-0e4a-4a8a-8971-ab46e6e1be91.png)

21. Un amplificador con un equivalente de Thévenin de 10 V y RTh de 25 Ω manejan una bocina de 4 Ω a través de un transformador con una relación de vueltas de a = 5. ¿Cuánta potencia es suministrada a la bocina? ¿Qué relación de vueltas produce 1 W?

![image](https://user-images.githubusercontent.com/84425276/132609206-8816997c-6b6a-474b-a993-5c94a1b69f4e.png)

![image](https://user-images.githubusercontent.com/84425276/132609214-19fc7b61-34c6-4f5e-b471-255e7896ec69.png)

23. Para la figura 23-30(a), a2 = 2 y a3 = 5, Z2 = 20 Ω∠50°, Z3 = (12 + j4)  Ω y Eg = 120 V∠0°. Encuentre cada corriente de carga y la corriente del generador.

![image](https://user-images.githubusercontent.com/84425276/132606572-2a62edbb-3a06-4344-8a25-27a40d866115.png)

![image](https://user-images.githubusercontent.com/84425276/132607125-691894c2-cc2b-490e-adf1-13549ca5bba5.png)

### 3.1.6 TRANSFORMADORES DE NÚCLEO DE HIERRO PRÁCTICOS 
25. Para la figura 23-77, Eg = 1220 V∠∠0°.

![image](https://user-images.githubusercontent.com/84425276/132602768-2db10859-0081-4dd9-a2fd-829ac52719ce.png)

a. Dibuje el circuito equivalente.

![image](https://user-images.githubusercontent.com/84425276/132607291-0a201e16-f6d5-4d94-b46d-115b02720c5e.png)

![image](https://user-images.githubusercontent.com/84425276/132607316-5f140967-f4cd-4bc2-8d98-3ef3a16fd807.png)

b. Determine Ig, IL, y VL.

![image](https://user-images.githubusercontent.com/84425276/132607327-95bef86d-c97a-44e8-abe2-19832fa23e54.png)

27. Un transformador que entrega Psal = 48 kW tiene un perdida en el núcleo de 280 W y una perdida en el cobre de 450 W. ¿Cuál es su eficiencia a esta carga?

![image](https://user-images.githubusercontent.com/84425276/132607407-53b2e896-e883-4711-97a1-ac4d500406e1.png)

### 3.1.9 CIRCUITOS DÉBILMENTE ACOPLADOS 
29. Para la figura 23-78,

![image](https://user-images.githubusercontent.com/84425276/132608106-89856b5b-13ad-4b1b-b563-901b15ff8273.png)

Para cada circuito indique que signo usar con M, más o menos.

![image](https://user-images.githubusercontent.com/84425276/132607501-d147b451-ac06-4295-a6c6-08bc098478e5.png)

a)

![image](https://user-images.githubusercontent.com/84425276/132607571-d57bc35a-6fc3-4ecb-b5f7-abaa6fdb504f.png)

![image](https://user-images.githubusercontent.com/84425276/132607583-deee0b17-55b6-46c5-a24b-d22160a47a9a.png)

b)

![image](https://user-images.githubusercontent.com/84425276/132607596-e52f84f8-bd8e-47c2-9a9c-088ca2edc319.png)

![image](https://user-images.githubusercontent.com/84425276/132607604-54bd879a-e85d-45c3-af80-b0b769de9ae7.png)

c)

![image](https://user-images.githubusercontent.com/84425276/132607620-1967c6a1-6f46-4fed-bbc8-f758d11776ab.png)

![image](https://user-images.githubusercontent.com/84425276/132607626-88b2419f-a32a-4912-b6b9-49885addb305.png)

31. Para un conjunto de bobinas acopladas, L1 = 2 H, M = 0.8 H y el coeficiente de acoplamiento es de 0.6. Determine L2.

![image](https://user-images.githubusercontent.com/84425276/132607679-6e698719-d7b5-45f5-a0bc-41dcc4074823.png)

33. Todo igual que en el problema 32, excepto que i1 = 10 e^-500t A. Encuentre las ecuaciones de los voltajes del primario y el secundario. Calcule los a t = 1 ms.

![image](https://user-images.githubusercontent.com/84425276/132606901-c276ca2c-42a3-40f9-9ac1-f07c1ca1a80d.png)

![image](https://user-images.githubusercontent.com/84425276/132607766-3d24fb8a-dab8-4002-a6ed-32eae41d4bd7.png)

35. Para la figura 23-80, determine LT.

![image](https://user-images.githubusercontent.com/84425276/132602810-23a25522-f3b3-496f-b175-587a39728706.png)

![image](https://user-images.githubusercontent.com/84425276/132607824-c93db671-9ca4-4e2a-bccb-913fc603d659.png)

37. Los inductores de la figura 23-82 están mutuamente acoplados. ¿Cuál es su
inductancia equivalente? Si f = 60 Hz, ¿cuál es la corriente en la fuente?

<div align="center">

![23-82 (2)](https://user-images.githubusercontent.com/84458025/132618981-57cc8f83-1b5d-405b-a0da-4b354c1db52b.png)
 
</div>

![37 (2)](https://user-images.githubusercontent.com/84458025/132619886-d86b701a-fffa-41b6-83cf-bd8ac1b39048.png)

### 3.1.10 CIRCUITOS ACOPLADOS MAGNÉTICAMENTE CON EXCITACIÓN SINUSOIDAL 

39. Para el circuito de la figura 23-83, escriba las ecuaciones de malla.

<div align="center">
  
![23-83 (2)](https://user-images.githubusercontent.com/84458025/132619985-d87d8fce-0d38-4de4-bed7-97ad0bd4dff4.png)

</div>

![39 (2)](https://user-images.githubusercontent.com/84458025/132620837-d2413f84-a309-4257-82d7-74bb10cc8c34.png)

41. Escriba las ecuaciones de malla para el circuito de la figura 23-85. (Este es un problema desafiante.)

<div align="center">
 
![5 (2)](https://user-images.githubusercontent.com/84458025/132620956-e26c6ecb-5c97-41d7-9e9c-bf3a491ad820.png)

</div>


### 3.1.12 ANÁLISIS DE CIRCUITOS POR COMPUTADORA 
43. Un transformador con núcleo de hierro con una relación de vueltas 4:1 tiene una carga que consiste en un resistor de 12 Ω en serie con un capacitor de 250 μF. El transformador se opera con una fuente de 120-V ∠ 0° y 60 Hz Utilice Multisim o PSpice para determinar las corrientes de la fuente y la carga. Verifique las respuestas con cálculos manuales.


45. Use PSpice para encontrar la corriente de la fuente para los inductores en paralelo acoplados de la figura 23-82. Sugerencia: use XFRM_LINEAR para hacer el modelo de los dos inductores. Necesitará un resistor de valor bajo en serie con cada inductor para evitar que se creen lazos fuente-inductor.

<div align="center">
 
![23-82 (2)](https://user-images.githubusercontent.com/84458025/132621928-4f654e46-ceb8-459c-8774-2c7cdfaee854.png)

</div>

47. Encuentre las corrientes de la figura 23-63 con PSpice. Compare estas respuestas con las de los Problemas prácticos 8.

<div align="center">
 
![23-63 (2)](https://user-images.githubusercontent.com/84458025/132622086-8902795f-b895-467a-992e-e49f6abda2e1.png)

 </div>

## 3.2 SISTEMA DE TRES FASES
### 3.2.2CONEXIONES BÁSICAS DE CIRCUITOS TRIFÁSICOS 
1. Mientras las cargas y voltajes de la figura 24-3(c) estén balanceados (sin tener en cuenta su valor real) las corrientes IA, IB, e IC sumaran cero. Para ilustrarlo,
cambie la impedancia de carga de 12 Ω a 15 Ω ∠ 30° Ω y para EAA =120 V ∠ 0°, haga lo siguiente:

a. Calcule las corrientes IA, IB e IC.

b. Sume las corrientes. ¿Se cumple IA + IB + IC = 0?

3. Dibuje el conjunto de formas de onda de las corrientes iA, iB e iC para el circuito de la figura 24-3(c). Suponga carga puramente resistiva y balanceada.

### 3.2.3 RELACIONES TRIFÁSICAS BÁSICAS 
5. Para las cargas de la figura 24-4, Vbc = 208 V∠ - 75°.

a. Determine los voltajes línea a línea Vab y Vca.

b. Determine los voltajes de fase.

c. Dibuje el diagrama fasorial

7. Para la carga de la figura 24-47, Van = 347 V∠ 15°. Determine todas las corrientes de línea. Dibuje el diagrama fasorial.

<div align="center">
 
![24-47 (2)](https://user-images.githubusercontent.com/84458025/132622820-df2ef65d-158f-401d-9fc0-d2c23867f9f1.png)

 </div>
 
 9. Una carga Y balanceada tiene una impedancia de Zan = 14.7Ω ∠16 ° . Si Vcn = 120 V∠160° , determine todas las corrientes de línea.

11. Para el circuito de la figura 24-48, Vab = 480 V∠0°. Encuentre la fase y las corrientes de línea.

<div align="center">
 
![24-48 (2)](https://user-images.githubusercontent.com/84458025/132623095-f3340a6d-f8aa-4b20-94c3-20c048eba3b6.png)

</div>

13. Para el circuito de la figura 24-48, si Iab = 10 A∠- 21°, determine todos los voltajes de línea.

15. Una carga Y balanceada tiene una impedancia de fase de 24 Ω ∠33 °y un voltaje línea a línea de 600 V. Tome Van como referencia y determine todas las corrientes de línea.

17. a. Para cierta carga Y balanceada, Vab = 208 V∠30°, Ia = 24 A∠40° y f = 60 Hz. Determine la carga (R y L o C).

19. Una carga  balanceada a 60 Hz tiene una corriente de Ibc = 4.5 A∠-85°. El voltaje de línea es de 240 volts y Vab se toma como referencia.


### 3.2.4 EJEMPLOS 
21. Para la figura 24-49, Van = 120 V∠0°. Dibuje el equivalente de una sola fase y:

<div align="center">
 
![28-49 (2)](https://user-images.githubusercontent.com/84458025/132624503-37ea5318-24cc-4fe1-9f29-e14fbfdbd022.png)

 </div>

a. Encuentre el voltaje de fase EAN, magnitud y ángulo.

b. Encuentre el voltaje de línea EAB, magnitud y ángulo.

23. Para la figura 24-48, EAN =120 V∠-10°. Encuentre la corriente de línea con el método equivalente de una sola fase.

<div align="center">

![24-48 (2)](https://user-images.githubusercontent.com/84458025/132624609-1ab60143-311d-4f00-8283-ba0c310f98cb.png)

</div>

25. Para la figura 24-48, suponga que las líneas tienen una impedancia Zlínea = 0.15Ω+ j0.25Ω y EAN = 120 V∠0°. Convierta la carga  en Y y use el equivalente de una fase para encontrar las corrientes de línea.

![24-48 (2)](https://user-images.githubusercontent.com/84458025/132624617-162862af-bd72-47fb-bc0e-72f8fb3548f2.png)
 
![25 (2)](https://user-images.githubusercontent.com/84431598/132624988-3ecd69dd-8674-4786-a40f-081a83c417ac.png)


27. Para el circuito de la figura 24-49, suponga que Zlínea = 0.15Ω + j0.25Ω y Vab = 600 V∠30°. Determine EAB.

![28-49 (2)](https://user-images.githubusercontent.com/84458025/132625314-2388ebe5-5d51-4479-a4bc-9cb757c5f1c5.png)
 
![27 (2)](https://user-images.githubusercontent.com/84431598/132627981-e49d4a10-8680-4523-b623-efb4202bcbb1.png)


29. Los mismos datos que el problema 28 excepto que el voltaje de fase en la carga  es Va´b´ = 480 V∠30°. Encuentre el voltaje del generador EAB, magnitud y ángulo.

![29 1 (2)](https://user-images.githubusercontent.com/84431598/132627562-ae44122a-b835-422e-b3e7-dff2371b67f6.png)

![29 2 (3)](https://user-images.githubusercontent.com/84431598/132628078-c2d3cf18-86d6-4a0e-aff8-d158b791d0cd.png)

![29 3 (2)](https://user-images.githubusercontent.com/84431598/132627714-bba4787b-02ff-46ae-a459-9a2fe378fab9.png)


31. Para la figura 24-21(a), ZY = 15Ω + j20Ω, Z = 9 Ω- j12Ω, Zlínea = 0.1Ω + j0.1Ω, e Ia´b´ = 40 A∠73.13°. Encuentre el voltaje de fase Y Van, magnitud y ángulo.

![31 (2)](https://user-images.githubusercontent.com/84431598/132628177-c2e7ea77-3dbf-4d78-afdd-be50c5b3a781.png)

### 3.2.5 POTENCIA EN SISTEMAS BALANCEADOS
33. Repita el problema 32 para la carga balanceada de la figura 24-51, dado EAN = 120 V.
 
![24-51 (2)](https://user-images.githubusercontent.com/84458025/132625930-86ff219f-82ce-4d53-b804-287165627ade.png)
 
![33 1 (3)](https://user-images.githubusercontent.com/84431598/132628332-070751dd-9e33-424e-8d2f-7357f0b7361b.png)

![33 2 (2)](https://user-images.githubusercontent.com/84431598/132628450-542031be-adf6-4400-8f0e-7f49f3a1f63f.png)

35. Para la figura 24-47, calcule las potencias real, reactiva y aparente con las fórmulas para PT, QT, y ST de la tabla 24-2. (Use VL = 207.8 V en lugar del valor
nominal de 208 V.) Compare sus resultados con los del problema 34.

![24-47 (2)](https://user-images.githubusercontent.com/84458025/132626020-18797b35-4a72-4b8a-98d9-e6b4a00ff937.png)

![53 (2)](https://user-images.githubusercontent.com/84431598/132628917-91adf441-e61d-419f-bc20-302ebe139072.png)

37. Para la figura 24-48, EAB = 208 V. Calcule las potencias real, reactiva y aparente con las fórmulas para PT, QT, y ST de la tabla 24-2. Compare sus resultados con los del problema 36.
 
![24-48 (2)](https://user-images.githubusercontent.com/84458025/132626157-9c3005e1-5da0-4c27-808c-df71a29c63bf.png)

![37 1 (2)](https://user-images.githubusercontent.com/84431598/132629046-2300964a-fdb4-4827-8b4a-281a57acb183.png)

![37 2 (2)](https://user-images.githubusercontent.com/84431598/132629127-5d7f8891-9fab-4b12-80d2-62e67660e143.png)

39. Para la figura 24-53, si Vab = 600 V, determine la potencia total, la potencia reactiva total, la potencia aparente total y el factor de potencia.
 
![24-53 (2)](https://user-images.githubusercontent.com/84458025/132626318-4dc05ebb-1a93-4e27-ac05-b8ac426af4fc.png)

![39 (3)](https://user-images.githubusercontent.com/84431598/132629257-94c288e7-98cd-42ee-8d65-ac1354388346.png)


41. Para la figura 24-19, si Vab = 480 V, determine la potencia total, la potencia reactiva total, la potencia aparente total y el factor de potencia.

43. Vab = 208 V para una carga balanceada Y, PT = 1200 W, y QT = 750 VAR/(ind). Seleccione Van como referencia y determine Ia. (Use el triángulo de potencia)

45. Los capacitores de la figura 24-54 están conectados en Y y cada uno tiene el valor de C = 120 uF. Calcule el factor de potencia resultante. La frecuencia es de 60 Hz.
### 3.2.6 MEDICIÓN DE POTENCIA EN CIRCUITOS TRIFÁSICOS 
47. Para la figura 24-47, el voltaje de fase del generador es de 120 volts.

<div align="center">

![24-47 (2)](https://user-images.githubusercontent.com/84458025/132626572-8c0ba9e3-b265-4b5b-be9a-6a97c387199c.png)

 </ div >

a. Dibuje tres wattímetros correctamente en el circuito.

b. Calcule la lectura de cada uno.

c. Sume las lecturas y compárelas con el resultado de 2304 W que se obtuvo en el problema 34.

49. Para el circuito de la figura 24-56, Vab = 208 V∠30°.

a. Determine la magnitud y ángulo de las corrientes.

b. Determine la potencia por fase y la potencia total, PT.

c. Calcule las lecturas de cada wattímetro.

d. Sume las lecturas de los medidores y compare los resultados para PT de (b).

51. Considere el circuito de la figura 24-56.

a. Calcule el factor de potencia a partir del ángulo de las impedancias de fase.

b. En el problema 49 se determinaron las lecturas del wattímetro en Ph = 1164 W y PL = 870 W. Sustituya estos valores en la ecuación 24-24 y calcule el factor de potencia de la carga. Compare sus resultados con los del inciso (a).

### 3.2.7 CARGAS DESBALANCEADAS 
53. Para la figura 24-58, Rab  60 , Zbc  80 j60 . Calcule

a. Las corrientes de fase y de línea.

b. La potencia en cada fase y la potencia total.

55. Para la figura 24-59, calcule lo siguiente:

a. Las corrientes de línea, sus magnitudes y ángulos.

b. La corriente en el neutro.

c. La potencia en cada fase.

d. Potencia total en la carga.



### 3.2.9 ANÁLISIS DE CIRCUITOS POR COMPUTADORA
## 4. VIDEO
## 5. CONCLUSIONES
### 5.1  TRANSFORMADORES Y CIRCUITOS ACOPLADOS 
### 5.2 SISTEMAS DE TRES FASES 
## 6. BIBLIOGRAFÍA
