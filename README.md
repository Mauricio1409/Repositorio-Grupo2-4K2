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
| Torti - Mauricio Ivan           | 400619 |
| Piaggio - Uriel Agunstin      | 87599  |
| D'Andrea Escoda - Thiago Augusto | 87381  |
| Soria - Carolina Mikaela       |84829  |


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
│   │   └──Mails/
│   ├── Minutas/                                 # Minutas de reunión, cronogramas y el Plan de SCM.
│   └── Cronograma/                              # Planificación y seguimiento
├── 03_Entregas/                                 # Trabajos entregables
│   ├── TIs/                                     # Trabajos de Investigación
│   │   └── Ti_[N]/                           
│   │       ├── Consigna/
│   │       └── Entrega/                    
│   └── TPs/                                     # Trabajos Prácticos             
│       └── Tp_[N]/ 
│           ├── Consigna/
│           └── Entrega/                          
├── 04_Producto/                         # Artefactos que forman parte del producto 
│   ├── Documentacion/                   # ERS, Arquitectura, Manuales.
│   └── Codigo_fuente/                   # Repositorio del código desarrollado en el TP 6.
└── 05_Material_extra/
    └── Clases/
        └── Clase_[Fecha]_[Descripcion]/         
                       
---
```
## Reglas de Nombrado

**Los nombres de las carpetas deberán comenzar con mayúscula y utilizar guion bajo (_) como separador entre palabras.
Los nombres de los archivos deberán escribirse estrictamente en minúsculas, sin acentos ni caracteres especiales, utilizando guion bajo (_) como separador entre palabras.

| Ítem de Configuración (SCI) | Ubicación                                                 | Regla de nombrado                         |
| --------------------------- | --------------------------------------------------------- | ----------------------------------------- |
| Material de referencia      | `/01_Catedra/Bibliografia/Material_de_referencia/`        | `nombre_del_tema.ext`                     |
| Material recomendado        | `/01_Catedra/Bibliografia/Material_recomendado_en_clase/` | `nombre_del_material.ext`                 |
| Presentaciones              | `/01_Catedra/Bibliografia/Presentaciones/`                | `nombre_del_tema.ext`                     |
| Clases grabadas             | `/01_Catedra/Bibliografia/Clases_grabadas/`               | `clase_[fecha]_[descripcion].ext`         |
| Modalidad                   | `/01_Catedra/Modalidad/`                                  | `nombre_del_documento.ext`                |
| Templates                   | `/01_Catedra/Templates_para_practicos_y_parciales/`       | `tipo_de_template.ext`                    |
| Parciales                   | `/01_Catedra/Parciales/`                                  | `nombre_o_descripcion.ext`                |
| Plan de SCM                 | `/02_Gestion_grupo/`                                      | `plan_scm_g[N].pdf`                       |
| Minuta de reunión           | `/02_Gestion_grupo/Minutas/`                              | `minuta_[yyyy_mm_dd].pdf`                 |
| Cronograma                  | `/02_Gestion_grupo/Cronograma/`                           | `cronograma_g[N].xlsx`                    |
| Trabajo Práctico            | `/03_Entregas/TPs/Tp_[N]/Entrega/`                        | `tp[N]_[nombre_corto]_g[N].pdf`           |
| Trabajo de Investigación    | `/03_Entregas/TIs/Ti_[N]/Entrega/`                   | `ti[N]_[nombre_corto]_g[N].pdf`           |
| User Stories                | `/03_Entregas/TPs/Tp_[N]/Entrega/`                        | `tp[N]_req_[ejercicio]_user_stories.md`   |
| MVP                         | `/03_Entregas/TPs/Tp_[N]/Entrega/`                        | `tp[N]_req_[ejercicio]_mvp.pdf`           |
| Estimaciones                | `/03_Entregas/TPs/Tp_[N]/Entrega/`                        | `tp[N]_req_[ejercicio]_estimaciones.xlsx` |
| Casos de prueba             | `/03_Entregas/TPs/Tp_[N]/Entrega/`                        | `tp[N]_tst_[ejercicio]_casos_prueba.md`   |
| Retrospectiva de Sprint     | `/03_Entregas/TPs/Tp_[N]/Entrega/`                        | `tp[N]_scr_retrospective_sprint_[N].md`   |
| Requerimientos (ERS)        | `/04_Producto/Documentacion/`                             | `ers_[nombre_producto].pdf`               |
| Arquitectura                | `/04_Producto/Documentacion/`                             | `arquitectura_[nombre_producto].pdf`      |
| Código fuente               | `/04_Producto/Codigo_fuente/`                             | `[nombre_modulo].[extension]`             |
| Manual de usuario           | `/04_Producto/Documentacion/`                             | `manual_usuario_[nombre_producto].pdf`    |

---



## Criterio de Línea Base

Una línea base es un conjunto de Ítems de Configuración (SCIs) formalmente revisados y aprobados, que sirven de referencia para el desarrollo posterior.

### 1. Establecimiento de Línea Base
Se marcará una nueva línea base inmediatamente después de la entrega formal de cada hito evaluable, 
como Trabajos Prácticos o Trabajos Conceptuales, en el Aula Virtual, tras la validación interna del equipo y externa de la cátedra.

### 2. Convención de Etiquetas (Tags)

Para mantener consistencia, las etiquetas en Git se escribirán en minúscula, sin espacios ni caracteres especiales.

Regla de nombrado para tags:

`base_tp[N]_[nombre_corto]`

Ejemplo:

`base_tp4_scm`

### Historial de Línea Base
| Línea Base     | Fecha        | Descripción                                     |
| -------------- | ------------ | ----------------------------------------------- |
| `base_tp4_scm` | `2026-08-XX` | Línea base correspondiente a la entrega del TP4 |

---
* Nota: Tenemos una LB en la misma fecha, esto se debe a una consulta a los PO sobre la nota del mismo trabajo práctico evaluable, por ello tras su respuesta, cerramos la LB junto a la entrega del TP 11 que se realizó en base al cronograma de la materia.



## Glosario

| Sigla   | Significado                                                                |
| ------- | -------------------------------------------------------------------------- |
| **TIs** | Trabajos de Investigación                                                  |
| **TPs** | Trabajos Prácticos                                                         |
| **TP**  | Trabajo Práctico                                                           |
| **SCM** | Gestión de Configuración de Software (*Software Configuration Management*) |
| **SCI** | Ítem de Configuración de Software (*Software Configuration Item*)          |
| **N**   | Número de ítem o trabajo (1, 2, ..., n)                                    |
| **G**   | Número de grupo                                                            |
| **REQ** | Requerimientos                                                             |
| **TST** | Testing                                                                    |
| **SCR** | Scrum                                                                      |
| **MVP** | Producto Mínimo Viable (*Minimum Viable Product*)                          |
| **LB**  | Línea Base                                                                 |
| **ERS** | Especificación de Requisitos de Software                                   |



## Herramienta a utilizar para SCM

- GitHub: Plataforma de alojamiento en la nube del repositorio remoto.
- Git: Herramienta local de control de versiones distribuida.

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



