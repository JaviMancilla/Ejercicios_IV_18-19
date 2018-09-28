# EJERCICIOS TEMA 1

## EJERCICIO 1
### Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años.

![servidor](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_1/Imagenes_T1/servidor.png)


- Coste de amortización a cuatro años:

	PVP=1179€;      PVP sin IVA = 974,38€

	Primer Año = 243,60€

	Segundo Año = 243,60€

	Tercer Año = 243,60€

	Cuarto Año = 243,60€	


- Coste de amortización a siete años:

	PVP=1179€;      PVP sin IVA = 974,38€

	Primer año = 139.20€

	Segundo año = 139.20€

	Tercer año = 139.20€

	Cuarto año = 139.20€

	Quinto año = 139.20€

	Sexto año = 139.20€

	Septimo año = 139.20€


## EJERCICIO 2
### Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

![serverplan](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_1/Imagenes_T1/VPS_ejerc2.PNG)

En esta primera imagen, referente a VPS, elegimos el plan "Entrerprise" de la empresa "ServerPlan", con un coste mensual de 99€. 

- Caso donde la infraestructura se use el 1%:
    
	99€ x 12 meses x 0.01 = 11.88 €/año.

- Caso donde la infraestructura se use el 10%:
    
	99€ x 12 meses x 0.1 = 118.8 €/año.

![axarnet](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_1/Imagenes_T1/Cloud_ejerc2.PNG)

En la imagen anterior se muestra el plan elegido para "Cloud". He seleccionado el plan nombrado como "Servidor Claud XL", con un coste mensual de 39.98€, de la empresa "Axarnet", el cual es bastante similar al plan de VPS visto antes.
- Caso donde la infraestructura se use el 1%:

	39.98€ x 12meses x 0.01 = 4.79 €/año

- Caso donde la infraestructura se use el 10%

	39.98€ x 12meses x 0.1 = 47.97 €/año

## EJERCICIO 3
### En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?


- MODELO PROCESADOR: Intel(R) Core(TM) i5-2430M CPU @ 2.40GHz
- SALIDA COMANDO: ``egrep '^flags.*(vmx|svm)' /proc/cpuinfo``

![salida](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_1/Imagenes_T1/salidadE3.png)

## EJERCICIO 4
### 1.Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.

Si, lo tiene.

![salidaE4](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_1/Imagenes_T1/salidaE4_1.png)


### 2.Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.

## EJERCICIO 5
### Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.

## EJERCICIO 6
### Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube anteriores.
