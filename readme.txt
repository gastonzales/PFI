Objetivos: Estructurar proyecto.

Estructura base, ir modificando acorde a necesidades

ProyectoFinalCarrera/

|-- docs/
|   |-- Datasheet
|   |-- Informe
|   |-- ...
|
|-- src/
|   |-- Firmware/
|   |   |-- PIC16F887/
|   |   |   |-- main.c
|   |   |   |-- pwm.c
|   |   |   |-- ...
|   |
|   |-- ControlPID/
|   |   |-- PIDController.c
|   |   |-- ...
|   |
|   |-- Interfaces/
|   |   |-- SerialCommunication.c
|   |   |-- UserInterface.c
|   |   |-- ...
|
|-- tests/
|   |-- simulaciones/
|   |   |--
|   |   |-- 
| 
|
|-- hardware/
|   |-- Esquematico
|   |   |-- LM2596_Module.pdf
|   |   |-- PIC16F887_Connections.pdf
|   |   |-- ...
|
|-- data/
|   |-- Recursos/
|   |   |-- ...
|
|-- assets/
|   |-- Images/
|   |   |-- Diagrams/
|   |   |   |-- SystemArchitecture.png
|   |   |   |-- ...
|   |   |-- Icons/
|   |   |   |-- Logo.png
|   |   |   |-- ...
|
|-- .gitignore
|-- LICENSE.txt
|-- README.md
|-- .github/
|   |-- workflows/
|       |-- build.yml
|       |-- test.yml
|
|-- .vscode/
|   |-- settings.json
|   |-- tasks.json
|   |-- ...
