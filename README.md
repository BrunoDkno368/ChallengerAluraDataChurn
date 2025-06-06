                                                         PROYECTO

A continuacion brindamos la resolucion del Proyecto propuesto por la plataforma Alura Latam en la especializacion de Analisis de datos

El proyecto consiste principalmente en varificar la variables que influyen sobre la baja de clientes y el abandono con un dashboard brindado de la empresa Telecom X

Lo que queremos implentar es lo aprendido en los cursos anteriores como uso de google colab, programacion en python, carga, manipulacion de datos y visualizacion de los mismos

                                                       DESARROLLO

**Carga de datos**

En el comienzo del proyecto nos brindan un link de una Api para poder cargar los datos mendiante la boblioteca Pandas en Python

Una vez cargado los datos varias columnas poseen diccionarios normalizamos dichas columnas para poder manipular correctamente los datos

Finalmente cargamos los datos normalizados del dataframe en una variable llamada df

**Manipulacion de datos:**

Una vez normalizados los datos exploramos para ver las variables con las que vamos a trabajar

Primero verificamos con el diccionario brindado que contiene y a que se refiere cada columna

Exploramos las variables que vamos a estudiar separandolas por la caracteristica del cliente y por la caracteristica del contrado del servicio

**Limpieza de datos:**

Durante el proceso de exploracion de los datos vamos a ver que datos contienen datos erroneos, fuera de rango, nulos y datos vacios 

En este caso en particular verificamos columnas que poseen datos vacios y procedemos a eliminarlos

Con los datos de las columnas corregidos verificamos si el tipo de datos que contiene las columas coincides con el tipo brindado en dataframe por ejemplo un dato es un numero y el df nos brinda como object procedemos a corregir el tipo

Creamos una nueva columna llamada Cuentas_diarias ya que el cliente nos pide para saber cuando paga el cliente por dia 

Renombramos columnas para poder tener mayor comprension y estandarizamos datos booleanos por 1 y 0 

**Graficos**

Con los datos ya limpios vamos a proceder a graficar como primera medida vamos a comparar el total gastado con la cancelacion de los cientes 


![cuentas totales](https://github.com/user-attachments/assets/e1df6a2d-7073-44cf-93f2-55520a6fe3c6)


seguidamente graficamos el tiempo de contrato con la cancelacion del servicio 

![tiempo en la empresa](https://github.com/user-attachments/assets/f6b1d567-ec46-4694-b066-d82b0d53ced2)

**Analisi descriptivo**

hacemos una visualizacion de los valores para deteminar como estan distrubuidos por ejemplo la madia, la mediana, la moda y los cuartiles

**Variables categoricas**

Mostramos graficamente las variables categoricas que vamos a comparar con el cancelacion del servicio 

Comparamos el genero
![genero](https://github.com/user-attachments/assets/f0384765-a8c2-4126-96d8-f53e56ba5676)


El tipo de contrato

![tipo de contrato](https://github.com/user-attachments/assets/6c7fdf9b-a829-41c5-be94-46d8d7b9620b)


El metodo de pago 
![metodo de pago](https://github.com/user-attachments/assets/002ad61b-0ba1-4ef7-a8d4-bcac6dddd19c)




