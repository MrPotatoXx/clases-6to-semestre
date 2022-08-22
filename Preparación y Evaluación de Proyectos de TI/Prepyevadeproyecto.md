# Calse de Preparacion y Evalualuacion de proyectos TI

### Definiciones financieras

mes = 30 dias

año = 360 dias

## Clase 1

### Interes simple

Se paga al final de cada periodo

	I = P*i*n

El capital inicial (P), la tasa de interés (i) y el tiempo (n)

Ej:

Si se depositan en una cuenta de ahorros $ 5.000.000 y la corporación paga el 3% mensual.

¿Cuál es el pago mensual por interés?

	P = $ 5.000.000

	n = 1 mes

	i = 3%/mes

	I = P*i*n ; I = 5.000.000 * 1 * 0.03 = $ 150.000/ mes.

El depositante recibirá cada mes $ 150.000 por interés.

Cuando no te dicen si es mensual se toma por año (360 dias)

Desventajas:

1. Su aplicacion en las finansas es limitada

2. No concidera el valor en el tiempo

3. No capitaliza los intereses no pagados

#### Monto o valor futuro a interes simple

A la suma del capital inicial, más el interés simple ganado se le llama monto o valor futuro simple, y se simboliza mediante la letra F.

	F = P + I

Al reemplazar la ecuación I = P*i*n en la F = P+I, se tiene,

	F = P + Pin = P(1+in)

Ej:

Hallar el monto de una inversión de $ 200.000, en 5 años, al 25% EA (tasa efectiva anual).

	F = P(1+in) = 200.000(1+0,25x5) = $450.000

#### Valor actial a interes simple

F=P(1+in), y multiplicando a ambos lados por el inverso de (1 + in), se tiene que

	P=F/(1+in)

Ej:

Dentro de dos años y medio se desean acumular la suma de $3.500.000 a una tasa del 2.8% mensual, ¿Cuál es el valor inicial de la inversión?

	P=F/(1+in)=3500000/(1+0,028*30)=$1902173,91

#### Calculo de la tasa de interes simple

F =P(1+ in) , multiplicando a ambos lados por el inverso de P y restando uno a ambos lado de la ecuación se obtiene: (F/P)-1=in , si luego se multiplica los dos términos de la ecuación por el inverso de n, resulta:

	i=((F/P)-1)/n

Ej:

Una persona le prestó a un amigo la suma de $2.000.000 y paga después de 8 meses la suma de $ 2.400.000 ¿Qué tasa de interés mensual simple le cobraron?.

	i=((F/P)-1)/n=((2400000/2000000)-1)/8=0.025 m = 2,5% m

#### Calcuo del tiempo (n)

F =P(1+ in) , multiplicando a ambos lados por el inverso de P y restando uno a ambos lado de la ecuación se obtiene: (F/P)-1=in , si luego se multiplica los dos términos de la ecuación por el inverso de i, resulta:

	n=((F/P)-1)/i

Ej:

¿En cuánto tiempo se acumularían $ 8.000.000 si se depositan hoy $ 2.500.000 en un fondo que paga al 3% simple mensual?.

	n=((F/P)-1)/i=((8000000/25000000)-1)/0,03=73,3 meses

### Interes compuesto

Operacion financieara el cual se suma al interes capital al final de cada periodo

#### Valor futuro equivalente a un presente dado

	F=P(1+i)^n

	F= Monto o valor futuro.
	P = Valor presente o valor actual.
	I = tasa de interés por periodo de capitalización.
	n = Número de periodos ó número de periodos de capitalización

EJ:

El 2 de enero se consignó $150.000 en una cuenta de ahorros y deseo saber cuánto puedo retirar al finalizar el año, si me reconocen una tasa de interés mensual igual a 3%.

	F=P(1+i)^n=150000(1+0.03)^12=$213864


#### Calculo del valor presente equivalente de un futuro dado

	P=F(1+i)^-n

Ej:

Una persona desea invertir hoy una suma de dinero en una institución financiera para retirar $ 2.500.000 dentro de 2 años ¿Cuál será la suma a depositar si el rendimiento reconocido es de 7,01 trimestral?

	P=F(1+i)^-n=25000000(1+0,0701)^-8=$1453935,35

### Valor actual neto (VAN) o Valor presente neto (VPN)

Consiste en actualizar los cobros y pagos de un proyecto o inversión para conocer cuanto se va a ganar o perder con esa inversión.

VAN > 0: El valor actualizado de los cobro y pagos futuros de la inversión, a la tasa de descuento elegida generará beneficios.

VAN = 0: El proyecto de inversión no generará ni beneficios ni pérdidas, siendo su realización, en principio, indiferente.

VAN < 0: El proyecto de inversión generará pérdidas, por lo que deberá ser rechazado

Mientras mas lejos del 0 es mejor

### Tasa de retorno (TIR)

Es la rentabilidad que ofrece una invercion, porcentaje de beneficio o pérdida que tendrá una inversión para las cantidades que no se han retirado del proyecto

Si TIR > k , el proyecto de inversión será aceptado. En este caso, la tasa de rendimiento interno que obtenemos es superior a la tasa mínima de rentabilidad exigida a la inversión.

Si TIR = k , estaríamos en una situación similar a la que se producía cuando el VAN era igual a cero. En esta situación, la inversión podrá llevarse a cabo si mejora la posición competitiva de la empresa y no hay alternativas más favorables.


Si TIR < k , el proyecto debe rechazarse. No se alcanza la rentabilidad mínima que le pedimos a la inversión.

### Retorno del la inversion (ROI)

Es el retorno de la inversion

	ROI = (Ingresos - Inversión) / Inversión

### Relacion costo beneficio

Es la cmparacion de los costos con las ganancias generadas

La siguiente es una lista de pasos que comprenden un análisis genérico de costo-beneficio.

1. Lista las alternativas de proyectos/programas.

2. Listar a las partes

3. Seleccione la/s medida/s y mida todos los elementos de costo/beneficio.

4. Predecir el resultado del costo y los beneficios durante el período pertinente.

5. Convierta todos los costos y beneficios en una moneda común.

6. Aplicar la tasa de descuento.

7. Calcule el valor presente neto de las opciones del proyecto.

8. Realizar análisis de sensibilidad.

9. Adopte la opción recomendada

### Periodo de recuperacion de la inversion (Payback)

criterio para evaluar inversiones que se define como el periodo de tiempo requerido para recuperar el capital inicial de una inversión.