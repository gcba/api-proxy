# Descripción

El componente API Proxy, también conocido como reverse proxy, esta diseñado para
operar como un punto de entrada a múltiples DID Methods, con el fin de simplificar su gestión y
resolución. Esto se debe a que cada implementación de DID tiene sus propias especificaciones
y dinámicas.

## Tecnologías

La aplicación cuenta con las siguientes técnologias:

* NodeJs
* TypeScript
  
## Arquitectura
[Diagrama](https://docs.quarkid.org/Arquitectura/)

## Documentación
[Link](https://docs.quarkid.org/Arquitectura/componentes/)

## Configuración de entorno local
Clonar el repositorio

- Abrir el proyecto con el editor seleccionado
- Abrir una terminal y ejecutar:

```bash
- cd source
- yarn
- yarn build
- yarn start
```

## Variables de Entorno

Se tienen que configurar las mismas en el archivo /api-proxy/source/src/.env

### Generales

N/A

## Logs

N/A

## Requerimientos de red

La aplicación debe tener conectividad a internet para comunicarse con la red y al componente api-zkSync.

## Ruta de acceso
La aplicación debe tener conectividad a internet.

## Licencia
Derechos de autor © 2023 Gobierno de la Ciudad de Buenos Aires

Licenciado bajo la Licencia Apache, Versión 2.0 (la "Licencia");
usted no puede utilizar este archivo excepto en cumplimiento con la Licencia.
Puede obtener una copia de la Licencia en
http://www.apache.org/licenses/LICENSE-2.0.
A menos que lo requiera la ley aplicable o se acuerde por escrito, el software
distribuido bajo la Licencia se distribuye "TAL CUAL",
SIN GARANTÍAS O CONDICIONES DE NINGÚN TIPO, ya sean expresas o implícitas.
Consulte la Licencia para el idioma específico que rige los permisos y
limitaciones bajo la Licencia.
