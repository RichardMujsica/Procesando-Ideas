---
{"dg-publish":true,"permalink":"/w-ideas/guia-pkm-base/","dgShowBacklinks":true,"dgShowLocalGraph":true,"noteIcon":""}
---

![](/img/user/W-ideas/img/pachakamani.jpg)
# PKM Base v0.3 - Guía de uso
# Entorno e instrumentos iniciales para construir tu PKM con Obsidian

## Presentación

¿Qué es el _PKM_? es una sigla en ingles que se traduce como _Gestión del Conocimiento Personal_. Es decir, se trata del uso y articulación de métodos, habilidades o técnicas que nos ayuden procesar y aprovechar lo mejor posible la información para generar nuestro conocimiento y saber. Wow, así es, estamos hablando de procesos muy grandes o relativamente sencillos, según sea el caso y la situación de cada persona. Recuerda: "cada persona es un mundo", entonces es dificil crear una única receta, o un único PKM. 

Es muy posible que todos tengamos un PKM implícito ayudándonos y no nos dimos cuenta. Pero si no lo tenemos, es necesario iniciar con algo y no dejarnos consumir por la complejidad que desde ya nos parecería construir conscientemente nuestro PKM. 

Por ello, antes de atascarnos (más de la cuenta) en la "parálisis por análisis", hemos preparado este entorno básico en Obsidian para el inicio de la construcción de tu PKM. 

