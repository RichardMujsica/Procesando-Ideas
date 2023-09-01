---
{"dg-publish":true,"permalink":"/w-ideas/web-content/obsidian-v1-4-escritorio/"}
---

# Obsidian Actualización v1.4 Escritorio (Público)

> Esta actualización presenta Propiedades, una forma sencilla y duradera de agregar etiquetas, enlaces, fechas y otros metadatos a sus notas. Los complementos principales Búsqueda, Plantillas y Vínculos de retroceso han recibido actualizaciones para admitir Propiedades. 

Artículo original: [https://obsidian.md/changelog/2023-08-31-desktop-v1.4.5/](https://obsidian.md/changelog/2023-08-31-desktop-v1.4.5/)

### Algunas de las nuevas características de esta versión:

-   Una nueva interfaz de usuario para editar propiedades, con autocompletar para nombres y valores de propiedades
-   Las propiedades pueden tener tipos (por ejemplo, texto, lista, fecha, número, casilla de verificación) que agilizan la entrada de datos.
-   Las propiedades pueden contener enlaces internos a otras notas.
-   La nueva vista de la barra lateral enumera todas las propiedades en su bóveda y las ordena por nombre o frecuencia.
-   Navegación por teclado, comandos y teclas de acceso rápido
-   Sintaxis de búsqueda para buscar notas por propiedad y valor
-   Las plantillas fusionan automáticamente propiedades con propiedades existentes en la nota
-   Los datos todavía se almacenan como contenido frontal YAML en la parte superior de cada archivo Markdown. Los metadatos se formatean automáticamente como YAML válido.

Con esta actualización también puedes habilitar la autenticación de dos factores para tu cuenta de Obsidian.

_Nota:_ El instalador se actualizó para usar Electron v25.8.0 (requiere descargar [el instalador más reciente](https://obsidian.md/) ).

## Las "Propiedades"

![editor de propiedades](https://github.com/obsidianmd/obsidian-api/assets/693981/aea72173-5663-459d-83de-6ff888f6bdd5)

Las propiedades le ayudan a organizar la información sobre una nota. Agregar propiedades a una nota le ayuda a realizar un seguimiento de datos estructurados como texto, enlaces, fechas y números. Las propiedades también se pueden usar en combinación con complementos comunitarios que pueden hacer cosas útiles con sus datos estructurados. [Aprende más.](https://help.obsidian.md/Editing+and+formatting/Properties)

### Uso básico

Para agregar una propiedad a una nota, tienes varias opciones:

-   Utilice el comando **Agregar propiedad de archivo** .
-   Utilice la **`Cmd/Ctrl+;`**tecla de acceso rápido.
-   Elija **Agregar propiedad de archivo** en el menú **Más acciones** (icono de tres puntos) o haga clic derecho en la pestaña.
-   Escriba `---`al principio de un archivo.

Una vez que agregue una propiedad, aparecerá una fila en la parte superior del archivo con dos entradas: el _nombre_ de la propiedad y el _valor_ de la propiedad . Una vez que elija el nombre de la propiedad, puede darle un valor y tipo.

### Uso avanzado

Además del editor de propiedades en línea, hay un nuevo complemento principal **de vista de Propiedades** que agrega dos nuevas vistas para administrar sus propiedades:

-   **La vista de la barra lateral de todas las propiedades** muestra una lista de todas las propiedades de su bóveda y la cantidad de usos para cada una. Haga clic en una propiedad para buscar todos sus usos en su bóveda.
-   **La vista de la barra lateral de propiedades del archivo** muestra las propiedades del archivo activo. Si prefiere ocultar el editor de propiedades en línea, puede optar por editar las propiedades de su archivo desde la barra lateral, sin perder su lugar en el archivo activo.

Las propiedades son una característica extremadamente poderosa pero flexible que le brinda aún más formas de organizar su información. Consulte la [documentación de Propiedades](https://help.obsidian.md/Editing+and+formatting/Properties) para obtener aún más información.

## Autenticación de dos factores (2FA) para cuentas de Obsidian

Para mayor seguridad, ahora puedes habilitar la autenticación de dos factores en tu cuenta de Obsidian. Para hacerlo, vaya a [obsidian.md/account](https://obsidian.md/account) y habilite la "autenticación de 2 factores". Esto le indicará instrucciones de configuración.

_Nota:_ Cualquier dispositivo que inicie sesión en Obsidian debe ejecutar v1.4.5+ para iniciar sesión mediante la autenticación de dos factores.

## Actualizaciones de complementos principales

-   Buscar: Nueva [sintaxis de búsqueda](https://help.obsidian.md/Plugins/Search#Search+properties) de propiedades.
    -   Para buscar notas que contengan una propiedad, utilice \[ _propiedad_ \]
    -   Para buscar notas con una propiedad y un valor correspondiente, use \[ _propiedad_ : _valor_ \]
    -   Tanto la propiedad como el valor permiten subconsultas complejas, como paréntesis para agrupar, el operador OR, comillas dobles para una coincidencia exacta y expresiones regulares.
-   Plantillas: al utilizar el comando "Insertar plantilla", las propiedades dentro de los archivos de plantilla se fusionarán con el archivo actual.
-   Vínculos de retroceso: las propiedades con vínculos ahora se mostrarán correctamente en las entradas de vínculos de retroceso.
-   Note Composer: al fusionar notas ahora se fusionarán sus propiedades.

## Mejoras varias

-   Búsqueda: la función de autocompletar de búsqueda ahora se mostrará según el contexto de entrada actual.
-   Live Preview ahora admite tablas de una sola columna.
-   La función de autocompletar de etiquetas ahora utiliza un algoritmo de búsqueda difusa.
-   PDF: Se agregaron las opciones del menú contextual “Copiar como cita” y “Copiar anotación”.
-   PDF: se agregó un botón para copiar anotaciones desde la ventana emergente de anotaciones
-   PDF: se agregó “Copiar enlace a la página” al menú contextual de miniaturas de PDF
-   Editor: los comandos de formato para **negrita** , _cursiva_ , etc. ahora tienen en cuenta el contexto. Por ejemplo, "Alternar negrita" dentro de una oración en negrita quitará la negrita de la oración.
-   Búsqueda: se eliminó la demora entre escribir y realizar la búsqueda.
-   Sincronización: muestra siempre una representación visual del uso del almacenamiento.
-   Los números en todas partes ahora deberían tener formato en la aplicación. Por ejemplo, el recuento de palabras y el recuento de caracteres tendrán separadores de miles.
-   El complemento principal de Etiquetas ahora se llama "Vista de Etiquetas".

## ya no está roto

-   Corregido: la vista de una sola página del Visor de PDF se restablece a la primera página.
-   Corregido: no se puede hacer clic en la configuración de búsqueda del visor de PDF al alternar la barra lateral.
-   Se corrigió el error por el cual cerrar una ventana emergente con un modal activo mantendría el modal activo.
-   macOS: en el modo de ventana sin marco, los botones superior derecho ya no se mueven al crear o cerrar grupos de pestañas.
-   El modo de recuperación de archivos ahora mostrará un estado de carga al cargar bóvedas grandes.
-   Espacio de trabajo: corrige los comandos "seguir enlace debajo del cursor" en Canvas.
-   Lienzo: empujar la selección no debería hacer que las pestañas apiladas se desplacen.
-   Contorno: Se corrigió que el contorno no se representara si la vista se abría mediante el comando "Mostrar contorno".
-   La vista "Nueva pestaña" ahora mostrará las teclas de acceso rápido actuales.
-   Editor: la barra de desplazamiento ya no debería afectar la posición del texto cuando aparece en documentos largos.
-   Vim: Corrección para el corrector ortográfico.

## Desarrolladores

-   Vault: createFolder ahora devuelve un archivo `TFolder`.
-   Metadatos: `FrontMatterCache`ya no hereda de `CacheItem`.
-   Tematización: se han agregado [nuevas variables CSS para las propiedades que comienzan con](https://docs.obsidian.md/Reference/CSS+variables/Editor/Properties)`--metadata`
-   Se deshabilitó el ancho de línea suave `stringifyYaml`(esto estaba causando algunas roturas con otros complementos que leían YAML).

**Volver**: [[W-ideas/Obsidian en LinkedIn\|Obsidian en LinkedIn]]