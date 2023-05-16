# Estructura de Carpetas Recomendada para una Aplicación en Angular 14

A continuación se muestra la estructura de carpetas recomendada para proyectos de Angular 14:

- **src**: Carpeta raíz que contiene todo el código fuente de tu aplicación.
    - **app**: Carpeta que contiene el código específico de tu aplicación.
        - **components**: Contiene los componentes de tu aplicación. Puedes organizarlos en subcarpetas según su función o características.
        - **services**: Aquí se encuentran los servicios utilizados para lógica de negocio o comunicación con APIs externas.
        - **models**: Contiene las definiciones de modelos de datos utilizados en tu aplicación.
        - **modules**: Carpeta que contiene los módulos de tu aplicación. Puedes organizarlos en carpetas según las características o funcionalidades que proporcionen.
        - **guards**: Contiene los guardias de ruta utilizados para proteger rutas en tu aplicación.
        - **interceptors**: Carpeta que contiene los interceptores de peticiones HTTP.
        - **enums**: Contiene las enumeraciones utilizadas en tu aplicación.
        - **pipes**: Aquí se encuentran los pipes personalizados utilizados para transformar datos en tus plantillas.
        - **directives**: Contiene las directivas personalizadas utilizadas en tu aplicación.
        - **assets**: Carpeta que contiene los archivos estáticos, como imágenes o archivos de estilos globales.
    - **assets**: Carpeta que contiene los recursos estáticos de tu aplicación.
    - **environments**: Carpeta que contiene los archivos de configuración para diferentes entornos, como desarrollo y producción.
    - **index.html**: Archivo HTML principal de tu aplicación.
    - **main.ts**: Punto de entrada de tu aplicación.
    - **styles.css**: Archivo de estilos globales de tu aplicación.
- **angular.json**: Archivo de configuración de Angular.
- **package.json**: Archivo de configuración de paquetes y dependencias de tu aplicación.
- **tsconfig.json**: Archivo de configuración del compilador de TypeScript.
- **tslint.json**: Archivo de configuración para las reglas de linting de TypeScript.

Esta estructura de carpetas es una recomendación general y puedes adaptarla según las necesidades específicas de tu proyecto.
