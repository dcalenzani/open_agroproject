Proyecto de sistematizacion de informacion agrícola para la venta DTC
---
## 1. Planteamiento
El proyecto busca *sistematizar* digitalmente la información de productores del valle de Huaral para la creación de una plataforma para la venta de *productos órganicos directo al consumidor*. El giro de valor para el producto consiste en *agrupar* la información de productores del valle de Huaral, aprovechando frutas de estación para crear *paquetes frescos* actualizados periodicamente según las tendencias en cultivos y productos.

#### 1.1 Potencial de crecimiento
La base de datos permite crecimiento vertical de la información de manera directamente proporcional a la cantidad de usuarios registrados y tipos de cultivos. En otras palabras, el proyecto puede crecer facilmente agrupando otros terrenos fuera de huaral para generar nuevas estrategias de negocio.

## 2. Fases del proyecto
El proyecto consta de 2 fases de clara división, donde la segunda puede ampliar su cronograma de acuerdo a las necesidades de mantenimiento de las bases de datos.
#### 2.1 Fase 1: Formulario
Consiste en crear el formulario virtual y físico para el llenado por los usuarios de la base de datos. Pensando en la actualización periódica debe pensarse sobre preguntas iterativas (que se repiten en el futuro). En esta fase se necesita *1 reunión de revisión* del formulario, ya que esta información será la principal para organizar el modelo de la base de datos y las relaciones en ella. 

*_Duración aproximada:_* 3 días
#### 2.22 Fase 2: Base de datos
Pensando en el problema del negocio, los datos necesitan estar organizados "jerárquicamente. Por poner un ejemplo, datos personales como telefono o correo electrónico están separados porque no queremos visualizarlos todo el tiempo, pero datos como tipo de cultivos activos necesitan estar más "cerca" a nosotros en nuestras búsquedas. Esta fase, aunque inicia junto con el planteamiento del formulario, muestra sus fortalezas después del recojo de información.

Según el planteamiento, las necesidades existentes se enfocan en implementar la base de datos y su análisis inicial, con potencial de crecimiento para su mantenimiento y análisis periódico para el desarrollo de la plataforma de venta al consumidor. En ese sentido la segunda fase finaliza idealmente con la integración del análisis de los datos en el crecimiento del negocio.

##3. Retos y posibilidades
La sostenibilidad y potencial de crecimiento de la base de datos depende directamente del desarrollo de la plataforma de ventas. Aunque los datos pueden ser útiles también para análisis agrarios y de ventas, dichos análisis no son contemplados en el alcance de este proyecto. Por otro lado, existen referentes internacionales ([Fruit Guys](https://fruitguys.com/);[Farm Fresh to you](https://www.farmfreshtoyou.com/)) que llevan a pensar si existen referentes nacionales que puedan ser una competencia directa o aliados estratégicos.

Las posibilidades del desarrollo de una base de datos sólida y escalable con aplicaciones relacionadas a la producción agrícola son diversas, los datos incluso pueden ser vendidos por sí mismos a los correctos proveedores. Por poner un ejemplo, [El Frutero](https://www.elfrutero.pe/) podría estar interesado en monitorear excedentes de frutas para sus procesos de congelado. 

La plataforma web de venta genera una mayor independencia en el desarrollo del negocio y la tecnología, pero se necesitan incentivar los beneficios para los productores para aprovechar los recursos al máximo. 

## 4. Tecnologías y herramientas utilizadas
_Nota general:_ En apoyo a la difusión del conocimiento y la gratuitidad del aprendizaje, todas las herramientas utilizadas son de "Open Source", un modelo descentralizado en el que todos podemos acceder al código del programa distribuido. Todos los programas de esta lista son *gratuitos*, pero esa característica puede perderse en caso necesitemos una licencia comercial para alguna etapa, lo que no debería ocurrir hasta un crecimiento moderado del proyecto

#### 4.1 Software y código
* [PostgreSQL:](https://www.postgresql.org/): Sistema de administración de Base de datos relacional (RDBMS) basada en C con integración en Python, gratuita en descarga y uso. Cuenta con soporte comercial disponible y soluciones de hosting por un precio adicional
* [PGadmin:](https://www.pgadmin.org/): Administrador de escritorio y plataforma de desarrollo para PostgreSQL. Permite visualizar de manera gráfica las bases de datos disponibles y acceder a los datos.
* [PHP] (https://www.php.net/): Lenguaje general para desarrollo web. Tiene capacidad de ser integrado en código HTML para su interacción con páginas web con una interfaz gráfica más avanzada
* [Apache:](https://httpd.apache.org/): Proveedor de servicios de HTTP en código abierto, parte base de la comunicación con la base de datos a distancia.

#### 4.2 Hardware
El hardware puede ser instalado en cualquier lugar siempre y cuando tenga un acceso estable a flujo eléctrico e internet. Los datos contenidos en él solo pueden ser accedidos por las personas que cuenten con autorización de seguridad.
* [RaspberryPi](https://www.raspberrypi.com/): Computadora modular adaptable de precio accesible. Reemplazaría a un host en la nube o comprar un servidor que supere nuestras necesidades de negocio. El equipo Raspberry sería donde se ubicaría nuestro servidor la base de datos. Con 8GB de RAM podríamos sostener una página web ligera y nuestra red personal sin mayores problemas. En Perú existe un proveedor autorizado )[The Pi Box](https://thepibox.pe/), lo que permitiría comprar estos equipos con RUC y contar con soporte oficial si se hace desde un contacto empresarial.
* Disco Duro externo: Un punto en contra del Raspberry es que, si deseamos guardar grandes cantidades de información, requerimos invertir en un HDD o SDD para contener dicha información.
* Fuente de Poder: Cable y transformador para conectar el equipo a la corriente eléctrica

## 5. Cronograma e Inversión
El trabajo está planteado para ser trabajado por productos y según entregables establecidos en fechas concretas. La tabla desagregada de procesos y productos del proyecto se presenta a continuación:

Teniendo en cuenta dichos entregables y reuniones, la inversión total correspondiente es explicada en el siguiente cuadro:
