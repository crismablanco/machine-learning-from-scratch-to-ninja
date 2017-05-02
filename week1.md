
# Semana 1 
Lo primero fue la bienvenida... Presentaciones y demás menesteres. Pero rápidamente se pasa a la acción preparando el _environment_

### Environment.
Se utiliza Anaconda + Jupyter notebooks

#### **Anaconda** 
Es un entorno de desarrollo (especial para data science), que se utiliza para mantener separados los proyectos que requieren diferentes versiones de paquetes. Entonces usando anaconda creamos diferentes _environments_ para que no se pisen unos con otros.
#### Commands:
- PARA CREAR UN ENVIRONMENT: conda create -n nameOfEnvironment
- PARA ACTIVAR UN ENVIRONMENT (en windows): activate nameOfEnvironment
- PARA DESACTIVAR UN ENVIRONMENT (en windows): deactivate nameOfEnvironment
- PARA VER LOS ENVIRONMENTS: conda info --envs 
- PARA INSTALAR PAQUETES: conda install pandas matplotlib scikit-learn


#### **Jupyter** 
Es una web app que se instala preferentemente con Anaconda (no obligatorio) y genera un web server que se comunica con un kernel (Python, R, Julia -> **Ju**lia **py**thon **R** = **Jupyter**).

#### **Jupyter Notebooks** 
Son files que contienen texto, bloques de programación, visualización y se muestran como HTML en el browser. entonces podemos tener un software que se ejecuta con explicaciones y resultados de ejecución todo en un mismo lugar... Notebooks are a form of [literate programming](http://www.literateprogramming.com/) proposed by Donald Knuth in 1984.

- [Anaconda](https://www.continuum.io/downloads)
- [Conda Documentation](https://conda.io/docs/using/index.html)
- [Jupyter](http://jupyter.org/)
- [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/index.html)

---

### Style Transfer
En esta lección se ven los efectos de aplicar deeplearning. En el primer ejemplo se utiliza [fast Style Transfer](https://github.com/lengstrom/fast-style-transfer) para hacer que una imagen X adquiera el estilo de otra. Entonces podemos ver una foto nuestra con el estilo de Picasso por ejemplo. En todos los casos la red neuronal que resuelve esto ya fue entrenada y nosotros solamente aplicamos los estilos que ya fueron "aprendidos". _de a poco nos vamos acercando al potencial del DL (deep learning)_. Luego hay otros ejemplos: deep trafic, flappy bird, books to read.

#### ¿Cómo ejecutar el Style Transfer?
- Creamos un nuevo environment con Python3.5 utilizando Anaconda **_conda create -n style-transfer python=3.5_**
- lo activamos **_activate style-transfer_**
- le instalamos tensorflow **_conda install -c conda-forge tensorflow=0.12.1_**
- le instalamos scipy pillow **_conda install scipy pillow_**

### Ejercicios.
- Mediante una regresión lineal, predecimos el peso de un animal, dependiendo del peso de su cerebro.
- Mediante una regresión lineal, predecimos la expectativa de vida de una persona, basada en su Indice de Masa Corporal al momento del nacimiento.
- Mediante regresión lineal multivariable, predecimos el valor de una casa, teniendo en cuenta las caracteristicas/valores de un set de datos de casas de Boston.


### Some basic resources:
- Pandas - an extremely popular library for handling data in Python. [10 minutes to Pandas.](http://pandas.pydata.org/pandas-docs/stable/10min.html#min)
- Scikit-learn - a comprehensive library for Machine Learning in Python. [Scikit-Learn's official tutorial.](http://scikit-learn.org/stable/tutorial/basic/tutorial.html)
- Matplotlib - a library for plotting and visualizing graphs in Python. [Matplotlib's official tutorial.](http://matplotlib.org/users/pyplot_tutorial.html)


## Intro texts
[Machine Learning is Fun! The world’s easiest introduction to Machine Learning](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.gome4aeut)

