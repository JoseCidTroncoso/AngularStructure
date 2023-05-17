<div align="center">
  <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular Logo" width="150px">
  <h1>Estructura de Carpetas Recomendadas</h1>
  <h1>para una Aplicación en Angular</h1>
</div>

---

## 📂 Estructura de Carpetas
Esta estructura de carpetas se encuentra optimizada para proyectos de Angular en versiones desde 10 en adelante:

- src
    - app
        - components
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
        - services
            - service1.service.ts
            - service2.service.ts
        - models
            - model1.ts
            - model2.ts
        - modules
            - feature1
                - feature1.module.ts
                - feature1.component.ts
                - feature1.component.html
                - feature1.component.css
            - feature2
                - feature2.module.ts
                - feature2.component.ts
                - feature2.component.html
                - feature2.component.css
        - guards
            - auth.guard.ts
            - admin.guard.ts
        - interceptors
            - http.interceptor.ts
        - enums
            - enum1.ts
            - enum2.ts
        - pipes
            - pipe1.pipe.ts
            - pipe2.pipe.ts
        - directives
            - directive1.directive.ts
            - directive2.directive.ts
        - assets
            - images
            - styles
    - assets
    - environments
    - index.html
    - main.ts
    - styles.css
- angular.json
- package.json
- tsconfig.json
- tslint.json

---
## 📚 Descripción de Carpetas y Archivos

| Carpeta/Archivo    | Descripción                                                                                       |
|--------------------|---------------------------------------------------------------------------------------------------|
| src/               | Carpeta raíz que contiene todo el código fuente de tu aplicación.                                |
| src/app/           | Carpeta que contiene el código específico de tu aplicación.                                       |
| src/app/components/| Contiene los componentes de tu aplicación, estos deben ser organizados en subcarpetas según su función o características |
| src/app/services/  | Aquí se deberan colocar los servicios utilizados para lógica de negocio o comunicación con APIs externas.|
| src/app/models/    | Contiene las definiciones de modelos de datos utilizados en tu aplicación.                        |
| src/app/modules/   | Carpeta que contiene los módulos de tu aplicación, estos deben ser organizados en carpetas según las características o funcionalidades que proporcionen |
| src/app/guards/    | Contiene los "guardias de ruta" utilizados para proteger rutas en tu aplicación.                    |
| src/app/interceptors/ | Carpeta que contiene los interceptores de peticiones HTTP.                                      |
| src/app/enums/     | Contiene las enumeraciones utilizadas en tu aplicación.                                           |
| src/app/pipes/     | Contiene los pipes personalizados utilizados para transformar datos en tus plantillas.  |
| src/app/directives/| Contiene las directivas personalizadas utilizadas en tu aplicación.                               |
| src/assets/        | Carpeta que contiene los recursos estáticos de tu aplicación, como imágenes, frameworks de diseño UI que no se instalen mediante npm, etc. |
| src/environments/  | Carpeta que contiene los archivos de configuración para diferentes entornos, como desarrollo y producción. |
| src/index.html     | Archivo HTML principal de tu aplicación.                                                          |
| src/main.ts        | Punto de entrada de tu aplicación.                                                                |
| src/styles.css     | Archivo de estilos globales de tu aplicación.                                                     |
| angular.json       | Archivo de configuración de Angular.                                                              |
| package.json       | Archivo de configuración de paquetes y dependencias de tu aplicación.                             |
| tsconfig.json      | Archivo de configuración del compilador de TypeScript.                                            |
| tslint.json        | Archivo de configuración para las reglas de linting de TypeScript.                               |

---
## 📚 Recomendaciones y Consideraciones para el Desarrollo de Aplicaciones en Angular


### ***Reutilización de componentes:***
* Identificar funcionalidades recurrentes en varios sitios de la aplicación y desarrollar componentes reutilizables para ellas. Estos componentes pueden ser insertados en diferentes partes de la aplicación utilizando etiquetas HTML.

### ***Separación de responsabilidades:***
* Aplicar el principio de responsabilidad única para mantener los componentes lo más enfocados y cohesivos posible. Cada componente debe tener una única responsabilidad y no debe abarcar funcionalidades demasiado diversas.

### ***División en módulos:***
  Organizar la aplicación en módulos, lo cual permite una mejor modularidad y facilita el mantenimiento y la reutilización de código. Cada módulo debe tener un propósito claro y agrupar componentes y servicios relacionados.

### ***Gestión de estado:***
Utilizar una biblioteca de gestión de estado, como Redux o NgRx, para administrar el estado de la aplicación de manera centralizada. Esto facilita el manejo de datos y la comunicación entre componentes.

### ***Optimización del rendimiento:***
Aplicar técnicas de optimización de rendimiento, como la detección de cambios OnPush y el uso de observables en lugar de promesas cuando sea posible. Esto ayuda a mejorar la eficiencia y la velocidad de la aplicación.

### ***Buena práctica de nombres:***
Utilizar nombres descriptivos y significativos para las variables, componentes, servicios, etc. Esto mejora la legibilidad del código y facilita la comprensión para otros desarrolladores.

### ***Pruebas unitarias:***
Escribir pruebas unitarias para validar el funcionamiento correcto de los componentes y servicios. Esto ayuda a detectar errores y garantiza un código más confiable y robusto.

### ***Documentación:***
Mantener una documentación clara y actualizada de la aplicación, incluyendo explicaciones de arquitectura, componentes clave, flujos de trabajo y convenciones de codificación. Esto facilita la colaboración y el mantenimiento a largo plazo.

### ***Control de versiones:***
Utilizar un sistema de control de versiones, como Git, para realizar un seguimiento de los cambios y facilitar la colaboración en equipo. Esto permite mantener un historial de versiones, gestionar conflictos y revertir cambios si es necesario.

### ***Seguridad:***
Aplicar buenas prácticas de seguridad, como la validación de entrada, el manejo seguro de datos confidenciales y la protección contra vulnerabilidades conocidas. Esto ayuda a proteger la aplicación contra posibles ataques y garantiza la privacidad y la integridad de los datos.

---

## Fuente:
1. [Documentacion de angular](https://angular.io/docs)
2. [ChatGPT](https://chat.openai.com/)
3. Mi experiencia como desarrollador.

## Autor:
### José Ant. Cid Troncoso
