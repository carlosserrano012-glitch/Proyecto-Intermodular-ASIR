# 4. Establecimiento de requisitos

## 4.1. Requisitos funcionales

Los requisitos funcionales definen las funciones que deberá proporcionar el sistema.

| ID | Requisito |
|---|---|
| RF01 | El sistema deberá permitir registrar clientes. |
| RF02 | El sistema deberá permitir consultar y modificar los datos de los clientes. |
| RF03 | El sistema deberá permitir registrar las habitaciones del hotel. |
| RF04 | El sistema deberá permitir consultar la disponibilidad de las habitaciones. |
| RF05 | El sistema deberá permitir crear reservas. |
| RF06 | El sistema deberá permitir consultar y modificar las reservas existentes. |
| RF07 | El sistema deberá almacenar la información de clientes, habitaciones y reservas en una base de datos. |
| RF08 | El sistema deberá disponer de una plataforma web para acceder a las funcionalidades de gestión. |
| RF09 | El sistema deberá disponer de una zona de administración para gestionar la información. |
| RF10 | El sistema deberá permitir realizar copias de seguridad de la información almacenada. |

## 4.2. Requisitos no funcionales

Los requisitos no funcionales definen las características que deberá cumplir la solución.

| ID | Requisito |
|---|---|
| RNF01 | La infraestructura deberá estar basada en servicios virtualizados mediante Docker. |
| RNF02 | Los servicios deberán estar organizados de forma modular e independiente. |
| RNF03 | La plataforma deberá estar disponible mediante un navegador web. |
| RNF04 | La información almacenada deberá estar protegida mediante medidas básicas de seguridad. |
| RNF05 | La infraestructura deberá permitir realizar tareas de mantenimiento y configuración de los servicios. |
| RNF06 | La solución deberá disponer de mecanismos de copia de seguridad. |
| RNF07 | La documentación del proyecto deberá mantenerse mediante un sistema de control de versiones. |

## 4.3. Requisitos de red

Los requisitos de red establecen las necesidades de comunicación de la infraestructura.

| ID | Requisito |
|---|---|
| RN01 | Los servicios deberán disponer de conectividad de red para comunicarse entre ellos. |
| RN02 | La infraestructura deberá disponer de una configuración de red organizada. |
| RN03 | Los servicios necesarios deberán utilizar los puertos de red correspondientes. |
| RN04 | La comunicación entre los diferentes servicios deberá estar controlada. |
| RN05 | La infraestructura deberá permitir realizar pruebas de conectividad y funcionamiento de los servicios. |

## 4.4. Prioridad de los requisitos

Los requisitos se clasificarán según su importancia para el funcionamiento del proyecto:

- **Alta:** requisitos necesarios para que el sistema pueda funcionar.
- **Media:** requisitos que mejoran el funcionamiento y la administración de la solución.
- **Baja:** requisitos que pueden incorporarse posteriormente sin afectar al funcionamiento principal.
