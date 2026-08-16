# Sistema Automatizado para la Cruz Blanca de Bilwi

Sistema desarrollado como proyecto monográfico para apoyar el **control administrativo de expedientes y actividades de la Cruz Blanca de Bilwi, Puerto Cabezas - 2026**.

El propósito del sistema es mejorar la organización de la información institucional, reducir la dependencia de registros dispersos y facilitar el seguimiento de expedientes, actividades, usuarios y reportes administrativos.

---

## Objetivo del proyecto

Desarrollar un sistema automatizado para el control administrativo de expedientes y actividades de la Cruz Blanca de Bilwi, Puerto Cabezas, que permita optimizar la gestión de la información y mejorar la eficiencia de los procesos administrativos.

---

## ¿Qué problema busca resolver?

Actualmente, cuando la información se administra de forma manual o mediante herramientas separadas, pueden presentarse dificultades como:

- Búsqueda lenta de expedientes.
- Duplicidad de registros.
- Riesgo de pérdida o extravío de información.
- Falta de reportes automáticos.
- Dificultad para conocer quién registró o modificó información.
- Uso de formatos no estandarizados.
- Dependencia de archivos físicos, hojas sueltas o documentos separados.

El sistema busca centralizar estos procesos en una sola herramienta.

---

## Funciones principales

### Gestión de expedientes

El sistema permitirá:

- Registrar nuevos expedientes.
- Consultar expedientes existentes.
- Actualizar información.
- Manejar estados de los expedientes.
- Buscar por diferentes criterios.
- Registrar responsable y observaciones.
- Mantener un mejor seguimiento de la información.

### Gestión de actividades

Permitirá registrar:

- Nombre o descripción de la actividad.
- Fecha.
- Lugar.
- Responsable.
- Estado.
- Resultados.
- Observaciones.

### Usuarios y acceso

El sistema contempla el acceso mediante **usuario y contraseña**, permitiendo que la información institucional sea utilizada únicamente por personal autorizado.

Los permisos podrán variar según el tipo de usuario.

### Reportes

El módulo de reportes permitirá consultar información utilizando criterios como:

- Fecha.
- Estado.
- Responsable.

Esto facilitará la preparación de informes y el seguimiento administrativo.

### Seguridad y trazabilidad

El sistema está orientado a proteger la información institucional mediante:

- Acceso controlado.
- Permisos de usuario.
- Registro organizado de información.
- Seguimiento de modificaciones.
- Respaldo de datos.

---

# Guía básica de usuario

## 1. Iniciar sesión

1. Abrir el sistema.
2. Ingresar el usuario asignado.
3. Escribir la contraseña.
4. Presionar **Iniciar sesión**.

> El usuario y contraseña deben ser asignados por el administrador del sistema.

---

## 2. Registrar un expediente

1. Ingresar al módulo **Expedientes**.
2. Seleccionar la opción para registrar un nuevo expediente.
3. Completar los campos requeridos:
   - Código.
   - Nombre o identificación del expediente.
   - Tipo.
   - Fecha.
   - Responsable.
   - Estado.
   - Observaciones.
4. Revisar que la información sea correcta.
5. Presionar **Guardar**.
6. Verificar que el expediente aparezca en la lista de consulta.

---

## 3. Consultar un expediente

1. Entrar al módulo **Expedientes**.
2. Utilizar el buscador o los filtros disponibles.
3. Localizar el expediente deseado.
4. Seleccionarlo para consultar su información.

Según los permisos del usuario, también podrá actualizarse la información correspondiente.

---

## 4. Registrar una actividad

1. Ingresar al módulo **Actividades**.
2. Seleccionar la opción para registrar una nueva actividad.
3. Completar los datos:
   - Actividad.
   - Fecha.
   - Lugar.
   - Responsable.
   - Estado.
   - Resultados.
4. Guardar el registro.

---

## 5. Consultar reportes

1. Ingresar al módulo **Reportes**.
2. Seleccionar los filtros que se desean utilizar.
3. Filtrar por:
   - Fecha.
   - Estado.
   - Responsable.
4. Consultar la información generada.

---

## 6. Cerrar sesión

Al terminar de utilizar el sistema:

1. Ir a la opción de usuario.
2. Seleccionar **Cerrar sesión**.

Esto ayuda a proteger la información institucional y evita accesos no autorizados.

---

## Flujo general del sistema

```text
Inicio de sesión
      |
      v
Menú principal
      |
      +------------------+
      |                  |
      v                  v
 Expedientes         Actividades
      |                  |
      v                  v
Registrar /          Registrar /
Consultar            Consultar
      |                  |
      +--------+---------+
               |
               v
            Reportes
               |
               v
        Cerrar sesión
```

---

## Estructura del repositorio

```text
Sistema-Cruz-Blanca-Bilwi/
│
├── README.md
├── protocolo/
│   └── Protocolo_Cruz_Blanca_2026.docx
│
├── instrumentos/
│   ├── Instrumentos_Cruz_Blanca_Aurelia.docx
│   └── Procesamiento_Instrumentos.xlsx
│
├── documentacion/
│   ├── requerimientos/
│   ├── diagramas/
│   └── manual_usuario/
│
├── base_de_datos/
│
├── sistema/
│   ├── frontend/
│   └── backend/
│
└── evidencias/
```

---

## Metodología del proyecto

El desarrollo se plantea mediante un modelo **iterativo-incremental con apoyo de prototipado**, permitiendo construir el sistema por módulos, revisar avances y realizar ajustes progresivos.

Para el levantamiento de información se utilizan:

- Entrevista semiestructurada.
- Observación directa.
- Análisis documental.

---

## Estado del proyecto

Actualmente el proyecto contempla las siguientes etapas:

- [x] Elaboración del protocolo.
- [x] Diseño de instrumentos de recolección de datos.
- [ ] Aplicación de instrumentos.
- [ ] Procesamiento de información.
- [ ] Definición y validación de requerimientos.
- [ ] Diseño de base de datos.
- [ ] Diseño de interfaces.
- [ ] Desarrollo de módulos.
- [ ] Pruebas del sistema.
- [ ] Implementación piloto.
- [ ] Manual de usuario final.

---

## Tecnologías

Las tecnologías específicas utilizadas en la implementación deben documentarse de acuerdo con el desarrollo real del sistema.

Ejemplo de cómo completar esta sección posteriormente:

```text
Frontend: __________________
Backend:  __________________
Base de datos: _____________
Servidor/entorno: __________
```

---

## Consideraciones de seguridad

El sistema manejará información institucional, por lo que se recomienda:

- No compartir contraseñas.
- Cerrar sesión al finalizar.
- Limitar el acceso según el rol del usuario.
- Evitar publicar información personal o sensible en este repositorio.
- Mantener copias de seguridad de la información.

---

## Proyecto académico

**Bluefields Indian & Caribbean University - BICU**  
**Área de Conocimiento de Ciencias y Tecnología**  
**Ingeniería en Sistemas**

**Proyecto:**  
Diseño e implementación de un sistema automatizado para el control administrativo de expedientes y actividades de la Cruz Blanca de Bilwi, Puerto Cabezas - 2026.

**Autora:**  
Br. Aurelia Zelaya Gómez

**Tutor:**  
MSc. Edrad Jared Godoy Flores

**Bilwi, Puerto Cabezas - 2026**

---

> Este repositorio corresponde a un proyecto académico orientado a desarrollar una solución tecnológica para una necesidad administrativa real de la Cruz Blanca de Bilwi.
