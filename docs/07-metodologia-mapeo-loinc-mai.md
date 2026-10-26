# Metodología de mapeo LOINC → MAI

## Estado

Borrador metodológico en desarrollo.

## 1. Fuente terminológica

Para el mapeo LOINC → MAI se utilizará el catálogo elaborado por **LABSIEL**, cargado en Open
Concept Lab (OCL) con la siguiente identificación:

- **Organización OCL:** `MINSAL`
- **Fuente OCL:** `LABSIEL`
- **Catálogo institucional:**
  <https://192.168.60.12:8443/#/orgs/MINSAL/sources/LABSIEL/>

El catálogo será consultado mediante el **servicio terminológico institucional**. De esta forma, los
términos y sus identificadores se obtendrán desde la fuente administrada en OCL y no desde copias
manuales incorporadas al código de la herramienta.

La URL pertenece a una red privada, por lo que su consulta requiere conectividad y autorización
institucional. La definición del endpoint de consulta, mecanismo de autenticación, versión del
catálogo y reglas de correspondencia se documentará en las siguientes etapas.
