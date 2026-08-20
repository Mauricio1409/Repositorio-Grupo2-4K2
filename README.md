# Repositorio-Grupo2-4K2

**Universidad Tecnológica Nacional**  
**Facultad Regional Córdoba (FRC)**  
**Ingeniería en Sistemas de Información**

## Ingeniería y Calidad de Software

**Trabajo Práctico:** "Herramientas de SCM"  
**Año:** 2026  
**Curso:** 4K2
**Grupo:** 2

---

## Integrantes del Grupo

| Nombre                        | Legajo |
|-------------------------------|--------|
| Quispe Ricra - Junior Jesus   | 97139  |
| Torti Mauricio Ivan           | 400619 |
| Piaggio - Uriel Agunstin      | 87599  |


---

## Estructura del repositorio

```
Repositorio-Grupo2-4K2
├── 01_Catedra/                 # Material provisto por los profesores (enunciados, guías)  
│   ├── Bibliografia/ 
│   │       ├── Material_de_referencia/
│   │       │   ├── Agilismo/
│   │       │   ├── Gestion_de_configuracion_de_software/
│   │       │   ├── Ingenieria_de_software/
│   │       │   ├── Lean_y_kanban/
│   │       │   ├── Test_driven_development/
│   │       │   └── Testing_de_software/
│   │       ├── Material_recomendado_en_clase/
│   │       ├── Presentaciones/
│   │       └── Clases_grabadas/
│   ├── Modalidad/
│   ├── Templates_para_practicos_y_parciales/
│   └── Parciales/
├── 02_Gestion_grupo/ 
│   ├── Comunicacion_docente/                    # Medio de comunicacion con los docentes y formato sugerido
│   │   └──Mails
│   ├── Minutas/                                 # Minutas de reunión, cronogramas y el Plan de SCM.
│   └── Cronograma/                              # Planificación y seguimiento
├── 03_Entregas/                                 # Trabajos entregables
│   ├── TIs/                                     # Trabajos de Investigación
│   │   └── Ti_<N>/                           
│   │       ├── Consigna/
│   │       └── Presentacion/                    
│   └── TPs/                                     # Trabajos Prácticos             
│       └── Tp_<N>/ 
│           ├── Consigna/
│           └── Entrega/                          
├── 04_Producto/ # Artefactos que forman parte del producto ```
│   ├── Documentacion/                   # ERS, Arquitectura, Manuales.
│   └── Codigo_fuente/                   # Repositorio del código desarrollado en el TP 6.
└── 05_Material_extra/
    └── Clases/
        └── Clase_<Fecha>_<Descripcion>/         
                       
---
```
## Reglas de Nombrado

**Archivos y carpetas:** Nombres descriptivos en minúscula y separados por guión bajo (_).

| Ítem de configuración | Regla de nombrado                                       | Ejemplo                                            |
|-----------------------|---------------------------------------------------------|----------------------------------------------------|
| User Stories          | `TP[N] - REQ - NombreEjercicio - UserStories.md`        | `TP4 - REQ - ParqueDiversiones - UserStories.md`   |
| MVP                   | `TP[N] - REQ - NombreEjercicio - MVP.pdf`               | `TP4 - REQ - ParqueDiversiones - MVP.pdf`          |
| Estimaciones          | `TP[N] - REQ - NombreEjercicio - Estimaciones.xlsx`     | `TP4 - REQ - ParqueDiversiones - Estimaciones.xlsx`|
| Casos de Prueba       | `TP[N] - TST - NombreEjercicio - CasosPrueba.md`        | `TP4 - TST - ParqueDiversiones - CasosPrueba.md`   |
| Retrospectiva Sprint  | `TP[N] - SCR - Retrospective - Sprint[N].md`            | `TP11 - SCR - Retrospective - Sprint3.md`          |

---

## Glosario

| Sigla  | Significado                                   |
|--------|-----------------------------------------------|
|  TIs   | Trabajos de Investigación                     |
|  TPs   | Trabajos Prácticos                            |
|  tp    | Trabajo práctico                              |
|  SCM   | Gestión de Configuración de Software          |
|   b    | Bibliografía                                   |
|   N    | Número de ítem (1, 2, ..., n)                  |
| REQ    | Requerimientos                                 |
| TST    | Testing                                        |
| SCR    | Scrum                                          |
| MVP    | Producto Mínimo Viable (Minimum Viable Product)|

 

## Herramienta a utilizar para SCM

- GitHub

- Git

---

## Flujo de trabajo

1. Siempre hacer `git pull origin master` antes de comenzar a trabajar
2. Realizar los cambios necesarios
3. Usar `git add .` para preparar los cambios
4. Crear un commit descriptivo siguiendo la convención de nombrado
5. Hacer `git push origin master` para subir los cambios

---

**Materia:** Ingeniería y Calidad de Software (ICS)  
**Curso:** 4K2 - Grupo 2
**Universidad:** UTN-FRC  
**Período:** 2026



