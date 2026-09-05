# Caso "Un Corto en Cannes" – Resolución (hasta Gantt, sin costos)

## Supuesto de planificación
Inicio del proyecto: lunes 5 de enero de 2026. Con 16 semanas de duración total, el cierre cae el
27 de abril de 2026, cumpliendo el requisito de "listo a fines de abril".

## 1. Project Charter

**Proyecto:** Producción del cortometraje de apertura – Festival de Cannes 2026 ("Un Corto en Cannes")

**Objetivo:** Producir un cortometraje de hasta 20 minutos que narre la historia del cine de forma
innovadora, cubriendo los hitos relevantes desde sus orígenes hasta la actualidad, para la apertura
del Festival de Cannes de mayo de 2026.

**Justificación:** La productora fue contratada para abrir el festival con una pieza audiovisual
propia, lo que la posiciona ante la industria internacional del cine.

**Descripción de alto nivel del proyecto:** Gestión integral de la pre-producción (locación, elenco,
recursos materiales) y de la producción (catering y rodaje) del cortometraje. La post-producción
(edición y tráiler) queda fuera del alcance: la productora la subcontrata de forma directa.

**Entregable final del proyecto:** Grabaciones originales de las escenas del rodaje más dos copias
de resguardo.

**Fecha límite:** Material filmado listo a fines de abril de 2026, para permitir la edición previa al
estreno en Cannes (mayo de 2026).

**Restricciones:**
1. Duración final del corto no mayor a 20 minutos.
2. Plazo: material listo a fines de abril de 2026.
3. Técnica de filmación Croma-Key (fondo verde), condiciona el tipo de locación.

**Supuestos:**
1. El proyecto comienza la primera semana de enero de 2026.
2. Se contratarán 20 actores.
3. La post-producción queda a cargo de un proveedor contratado directamente por la productora.

**Interesados clave:**
1. Productora (cliente / sponsor)
2. Project Manager (equipo a cargo del caso)
3. Equipo de arte y dirección
4. Elenco y equipo técnico
5. Proveedores (locación, catering, recursos materiales)
6. Organización del Festival de Cannes (interesado externo, fija la fecha de estreno)

**Entregables principales:**
1. Locación acondicionada y disponible
2. Elenco contratado
3. Recursos materiales dispuestos en la locación
4. Catering contratado
5. Grabaciones originales del rodaje más dos copias de resguardo

**Project Manager designado:** A cargo de la gestión del cronograma y el presupuesto de
pre-producción y producción.

**Riesgos iniciales de alto nivel:**
1. Demoras en encontrar una locación con las características técnicas requeridas.
2. Demoras en el proceso de audición (actividad más larga y crítica del proyecto).
3. Disponibilidad de un proveedor de catering de calidad dentro del presupuesto previsto.

## 2. Exclusiones del Scope Statement

1. La post-producción del cortometraje (edición del material y desarrollo del tráiler teaser) queda
   excluida del alcance del proyecto; la productora la subcontratará de forma directa a otra compañía.
2. La distribución, proyección o logística del estreno en el Festival de Cannes no forma parte del
   proyecto.
3. El desarrollo del guion y la definición del contenido histórico del corto no se gestionan como
   actividad de este proyecto; se asumen definidos por el área de dirección/guion.
4. Los seguros de locación, equipos y personal no están descriptos como actividad en el caso, por lo
   que quedan fuera del alcance salvo indicación en contrario del cliente.
5. El resguardo de las dos copias del material se limita a su guardado seguro; no incluye ningún tipo
   de edición o procesamiento del contenido.

## 3. WBS (posterior a la firma del Scope Statement)

```
1.0 Un Corto en Cannes
├── 1.1 Pre-Producción
│   ├── 1.1.1 Locación
│   │   ├── 1.1.1.1 Búsqueda de locación
│   │   └── 1.1.1.2 Alquiler de locación
│   ├── 1.1.2 Actores
│   │   ├── 1.1.2.1 Desarrollo de perfiles
│   │   ├── 1.1.2.2 Audición
│   │   └── 1.1.2.3 Contratación de actores
│   └── 1.1.3 Recursos Materiales
│       ├── 1.1.3.1 Listado de recursos
│       ├── 1.1.3.2 Búsqueda de proveedores
│       ├── 1.1.3.3 Análisis de alternativas
│       ├── 1.1.3.4 Contratación de proveedores
│       └── 1.1.3.5 Envío y disposición en locación
└── 1.2 Producción
    ├── 1.2.1 Catering
    │   ├── 1.2.1.1 Búsqueda de alternativas
    │   ├── 1.2.1.2 Análisis de propuestas
    │   └── 1.2.1.3 Contratación de catering
    └── 1.2.2 Rodaje
        ├── 1.2.2.1 Filmación (Rodaje)
        └── 1.2.2.2 Resguardo y entrega de material fílmico
```

Nota: la post-producción (1.3 en el enunciado original) no integra el WBS porque fue excluida en el
Scope Statement.

## 4. Listado de actividades (duración y precedencias, sin costos)

