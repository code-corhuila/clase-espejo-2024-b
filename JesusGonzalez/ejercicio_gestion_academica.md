
# Ejercicio: Gestión Académica de Estudiantes y Materias

## Contexto del Ejercicio
En este ejercicio, desarrollarás un programa que permita gestionar la información de estudiantes, materias y sus matrículas. Además, implementarás el cálculo de las notas finales de cada materia considerando tres cortes evaluativos. Al final, se plantea un reto para optimizar el proceso de captura de datos mediante la construcción de funciones.

---

## Requerimientos del Ejercicio

1. **Entidad: Estudiante**
   Captura la información básica de cada estudiante:
   - Nombre
   - Apellido
   - Edad
   - Género
   - Correo electrónico
   - Teléfono

2. **Entidad: Materia**
   Gestiona las materias disponibles:
   - Nombre de la materia
   - Créditos
   - Descripción

3. **Entidad: Matrícula**
   Permite asociar estudiantes con materias, registrar las notas de los cortes evaluativos, y calcular la nota final de la materia.
   - **Datos requeridos**:
     - Estudiante
     - Materia
     - Tres cortes evaluativos:
       - **Corte 1**:
         - Nota de Trabajos: 15%
         - Nota Parcial: 70%
         - Nota de Certificación: 10%
         - Auto y Coevaluación: 5%
       - **Corte 2**: Igual ponderación
       - **Corte 3**: Igual ponderación
     - Nota final por materia: promedio ponderado de los tres cortes.

4. **Reto Adicional**
   Debido a la cantidad de datos que se deben capturar, **se propone construir funciones** que optimicen y simplifiquen el proceso de entrada de datos y cálculos. Este será tu desafío para optimizar el programa.

---

## Indicaciones del Ejercicio
1. Diseña un programa en **Java** que implemente las tres entidades.
2. Crea las clases necesarias con sus atributos y métodos.
3. Implementa:
   - Funcionalidad para registrar estudiantes.
   - Funcionalidad para registrar materias.
   - Funcionalidad para matricular estudiantes en materias y registrar las notas de los cortes.
   - Cálculo automático de la nota final de cada materia.
4. **Bonus**: Construye funciones reutilizables para la captura de datos y el cálculo de notas.

---

## Ejemplo de Salida del Programa
### Registro de un Estudiante:
```
Nombre: Juan
Apellido: Pérez
Edad: 20
Género: Masculino
Correo: juan.perez@example.com
Teléfono: 1234567890
```

### Registro de una Materia:
```
Nombre: Programación Orientada a Objetos
Créditos: 4
Descripción: Curso avanzado de Java con enfoque en POO.
```

### Matrícula y Notas:
```
Estudiante: Juan Pérez
Materia: Programación Orientada a Objetos
Notas Corte 1: 
    Trabajos: 4.5
    Parcial: 3.8
    Certificación: 4.0
    Auto y Coevaluación: 4.8
Notas Corte 2:
    Trabajos: 4.0
    Parcial: 4.2
    Certificación: 3.5
    Auto y Coevaluación: 4.5
Notas Corte 3:
    Trabajos: 4.8
    Parcial: 4.0
    Certificación: 4.2
    Auto y Coevaluación: 4.9
Nota Final: 4.23
```

### Optimización del Código:
Plantea cómo se podría reducir la repetición de código en el proceso de captura y cálculos mediante funciones específicas, como:
- Capturar información de estudiantes y materias.
- Calcular las notas de cada corte evaluativo.
- Mostrar los resultados en un formato claro.

---

