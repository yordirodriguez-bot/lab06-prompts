# Bitacora de prompts

Laboratorio 06: Fundamentos de Ingenieria de Prompts.

Herramienta de IA usada: (escribe aqui cual usaste)

## Ejercicio 2: Tokens y ventana de contexto

pasa por que en la ia no se guarda los datos como tal

| Texto                              | Caracteres | Tokens |
| ---------------------------------- | ---------- | ------ |
| Los estudiantes programan en Java. | 35         | 7      |
| The students program in Java.      | 30         | 6      |
| desafortunadamente                 | 5          | 20     |

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos                             |
| ----------- | -------------- | ----------------------------------------------------- |
| 0           | 100%           | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5         | 65.3%          | LibroYa, BiblioTec, BiblioTec, LibroYa, BiblioTec     |
| 1           | 44.5%          | BiblioTec, LectoGo, BiblioTec, PaginaLibre, LibroYa   |
| 1.8         | 32.2%          | NubeDeTinta, NubeDeTinta, LectoGo,BiblioTec,LibroYa   |

no inventa otro noombre por que tiene los datos ya obtenidos.

## Ejercicio 4: Prompt vago vs estructurado

| Criterio                            | Prompt vago | Prompt estructurado |
| ----------------------------------- | ----------- | ------------------- |
| Menciona el objetivo del sistema    | no          | si                  |
| Menciona a los usuarios principales | no          | si                  |
| Tiene exactamente 3 funcionalidades | no          | si                  |
| Esta en 3 parrafos                  | no          | si                  |
| Lo usaria en un informe real        | no          | si                  |

## Ejercicio 5: Anatomia de un prompt

| Componente  | Texto de mi prompt                                                   |
| ----------- | -------------------------------------------------------------------- | --- |
| Rol         | Actua como desarrollador Java.                                       |
| Instruccion | Crea un programa en Java usando una clase Producto ..                |
| Contexto    | para gestionar los productos de una tienda.                          |     |
| Ejemplo     | Usa este estilo para los metodos: getPrecio()...                     |
| Formato     | Explica primero la estructura de la clase y luego presenta el codigo |

| Qué revisar                                            | Cumple (Sí / No) |
| ------------------------------------------------------ | ---------------- |
| ¿Está escrito en Java y usa Swing?                     | si               |
| ¿Pide correo y contraseña?                             | si               |
| ¿Explica el funcionamiento antes o después del código? | si               |
| ¿El código está organizado en clases?                  | si               |
| ¿Valida los datos que ingresa el usuario?              | no               |

## Ejercicio 6: Del prompt basico al profesional

```text
(Actua como desarrollador Java. Crea un ejemplo de login para una
aplicacion de escritorio utilizando Swing. El usuario debe ingresar
correo y contrasena. Explica brevemente el funcionamiento y presenta
el codigo organizado por clases.

Mejora el codigo anterior con estas restricciones: no uses librerias
externas, valida que el correo contenga @ y que la contrasena tenga
al menos 8 caracteres, y muestra los mensajes con JOptionPane.)
```
