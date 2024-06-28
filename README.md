# Análisis Dinámico de los Gaps de Kirkwood en el Cinturón de Asteroides utilizando la Simulación Numérica REBOUND
El presente proyecto fue elaborado para curso Medio Circunestelar y Sistemas Planetarios (AST 210) de la Universidad Técnico Federico Santa María, el cual pertenece a la malla de la carrera Licenciatura en Astrofísica.
Este curso, es dictado por el profesor Matias Montesinos Armijo.

## Tabla de Contenidos
1. [Descripción](#descripción)
2. [Instalación](#instalación)
3. [Uso](#uso)
4. [Contacto](#contacto)

## Descripción
El proyecto tiene como objetivo analizar la formación de los gaps de Kirkwood en el cinturón de asteroides mediante simulaciones con REBOUND.

## Instalación

Para instalar y ejecutar este proyecto, es necesario:

1. Clonación de repositorio:
    ```sh
    git clone https://github.com/barbarantares/Proyecto-Gaps-de-Kirkwood.git
    cd Proyecto-Gaps-de-Kirkwood
    ```
2. Instalación de las dependencias necesarias:
    ```sh
    pip install -r requirements.txt
    ```
## Uso

REBOUND es un integrador de cuerpos N, siendo un paquete de software que puede integrar el movimiento de partículas bajo la influencia de la gravedad. Las partículas pueden representar estrellas, planetas, lunas, anillos o partículas de polvo. REBOUND es muy flexible y puede personalizarse para resolver de manera precisa y eficiente muchos problemas en astrofísica.
https://github.com/hannorein/rebound
Se puede isntalar REBOUND usando pip: 

 ```
 pip install rebound
```
Luego, se puede ejecutar una simulación simple:
 ```
import rebound
sim = rebound.Simulation()
sim.add(m=1.0)
sim.add(m=1.0e-3, a=1.0)
sim.integrate(1000.)
sim.status()
```
De esta forma, se creó una simulación que permitiera la visualizacion de los gaps de Kirkwood.
## Contacto
Nombres: Bárbara Antares Gutiérrez Cáceres y Lucas Ignacio Gajardo Jara
Correos: barbara.gutierrezc@usm.cl lucas.gajardo@usm.cl
GitHub: barbarantares




######

