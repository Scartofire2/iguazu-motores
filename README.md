# Iguazú Motores

Aplicación web instalable para Android, con órdenes de trabajo, clientes, vehículos y presupuestos. Edición móvil simplificada del prototipo original.

## Abrir e instalar

https://scartofire2.github.io/iguazu-motores/

Abrir con Chrome y conexión a internet. En «Copias y app», esperar el aviso de preparación sin conexión. Desde el menú de Chrome, elegir «Instalar aplicación» o «Añadir a pantalla de inicio». Probar después en modo avión.

## Datos y copias

Pulsar «Guardar orden» para conservar los cambios. Los datos se guardan en IndexedDB, dentro del navegador del dispositivo. No se suben a GitHub ni se sincronizan con una nube. No usar modo incógnito. Borrar los datos del navegador o perder el celular puede hacer perder las órdenes.

Descargar regularmente una copia JSON y conservarla fuera del teléfono. Restaurar una copia reemplaza todas las órdenes tras pedir confirmación. Si se cambia desde otro dominio, exportar allí la copia e importarla en este enlace: los datos no se trasladan automáticamente.

## Alcance

Comprobantes internos sin validez fiscal. Sin facturación fiscal, inventario ni escáner automático. Compartir e imprimir utilizan la última orden guardada.

## Publicación

Archivos estáticos sin dependencias externas. GitHub Pages: rama main, carpeta raíz. Servir por HTTPS para instalar el service worker. No abrir index.html directamente como archivo.

## Verificación

Se probó localmente creación de orden, cálculo, persistencia al recargar y reapertura con el servidor apagado. La instalación y el modo avión deben comprobarse también en el Android de destino.
