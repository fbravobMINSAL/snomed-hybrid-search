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

## 2. Buenas prácticas LOINC

El mapeo aplicará las
[Recommendations for best practices in using and mapping to LOINC](https://loinc.org/kb/users-guide/recommendations-for-best-practices-in-using-and-mapping-to-loinc)
publicadas por Regenstrief Institute, en lo pertinente al caso LOINC → MAI. En particular:

- se verificará que un panel contenga todos sus elementos requeridos y que no incorpore mediciones
  primarias adicionales antes de considerarlo equivalente;
- los elementos opcionales y las sustituciones de método, propiedad o sistema se tratarán conforme a
  las reglas oficiales de LOINC;
- no se sustituirán resultados cuantitativos o semicuantitativos por cualitativos, ni a la inversa;
- se registrará la versión LOINC utilizada y se planificará su actualización según la recomendación
  oficial vigente.

Estas reglas se utilizarán para validar el significado del término o panel LOINC antes de asociarlo a
un código MAI agrupador.
