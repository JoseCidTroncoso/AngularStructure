<div align="center">
  <h1>Estructura de Carpetas Recomendada</h1>
  <h1>para una Aplicación en Angular</h1>
  <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular Logo" width="200px">
</div>

---

## 📂 Estructura de Carpetas
Esta estructura de carpetas se encuentra optimizada para proyectos de Angular en versiones desde 10 en adelante:

## 📚 Descripción de Carpetas y Archivos

- **<h3>src</h3>**: Carpeta raíz que contiene todo el código fuente de tu aplicación.
    - **<h4>app</h4>**: Carpeta que contiene el código específico de tu aplicación.
        - **<h5>components</h5>**: Contiene los componentes de tu aplicación. Estos deben ser organizados en subcarpetas según su función o características.
            - shared
                - shared.component.ts
                - shared.component.html
                - shared.component.css
            - component1
                - component1.component.ts
                - component1.component.html
                - component1.component.css
            - component2
                - component2.component.ts
                - component2.component.html
                - component2.component.css
        - **</h5>services</h5>**: Aquí se encuentran los servicios utilizados para lógica de negocio o comunicación con APIs externas.
        - **models**: Contiene las definiciones de modelos de datos utilizados en tu aplicación.
        - **modules**: Carpeta que contiene los módulos de tu aplicación. Deben ser organizados en carpetas según las características o funcionalidades que proporcionen.
        - **guards**: Contiene los guardias de ruta utilizados para proteger rutas en tu aplicación.
        - **interceptors**: Carpeta que contiene los interceptores de peticiones HTTP.
        - **enums**: Contiene las enumeraciones utilizadas en tu aplicación.
        - **pipes**: Aquí se encuentran los pipes personalizados utilizados para transformar datos en tus plantillas.
        - **directives**: Contiene las directivas personalizadas utilizadas en tu aplicación.
    - **assets**: Carpeta que contiene los recursos estáticos de tu aplicación, como imágenes, frameworks de diseño UI que no se instalen por npm, etc.
    - **environments**: Carpeta que contiene los archivos de configuración para diferentes entornos, como desarrollo y producción.
    - **index.html**: Archivo HTML principal de tu aplicación.
    - **main.ts**: Punto de entrada de tu aplicación.
    - **styles.css**: Archivo de estilos globales de tu aplicación.
- **angular.json**: Archivo de configuración de Angular.
- **package.json**: Archivo de configuración de paquetes y dependencias de tu aplicación.
- **tsconfig.json**: Archivo de configuración del compilador de TypeScript.
- **tslint.json**: Archivo de configuración para las reglas de linting de TypeScript.

---


