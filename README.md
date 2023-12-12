Herramienta diseñada para realizar la homologación de columnas en las planillas de proyectos, horas y clientes. Este proyecto aborda la crítica tarea de comparar y corresponder las columnas entre estas planillas, asegurando la coherencia necesaria para la generación de presupuestos y facturación.

1. Estructura del Proyecto
    Estructura de Carpetas
        DataWorker/
            Contiene el núcleo del proyecto y archivos fundamentales.

            /main.py
                Punto de entrada principal del programa.
                Gestiona la ejecución del flujo principal y la interacción entre los diferentes módulos.
            
        modules/
            Almacena módulos específicos para manejar tareas particulares.
        
            /homologation.py
                Lógica de homologación de columnas.
                Contiene funciones para la comparación y correspondencia entre las planillas de proyectos, horas y clientes.
            /file_operations.py
                Operaciones relacionadas con la manipulación de archivos, como lectura, escritura y actualización.
                Utilizado por el módulo de homologación.
        
        data/
            Archivos de datos necesarios para la homologación.

            /proyectos.xlsx
                Contiene la información de la planilla de proyectos.
            /horas.xlsx
                Contiene la información de la planilla de horas.
            /clientes.xlsx
                Contiene la información de la planilla de clientes.
        
        output/
            Guarda los resultados o archivos de salida generados durante la homologación.

            resultado_homologacion.xlsx
                Almacena el resultado final de la homologación.
        
        docs/
            Documentación relacionada con el proyecto.

        README.md
            Guía rápida sobre la estructura del proyecto, instrucciones de ejecución y descripción del proceso de homologación.

        requirements.txt
            Lista de dependencias del proyecto para facilitar la instalación.

2. Ejecución del Proyecto
Asegúrese de tener las dependencias instaladas ejecutando:

    pip install -r requirements.txt

Ejecute el programa principal:

    python main.py

3. Resultados y Salida
    Los resultados de la homologación se encuentran en la carpeta output en el archivo resultado_homologacion.xlsx.