| ID | WBS     | Actividad                                  | Duración | Predecesora(s) |
|----|---------|---------------------------------------------|---------:|----------------|
| A  | 1.1.1.1 | Búsqueda de locación                        | 4 sem    | —              |
| B  | 1.1.1.2 | Alquiler de locación                        | 1 sem    | A              |
| C  | 1.1.2.1 | Desarrollo de perfiles de actores           | 3 sem    | —              |
| D  | 1.1.2.2 | Audición de actores                         | 6 sem    | C              |
| E  | 1.1.2.3 | Contratación de actores                     | 1 sem    | D              |
| F  | 1.1.3.1 | Listado de recursos materiales              | 2 sem    | —              |
| G  | 1.1.3.2 | Búsqueda de proveedores de materiales       | 4 sem    | F              |
| H  | 1.1.3.3 | Análisis de alternativas de proveedores     | 1 sem    | G              |
| I  | 1.1.3.4 | Contratación de proveedores de materiales   | 1 sem    | H              |
| J  | 1.1.3.5 | Envío y disposición de recursos en locación | 1 sem    | I, B           |
| K  | 1.2.1.1 | Búsqueda de alternativas de catering        | 3 sem    | —              |
| L  | 1.2.1.2 | Análisis de propuestas de catering          | 2 sem    | K              |
| M  | 1.2.1.3 | Contratación del catering *(supuesto)*      | 1 sem    | L              |
| N  | 1.2.2.1 | Rodaje (filmación)                          | 6 sem    | E, J, M        |
| O  | 1.2.2.2 | Resguardo y entrega de material (hito)      | 0 sem    | N              |

*Supuesto sobre la tarea M:* el caso no indica la duración de la contratación final del catering.
Por analogía con las demás tareas de "contratación" del caso (contratación de actores = 1 semana,
contratación final de proveedores = 1 semana), se asume 1 semana. Se deja explícito como supuesto a
validar con el cliente.

## 5. Diagrama de Red (AON) y camino crítico

Duración total del proyecto: **16 semanas**.

Camino crítico: **C → D → E → N → O** (3 + 6 + 1 + 6 + 0 = 16 semanas).

| ID | Dur | ES | EF | LS | LF | Holgura | ¿Crítica? |
|----|----:|---:|---:|---:|---:|--------:|:---------:|
| A  | 4   | 0  | 4  | 4  | 8  | 4       | No        |
| B  | 1   | 4  | 5  | 8  | 9  | 4       | No        |
| C  | 3   | 0  | 3  | 0  | 3  | 0       | **Sí**    |
| D  | 6   | 3  | 9  | 3  | 9  | 0       | **Sí**    |
| E  | 1   | 9  | 10 | 9  | 10 | 0       | **Sí**    |
| F  | 2   | 0  | 2  | 1  | 3  | 1       | No        |
| G  | 4   | 2  | 6  | 3  | 7  | 1       | No        |
| H  | 1   | 6  | 7  | 7  | 8  | 1       | No        |
| I  | 1   | 7  | 8  | 8  | 9  | 1       | No        |
| J  | 1   | 8  | 9  | 9  | 10 | 1       | No        |
| K  | 3   | 0  | 3  | 4  | 7  | 4       | No        |
| L  | 2   | 3  | 5  | 7  | 9  | 4       | No        |
| M  | 1   | 5  | 6  | 9  | 10 | 4       | No        |
| N  | 6   | 10 | 16 | 10 | 16 | 0       | **Sí**    |
| O  | 0   | 16 | 16 | 16 | 16 | 0       | **Sí**    |

Lectura clave: la ruta de casting (perfiles → audición → contratación) es el verdadero cuello de
botella del proyecto, no la locación ni los recursos materiales, que tienen 4 semanas de holgura. La
ruta de recursos materiales (F-G-H-I-J) es la "casi crítica", con solo 1 semana de holgura.

## 6. Gantt (fechas, sin costos)

Inicio de proyecto: lunes 5 de enero de 2026.

| ID | Actividad                                   | Inicio      | Fin         |
|----|-----------------------------------------------|------------|------------|
| A  | Búsqueda de locación                          | 05-ene-26  | 01-feb-26  |
| B  | Alquiler de locación                          | 02-feb-26  | 08-feb-26  |
| C  | Desarrollo de perfiles de actores             | 05-ene-26  | 25-ene-26  |
| D  | Audición de actores                           | 26-ene-26  | 08-mar-26  |
| E  | Contratación de actores                       | 09-mar-26  | 15-mar-26  |
| F  | Listado de recursos materiales                | 05-ene-26  | 18-ene-26  |
| G  | Búsqueda de proveedores de materiales         | 19-ene-26  | 15-feb-26  |
| H  | Análisis de alternativas de proveedores       | 16-feb-26  | 22-feb-26  |
| I  | Contratación de proveedores de materiales     | 23-feb-26  | 01-mar-26  |
| J  | Envío y disposición de recursos en locación   | 02-mar-26  | 08-mar-26  |
| K  | Búsqueda de alternativas de catering          | 05-ene-26  | 25-ene-26  |
| L  | Análisis de propuestas de catering            | 26-ene-26  | 08-feb-26  |
| M  | Contratación del catering                     | 09-feb-26  | 15-feb-26  |
| N  | Rodaje (filmación)                            | 16-mar-26  | 26-abr-26  |
| O  | Resguardo y entrega de material (hito)        | 27-abr-26  | 27-abr-26  |

El cierre del 27 de abril de 2026 coincide con el límite de "fines de abril" fijado en el caso: el
proyecto cumple el plazo, pero sin ninguna holgura en el camino crítico.
