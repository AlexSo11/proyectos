# Proyectos pequeños

Colección de proyectos universitarios pequeños, agrupados en un solo repositorio:
dos de 2025 y dos de la materia de Sistemas Operativos.

## Requisitos

- Python 3
- Tkinter (incluido en Python en Windows y macOS; en Linux: `sudo apt install python3-tk`)

No hay dependencias externas: todos los scripts usan solo la biblioteca estándar.

## Proyectos

| Proyecto | Archivo | Descripción |
|----------|---------|-------------|
| Calculadora de programador | `code_proyectos/Calculadora_programador.py` | Calculadora Tkinter con operaciones básicas, trigonometría, raíz cuadrada, factorial, porcentaje y conversión entre hexadecimal, decimal, octal y binario. |
| Índice de masa corporal | `code_proyectos/Indice_masa_corporal.py` | Calcula el IMC a partir del peso y la altura, y muestra su clasificación. |
| Planificación Round-Robin | `code_proyectos/PLANIFICACION ROUND-ROBIN.py` | Simulación de planificación Round-Robin con quantum configurable, colas de nuevos, listos, bloqueados y terminados, y tabla BCP. |
| Sistema por lotes | `code_proyectos/SISTEMA_POR_LOTES.py` | Simulación de procesamiento por lotes: agrupa los procesos de tres en tres y permite pausar, interrumpir o marcar error. |

## Ejecución

Cada script abre su propia ventana de Tkinter:

```bash
python code_proyectos/Calculadora_programador.py
python code_proyectos/Indice_masa_corporal.py
python "code_proyectos/PLANIFICACION ROUND-ROBIN.py"
python code_proyectos/SISTEMA_POR_LOTES.py
```

## Notas

- Las operaciones del simulador Round-Robin se generan internamente y se resuelven sin `eval`.
- En el simulador por lotes, al interrumpir un proceso el lote se vuelve a encolar, pero la
  simulación en curso termina; hay que pulsar **Iniciar** de nuevo para continuar con el lote.
- Los cuatro programas son aplicaciones de escritorio; no tienen interfaz de línea de comandos.

## Créditos

Desarrollo: AlexWhite / [AlexSo11](https://github.com/AlexSo11).

Código original de los repositorios `Proyectos_2025` y `Proyectos_SistemasOperativos`,
unificados aquí.
