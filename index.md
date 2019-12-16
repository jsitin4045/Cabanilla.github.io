---
title: Justin Cabanilla
feature_text: |
  ## INTRODUCCION A LA INGENIERIA DE SOFTWARE
  Una página creada con una plantilla de jekyll
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "PINCIPIOS DE LA INGENIERIA DE SOFTWARE"
---


{% include button.html text="Fork" icon="github" link="https://github.com/daviddarnes/alembic" color="#0366d6" %} {% include button.html text="Tweet it" icon="twitter" link="https://twitter.com/intent/tweet/?url=https://alembic.darn.es&text=Alembic%20-%20A%20Jekyll%20boilerplate%20theme&via=DavidDarnes" color="#0d94e7" %} {% include button.html text="Personal Blog" link="https://github.com/daviddarnes/alembic#installation" %} {% include button.html text="Clases" link="https://www.paypal.me/daviddarnes/5usd" color="#333333" %}


## OBJETIVO

- Esta pagina brinda informacion esencial de los principios de la ingeniería de Software, herramientas y conceptos basicos en esta rama   de las ciencias exactas

## 1.1 Fundamentos a la ingeniería de software
Según Fritz Bauer (1969), más que una disciplina o una parte del conocimineto, la ingeniería es un verbo, una palabra de acción, un modo de enfocar un problema.
Es la aplicación de un enfoque sistemático, disciplinado y cuantificable hacia el desarrollo, operación y mantenimiento del software; es decir, la aplicación de Ingeniería de Software (IEEE, 1993)
OBJETIVOS:
- Diseño de programas con respecto a las exigencias de la sociendad
- Seguimiento de costes y plazos
- Procesos de calidad en los sistemas, calculo de métricas y chequeo de calidad del software
- Diseñar, construir y administrar bases de datos

## Evolución del Software
Primera fase: Los albores (1945-1955)
Programar no era una tarea diferenciada del diseño de una máquina (lenguaje máquina y emsamblador);
Segunda fase: El florecimiento (1955-1965)
Aparecimiento de una multitud de lenguajes;
Tercera fase: La crisis (1965-1970)
Desarrollo inacabable de programas, errores e ineficiencia;
Cuarta fase: Innovación conceptual (1970-1980)
Metodologías de diseño;
Quinta fase: El diseño es el problema (1980-?)
Entornos de programación

## 1.2 Proceso de ingeniería de Software
CALIDAD DE SOFTWARE:
Es la producción de un software que cumpla las exigencias del cliente y que sea posible darle mantenimiento. Factores que determianna la calidad: facilidad de mantenimiento, integridad, corrección, facilidad de uso y costo.

## Sosfware de sistemas y de aplicaciones
El software de sistemas mantiene el sistema infomático, mientras que el de aplicaciones provee servicios a clientes y ejecutar negocios de forma más eficiente

## Ingenieria de Software
Rama de la ingeniería que crea y mantiene aplicaciones usando tecnologías de las ciencias de la computación y otros campos

### 1.3 Sistemas de información
Lo define Peña (2016) como un conjunto de elementos que prestan atencion a las demandas de uan organizacion, para el amplio conociemiento de los registros que lleva la emperesa
TIPOS:
- Sistemas transaccionales
- Sistemas de soporte a la toma de decisiones
- Sistemas estratégicos

### 2 MODELOS DE PROCESO DEL SOFTWARE
Actividades necesarias para transformas las ideas del usuario, para desarrollar el producto software
---
title: 
feature_text: 
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: Modelos
---
## 2.1 Métodos de Desarrollo de Software
Se dividen en dos grupos:
# Orientado a Función/Dato
Hacen enfasis en la transformación de datos, funciones dependientes y la estructura de lso datos. Las funciones dependen generalmente de la estructura de datos
Por ejemplo: 
SADT: Structured Analysis and Design Technique
RDD: Requirement Driven Design
SA/SD: Structured Analysis and Structured Design
# Orientado a Objetos
Datos y funciones estan relacionados y centrado en la abstracción de datos
Por ejemplo: OOSE, OOA, OMT, UP y Catalysis

## 2.2 Ciclo de vida del Software
Los proyectos se desarrollan en una serie de fases:
1. Análisis
2. Diseño
3. Implementación
4. Prueba
5. Mantenimiento (correctivo, adaptativo, perfectivo y preventivo)

## 2.3 Modelos de desarrollo
Refleja las metas, conforme se construye de evalua las actividades 
Modelo general:
- Especificación
- Diseño
- Fabricación
- Prueba
- Instalación
- Mantenimiento

## Modelos Tradicionales
Formados por un conjunto de fases o actividades en las que no tienen en cuenta la naturaleza evolutiva del software
Método de Cascada:
Ordena rigurosamente las etapas del ciclo de vida del software de forma tal que el inicio de cada etapa debe esperar a la finalización inmediata de la anterior
Método Prototipo:
Este método es útil cuando el cliente no identifica los requisistos detallados. El sistema se contruye rapidamente para aclarar aspectos que aeguren al desarrollador
Modelo Espiral:
Las actividades no están fijadas , sino que las siguientes se eligen en función al análisis de riesgo

## Metodologías ágiles
Son herramientas que se emplean en el desarrollo de software que permiten que sea adaptable a los posibles cambios, a errores y cambios en su diseño. Un proceso que debe adaptarse incrementalmente y retroalimentación del cliente.
## SCRUM
Se basa en el empirismo que asegura que se resuelva con los conocimientos y la experiencia
## CYSTAL
El problema se divide en colores, mientras mas oscuro es más complejo el problema
## ADAPTATIVE
Se adapta al cambio en lugar de luchar contral él, es fácul modificacion y se divide en tres fases: Especulacion, colaboracion y aprendisaje
## Xtreme programming 
Ligera al desarrollar software que se basa en la simplicidad, comunicación y la realimentación
## KanBan
Sistema de etiquetas que identifican los procesos de fabricació y transporte. Para llevar un registro
## DSDM
Se simplifica en tres fases: el pre-proyecto, fase del ciclo de vida y el pos-proyecto. Se estudia la viabilidad de proyecto
## FDD
Basada en la calidad y el monitoreo constante del proyecto




### BIBLIOGRAFIA
- Alonso Amo, F y Segovia Pérez, F. "Entornos y metodologías de programación". Paraninfo, Madrid 1995
- Somerville, Ian, "Ingeniería del software". Addison Wesley Iberoamericana, Wilnington (EE.UU.) 1998
- Piattini, M. y otros "Análisis y diseño de aplicaciones informáticas de gestión". RA-MA, Madrid 2004



bundle install
bundle exec jekyll serve
