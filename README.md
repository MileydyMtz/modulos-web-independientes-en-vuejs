# Módulos Web Independientes en VueJS
Este repositorio central contiene submódulos de los repositorios donde se alojan los diferentes componentes web independientes. Cada componente ha sido desarrollado en Vue 3, utilizando las siguientes tecnologías:
* **Vite** para la creación del proyecto.
* **Preprocesador SCSS** para los estilos.
* **Vitest** para las pruebas, siguiendo la metodología de TDD.

## Uso de los Componentes
Cada componente tiene su propia documentación que detalla cómo usarlo y qué modificaciones se pueden realizar para adaptarlo a las necesidades de tu proyecto. Se recomienda revisar la documentación de cada componente antes de utilizarlo.

### Clonar un Componente Específico
Si solo necesitas un componente específico, puedes clonar directamente su repositorio. Para hacer esto, sigue estos pasos:
* Haz clic en el submódulo correspondiente al componente que deseas en este repositorio.
* Serás redirigido a la página de GitHub del repositorio del componente.
* Una vez allí, haz clic en el botón "Code" y copia la URL del repositorio.
* Abre una terminal en tu máquina local, navega al directorio donde deseas clonar el repositorio y ejecuta:
  git clone URL-del-repositorio.

### Clonar todos los Componentes

Si prefieres clonar todos los componentes a la vez, puedes hacerlo clonando este repositorio central con todos sus submódulos. Para hacer esto, abre una terminal en tu máquina local, navega al directorio donde deseas clonar el repositorio y ejecuta:

```sh
git clone --recursive https://github.com/MileydyMtz/modulos-web-independientes-en-vuejs.git
```

Este comando clonará el repositorio central y todos sus submódulos, proporcionándote una copia local de todos los componentes.

## Instalacion
Puede ejecutar el proyecto donde se encuentra el componente para comprobar su funcion de acuerdo al ejemplo que se presenta, para ello se recomienda lo siguiente. 

### Configuración IDE recomendada

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

### Personalizar configuración

See [Vite Configuration Reference](https://vitejs.dev/config/).

### Configuración del Proyecto
```sh
npm install
```

#### Compilar y Recargar en Caliente para Desarrollo
```sh
npm run dev
```

#### Compilar y Minificar para Producción
```sh
npm run build
```

#### Ejecutar Pruebas Unitarias con [Vitest](https://vitest.dev/)
```sh
npm run test:unit
```

#### Lint con [ESLint](https://eslint.org/)
```sh
npm run lint
```


