# DBT (Data Build Tool)

## Introduccion
DBT es una herramienta de transformacion de datos de codigo abierto que se utiliza para construir
y orquestar flujos de trabajo de datos. Permite a los analistas de datos definir, documentar y 
probar transformaciones de datos de manera controlada y escalable.

## Instalacion

Para instalar DBT, se siguen estos pasos:
1. Instalar Python o tener Python instalado
2. Instalar DBT utilizando pip: `pip install dbt`

## Comandos basicos de DBT

### Inicializar un proyecto DBT
`dbt init <nombre>`

### Ejecutar un modelo DBT
`dbt run`

### Compilar un modelo DBT
`dbt compile`

### Recargar modelos DBT
`dbt source snapshot-freshness`

### Ejecutar pruebas en un proyecto DBT
`dbt test`

### Limpiar archivos generados por DBT
`dbt clean`

## Configuración de DBT

Se puede configurar DBT mediante el archivo `dbt_project.yml`. Aquí se pueden establecer las siguientes opciones:

- `name`: Nombre del proyecto.
- `version`: Versión del proyecto.
- `profile`: Perfil de conexión a la base de datos.
- `models`: Rutas a los directorios que contienen los modelos DBT.
- `target`: Configuración de la base de datos de destino.
- `seeds`: Ruta al directorio que contiene los datos de semilla.
- `test`: Configuración de las pruebas DBT.