_¿Y por qué en Obsidian?_
Optamos por utilizar [Obsidian.md](https://obsidian.md/), por su versatilidad y características permiten el crecimiento paulatino y orgánico de nuestro _PKM_. Esta aplicación, puede ser tan simple o compleja como gustes, ya que es "modular", y eso te permite: 
- Añadir complementos (plugins) según tus necesidades personales.
- Permite manejar diferentes soportes de archivos digitales.
- Permite una fluidez y versatilidad para conectar notas simples y crear complejas bases de datos.
Además, es gratis y tienes a una comunidad mundial que apoya su uso y crecimiento constante. Esta bóveda intenta ser un aporte para retribuir lo aprendido.

## Entorno PKM Base en Obsidian

La estructura de este entorno base, pretende la articulación de 2 métodos:
- Zettelkasten.
- GTD / BuJo.

Se inició con una base simplificada (versión v01-2022-04), dando énfasis a  Zettelkasten. Como un apoyo inicial a los procesos de análisis de información para la investigación, sin incorporar aún la codificación Folgezettel sino a partir de `[[Wikilinks]]`. Sin embargo, reconocemos la importancia de contar con una herramienta de gestión de tareas y proyectos (como GTD o BuJo). Por lo cual, luego añadimos algunos componentes de esos métodos en este entorno. Todo esto se expresa de manera simple en la estructura y organización mínima de algunas carpetas/ficheros.

![](/img/user/W-ideas/img/PKM-kamani.JPG)

### Estructura de carpetas y archivos
- En el siguiente enlace: [Info PKM Base](Info%20PKM%20Base.md), encontrará información detallada de la estructura de archivos/ficheros y flujo de trabajo de este entorno base de PKM.

### Uso de esta bóveda
1. Descargue la bóveda como una carpeta comprimida (ZIP). Ingrese al botón `Code` y descargue en [Download Zip](https://github.com/RichardMujsica/PKM-Base-Obsidian/archive/refs/heads/main.zip).
2. Extraer el contenido del Archivo ZIP y utilícelo como bóveda en Obsidian (Abrir carpeta como bóveda).
3. Esta bóveda ya cuenta con algunos _plugins_ instalados. Por tanto, es necesario que durante su instalación se permita el uso de plugins externos.


## Contenido y entorno del PKM Base en Obsidian 1.0

### 1. Estructura mínima de carpetas/ficheros y notas

A partir de lo mencionado, la estructura mínima (base) de los archivos se agrupa en dos:
1. **Para el Método Zettelkasten**
	1. Carpeta "01 IDEAS": Notas de ideas (permanentes-atómicas).
	2. Carpeta "02 REFERENCIAS": Notas Bibliográficas y Resumen.
	3. Carpeta "03 MOC": Notas tipo índice o mapa de contenido. 
2. **Ingreso de información y organización de proyectos:** Carpeta "00 LIBRETA"
	1. Subcarpeta _INBOX_: Captura de notas iniciales o de tareas. Espacio de entrada general para toda la Bóveda. Luego de la revisión o aclarado de estas, se derivan a la sección correspondiente.
	2. Subcarpeta _Proyectos_: Esta es la sección de _colecciones_ de notas referidas a proyectos (resultado buscado). Asimismo, este espacio tiene la posibilidad de articular y/o generar nuevas notas de idea (Zettel) o solo referencia en el proceso de trabajo cotidiano.
	3. Carpeta _"05 Archivo"_: Sección para el _incubado_ de notas o colecciones producidas en los proyectos (paso previo a su eliminación o extracción de la bóveda). O tambien puede utilizarse como fichero de almacenamiento de otros "Recursos" (por ejemplo las plantillas de este sistema). 

### 2. Materiales y procedimientos

#### Plantillas
Adicionalmente, añadimos el uso de **plantillas** orientadas a las notas base de Zettelkasten: 
- Nota (permanente | temporal)
- Nota de Referencia (bibliográfica o resumen)
- Mapa de Contenido (moc).

#### Etiquetas

Sugerimos algunas _etiquetas_ para agrupar las notas del Zettelkasten, las cuales ya están incorporadas en las plantillas: _permanente_, _temporal_, _moc_, y _referencia_.

#### Flujo de trabajo

Con ayuda de algunos plugins ya instalados y mediante el uso de "atajos de teclado", proponemos el siguiente proceso:
- Alt + W : Ingresa a workspace para seleccionar un Espacio de Trabajo: El Dashboard con el resumen del PKM, el tablero Kanban de proyectos o la Información de esta Bóveda. 
- Ctrl+N : **Ingresa una nota general (en blanco)** en la carpeta INBOX, sin utilizar plantillas.
- Alt+N : Activa el Plugin QuickAdd para seleccionar el TIPO DE NOTA que desea ingresar. Estas **notas específicas** se almacenan automáticamente en sus respectivas carpetas:
	- Nota Idea, se almacena en el Fichero "01 IDEAS"
	- Nota Referencia, se almacena en el fichero "02 REFERENCIAS"
	- Nota MOC (mapa de contenido), en el fichero "03 MOC"
	- Nota de Proyecto, en la subcarpeta "Proyectos" dentro de "00 LIBRETA"

#### Plugins preinstalados

Esta bóveda ya incluye algunos plugins que consideramos ayudan en el proceso inicial (algunos son "externos", por lo cual deberá desactivar el "modo seguro"). 
5. QuickAdd (para organización de notas)
7. Templater (para uso de plantillas)
6. Recent Files (visualizar documentos recientes)
3. LanguageTool Integration (corrección)
1. Dataview (base de tados y reportes)
2. Kanban (organización de proyectos)
4. Mind Map (mapas mentales)

### 3. Consideraciones a futuro

El contenido de esta bóveda está pensado en una base inicial de trabajo con Obsidian. Sobre la cual se pueden incorporar otras secciones, ficheros o colecciones de notas (por ejemplo para diferenciar tipos de fuentes). También se pueden añadir otros plugins (ejemplo ReadItLater para la captura de información de sitios web). Todo ello, según las necesidades de cada usuario.
A futuro, consideramos incorporar en esta bóveda (o implementar otra) que incluyan más componentes dirigidos a distintos flujos de trabajo, por ejemplo:
1. Gestión de proyectos. Lo que implica incorporar calendario (básico o avanzado).
2. Desarrollo de un diario o bitácora. Que implica el uso de anotaciones constantes y organización de tareas.
3. Análisis de datos. Incorporar procesos más ágiles de relación y extracción de notas, utilización de gráficos y administración de etiquetas. 

---

### Contenido del Curso

La versión inicial de esta bóveda fue realizada como instrumento didáctico del Curso de PKM. Este fue el contenido:
- **Sesión 1. Criterios y métodos de la Gestión del Conocimiento Personal (PKM)**
- **Sesión 2. Articulación del proceso de investigación con los métodos del PKM.**
- **Sesión 3. Herramientas digitales para la implementación del PKM en la investigación.**

[Más información del curso PKM](https://pachakamani.com/blog/curso-gestion-conocimiento-personal-pkm-investigadores-sociales-2022/)

### Elaboración
- [Richard Mújica Angulo](https://bio.link/richardmujica), antropólogo UMSA, cofundador de [PachaKamani](https://pachakamani.com/).
- La Paz, Bolivia.

---

### Referencias y sitios de consulta

- Sitio web Obsidian: https://obsidian.md/
- "Zettelkasten Español" - https://telegra.ph/Zettelkasten-Espa%C3%B1ol-05-17
- "Gestión del conocimiento Personal" - https://pkm.es/
- Grupo Telegram en Obsidian Español: https://t.me/ObsidianEs
- Grupo Telegram de PKM: https://t.me/PKM_es
- Grupo Telegram de Zettelkasten: https://t.me/zettelkasten_es
- Grupo LinkedIn de Obsidian y PKM (nuevo): https://www.linkedin.com/groups/12708607/



### Elaboración
- [Richard Mújica Angulo](https://bio.link/richardmujica), antropólogo UMSA, cofundador de [PachaKamani](https://pachakamani.com/).
- Versión inicial: 2022-04-20.
- Actualizaciones: 2022-06-23 | 2022-10-14.