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
## 2.2 Ciclo de vida del Software
Los proyectos de desarrollan en una serie de fases:
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


### As a Boilerplate / Fork

_(deprecated, not recommended)_

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Replace the `Gemfile` with one stating all the gems used in your project
3. Delete the following unnecessary files/folders: `.github`, `LICENSE`, `screenshot.png`, `CNAME` and `alembic-jekyll-theme.gemspec`
4. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, simply by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file in your own `styles.scss`, make sure to state them before the `@import "alembic";` line so they take effect. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
bundle install
bundle exec jekyll serve
