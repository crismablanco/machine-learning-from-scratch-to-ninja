# Machine Learning from scratch to *ninja*
Este es un aporte desde mi experiencia como programador que inicia en el año 2003. Me propongo armar una especie de guía de estudio donde publicaré los avances que voy teniendo en Machine Learning and Artificial Intelligence. Son bienvenidas las colaboraciones que deseen aportar

This is a contribution from my experience as a programmer that started in 2003. I intend to set up a kind of study guide where I will publish the advances that I am having in Machine Learning and Artificial Intelligence. All the collaborations to contribute are welcome

# Semana 1 
Lo primero fue la bienvenida... Presentaciones y demás menesteres. Pero rápidamente se pasa a la acción preparando el _environment_

### Environment.
Se utiliza Anaconda + Jupyter notebooks

#### **Anaconda** 
Es un entorno de desarrollo (especial para data science), que se utiliza para mantener separados los proyectos que requieren diferentes versiones de paquetes. Entonces usando anaconda creamos diferentes _environments_ para que no se pisen unos con otros.

#### **Jupyter** 
Es una web app que se instala preferentemente con Anaconda (no obligatorio) y genera un web server que se comunica con un kernel (Python, R, Julia -> **Ju**lia **py**thon **R** = **Jupyter**).

#### **Jupyter Notebooks** 
Son files que contienen texto, bloques de programación, visualización y se muestran como HTML en el browser. entonces podemos tener un software que se ejecuta con explicaciones y resultados de ejecución todo en un mismo lugar... Notebooks are a form of [literate programming](http://www.literateprogramming.com/) proposed by Donald Knuth in 1984.

- [Anaconda](https://www.continuum.io/downloads)
- [Conda Documentation](https://conda.io/docs/using/index.html)
- [Jupyter](http://jupyter.org/)

---

### Style Transfer
En esta lección se ven los efectos de aplicar deeplearning. En el primer ejemplo se utiliza [fast Style Transfer](https://github.com/lengstrom/fast-style-transfer) para hacer que una imagen X adquiera el estilo de otra. Entonces podemos ver una foto nuestra con el estilo de Picasso por ejemplo. En todos los casos la red neuronal que resuelve esto ya fue entrenada y nosotros solamente aplicamos los estilos que ya fueron "aprendidos". _de a poco nos vamos acercando al potencial del DL (deep learning)_. Luego hay otros ejemplos: deep trafic, flappy bird, books to read.

#### ¿Cómo ejecutar el Style Transfer?
- Creamos un nuevo environment con Python3.5 utilizando Anaconda **_conda create -n style-transfer python=3.5_**
- lo activamos **_activate style-transfer_**
- le instalamos tensorflow **_conda install -c conda-forge tensorflow=0.12.1_**
- le instalamos scipy pillow **_conda install scipy pillow_**



## Intro texts
[Machine Learning is Fun! The world’s easiest introduction to Machine Learning](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.gome4aeut)

# Intro Videos
## Siraj Raval
* [How to Make a Prediction - Intro to Deep Learning 1](https://www.youtube.com/watch?v=vOppzHpvTiQ)
* [How to Make a Neural Network - Intro to Deep Learning 2](https://www.youtube.com/watch?v=p69khggr1Jo)

---
