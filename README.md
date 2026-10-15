# Sistema de gestión de servicios tecnológicos

Proyecto grupal de PFU-111 Programación Fundamental
Programa en Python que usa herencia y polimorfismo para registrar servicios
de mantenimiento, instalación y soporte técnico, y calcular su costo.

## Integrantes

Hugo Marcelo Nina Garcia 

Brayan Oruña Guarachi  

Adriana Micaela Torrejon Peña  

Elvis Quispe Mamani 

## Descripción
Una empresa de servicios tecnológicos necesita administrar distintos tipos de servicios.
Todos comparten datos (código, cliente, descripción y precio base), pero cada tipo calcula
su costo de forma distinta.

- `Servicio` es la clase base.
- `Mantenimiento`, `Instalacion` y `SoporteTecnico` heredan de `Servicio`.
- Todos tienen el método `calcular_costo()`, y cada clase lo calcula a su manera.

Tipo Regla de cálculo 

| Mantenimiento | Precio base + cantidad de equipos × costo por equipo |
| Instalación | Precio base + cantidad de dispositivos × costo por dispositivo |
| Soporte técnico | Precio base + horas de atención × tarifa por hora |

# Cómo ejecutarlo
1. Instalar Python 3 (https://www.python.org).
2. Descargar este repositorio.
3. Abrir una terminal en la carpeta del proyecto y escribir:

python servicios.py

(En algunos sistemas el comando es `python3 servicios.py`.)

## Menú del programa
1. Registrar servicio de mantenimiento
2. Registrar servicio de instalación
3. Registrar servicio de soporte técnico
4. Mostrar los servicios registrados
5. Calcular y mostrar el costo de cada servicio
6. Mostrar el costo total de todos los servicios
7. Salir

El programa rechaza cantidades negativas, horas inválidas, valores que no son números y textos vacíos.
