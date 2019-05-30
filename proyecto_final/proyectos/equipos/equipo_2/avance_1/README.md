# avance_1

## Integrantes:

* Sol

* Iker

* Luis

## Trabajo:

### Individual

Sol: 

Investigación relacionada con la historia e inicios de los sistemas de recomendación.
Lectura e investigación de los algoritmos usados en el consurso de Netflix. 
Instalación de R con OpenBLAS.
Inicialmente se había considerado la implementación en R, pero revisando papers y distintos artículos, decidimos hacer la implementación en Python   
Documentación de los papers y artículos investigados. El trabajo escrito se ha ido trabajando en colaboración.  
Inicio implementación SVD en Python, utilizando descenso en gradiente estocástico, SGD, por sus siglas en inglés.

Referencias usadas:
* [Capitulo 9: Recommendation Systems](http://www.mmds.org.) Leskovec, Jure, Anand Rajaraman, and Jeffrey David Ullman. 2014. Mining of Massive Datasets. 2nd ed. New York, NY, USA: Cambridge University Press. 

* [Apache Mahout, Solr/Lucene Practical Machine Learning: Innovations. 1rst ed. O'Reilly](http://shop.oreilly.com/product/0636920033172.do)

* [Understanding matrix factorization for recommendation part 1](http://nicolas-hug.com/blog/matrix_facto_1)

* [Understanding matrix factorization for recommendation part 2](http://nicolas-hug.com/blog/matrix_facto_2)

* [Understanding matrix factorization for recommendation part 3](http://nicolas-hug.com/blog/matrix_facto_3)

* [Understanding matrix factorization for recommendation part 4](http://nicolas-hug.com/blog/matrix_facto_4)

* [Artículo Simon Funk, tercer lugar en el concurso Netflix](https://sifter.org/simon/journal/20061211.html)


Iker:

* [Propuesta del Data Set](https://github.com/luis58/recommendation_algorithms/blob/master/documentaci%C3%B3n/MNO%20-%20Proyecto%20Final.docx)

* [Lectura de Artículo SVD acelerado usando optimización de descenso en gradiente](https://www.sciencedirect.com/science/article/pii/S1319157818300636)




Luis:

* [Lectura de Capitulo 11: Recommendation Systems](http://infolab.stanford.edu/~ullman/mmds/ch11.pdf)

* [resumen](https://github.com/luis58/recommendation_algorithms/blob/master/documentaci%C3%B3n/Reducci%C3%B3n%20de%20dimensionalidad%20(Leskovec).docx) 

* [Revisión de documentación de Cuda](https://docs.nvidia.com/cuda/cusolver/index.html#gesvda-example1)

* [Revisión de artículos de implementaciones para iniciar pruebas](http://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/ConferencePapers/2009/Sheetal09Singular.pdf)




### Equipo

Compartimos impresiones sobre las lecturas de Reducción de Dimensionalidad y Sistemas de Recomendación, bases para el proyecto y que nos facilitarán entender los avances de nuestros compañeros en tareas más específicas.

### Comentarios Revisión

Ver publicaciones de Leon Bottou:

* ["Tradeoffs" de aprandizaje con datos en gran escala](https://leon.bottou.org/publications/pdf/nips-2007.pdf)

* [Aprendizaje con descenso en gradiente estocástico con datos de gran escala](http://khalilghorbal.info/assets/spa/papers/ML_GradDescent.pdf)

Implementar primero una versión en python de CUR, SVD y SVD con descenso estocásitco posteriormente analizar si se puede aplicar en CUDA


