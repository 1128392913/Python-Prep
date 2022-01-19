![HenryLogo](https://henry-11ty-resources.s3.sa-east-1.amazonaws.com/Assets/logo-henry-white-lg.png)

# Primeros Pasos

#### Preparando tu compu

<div class="iframeContainer">
  <iframe src="https://player.vimeo.com/video/638636752" title="Instructivo de Primeros Pasos" allow="autoplay; fullscreen"></iframe>
</div>

> **Importante**: Github cambió el método de autenticación, ahora es por PAT (Personal Access Token), para crearlo pueden seguir este [link](https://docs.github.com/es/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). Pueden elegir expiration infinita para hacerlo una sóla vez.

## Cómo usar SLACK

<div class="iframeContainer">
  <iframe src="https://player.vimeo.com/video/548902078" title="Cómo usar SLACK" allow="autoplay; fullscreen; picture-in-picture"></iframe>
</div>

> Gracias [Nico Constantin (FT#12)](https://github.com/NicoConstantin) por el video y la explicación!

## Editores de Texto

Para poder escribir código que pueda ser interpretado por un lenguaje de programación, necesitamos utilizar un editor de texto.

Hay varios, puedes probarlos y optar por el que te sientas más a gusto.

A continuación veremos una lista de los más populares:

### Sublime Text

![Sublime Text](/_src/assets/00-PrimerosPasos/sublimeText_screen.png)

Es un editor de texto liviano, que cuenta con una serie de plugins para adaptarlo a las necesidades de cada desarrollador.

Es multiplataforma, por lo que se puede instalar tanto en Windows, como Linux y OS X.

Para instalarlo, realizaremos los siguientes pasos:

#### En Windows o en OS X

1. Nos dirigimos a la página oficial de [Sublime Text](https://www.sublimetext.com).

2. Al ingresar, detectará automáticamente el sistema operativo que tenemos, y nos sugerirá descargar el instalador apropiado.

3. Presionamos el botón **_Download_**.

4. Elegimos la opción adecuada según nuestro sistema operativo e iniciamos la descarga.

![Sublime Text Download](/_src/assets/00-PrimerosPasos/sublimeText_download.png)

5. Finalizada la descarga, ejecutamos el instalador, seleccionamos las opciones **_siguiente, siguiente, etc_**, hasta completar el proceso.

#### En Linux, en la distribución Ubuntu y derivados

1. Nos dirigimos al sitio oficial de Sublime Text. Aquí encontrarás las instrucciones para instalarlo:

[Descargar Sublime Text para Linux](https://www.sublimetext.com/docs/3/linux_repositories.html)

2. En la terminal, ejecutamos el siguiente comando, para instalar la clave GPG:

```shell
wget -q0 - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
```

3. Para asegurarnos de que `apt` esté configurado para trabajar con orígenes https, ejecutamos:

```shell
sudo apt-get install apt-transport-https
```

4. Luego para agregar el repositorio estable, ejecutamos:

```shell
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
```

5. Finalmente, procedemos a instalar el programa:

```shell
sudo apt-get install sublime-text
```

Ahora, si en el **Menú de inicio** buscamos **Sublime text**, veremos la siguiente imagen:

![Sublime Text Linux](/_src/assets/00-PrimerosPasos/sublimeText_linux.png)

### Atom

![Atom Site](/_src/assets/00-PrimerosPasos/atom_site.png)

Es un editor de código abierto, disponible tanto para Windows, como Linux y para OS X.

Tiene integrada una consola de Git y Github, para llevar un control de versiones de tus proyectos.
Para comenzar el proceso de instalación, realizamos los siguientes pasos:

En Windows, Linux o en OS X, nos dirigimos al sitio oficial, mediante el siguiente enlace:

<https://atom.io/>

Al ingresar, el navegador detecta automáticamente el instalador que necesitamos bajar, según nuestro sistema operativo.

Allí, presionamos el botón Download para almacenarlo en nuestra computadora.

#### En Windows

Una vez finalizada la descarga, hacemos doble click en el instalador y esperamos a que finalice el proceso de instalación.

#### En Ubuntu y derivados

Descomprimimos el instalador, hacemos doble click, y nos dirigimos a: `/usr/bin/atom`

Al hacer doble click, se abrirá el editor.

### Visual Studio Code

![VSC Console](/_src/assets/00-PrimerosPasos/vsc_console.png)

Es un editor desarrollado por Microsoft.

Tiene integrado el control de versiones mediante Git y Github para tener un seguimiento de tus proyectos. Brinda una cantidad de extensiones que facilitan el trabajo de un desarrollador.

Para descargarlo, nos dirigimos al sitio oficial, en la sección Dowload y descargamos el instalador según nuestro Sistema Operativo:

<https://code.visualstudio.com/download>

![VSC Download](/_src/assets/00-PrimerosPasos/vsc_download.png)

Una vez finalizada la descarga, procedemos a ejecutar el instalador.

## Git

### ¿Qué es Git?

Git es un sistema de control de versiones, distribuido y open source. Un control de versiones es un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas recuperar versiones específicas más adelante.

### Instalación

#### Para Mac y Linux

Ver estos enlaces:

<https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Instalaci%C3%B3n-de-Git>

<https://www.youtube.com/watch?v=PSULlxUk744>

<https://www.youtube.com/watch?v=oV0spTF71AI>

#### Para Windows

Ingreso a <https://git-scm.com> y descargo la útlima versión.

![installGit](/_src/assets/00-PrimerosPasos/instalar_window.png)

Una vez descargado, se abre el archivo .exe y van a visualizar la siguiente ventana

![installGit](/_src/assets/00-PrimerosPasos/1.png)

Clickeamos “Next” hasta que llegamos a esta parte:

![installGit](/_src/assets/00-PrimerosPasos/2.png)

En este momento de la instalación si quieres puedes elegir el editor de texto que van a usar. (Importante, ténganlo instalado antes de instalar Git)

Seguimos clickeando “Next” y luego “Install”

![installGit](/_src/assets/00-PrimerosPasos/3.png)

Por último, finalizar! Si seleccionan la opción "Launch Git Bash", una vez que finalizan la instalación se va a abrir la consola

![installGit](/_src/assets/00-PrimerosPasos/4.png)

Otra forma de abrir la consola es haciendo click derecho sobre el escritorio y elegir la opción "Git Bash Here"

![installGit](/_src/assets/00-PrimerosPasos/consola.png)

Una vez instalado Git van a poder visualizar la consola: ingresamos el comando `git --version` para chequear que está instalado. Si ven la consola así, ya están listos para comenzar a trabajar!

![installGit](/_src/assets/00-PrimerosPasos/5.png)

## GitHub

### ¿Qué es GitHub?

Es una red para almacenar tus repositorios, sería un repositorio de repositorios. Es uno de los tantos disponibles en internet, y el más popular. GitHub **NO** es lo mismo que Git, aunque funcionen muy bien juntos. Github es un lugar donde podés compartir tu código o encontrar otros proyectos. También actúa como portfolio para cualquier código en el que hayas trabajado.

### Comenzando

1. Para comenzar nos creamos una cuenta --- > <https://github.com> 🚀

![GitHub-Register](/_src/assets/00-PrimerosPasos/github_register.png)

2. Una vez registrados, ingresamos con usuario y contraseña:

![GitHub-Login](/_src/assets/00-PrimerosPasos/github_login.png)

3. Listo! Ahora vemos una página de inicio como la siguiente:

![GitHub-Home](/_src/assets/00-PrimerosPasos/github_home.png)

A la izquierda tenemos un acceso rápido a **mis repositorios**.

En el centro vemos la actividad de los usuarios a quienes seguimos.

En la parte superior derecha, vemos nuestra imagen de perfil. Desde ahí podemos desplegar opciones para gestionar nuestro perfil, repositorios y configuración. Si accedemos a nuestro perfil encontramos algo parecido a esto:

![GitHub-profile](/_src/assets/00-PrimerosPasos/github_profile.png)

Podemos poner una foto de perfil, editar el nombre, agregar la ubicación, link y organizaciones a las que pertenecemos. En el centro podemos fijar los repositorios que queremos mostrar para que estén visibles en nuestro perfil.

Más abajo se muestra un diagrama de todas las contribuciones que vamos haciendo a los repositorios.

Si accedemos a la pestaña de arriba que dice `repositorios` veremos una lista de todos ellos. Cuando elegimos un repositorio para ver, nos lleva a una página como esta:

![GitHub-repo](/_src/assets/00-PrimerosPasos/github_repo.png)

Así se ve un repositorio. Arriba a la izquierda tenemos el `nombre de usuario/nombre del repo`.

En el centro podemos ver todos los archivos que tiene dentro el repo. El botón verde que dice `Code` es importante, si clickeamos ahí vamos a poder obtener la url del repo, para así poder **_clonarlo_** (esto lo veremos más adelante).

Arriba a la derecha encontramos tres botones. `Watch` nos permite seguir un repositorio, mientras que con `Star` podemos marcar como favorito un repo que nos guste. Por último tenemos `Fork`, este es **muy** importante, lo vamos a necesitar cuando hagamos el **_Challenge!_**

Ya tenemos todo para empezar... Éxitos!!! 🍀

## Instalación de Python si estás usando Windows:

Python 3.7 (o superior
1. Para obtener el instalador dirígete a [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Descarga el instalador y ejecútalo en tu computadora.
3. Habilita la casilla de verificación en Install launcher for all users y Add Python 3.8 to PATH. A continuación presiona en Install Now. Windows te solicitará permisos para instalar Python en tu computadora.
4. Al finalizar la instalación se abrirá una ventana, en ella deberás presionar en la opción Disable path length limit. Windows te solicitará permisos para realizar este cambio.

Visual Studio Code

Visual Studio Code es un editor de textos que tiene integradas varias herramientas que te ayudarán a desarrollar tus ejercicios con facilidad. Para obtenerlo en tu computadora, dirígete a: [https://code.visualstudio.com/](https://code.visualstudio.com/)

1. Realiza una instalación normal de Visual Studio code.
2. En Visual Studio Code dirígete al panel de Extensiones, se encuentra en el panel lateral izquierdo. Ahí deberás buscar la extensión llamada Python.
3. Selecciona la extensión creada por Microsoft. Una vez seleccionada, instálala.
4. Una vez instalada, reinicia Visual Studio Code.

Listo con esto podrás correr los programas que escribas en python en la terminal de Visual Studio Code.

## Instalación de Python si estás usando Mac:

Dirígete a: [https://es.wikibooks.org/wiki/Python/Instalaci%C3%B3n_de_Python/Python_en_Mac_OS_X](https://es.wikibooks.org/wiki/Python/Instalaci%C3%B3n_de_Python/Python_en_Mac_OS_X)

## Instalación de Python si estás usando Linux:

En una distribución estándar Linux dispone por defecto el interprete Python instalado, para comprobar la correcta instalación solamente debería ejecutar el comando en la consola:

```bash
python
Python 2.7.13 (default, Sep 26 2018, 18:42:22)
[GCC 6.3.0 20170516] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Si le muestra los mensajes anteriores esta correctamente instalado el interprete Python en su Linux.

Si al ejecutar el comando anterior muestra el mensaje:

```bash
python
bash: python: no se encontró la orden
```

Esto es debido a que no tiene instalado el interprete, así que debe ejecutar el siguiente comando:
```bash
sudo apt-get install -y python-dev
```

De nuevo vuelva a ejecutar en su consola de comando el comando python.

# Introducción a la Programación

## ¿Qué es la Programación?

En la imagen, se representa un pequeño robot abeja en una esquina del cuadrilátero, y en la otra una flor. El objetivo del robot abeja es llegar hasta la flor, esquivando los arbustos que hay de por medio. Para esto, hay que decirle cómo se debe mover, pero puede saltar de a un casillero por vez y la forma en que se le puede "decir" es a travez de instrucciones. Esas instrucciones son "arriba", "abajo", "izquierda" y "derecha". Y por supuesto, teniendo en cuenta que debe moverse dentro del cuadrilátero.

Ahora bien, surgen algunas preguntas:

* ¿Cuántas instrucciones son necesarias?

* Al ser más de una instrucción ¿Es importante el orden en que se ejecutan?

* ¿Hay más de una forma, en que el robot abeja pueda llegar a la flor?

* ¿Hay un camino óptimo?

* ¿Cómo puedo medir si un camino es el óptimo con respecto a otros caminos?

![unaImagenConBoxShadow](../_src/assets/01_imagen01.jpg)

Cualquiera de las siguiente, podrían ser una solución:
* Derecha, Derecha, Arriba, Arriba, Derecha, Derecha, Arriba, Arriba, Arriba, Derecha, Derecha, Arriba
* Derecha, Derecha, Derecha, Derecha, Derecha, Derecha, Arriba, Arriba, Arriba, Izquierda, Izquierda, Arriba, Arriba, Derecha, Arriba, Derecha
* Arriba, Derecha, Derecha, Arriba, Arriba, Arriba, Arriba, Arriba, Derecha, Derecha, Derecha, Derecha, Arriba

Lo importante, en principio, es que notemos que al resolver el problema planteado, lo que estamos haciendo, utilizando un pensamiento lógico, es precisamente, **programación**

Entonces, **programar, es armar una secuencia lógica de pasos a seguir, en pos de cumplir un objetivo.** En el ejemplo visto, tuvimos un contexto que nos marcaba las posibilidades y restricciones del problema, por ejemplo moverse dentro del cuadrilátero ó no chocar con los arbustos. Y también un conjunto de instrucciones disponibles, que definian el lenguaje que teníamos que usar, para que el robot comprenda las instrucciones. Lo que usamos fue un lenguaje formal, muy básico y que fue suficiente para resolver el problema. Éstos lenguajes, se denominan lenguajes de programación, nos permiten plasmar esas instrucciones necesarias para darle una solución al problema que queremos resolver, generando así un programa (ó software).

Los primeros lenguajes de programación se escribían en instrucciones que podían interpretar las computadores muy facilmente, pero que resultaban menos amigables a las personas, tales como el lenguaje ensamblador (o Assembler) o Fortran, desarrollado en 1955. Con el tiempo, esto fue cambiando, se fueron desarrolando lenguajes de programación de más alto nivel y con diferentes aplicaciones, que por lo general eran comerciales o científicas, pero tambien con fines educativos, es decir, lenguajes desarrollados para aprender a programar, y consecuentemente, también sea más sencillo. 

Éste último, es el caso de **Python**, que nace a finales de la década del 80 y fue pensado para principiantes por su facilidad de aprendizaje y uso. Su código era compacto pero legible. Con el correr de los años fue incluyendo mejoras hasta llegar tambien a ser de licencia libre. Hoy por hoy, es usado desde en simples "scripts", hasta grandes servidores web que proveen servicio ininterrumpido las 24hs. Es utilizado para la programación de interfaces gráficas y bases de datos. Además tiene una amplia aceptación por científicos que hacen aplicaciones para las supercomputadores más rápidas del mundo y por los niños que recién están comenzando a programar.
La generalización del Big Data en los últimos años, seguida de la explosión de la Inteligencia Artificial, Machine Learning y el surgimiento de la Ciencia de Datos como un nuevo área de trabajo con especialistas propios, ha revolucionado el panorama ya que muchas de las nuevas herramientas que han surgido han sido desarrolladas en Python o nos ofrecen Python como la forma predilecta de interactuar con ellas.
Podemos hablar de tecnología para Big Data como PySpark, de herramientas para Data Science como Pandas, NumPy, Matplotlib o Jupyter. De herramientas del procesamiento del lenguaje natural como NLTK, y por último el área de Deep Learning como Tensorflow, MXNet o Scikit-Learn.

## Sintaxis de un lenguaje de programación

Para el ejemplo se uso un lenguaje con el que era posible determinar los pasos a seguir por el robot abeja hasta llegar a la flor, y nos fue suficiente para poder entender como resolveríamos el problema. El hecho es que, los lenguajes de programación que utilizamos, deben ser más específicos todavía, necesitamos tener un nivel de detalle mayor en nuestras instrucciones, por ejemplo, en lugar de la instruccion "Arriba", podría ser, especificar la cantidad de celdas que hay que moverse, e incluso qué implica "moverse", que seguramente será cambiar el estado de la propia abeja. 
Por otro lado tambien habrá un marco de referencia, es decir, el tablero donde se mueve la abeja y está la flor, en sí mismo, es algo que debemos conocer, saber donde hay ubicado un arbusto y donde no, saber cuales son los límites, y que pasa si con las instrucciones que le damos a la abeja, hacemos que rebase esos límites.
Para solventar esa complejidad, necesitamos un **set de instrucciones** un poco más complejo para poder interactuar con el computador y una forma de representar los datos de la realidad, es decir, dimensiones del tablero donde se mueve la abeja, posición de la abeja, posición de la flor, ubicaciones de los arbustos. Esto se hace mediante lo que se conoce como **estructuras** de datos, las cuales permiten representar la realidad. De hecho, todos **los datos son una representación de la realidad**.
La sintaxis de un programa, consiste en un conjunto de palabras reservadas a instrucciones, con una estructura específica, tal y como funciona un lenguaje como el que usamos los humanos para comunicarnos, como el español o el inglés. Los lenguajes de programación tambien tienen su sintaxis, que esta compuesta por diferentes elementos, como ser variables para representar el dato de la realidad, sentencias para representar las instrucciones ó estructuras de control que conforman el cuerpo del programa.

### El Zen de Python 

Es una colección de los 19 principios que influyen en el diseño del lenguaje Ptyhon. De alguna manera, muestran la filosofía del mismo:

1) Bello es mejor que feo.
2) Explícito es mejor que implícito.
3) Simple es mejor que complejo.
4) Complejo es mejor que complicado.
5) Plano es mejor que anidado.
6) Espaciado es mejor que denso.
7) La legibilidad es importante.
8) Los casos especiales no son lo suficientemente especiales como para romper las reglas.
9) Sin embargo la practicidad gana a la pureza.
10) Los errores nunca deben pasar silenciosamente.
11) A menos que se silencien explícitamente.
12) Frente a la ambigüedad, evitar la tentación de adivinar.
13) Debería haber una, y preferiblemente solo una, manera obvia de hacerlo.
14) A pesar de que esa manera no sea obvia a menos que seas Holandés (el creador lo era)
15) Ahora es mejor que nunca.
16) A pesar de que nunca es muchas veces mejor que ahora mismo.
17) Si la implementación es difícil de explicar, es una mala idea.
18) Si la implementación es fácil de explicar, puede que sea una buena idea.
19) Los namespaces son una gran idea, ¡tengamos más de esos!

## Variables

Una variable es un espacio de memoria donde guardamos un dato, ese espacio de memoria a la vez recibe un nombre:

![unaImagenConBoxShadow](../_src/assets/02_imagen01.jpg)

Y esto conforma la estructura de datos más simple que podemos encontrar.

Por otro lado existen ciertas normas a la hora de nombrar variables:

* El nombre no puede empezar con un número
* No se permite el uso de guiones del medio -
* No se permite el uso de espacios.
* No usar nombres reservados para Python. Las palabras reservadas son utilizadas por Python internamente, por lo que no podemos usarlas para nuestras variables o funciones.

## Constantes

Sin embargo, cuando ese dato no lo alojamos en una variable y lo utilizamos directamente, recibe el nombre de constante.

## Tipos de Datos

Es importante notar, que podemos encontrarnos con datos de tipos distintos, es decir numéricos, alfanuméricos o booleanos.

En Python tenemos los siguientes:
 * Enteros: El conjunto de números naturales
 * Floats: El conjunto de números reales o de punto flotante
 * Cadenas o Strings: Es texto, caracteres alfanuméricos que se introducen entre comillas dobles o simples
 * Booleanos: Representan Verdadero ó Falso
 * Complejos: El conjunto de números complejos

Todo valor que pueda ser asignado a una variable tiene asociado un tipo de dato y esto establece qué operaciones se pueden realizar sobre la misma.

## Operaciones entre Variables

Con diferentes tipos de datos podemos hacer diferentes tipos de operaciones. Y hay operaciones no permitidas entre variables de diferentes tipos de datos.

Tipos de datos numéricos:

| Operacion | Operador | Ejemplo |
| :---      |  :----:  |    ---: |
| Suma      | + | 3 + 5.5 = 8.5 |
| Resta   | -  | 4 - 1 = 3  |
| Multiplicación | *  | 4 * 2 = 8  |
| Potenciación | 4<sup>2</sup>  | 4**2 = 16  |
| División (Cociente) | /  | 4 / 2 = 2  |
| División (parte entera) | //  | 14 // 3 = 4  |
| División (resto) | %  | 14 % 3 =  2 |

Operadores relacionales

| Operacion | Operador | Ejemplo |
| :---      |  :----:  |    ---: |
| == | Igual | 10 == 3 = False |
| != | Distinto | 10 != 3 = True |
| >	| Mayor	| 10 > 3 = True |
| < | Menor	| 10 < 3 = False |
| >= | Mayor o igual | 10 >= 3 = True |
| <= | Menor o igual | 10 <= 3 = False |

Operaciones de asignación:

| Operacion | Operador | Ejemplo |
| :---      |  :----:  |    ---: |
| =   | x=7  | x=7  |
| +=  | x+=2  | x=x+2 = 9  |
| -=  | x-=2  | x=x-2 = 5  |
| *=  | x*=2  | x=x*2 = 14  |
| /=  | x/=2  | x=x/2 = 3.5  |
| %=  | x%=2  | x=x%2 = 1  |
| //=  | x//=2  | x=x//2 = 3  |
| **=  | x**=2  | x=x**2 = 49  |
| &=  | x&=2  | x=x&2 = 2  |
| |=  | x|=2  | x=x|2 = 7  |
| ^=  | x^=2  | x=x^2 = 5  |
| >>=  | x>>=2  | x=x>>2 = 1  |
| <<= | x<<=2 | x=x<<=2 = 28  |

Cuando tratamos con texto, podemos hacer otras operaciones:

| Operacion | Operador | Ejemplo |
| :---      |  :----:  |    ---: |
| Concatenar | + | 'hola ' + 'mundo !' = 'hola mundo!' |
| Multiplicar | * | 'ja ' + 3 = 'ja ja ja' |

Algunos ejemplos en Python:

```python
>>> a = 'Hola '
>>> b = 'Mundo !'
>>> print(a + b)
Hola Mundo !

>>> x = 3
>>> y = 12
>>> print(x + y)
15

>>> print(a + x)
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
~\AppData\Local\Temp/ipykernel_18232/136165486.py in <module>
----> 1 print(a + x)

TypeError: can only concatenate str (not "int") to str
```

Notar que en la operaciones que no están permitidas arroja un error, que es muy descriptivo. En este caso no es posible sumar un valor entero con un valor alfanumérico.

```python
>>> # Dividir "y" entre "x"
>>> y = 9
>>> x = 3
>>> print(y/x)
3.0

>>> # Potencia de "y" elevado a la "x"
>>> y = 2
>>> x = 4
>>> print(y**x)
16

>>> # Devolver el resto de la división
>>> y = 13
>>> x = 3
>>> print(y%x)
1
```

Notar que anteponiendo el caracter numeral (#) es posible agregar comentarios en el código.

Operaciones Lógicas

Son operaciones en las que entran en uso el tipo de datos booleano, es decir, que nos permiten representar valores verdadero ó falso. Para verlo mejor, es necesario recurrir a lo que llamamos tablas de verdad.
Veremos muy comunmente representar verdadero con un "1" y falso con un "0".

Tabla del operador lógico "and", se verifican que A y B sean verdaderas.  
| A | B | A and B |
| :- | :--: | -: |
| 1 | 0 | 0 |
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 1 | 1 |

Tabla del operador lógico "or", se verifican que A ó B sean verdaderas. 
| A | B | A or B |
| :- | :--: | -: |
| 1 | 0 | 1 |
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 1 | 1 |

Tambien es posible representar la negación, con el operador not()

Tabla del operador lógico "Or Exclusiva", se verifica ((A and not(B)) or (not(A) and B))
| A | B | A "or exclusiva" B |
| :- | :--: | -: |
| 1 | 0 | 1 |
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 1 | 0 |

## Flujos de Control

### Condicionales

Los condicionales son bloques de código que se ejecutan únicamente si se cumple una condición. 
El resultado de esta condición debe ser booleano (True o False).
Esto se logra mediante la sentencia **if**.
Con la sentencia **elif** se puede agregar un número arbitrario de condiciones. 
Por otra parte, se puede ejecutar código si la/s condición/es no se cumple/n con la sentencia **else**.


```python
>>> valor = 0
>>> if (valor < 0):
>>>     print('El número es negativo')
>>> elif (valor > 0):
>>>     print('El número es positivo')
>>> else:
>>>     print('El número es igual a cero')
El número es igual a cero
```

### Ciclos Iterativos o Loops

Son bloques de código que se repiten una cierta cantidad de veces en función de ciertas condiciones.

Un ciclo **for** repite un bloque de código tantas veces como elementos haya dentro del rango entre 1 y 10:

```python
>>> for n in range(1,10):
>>>     print(n)
1
2
3
4
5
6
7
8
9
```

Un ciclo **while** repite un bloque de código mientras que cierta condición se cumpla:

```python
>>> n = 1
>>> while (n < 10):
>>>     print(n)
>>>     n = n + 1
1
2
3
4
5
6
7
8
9
```

### Consideraciones

Hemos llegado hasta este punto y se repasaron algunos de los conceptos más fundamentales de la programación y también de Python, pero es necesario detenerse en algunos detalles, que tienen que ver precisamente con el lenguaje que estamos utilizando:

* En Python es importante la indentación, notar que el codigo que se ejecuta dentro de una sentencia if, for o while está indentado.
* Tambien es importante notar los ":"
* En Python hay algunas funcionalidades ya presentes por defecto, como por ejemplo la funcion print() que permite mostrar una salida por pantalla y la función range() que devuelve un rango numérico según los parámetros que recibe y con la función type() es posible ver el tipo de dato de una variable
* En Python, cada vez que hagamos referencia a un rango, por ejemplo "1,10" el primer numero se incluye y el último no.

### Sentencia Break

La sentencia break permite alterar el comportamiento de los bucles while y for. Concretamente, permite terminar con la ejecución del bucle. Esto significa que una vez se encuentra la palabra break, el bucle se habrá terminado.
Veamos como podemos usar el break con bucles for. El range(5) generaría 5 iteraciones, donde la i valdría de 0 a 4. Sin embargo, en la primera iteración, terminamos el bucle prematuramente.
El break hace que nada más empezar el bucle, se rompa y se salga sin haber hecho nada.

```python
>>> for i in range(5):
>>>   print(i)
>>>   break
0
```

Un ejemplo un poco más útil, sería el de buscar una letra en una palabra. Se itera toda la palabra y en el momento en el que se encuentra la letra que buscábamos, se rompe el bucle y se sale. Esto es algo muy útil porque si ya encontramos lo que estábamos buscando, no tendría mucho sentido seguir iterando la lista, ya que desperdiciaríamos recursos.

```python
>>> cadena = 'Python'
>>> for letra in cadena:
>>>     if letra == 'h':
>>>         print("Se encontró la h")
>>>         break
>>>     print(letra)
P
y
t
Se encontró la h
```

El break también nos permite alterar el comportamiento del while. En el ejemplo, la condición while True haría que la sección de código se ejecutara indefinidamente, pero al hacer uso del break, el bucle se romperá cuando x valga cero.

```python
>>> x = 5
>>> while True:
>>>     x -= 1
>>>     print(x)
>>>     if x == 0:
>>>         break
>>>     print("Fin del bucle")
4
3
2
1
0
Fin del bucle
```

Por norma general, y salvo casos muy concretos, si ves un while True, es probable que haya un break dentro del bucle.

### Sentencia Continue

El uso de continue al igual que el ya visto break, permite modificar el comportamiento de de los bucles while y for.
Concretamente, continue se salta todo el código restante en la iteración actual y vuelve al principio en el caso de que aún queden iteraciones por completar.
La diferencia entre el break y continue es que el continue no rompe el bucle, si no que pasa a la siguiente iteración saltando el código pendiente.
En el siguiente ejemplo vemos como al encontrar la letra P se llama al continue, lo que hace que se salte el print(). Es por ello por lo que no vemos la letra P impresa en pantalla.

```python
>>> cadena = 'Python'
>>> for letra in cadena:
>>>     if letra == 'P':
>>>         continue
>>>     print(letra)
y
t
h
o
n
```

## Estructuras de datos

Anteriormente se menciono que un dato representa la realidad, y se presento el concepto de variable, que es un elemento que nos permite guardar un dato dentro de nuestro programa. Sin embargo, rápidamente vamos a llegar a la conclusión de que una variable puede llegar a quedar insuficiente para ciertas representaciones. Ante esta situación, en los lenguajes de programación tenemos estructuras de datos más complejas, en el caso de Python contamos con listas, tuplas y diccionarios.

### Lista

Una estructura de dato muy importante en Python es la lista, que consiste en una serie de elementos ordenados.
Esos elementos pueden ser de distinto tipo, e incluso pueden ser de tipo lista también.<br>

Operaciones con listas:
* Creacion 
```python
mi_lista = ['Rojo','Azul','Amarillo','Naranja','Violeta','Verde']
```
* Imprimir
```python
print(mi_lista)
```
* Ver el tipo de dato 
```python
type(mi_lista)
```

Las listas, así como otras estructuras de datos que se verán en adelante, tienen varios elementos, motivo por el cual cuando se quiere acceder en específico se requiere de un **índice** que va a hacer referencia al elemento dentro de la lista:

* Imprimir el tercer elemento de la lista (el índice comienza en cero)
```python
print(mi_lista[2])
```
* Acceder a un rango dentro de la lista (el limite inferior se incluye y el superior se excluye)
```python
print(mi_lista[0:2])
```
* Al no poner primer valor, Python asume que es un 0
```python
>>> print(mi_lista[:2])
['Rojo', 'Azul']
```
* Al no poner segundo valor, Python asume que se trata de todos los elementos a partir del primero 
```python
 >>> print(mi_lista[0:])
 ['Rojo', 'Azul', 'Amarillo', 'Naranja', 'Violeta', 'Verde']
 ```
* Agregar un elemento al final de la lista (Si el elemento ya existe va a quedar duplicado)
```python
mi_lista.append('Blanco') 
```
* Agregar un elemento especificando el indice 
```python
 >>> mi_lista.insert(3,'Negro')
 >>> print(mi_lista[:])
['Rojo', 'Azul', 'Amarillo', 'Negro', 'Naranja', 'Violeta', 'Verde']
```
* Concatenar una nueva lista a la lista previamente creada 
```python
mi_lista.extend(['Marrón','Gris'])
```
* Encontrar el índice de un valor específico 
```python
>>> print(mi_lista.index('Azul'))
1
```
* Eliminar un elemento de la lista (Si el elemento no existe va a arrojar un error)
```python 
>>> mi_lista.remove('Blanco') 
---------------------------------------------------------------------------
ValueError                                Traceback (most recent call last)
~\AppData\Local\Temp/ipykernel_10044/308548076.py in <module>
----> 1 mi_lista.remove('Blanco')

ValueError: list.remove(x): x not in list
>>> mi_lista.remove('Negro') 
```
* Extraer y recuperar el último elemento de la lista 
```python 
>>> ultimo = mi_lista.pop()
>>> print(ultimo)
Gris
```
* Multiplicar la lista 3 veces 
```python 
>>> print(['a','b','c'] * 3)
['a', 'b', 'c', 'a', 'b', 'c', 'a', 'b', 'c']
```

### Tupla

La diferencia con la lista es que no se pueden modificar una vez creadas, es decir que son **inmutables**:

* Convertir una lista a tupla 
```python 
mi_tupla=tuple(mi_lista)
```
* Imprimir el índice 1 de la tupla 
```python 
>>> print(mi_tupla[1])
Azul
```
* Evaluar si un elemento está contenido en la tupla (Devuelve un valor booleano)
```python
>>> 'Rojo' in mi_tupla
True
```
* Evaluar las veces que está un elemento específico 
```python
>>> mi_tupla.count('Rojo')
1
```
* Tupla con un solo elemento 
```python
mi_tupla_unitaria = ('Blanco',)
```
* Empaquetado de tupla, tupla sin paréntesis 
```python
mi_tupla='Gaspar', 5, 8, 1999
```
* Desempaquetado de tupla, se guardan los valores en orden de las variables 
```python
>>> nombre, dia, mes, año = mi_tupla
>>> print("Nombre: ", nombre, " - Dia:", dia, " - Mes: ", mes, " - Año: ", año)
Nombre:  Gaspar  - Dia: 5  - Mes:  8  - Año:  1999
```
* Convertir una tupla en una lista 
```python
mi_lista=list(mi_tupla)
```

### Diccionario

Un diccionario tiene una organización de 'clave' y 'valor':

* Crear un diccionario 
```python
mi_diccionario = {  'Colores Primarios': ['Rojo','Azul','Amarillo'], 
                    'Colores secundarios': ['Naranja','Violeta','Verde'], 
                    'Clave3': 10,
                    'Clave4': False}
```
* Imprimir un valor a través de su clave 
```python
>>> print(mi_diccionario['Colores secundarios'])
['Naranja', 'Violeta', 'Verde']
```
* Agregar un valor 
```python
mi_diccionario['Clave5']='Otro ejemplo'
```
* Cambiar un valor 
```python
mi_diccionario['Clave3']=2
```
* Eliminar un elemento de un diccionario a través de su clave 
```python
del mi_diccionario['Clave4']
```
* Utilizar una tupla como clave de un diccionario 
```python
mi_tupla=("Argentina", "Italia", "Inglaterra")
mi_diccionario={mi_tupla[0]:"Buenos Aires", 
                mi_tupla[1]:"Roma", 
                mi_tupla[2]:"Londres"}
```
* Colocar una tupla dentro de un diccionario 
```python
mi_diccionario={'Clave1':'Valor1', 'Clave2':(1,2,3,4,5)}
```
* Colocar una lista dentro de un diccionario (Notar que la diferencia está en el paréntesis '()' y el corchete '[]')
```python
 mi_diccionario={'Clave1':'Valor1', 'Clave2':[1,2,3,4,5]} 
 ```
* Colocar un diccionario dentro de un diccionario 
```python
mi_diccionario={'Clave1':'Valor1', 'Clave2':{'numeros':[1,2,3,4,5]}}
```
* Imprimir las claves del diccionario 
```python
 >>> print(mi_diccionario.keys())
 dict_keys(['Clave1', 'Clave2'])
 ```
* Imprimir los valores del diccionario 
```python
 >>> print(mi_diccionario.values())
 dict_values(['Valor1', {'numeros': [1, 2, 3, 4, 5]}])
 ```
* Imprimir la longitud del diccionario 
```python
 >>> len(mi_diccionario)
 2
 ```

#### Consideraciones

* La funcionalidad **del** permite eliminar cualquier estructura de datos
* La funcionalidad **len** permite obtener el tamaño de la estructura de datos

## Iteradores e iterables

Permiten iterar colecciones de datos que sean iterables. Si tenemos una determinada colección de datos, en este caso una lista con varios valores, y queremos mostrar sus valores uno a uno por pantalla podría resolverse de la siguiente manera con un while.

```python
>>> lista = [5, 4, 9, 2]
>>> i = 0
>>> while i < len(lista):
>>>     elemento = lista[i]
>>>     print(elemento)
>>>     i += 1
5
4
9
2
```

Aunque es una forma válida, en Python existe una forma mucho más fácil de iterar una lista. Dicha forma es la siguiente.

```python
>>> lista = [5, 4, 9, 2]
>>> for elemento in lista:
>>>     print(elemento)
5
4
9
2
```

### Iterables

Una clase iterable es una clase que puede ser iterada. Dentro de Python hay gran cantidad de clases iterables como las listas, strings, diccionarios o archivos. Si tenemos una clase iterable, podemos usarla a la derecha del for de la siguiente manera.

```python
for elemento in [clase_iterable]:
```

En el ciclo for, como se puede ver, la variable elemento irá tomando los valores de cada elemento presente en la clase iterable. De esta manera, ya no tenemos que ir accediendo manualmente con [] a cada elemento.
Anteriormente hemos visto un ejemplo iterando una lista, pero también podemos iterar una cadena, ya que es una clase iterable. Al iterar una cadena se nos devuelve cada letra presente en la misma. La sintaxis se asemeja bastante al lenguaje natural, sería algo así como decir “poner en c cada elemento presente en la cadena”.

```python
>>> cadena = "Hola"
>>> for c in cadena:
>>>     print(c)
H
o
l
a
```

Para saber si una clase es iterable o no hay dos opciones. La primera sería consultar la documentación oficial de Python. La segunda es ver si la clase u objeto en cuestión hereda de Iterable. Con isinstance() podemos comprobar si una clase hereda de otra.

```python
>>> from collections import Iterable
>>> cadena = "Hola"
>>> numero = 3
>>> print("cadena", isinstance(cadena, Iterable))
>>> print("numero", isinstance(numero, Iterable))
cadena True
numero False
```

Python nos ofrece también diferentes métodos que pueden ser usados sobre clases iterables como los que se muestran a continuación:

* list() convierte a lista una clase iterable
* sum() para sumar
* join() permite unir cada elemento de una clase iterable con el primer argumento usado.

```python
>>> print(list("Hola"))
['H', 'o', 'l', 'a']

>>> print(sum([1, 2, 3]))
6

>>> print("-".join("Hola"))
H-o-l-a
```

De la misma forma que iteramos una cadena o una lista, también podemos iterar un diccionario. El iterador del diccionario devuelve las claves o keys del mismo.

```python
>>> mi_dict = {'a':1, 'b':2, 'c':3}
>>> for i in mi_dict:
>>>     print(i)
a
b
c
```

### Iteradores

Se podría explicar la diferencia entre iteradores e iterables usando un libro como analogía. El libro sería nuestra clase iterable, ya que tiene diferentes páginas a las que podemos acceder. El libro podría ser una lista, y cada página un elemento de la lista. Por otro lado, el iterador sería un marcapáginas, es decir, una referencia que nos indica en qué posición estamos del libro, y que puede ser usado para “navegar” por él.
Es posible obtener un iterador a partir de una clase iterable con la función iter(). En el siguiente ejemplo podemos ver como obtenemos el iterador del libro.

```python
>>> libro = ['página1', 'página2', 'página3', 'página4']
>>> marcapaginas = iter(libro)
```

Llegados a este punto, nuestro marcapaginas almacena un iterador. Se trata de un objeto que podemos usar para navegar a través del libro. Usando la función next() sobre el iterador, podemos ir accediendo secuencialmente a cada elemento de nuestra lista (las páginas de libro).

```python
>>> print(next(marcapaginas))
>>> print(next(marcapaginas))
>>> print(next(marcapaginas))
>>> print(next(marcapaginas))
página1
página2
página3
página4
```

Algo parecido a esto es lo que sucede por debajo cuando usamos el for sobre una clase iterable. Se va accediendo secuencialmente a los elementos hasta que la excepción StopIteration es lanzada. Dicha excepción se lanza cuando hemos llegado al final, y no existen más elementos que iterar.

```python
>>> print(next(marcapaginas))
---------------------------------------------------------------------------
StopIteration                             Traceback (most recent call last)
~\AppData\Local\Temp/ipykernel_10044/1391636315.py in <module>
----> 1 print(next(marcapaginas))
```

Una nota muy importante es que cuando el iterador es obtenido con iter() como hemos visto, apunta por defecto fuera de la lista. Es decir, si queremos acceder al primer elemento de la lista, deberemos llamar una vez a next().
Por otro lado, a diferencia de un marcapáginas de un libro, el iterador sólo puede ir hacia delante. No es posible retroceder.


### Sentencia zip

Si pasamos dos listas a zip como entrada, el resultado será una tupla donde cada elemento tendrá todos y cada uno de los elementos i-ésimos de las listas pasadas como entrada.

```python
>>> a = [1, 2]
>>> b = ["Uno", "Dos"]
>>> c = zip(a, b)
>>> type(c)
zip
>>> list(c)
[(1, 'Uno'), (2, 'Dos')]
```

### Añadiendo condicionales

Hemos visto como modificar todos los elementos de un iterable (como una lista) de diferentes maneras, pero ¿y si quisiéramos realizar la operación sobre el elemento sólo si una determinada condición se cumple? Debemos añadir un condicional if. 
La expresión genérica sería la siguiente.

lista = [expresión for elemento in iterable if condición]

Por lo tanto la expresión sólo se aplicará al elemento si se cumple la condición. Veamos un ejemplo con una frase, de la que queremos saber el número de erres que tiene.

```python
>>> frase = "El perro de san roque no tiene rabo"
>>> erres = [i for i in frase if i == 'r']
>>> print(errores)
['r', 'r', 'r', 'r']
>>> print(len(erres))
4
```

Lo que hace el código anterior es iterar cada letra de la frase, y si es una r, se añade a la lista. De esta manera el resultado es una lista con tantas letras r como la frase original tiene, y podemos calcular las veces que se repite con len().

## Funciones

Las funciones son una secuencia de comandos que ejecutan una sección de código. En Python las funciones se definen usando la palabra reservada **def** y luego el nombre de la función con paréntesis y dos puntos que indican que lo que sigue son las sentencias, eventualmente una función debe retornar un valor, para esto se usa la palabra reservada **return**.

### Limites al declarar funciones

* Los nombres no pueden comenzar con digitos
* No pueden utilizar una palabra reservada
* Las variables deben tener diferentes nombres
* Los nombres de las funciones deben ser descriptivas de lo que hacen las funciones "Imprimir_valor_variable"
* Los parámetros pueden tener valores por defecto.
* Se puede devolver ningun, uno o más de un valor, y de diferentes tipos de datos.
* Se puede asignar a variables, el resultado de retorno de una función.

Para poder imprimir el valor de una variable dentro de un string podemos hacerlo así:

```python  
>>> def imprimir_valor_variable(var):
>>>     print('El valor de la variable es' + str(var))
```

Para devolver dos números ordenados de menor a mayor podemos hacerlo así:

```python
>>> def ordenar_dos_numeros(num1=0, num2=0):
>>>     if (num1 > num2):
>>>         return num2, num1
>>>     else:
>>>         return num1, num2
```

### Declarar y Ejecutar

Declarar una función es escribir su estructura y ejecutar una función es llamar la función y ejecutar su código, estas dos cosas ocurren en sentencias diferentes.

### Donde se puede acceder a las variables

Cada vez que una función se ejecuta se genera un contenedor donde las variables de la función van a vivir, una vez se sale de la función estas variables dejan de existir, esto se denomina espacio de nombres, alcance o scope de la función.
Dentro de una función puede haber una variable que solo se pueda utilizar dentro del cuerpo de la función, son **variables locales**. Mientras que las variables en el código desde el cual se llama a la función, son **variables globales**.

![unaImagenConBoxShadow](../_src/assets/02_imagen07.jpg)

``` python
>>> def dividir(dividendo, divisor = 1):
>>>     if (divisor == 0):
>>>         return 'No se puede dividir por cero'
>>>     else:
>>>         return dividendo / divisor
>>> print(dividir(10))
10.0
>>> print(divisor)
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
~\AppData\Local\Temp/ipykernel_10044/1862935505.py in <module>
----> 1 print(divisor)

NameError: name 'divisor' is not defined
``` 

En este caso, 'divisor' es una variable local dentro de la función. Deja de existir cuando termina el llamado a la función, lo que denota el mensaje de error es que no encuentra esa variable para imprimir, porque de hecho, solo existió dentro del espacio de nombres de la función.

``` python
>>> divisor = 5
>>> def dividir(dividendo):
>>>     if (divisor == 0):
>>>         return 'No se puede dividir por cero'
>>>     else:
>>>         return dividendo / divisor
>>> print(dividir(10))
2.0
>>> print(divisor)
5
``` 

En este caso 'divisor' es una variable global. En el llamado de la función, como no encuentra una variable local llamada 'divisor', busca una variable global llamada 'divisor'. Desde dentro de la función, si se tiene acceso al espacio de nombres que la invoca.

``` python
>>> divisor = 5
>>> def dividir(dividendo, divisor = 1):
>>>     if (divisor == 0):
>>>         return 'No se puede dividir por cero'
>>>     else:
>>>         return dividendo / divisor
>>> print(dividir(10))
10.0
>>> print(divisor)
5
``` 

En este caso existe 'divisor' como variable global y 'divisor' como variable local. El llamado a la función usa siempre primero la variable local.

### Recursividad

En ocasiones, según la problemática que se quiera resolver, podemos utilizar la recursividad, que consiste en una función que hace referencia a sí misma. Python lo permite admitiendo el uso de las **llamadas recursivas**.
Entre las ventajas de usar funciones podemos encontrar que se obtiene código reutilizable y más prolijo o legible.
Es importante notar también que se puede documentar, mediante la inserción de comentarios y el uso de la función help().

``` python
>>> def factorial(numero):
>>>     '''
>>>     Devuelve el factorial
>>>     '''
>>>     if (numero > 1):
>>>         numero = numero * factorial(numero - 1)
>>>     return numero
>>> factorial(3)
6
>>> help(factorial)
Help on function factorial in module __main__:

factorial(numero)
    Devuelve el factorial
``` 

### Pasaje de parámetros por valor y referencia

En muchos lenguajes de programación existen los conceptos de paso por valor y por referencia que aplican a la hora de como trata una función a los parámetros que se le pasan como entrada. Su comportamiento es el siguiente:

Si usamos un parámetro pasado por **valor**, se creará una copia local de la variable, lo que implica que cualquier modificación sobre la misma no tendrá efecto sobre la original.
Con una variable pasada como **referencia**, se actuará directamente sobre la variable pasada, por lo que las modificaciones afectarán a la variable original.
En Python las cosas son un poco distintas, y el comportamiento estará definido por el tipo de variable con la que estamos tratando. 

Veamos un ejemplo de paso por valor.
``` python
>>> x = 10
>>> def funcion(entrada):
>>>     entrada = 0
>>> funcion(x)
>>> print(x)
10
``` 

Iniciamos la x a 10 y se la pasamos a funcion(). Dentro de la función hacemos que la variable valga 0. Dado que Python trata a los int como pasados por valor, dentro de la función se crea una copia local de x, por lo que la variable original no es modificada.

No pasa lo mismo si por ejemplo x es una lista como en el siguiente ejemplo. En este caso Python lo trata como si estuviese pasada por referencia, lo que hace que se modifique la variable original. La variable original x ha sido modificada.

``` python
>>> x = [10, 20, 30]
>>> def funcion(entrada):
>>>     entrada.append(40)
>>> 
>>> funcion(x)
>>> print(x)
[10, 20, 30, 40]
```

El ejemplo anterior nos podría llevar a pensar que si en vez de añadir un elemento a x, hacemos x=[], estaríamos destruyendo la lista original. Sin embargo esto no es cierto.

``` python
>>> x = [10, 20, 30]
>>> def funcion(entrada):
>>>     entrada = []
>>> funcion(x)
>>> print(x)
[10, 20, 30]
``` 

Una forma muy útil de saber lo que pasa por debajo de Python, es haciendo uso de la función id(). Esta función nos devuelve un identificador único para cada objeto. Volviendo al primer ejemplo podemos ver como los objetos a los que “apuntan” x y entrada son distintos.

``` python
>>> x = 10
>>> print(id(x))
4349704528
>>> def funcion(entrada):
>>>     entrada = 0
>>>     print(id(entrada))
>>> funcion(x)
4349704208
>>> print(x)
10
``` 

Sin embargo si hacemos lo mismo cuando la variable de entrada es una lista, podemos ver que en este caso el objeto con el que se trabaja dentro de la función es el mismo que tenemos fuera.

``` python
>>> x = [10, 20, 30]
>>> print(id(x))
4422423560
>>> def funcion(entrada):
>>>     entrada.append(40)
>>>     print(id(entrada))
>>> funcion(x)
4422423560
>>> print(x)
[10, 20, 30, 40]
```

Entonces, en Python por defecto los valores simples se pasan por valor (int, float, string, bool, complex)

### Consideraciones

Es importante notar que cuando se hacen asignaciones entre variables, si no usamos el método copy(), lo que vamos a estar haciendo en realidad, es referenciar al mismo valor con dos variables distintas, pero esto ocurre sólo ante tipos de datos complejos. 
Sigamos el ejemplo:


```python
>>> # Se crea la variable x con el valor 1
>>> x = 1
>>> # Se asigna x a la variable y
>>> y = x
>>> # Se modifica la variable y asignándole el valor 2
>>> y = 2
>>> # ¿Qué valor ahora tienen ambas?
>>> print(x)
1
>>> print(y)
2
```

Vamos a hacer el mismo proceso, pero asignando una lista:

```python
>>> # Se crea la variable x con la lista [1,2]
>>> x = [1,2]
>>> # Se asigna x a la variable y
>>> y = x
>>> # Se modifica la variable y agregando un elemento
>>> y.append(3)
>>> # ¿Qué valores ahora tienen ambas?
>>> print(x)
[1,2,3]
>>> print(y)
[1,2,3]
```

Notar que ahora x e y referencian al mismo espacio de memoria, el cuál contiene la lista [1,2,3].<br>
Ahora se utiliza el método copy():

```python
>>> # Se crea la variable x con la lista [1,2]
>>> x = [1,2]
>>> # Se asigna x a la variable y
>>> y = x.copy()
>>> # Se modifica la variable y agregando un elemento
>>> y.append(3)
>>> # ¿Qué valores ahora tienen ambas?
>>> print(x)
[1,2]
>>> print(y)
[1,2,3]
```

Notar que ahora x e y referencian a espacios de memoria distintos.

### Funciones Lambda

La función Lambda es una forma conveniente de crear una función en una sola línea. También se las conoce como funciones anónimas, ya que no tienen nombre, sino que se asignan a una variable.

* Pueden tener cualquier cantidad de argumentos, pero solo una expresión.
* No necesitan un return.
* Muy cómodas para crear funciones rápido.

``` python
>>> lambda_producto = lambda x, y: x * y
>>> lambda_producto(3, 4)
12
``` 

## Clases y objetos (POO)

El alto grado de planificación y previsión que requiere la programación es contrario a la propia realidad. El hombre aprende y crea a través de la experimentación, no de la planeación. La Orientación a Objetos (POO) brinda estos métodos de experimentación, y logra que los lenguajes sean de más alto nivel, es decir, más cercanos a como los humanos pensamos el mundo. Es decir, vemos la realidad como objetos que se interrelacionan y realizan acciones, y esto, es lo que se intenta emular en la POO.
Hasta 1966 la programación fue exclusivamente lineal, hasta que surgieron lenguajes como Simula, SmallTalk, C++, Ada, Delphi o Java. Hoy el lenguaje más popular es Python y su filosofía hace hincapié en la legibilidad de su código. 

### Objeto

Una estructura de datos que eventualmente tiene funciones asociadas, que están agrupados por razones de consistencia y comodidad conforman un **objeto**.
En la composición de un objeto tenemos entonces **propiedades** (datos) y **métodos** (funciones asociadas).

### Clase

Hay una diferencia muy importante entre un objeto y una variable, y es que mientras que la variable 'se crea', el objeto 'se instancia', lo que implica, ademas de su creación propiamente dicha, que su creación se realiza en base a una definición preliminar, disponibilizando en memoria, no solo la estructura de datos asociada sino sus métodos. Por medio de esta mecánica, además, se puede instanciar más de un solo objeto con la misma definicion. Esta definición, es una generalización del objeto, es decir que especifica que estructura de datos va a tener y qué métodos asociados. Esto lo que se conoce como **clase**

### Pilares de la Programación Orientada a Objetos

* **Abstracción**: Es cuando separamos los datos de un objeto para luego generar un molde (una clase).
* **Encapsulamiento**: Se utiliza cuando es necesario que ciertos métodos o propiedades sean inviolables o inalterables.
Un ejemplo del encapsulamiento podría ser una cuenta de banco, donde el usuario no puede simplemente aumentar su balance de dinero, si no que debe depender de unos métodos previamente validados para aumentar dicho balance (depósitos, transferencias, etc).
* **Herencia**: Permite crear nuevas clases a partir de otras. Si tuviéramos una clase “Autos” y quisiéramos crear unas clases “Auto deportivo” o “Auto clásico”, podríamos tomar varias propiedades y métodos de la clase “Autos”. Esto nos da una jerarquía de padre e hijo.
* **Polimorfismo**: Proviene de Poli = muchas, morfismo = formas. Se utiliza para crear métodos con el mismo nombre pero con diferente comportamiento.

### Ejemplos:

* Clase Animal<br>
&nbsp;&nbsp;- Especie<br>
&nbsp;&nbsp;- Edad<br>
&nbsp;&nbsp;- Color<br>
&nbsp;&nbsp;- Correr()<br>
&nbsp;&nbsp;- Dormir()<br>

Se instancian distintos objetos a partir de una clase:

* Objeto1<br>
&nbsp;&nbsp;- Especie: 'Perro'<br>
&nbsp;&nbsp;- Edad: 3<br>
&nbsp;&nbsp;- Color: 'Blanco'<br>
&nbsp;&nbsp;- Correr()<br>
&nbsp;&nbsp;- Dormir()<br>

* Objeto2
&nbsp;&nbsp;- Especie: 'Caballo'<br>
&nbsp;&nbsp;- Edad: 8<br>
&nbsp;&nbsp;- Color: 'Marrón'<br>
&nbsp;&nbsp;- Correr()<br>
&nbsp;&nbsp;- Dormir()<br>

* A partir de la sentencia **class** y el nombre de creamos la clase.
* La función **__init__()** es el **constructor** de la clase, esta función se ejecuta cuando se instancia el objeto.
* La clase posee atributos (especie, edad, color) y métodos que manipulan esos atributos (mePresento, cumplirAños).

``` python
>>> class Animal:
>>> '''
>>> En esta clase se crean los animales
>>> '''
>>> def __init__(self, especie, edad, color):
>>>     self.especie = especie
>>>     self.edad = edad
>>>     self.color = color
>>> def mePresento(self):
>>>     print('Hola, soy ', self.especie, ', de color', self.color, ' y tengo ', self.edad, ' años')
>>> def cumplirAños(self):
>>>     self.edad = self.edad + 1
>>> 
>>> a1 = Animal('Ratón', 2, 'Marrón')
>>> print(a1.especie)
Ratón
>>> print(a1.edad)
2
>>> a2 = Animal('Liebre', 3, 'Gris')
>>> print(a2.especie)
Liebre
>>> print(a2.edad)
3
``` 

Creamos los objetos a1 y a2. Al hacerlo se envían los parámetros de inicialización de sus atributos.
Utilizamos sus métodos para mostrar los atributos y/o modificarlos.
Este formato de clases, objetos, métodos y parámetros es muy común en Python y lo utilizamos cada vez que invocamos alguna de sus **librerías**

``` python
>>> a1.mePresento()
Hola, soy  Ratón , de color Marrón  y tengo  2  años
>>> a2.mePresento()
Hola, soy  Liebre , de color Gris  y tengo  3  años
>>> a1.cumplirAños()
>>> a1.mePresento()
Hola, soy  Ratón , de color Marrón  y tengo  3  años
```

## Librerías

Las librerías son proyectos con metodos o funciones puntuales, el cual es posible anexar a otros proyectos y complementarlo usando sus metodos especificos para una determinada solución. Son trozos de código hechos por terceros. Facilita mucho la programación y hace que nuestro programa sea más sencillo de hacer y luego de entender. También llamadas 'Frameworks', consiste en archivos de código a los que se invoca al proncipio de nuestro propio código.

### Módulos

Un módulo en Python es un archivo con extensión ".py" que alberga un conjunto de funciones, variables o clases y que puede ser usado por otros módulos. Nos permiten reutilizar código y organizarlo mejor en namespaces. Por ejemplo, podemos definir un módulo mimodulo.py con dos funciones suma() y resta().


``` python
>>> # mimodulo.py
>>> def suma(a, b):
>>>     return a + b
>>> 
>>> def resta(a, b):
>>>     return a - b
```

Una vez definido, dicho módulo puede ser usado o importado en otro código usando **import**, con lo que se puede acceder a todo el contenido.

``` python
>>> # otromodulo.py
>>> import mimodulo
>>> 
>>> print(mimodulo.suma(4, 3))
7
>>> print(mimodulo.resta(10, 9))
1
``` 

También podemos importar únicamente los componentes que nos interesen como mostramos a continuación.

``` python
>>> from mimodulo import suma, resta
>>> 
>>> print(suma(4, 3))   # 7
>>> print(resta(10, 9)) # 1
```

Por último, podemos importar todo el módulo haciendo uso de *, sin necesidad de usar mimodulo.*.

``` python
>>> from mimodulo import *
>>> 
>>> print(suma(4, 3))
7
>>> print(resta(10, 9))
1
```

### Consideraciones

Los módulos o librerías, permiten que Python pueda ser utilizado en diferentes entornos:

- **Desarrollo Web**: Existen frameworks como Django, Pyramid, Flask o Bottle que permiten desarrollar páginas web a todos los niveles.
- **Ciencia y Educación**: Debido a su sintaxis tan sencilla, es una herramienta perfecta para enseñar conceptos de programación a todos los niveles. En lo relativo a ciencia y cálculo numérico, existen gran cantidad de librerías como SciPy o Pandas.
- **Desarrollo de Interfaces Gráficos**: Gran cantidad de los programas que utilizamos tienen un interfaz gráfico que facilita su uso. Python también puede ser usado para desarrollar GUIs con librerías como Kivy o pyqt.
- **Desarrollo Software**: También es usado como soporte para desarrolladores, como para testing.
- **Machine Learning**: En los último años ha crecido el número de implementaciones en Python de librerías de aprendizaje automático como Keras, TensorFlow, PyTorch o sklearn.
- **Visualización de Datos**: Existen varias librerías muy usadas para mostrar datos en gráficas, como matplotlib, seaborn o plotly.
Finanzas y Trading: Gracias a librerías como QuantLib o qtpylib y a su facilidad de uso, es cada vez más usado en estos sectores.

### Rutas y Uso de sys.path

Normalmente los módulos que importamos están en la misma carpeta, pero es posible acceder también a módulos ubicados en una subcarpeta. Imaginemos la siguiente estructura:

``` bash
.
├── ejemplo.py
├── carpeta
│   └── modulo.py
```

Donde modulo.py contiene lo siguiente:

``` python
>>> # modulo.py
>>> def hola():
>>> 	print("Hola")
```

Desde nuestro ejemplo.py, podemos importar el módulo modulo.py de la siguiente manera:

``` python
>>> from carpeta.modulo import *
>>> print(hola())
Hola
```

Es importante notar que Python busca los módulos en las rutas indicadas por el **sys.path**. Es decir, cuando se importa un módulo, lo intenta buscar en dichas carpetas. Puedes ver tu sys.path de la siguiente manera:

``` python
>>> import sys
>>> print(sys.path)
```

Como es obvio, verás que la carpeta de tu proyecta está incluida, pero ¿y si queremos importar un módulo en una ubicación distinta? Pues bien, podemos añadir al sys.path la ruta en la que queremos que Python busque.

``` python
>>> import sys
>>> sys.path.append(r'/ruta/de/tu/modulo')
``` 

Una vez realizado esto, los módulos contenidos en dicha carpeta podrán ser importados sin problema como hemos visto anteriormente.

Por otro lado, es posible cambiar el nombre del módulo usando **as**. Imaginemos que tenemos un módulo moduloconnombrelargo.py.

``` python
>>> # moduloconnombrelargo.py
>>> hola = "hola"
```

En vez de usar el siguiente import, tal vez queramos asignar un nombre más corto al módulo.

``` python
>>> import moduloconnombrelargo
>>> print(moduloconnombrelargo.hola)
```

Podemos hacerlo de la siguiente manera con as:

``` python
>>> import moduloconnombrelargo as m
>>> print(m.hola)
``` 

La función **dir()** nos permite ver los nombres (variables, funciones, clases, etc) existentes en nuestro namespace. Si probamos en un módulo vacío, podemos ver como tenemos varios nombres rodeados de __. Se trata de nombres que Python crea por debajo.

``` python
>>> print(dir())
['__annotations__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__']
```

Por ejemplo, __file__ es creado automáticamente y alberga el nombre del archivo .py.

``` python
>>> print(__file__)
/tu/ruta/tufichero.py
```

Imaginemos ahora que tenemos alguna variable y función definida en nuestro script. Como era de esperar, dir() ahora nos muestra también los nuevos nombres que hemos creado, y que por supuesto pueden ser usados.

``` python
>>> mi_variable = "Python"
>>> def mi_funcion():
>>>     pass
>>> print(dir())
['__annotations__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'mi_funcion', 'mi_variable']
``` 

Por último, vamos a importar el contenido de un módulo externo. Podemos ver que en el namespace tenemos también los nombres resta y suma, que han sido tomados de mimodulo.

``` python
>>> from mimodulo import *
>>> print(dir())
['__annotations__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'resta', 'suma']
```

El uso de dir() también acepta parámetros de entrada, por lo que podemos por ejemplo pasar nuestro modulo y nos dará más información sobre lo que contiene.

``` python
>>> import mimodulo
>>> print(dir(mimodulo))
['__builtins__', '__cached__', '__doc__', '__file__','__loader__', '__name__', '__package__', '__spec__', 'resta', 'suma']
>>> print(mimodulo.__name__)
mimodulo
>>> print(mimodulo.__file__)
/tu/ruta/mimodulo.py
```

Importar un módulo puede lanzar la excepción "ImportError", cuando se intenta importar un módulo que no ha sido encontrado. Se trata de ModuleNotFoundError.

``` python
>>> import moduloquenoexiste
ModuleNotFoundError: No module named 'moduloquenoexiste'
``` 

Dicha excepción puede ser capturada para evitar la interrupción del programa.
Un problema muy recurrente es cuando creamos un módulo con una función como en el siguiente ejemplo, y añadimos algunas sentencias a ejecutar.

``` python
>>> # modulo.py
>>> def suma(a, b):
>>>     return a + b
>>> c = suma(1, 2)
>>> print("La suma es:", c)
```

Si en otro módulo importamos nuestro modulo.py, tal como está nuestro código el contenido se ejecutará, y esto puede no ser lo que queramos.


``` python
>>> # otromodulo.py
>>> import modulo
La suma es: 3
```

Dependiendo de la situación, puede ser importante especificar que únicamente queremos que se ejecute el código si el módulo es el __main__. Con la siguiente modificación, si hacemos import modulo desde otro módulo, este fragmento ya no se ejecutará al ser el módulo main otro.

``` python
>>> # modulo.py
>>> def suma(a, b):
>>>     return a + b
>>> if (__name__ == '__main__'):
>>>     c = suma(1, 2)
>>>     print("La suma es:", c)
```

Es importante notar que los módulos solamente son cargados una vez. Es decir, no importa el número de veces que llamemos a import mimodulo, que sólo se importará una vez.
Si queremos que el módulo sea recargado, tenemos que ser explícitos, haciendo uso de reload.

``` python
>>> import mimodulo
>>> import importlib
>>> importlib.reload(mimodulo)
>>> importlib.reload(mimodulo)
``` 

## Manejo de Errores

### Pruebas de caja negra

Las pruebas de caja negra se basan en la especificación de la función o el programa, aquí debemos probar sus inputs y validar los outputs. Se llama caja negra por que no necesitamos saber necesariamente los procesos internos del programa, solo contrastar sus resultados.
Hay dos tipos de pruebas muy importantes:
* Pruebas Unitarias: Se realizan pruebas a cada uno de los módulos para determinar su correcto funcionamiento.
* Pruebas de Integración: Se valida quee todos los módulos funcionan entre sí.

Es una buena práctica realizar las pruebas antes de crear código, esto es por que cualquier cambio que se realice a futuro los test estaran incorporados para determinar si los cambios cumplen lo esperado.
En Python existe la posibilidad de realizar estas pruebas gracias a la libreria **unittest**.

```python
>>> import unittest

>>> def suma(num_1, num_2):
>>>     return abs(num_1) + num_2

>>> class CajaNegraTest(unittest.TestCase):
>>> 
>>>     def test_suma_dos_positivos(self):
>>>         num_1 = 10
>>>         num_2 = 5
>>> 
>>>         resultado = suma(num_1, num_2)
>>> 
>>>         self.assertEqual(resultado, 15)
>>> 
>>>     def test_suma_dos_negativos(self):
>>>         num_1 = -10
>>>         num_2 = -7
>>> 
>>>         resultado = suma(num_1, num_2)
>>> 
>>>         self.assertEqual(resultado, -17)

>>> unittest.main(argv=[''], verbosity=2, exit=False)
test_suma_dos_negativos (__main__.CajaNegraTest) ... ok
test_suma_dos_positivos (__main__.CajaNegraTest) ... ok

----------------------------------------------------------------------
Ran 2 tests in 0.004s

OK
<unittest.main.TestProgram at 0x2226bd08400>
``` 

### Pruebas de caja de cristal

Se basan en el flujo del programa, por lo que se asume que conocemos el funcionamiento del programa, por lo que podemos probar todos los caminos posibles de una función. Esto significa que vamos a probar las ramificaciones, bucles for y while, recursiónes, etc.
Este tipo de pruebas son muy buenas cuando descubrimos un bug cuando corremos el programa, por lo que vamos a buscar el **bug** ó error de código gracias a que conocemos su estructura.

```python
>>> import unittest

>>> def es_mayor_de_edad(edad):
>>>     if edad >= 18:
>>>         return True
>>>     else:
>>>         return False

>>> class PruebaDeCristalTest(unittest.TestCase):
>>> 
>>>     def test_es_mayor_de_edad(self):
>>>         edad = 20
>>> 
>>>         resultado = es_mayor_de_edad(edad)
>>> 
>>>         self.assertEqual(resultado, True)
>>> 
>>>     def test_es_menor_de_edad(self):
>>>         edad = 15
>>> 
>>>         resultado = es_mayor_de_edad(edad)
>>> 
>>>         self.assertEqual(resultado, False)

>>> unittest.main(argv=[''], verbosity=2, exit=False)
test_es_mayor_de_edad (__main__.PruebaDeCristalTest) ... ok
test_es_menor_de_edad (__main__.PruebaDeCristalTest) ... ok

----------------------------------------------------------------------
Ran 2 tests in 0.003s

OK
<unittest.main.TestProgram at 0x2226bd153d0>
```

### Seguir el código paso a paso ó 'Debugging'

Los bugs son un problema que les sucede a todos, sin embargo si realizamos test a nuestro programa probablemente tendremos menos bugs, pero esto no es suficiente.
Existen unas reglas generales que nos ayudaran:
No te molestes con el debugger. Aprende a utilizar el print statement.
* Estudia los datos disponibles.
* Utiliza los datos para crear hipótesis y experimentos. Método científico.
* Ten una mente abierta. Si entendieras el programa, probablemente no habrían bugs.
* Lleva un registro de lo que has tratado, preferentemente en la forma de tests.
* Debuguear es un proceso de búsqueda de los bugs, por lo que al diseñar nuestros experimentos debemos acotar el espacio de búsqueda en cada prueba. Una forma ágil de debugear es utilizando una búsqueda binaria con print statements, esto significa que ejecutamos la mitad del código, si no falla entonces sabemos que el problema esta en la otra mitad, y en cada área que vamos acortando lo dividimos por mitades, de esta forma hallaremos rápidamente nuestro bug.

Existe un listado de errores comunes de los cuales también nos podemos apoyar:
* Encuentra a los sospechosos comunes (llamado a una función mal escrita, parámetros en orden incorrecto, etc.)
* En lugar de preguntarte por qué un programa no funciona, pregúntate por qué está funcionando de esta manera.
* Es posible que el bug no se encuentre donde crees que está.
* Explícale el problema a otra persona. De preferencia que no tenga contexto.
* Lleva un registro de lo que has tratado, preferentemente en la forma de tests.

### Manejo de excepciones

Los manejos de excepciones son muy comunes en la programación, no tienen nada de excepcional. Las excepciones de Python normalmente se relacionan con errores de semántica, también podemos crear nuestras propias excepciones, pero cuando una excepción no se maneja (unhandled exception), el programa termina en error.

Las excepciones se manejan con los keywords: **try**, **except**, **finally**. Se pueden utilizar también para ramificar programas.
No deben manejarse de manera silenciosa (por ejemplo, con print statements). Para crear tu propia excepción utiliza el keyword **raise**.

``` python
>>> def divide_elementos_de_lista(lista, divisor):
>>>     '''
>>>     Cada elemento de una lista es dividida por un divisor definido.
>>>     En caso de error de tipo ZeroDivisionError que
>>>     significa error al dividir en cero
>>>     la función devuelve la lista inicial
>>>     '''
>>>     try:
>>>         return [i / divisor for i in lista]
>>>     
>>>     except ZeroDivisionError as e:
>>>         print(e)
>>>         return lista
>>> 
>>> lista = list(range(10))
>>> divisor = 0
>>> 
>>> print(divide_elementos_de_lista(lista, divisor))
division by zero
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
>>> divisor = 3
>>> print(divide_elementos_de_lista(lista, divisor))
[0.0, 0.3333333333333, 0.6666666666666, 1.0, 1.3333333333333, 1.6666666666667, 2.0, 2.3333333333335, 2.6666666666665, 3.0]
```

### Excepciones y control de flujo

Hasta ahora hemos visto como las excepciones nos permiten controlar los posibles errores que pueden ocurrir en nuestro código. Sin embargo, dentro de la comunidad de Python tienen otro uso: control de flujo.

¿Por qué es necesaria otra modalidad para controlar el flujo? Una razón muy específica: el principio EAFP (easier to ask for forgiveness than permission, es más fácil pedir perdón que permiso, por sus siglas en inglés).

El principio EAFP es un estilo de programación común en Python en el cual se asumen llaves, índices o atributos válidos y se captura la excepción si la suposición resulta ser falsa. Es importante resaltar que otros lenguajes de programación favorecen el principio LBYL (look before you leap, revisa antes de saltar) en el cual el código verifica de manera explícita las precondiciones antes de realizar llamadas.

``` python
#Python
def busca_pais(paises, pais):
'''
Paises es un diccionario. Pais es la llave.
Codigo con el principio EAFP.
'''

try:
    return paises[pais]
except KeyError:
     return None
```

``` javascript
// Javascript

/**
* Paises es un objeto. Pais es la llave.
* Codigo con el principio LBYL.
*/
function buscaPais(paises, pais) {
  if(!Object.keys(paises).includes(pais)) {
    return null;
  }

  return paises[pais];
}
``` 

Como se puede ver, el código de Python accede directamente a la llave y únicamente si dicho acceso falla, entonces se captura la excepción y se provee el código necesario. En el caso de JavaScript, se verifica primero que la llave exista en el objeto y únicamente con posterioridad se accede.

Es importante resaltar que ambos estilos pueden utilizarse en Python, pero el estilo EAFP es mucho más propio de este lenguaje.

``` python
#All possible errors

except TypeError:
    print("is thrown when an operation or function is applied to an object of an inappropriate type.")
except IndexError:
   	print("is thrown when trying to access an item at an invalid index.")
except KeyError:
    print("is thrown when a key is not found.")
except ImportError:
  	print("Raised when the imported module is not found.")
except StopIteration:
  	print("is thrown when the next() function goes beyond the iterator items.")
except ValueError:
  	print("is thrown when a function's argument is of an inappropriate type.")
except NameError:
  	print("is thrown when an object could not be found.")	
except ZeroDivisionError:
  	print("is thrown when the second operator in the division is zero.")
except KeyboardInterrupt:
  	print("is thrown when the user hits the interrupt key (normally Control-C) during the execution of the program.")
except MemoryError:
  	print("Raised when an operation runs out of memory.")
except FloatingPointError:
  	print("Raised when a floating point operation fails.")
except OverflowError:
  	print("Raised when the result of an arithmetic operation is too large to be represented.")
except ReferenceError:
  	print("Raised when a weak reference proxy is used to access a garbage collected referent.")
except TabError:
  	print("Raised when the indentation consists of inconsistent tabs and spaces.")
except SystemError:
  	print("Raised when the interpreter detects internal error.")
except RuntimeError:
  	print("Raised when an error does not fall under any other category.")
except:
 	print("Error detected can't be handled nor clasified.")
```

## Características de Python

- Es un lenguaje interpretado, no compilado.
- Usa tipado dinámico, lo que significa que una variable puede tomar valores de distinto tipo.
- Es fuertemente tipado, lo que significa que el tipo no cambia de manera repentina. Para que se produzca un cambio de tipo tiene que hacer una conversión explícita.
- Es multiplataforma, ya que un código escrito en macOS funciona en Windows o Linux y vice versa.