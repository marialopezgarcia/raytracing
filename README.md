# Práctica Render 3D

* Prazo entrega: 23:59h luns 12 de xuño 2023
* Miembros:
    * Lema Carril, Ana María
    * López García, María
    * Rodríguez Miñambres, Pablo

# Práctica de Ray Tracing

Empregaremos como base este simple proxecto de ray tracer (python2): [rossant](https://gist.github.com/rossant/6046463).

### Primeira parte (ata 4 puntos sobre 10)

Engadirlla a este motor a posibilidade de traballar cun número arbitrario de fontes de luz, cada unha delas coas súas propias características (posición, cor).

Modificade a escena predeterminada a renderizar para que inclúa novas luces con distintas cores, mostrando a nova feature incorporada.

### Segunda parte (ata +3 puntos sobre o anterior)

Engadir ao motor unha nova primitiva gráfica coa que traballar: triángulo.

O código orixinal deste raytracer unicamente emprega esferas ou planos para construír unha escena e iluminala. Tedes que engadir a posibilidade de ter tamén triángulos na escena.

Modifica a escena predeterminada para que inclúa algún triángulo, ademais de esferas e planos como a escena orixinal.

* Consello: Podedes reutilizar a función para calcular a intersección raio-plano que xa está no código, e a maiores precisades outra función que, unha vez sabemos que o raio choca co plano, comprobe se este punto de intesección está dentro do triángulo co que estamos a comprobar a intersección raio-triángulo.

### Terceira parte (ata +3 puntos sobre o anterior)

Cambia o tiro de cámara para obter un render cenital (visto dende arriba, non ten por que ser perfectamente cenital).

### Entregables

   * URL a repositorio git co código, no que se vexa o progreso nas versións do traballo.

   * Etiquetade (=git tag=) as distintas versións que correspondan a cada unha das partes.

   No repositorio ten que haber tamén exemplos de renders obtido coas características incorporadas.

   Tamén podedes achegar algún texto aclarativo/explicativo se o considerades preciso.

## Comandos

sudo apt install python-pip

python2 -m pip install numpy 

python2 -m pip install matplotlib

sudo apt-get install python-tk

python2 raytracing.py
