# Conceptos de NPM y Node.js

# Que es npm?

Es un gestor de paquetes para node.js, que nos permite instalar paquetes de terceros, crear nuestros propios paquetes y compartirlos con la comunidad.

## comandos npm

### inicializar protyecto

1. **npm init**

```bash
npm init
```

En la consola nos va a preguntar por algunos datos:
nombre del proyecto, version, descripcion, entry point, test command, git repository, keywords, author, license

Este comando nos va a crear un archivo llamado package.json, en el cual se van a guardar las dependencias que instalemos en nuestro proyecto. tambien algunos datos como autor, version, descripcion, etc.

2. **npm init -y**

```bash
npm init -y
```

Este comando nos crea el package.json con los valores por defecto.

### npm install

1. **Instalar dependencias del proyecto**

```bash
npm install
```

Este comando nos permite instalar las dependencias que estan en el package.json

2. **Instalacion de nuevas dependencias**

```bash
npm install <nombre de la dependencia>
```

3. **Instalacion de depencias de desarrollo**

```bash
npm install -D <nombre de la dependencia>
npm install --save-dev <nombre de la dependencia>
```

Estos 2 comandos hacen lo mismo, instalan la dependencia pero la guardan en el package.json como dependencia de desarrollo.

4. **Instalacion de dependencias globales**

```bash
npm install -g <nombre de la dependencia>
```

Este comando instala la dependencia de forma global, es decir, que la dependencia se va a instalar en la carpeta de node_modules de nuestro sistema operativo.

5. **simular instalacion de dependencias**

```bash
npm install --dry-run
```

Este comando nos permite simular la instalacion de dependencias, es decir, que no se instalan las dependencias, pero nos muestra en consola que dependencias se instalarian. para evitar errores o poder ver en consola.

6. **instalar version especifica de una dependencia**

```bash
npm install <nombre de la dependencia>@<version>
```

Este comando nos permite instalar una version especifica de una dependencia.

### Ver los paquetes instalados

1. **Lsitar dependencias**

```bash
npm list
```

Este comando me listara en consola las dependencias que tengo instaladas en mi proyecto.

2. **Listar dependencias de desarrollo**

```bash
npm list -D
```

Este comando me listara en consola las dependencias de desarrollo que tengo instaladas en mi proyecto.

3. **Listar dependencias globales**

```bash
npm list -g
```

Este comando me listara en consola las dependencias globales que tengo instaladas en mi proyecto.

### npm uninstall

```bash
npm uninstall <nombre de la dependencia>
```

Este comando nos permite desinstalar una dependencia.

## Ejemplo de dependencias

{} [Ejemplo 1](

```bash
npm install lite-server
```

Esta dependencia me permite crear un servidor local para mi proyecto.
)

{} [Ejemplo 2](

```bash
npm install gh-pages
```

)

{} [Ejemplo 3](

```bash
npm install -g sass
```

)

{} [Ejemplo 4](

```bash

```
