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
[Diagrama](https://docs.quarkid.org/Arquitectura/arquitectura)

## Documentación
[Link](https://docs.quarkid.org/Arquitectura/componentes)

## Configuración de entorno local
Clonar el repositorio

- Abrir el proyecto con el editor seleccionado
- Abrir una terminal y ejecutar:

```bash
- yarn
- yarn build
- yarn start
```

## Variables de Entorno

### Generales

N/A

## Logs

N/A

## Requerimientos de red

La aplicación debe tener conectividad a internet para comunicarse con la red y al componente api-zkSyn.

## Ruta de acceso
La aplicación debe tener conectividad a internet.
