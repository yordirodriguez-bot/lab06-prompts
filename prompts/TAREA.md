# Tarea: Mi prompt profesional

## Funcionalidad elegida

Sistema de registro y gestión de clientes (CRUD de clientes) para una tienda de abarrote.

## Version 1: prompt basico

```text
Hazme un codigo para registrar clientes.
```

## Version 2

Actua como desarrollador Java. Crea un programa de consola en Java para registrar clientes con los atributos: id, nombre, correo y telefono. Presenta el codigo organizado en una clase Cliente y una clase Principal.

## Version 3: prompt final

Actua como un desarrollador Senior en Java. Crea un sistema por consola para la gestion y registro de clientes.

Atributos requeridos: id, nombre, correo y telefono.
Restricciones:

- No uses librerias externas ni frameworks (solo Java Standard Library).
- Valida que el correo contenga un '@' y un '.'
- Valida que el telefono tenga exactamente 9 digitos numericos.

Formato de entrega:

- Explica brevemente la estructura de las clases.
- Muestra el codigo organizado en dos clases: Cliente.java y GestionClientes.java.
- Incluye un metodo de prueba con datos simulados en la clase principal.

## Componentes del prompt final

| Componente                | Texto de mi prompt                                                                                                                                |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Rol**                   | Actua como un desarrollador Senior en Java.                                                                                                       |
| **Instruccion**           | Crea un sistema por consola para la gestion y registro de clientes.                                                                               |
| **Contexto**              | Atributos requeridos: id, nombre, correo y telefono.                                                                                              |
| **Ejemplo / Restricción** | No uses librerias externas. Valida que el correo contenga '@' y '.' y que el telefono tenga 9 digitos.                                            |
| **Formato**               | Explica brevemente la estructura, muestra el codigo organizado en dos clases (Cliente.java y GestionClientes.java) e incluye un metodo de prueba. |

## Evaluacion del resultado

| Criterio                                                                | Cumple (Sí / No) |
| ----------------------------------------------------------------------- | ---------------- |
| ¿El código está escrito exclusivamente en Java sin librerías externas?  | Sí               |
| ¿Contiene la estructura modular solicitada (Cliente y GestionClientes)? | Sí               |
| ¿Aplica las validaciones correctas para correo y teléfono?              | Sí               |
| ¿Incluye explicación de la estructura y método de prueba?               | Sí               |

## Errores que evite

Errores que evite
Ser demasiado general: En la V1 el pedido era vago; lo solucioné en la V3 delimitando el lenguaje, la interfaz (consola) y las clases específicas.

Asumir información no proporcionada: Para evitar que la IA inventara librerías o estructuras avanzadas (como bases de datos SQL), agregué explícitamente la restricción de usar solo la Java Standard Library.
