# 5. Matriz de trazabilidad

La matriz de trazabilidad permite relacionar los requisitos definidos para el proyecto con los diferentes módulos de 2.º de ASIR que intervienen en su desarrollo.

| ID | Descripción | Tipo | ASGBD | ASO | IAW | Red | Seguridad |
|---|---|---|---|---|---|---|---|
| RF01 | Registrar clientes | Funcional | ✓ | - | ✓ | - | - |
| RF02 | Consultar y modificar clientes | Funcional | ✓ | - | ✓ | - | ✓ |
| RF03 | Registrar habitaciones | Funcional | ✓ | - | ✓ | - | - |
| RF04 | Consultar disponibilidad | Funcional | ✓ | - | ✓ | ✓ | - |
| RF05 | Crear reservas | Funcional | ✓ | - | ✓ | ✓ | ✓ |
| RF06 | Consultar y modificar reservas | Funcional | ✓ | - | ✓ | ✓ | ✓ |
| RF07 | Almacenar información en base de datos | Funcional | ✓ | - | ✓ | - | ✓ |
| RF08 | Disponer de plataforma web | Funcional | - | ✓ | ✓ | ✓ | ✓ |
| RF09 | Disponer de zona de administración | Funcional | ✓ | ✓ | ✓ | - | ✓ |
| RF10 | Realizar copias de seguridad | Funcional | ✓ | ✓ | - | - | ✓ |
| RNF01 | Utilizar servicios virtualizados mediante Docker | No funcional | - | ✓ | ✓ | ✓ | ✓ |
| RNF02 | Organizar los servicios de forma modular | No funcional | - | ✓ | ✓ | ✓ | ✓ |
| RNF03 | Permitir acceso mediante navegador web | No funcional | - | - | ✓ | ✓ | ✓ |
| RNF04 | Proteger la información mediante medidas básicas de seguridad | No funcional | ✓ | ✓ | ✓ | - | ✓ |
| RNF05 | Permitir mantenimiento y configuración de servicios | No funcional | - | ✓ | ✓ | ✓ | ✓ |
| RNF06 | Disponer de mecanismos de copia de seguridad | No funcional | ✓ | ✓ | - | - | ✓ |
| RNF07 | Mantener la documentación mediante control de versiones | No funcional | - | ✓ | ✓ | - | ✓ |
| RN01 | Disponer de conectividad entre servicios | Red | - | ✓ | - | ✓ | ✓ |
| RN02 | Mantener una configuración de red organizada | Red | - | ✓ | - | ✓ | ✓ |
| RN03 | Utilizar los puertos de red correspondientes | Red | - | ✓ | ✓ | ✓ | ✓ |
| RN04 | Controlar la comunicación entre servicios | Red | - | ✓ | ✓ | ✓ | ✓ |
| RN05 | Permitir realizar pruebas de conectividad | Red | - | ✓ | ✓ | ✓ | ✓ |
