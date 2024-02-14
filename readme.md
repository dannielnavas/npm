## NPM

Instalar dependencias:
```bash
proyecto> npm install <nombre_dependencia> 
proyecto> npm install <nombre_dependencia> --save
desarrollo> npm install -D <nombre_dependencia>
desarrollo> npm install <nombre_dependencia> --save-dev
global> npm install -g <nombre_dependencia>
```
Listar dependencias globales:
```bash
npm list -g
```
Listar dependencias de un proyecto:
```bash
npm list
```
Intalar de forma opcional:
```bash
npm install <nombre_dependencia> -o
```
Simular instalacion sin instalar:
```bash
npm install <nombre_dependencia> --dry-run
```
Instalar una versión en particular:
```bash
npm install <nombre_dependencia>@<version>
```

Instalar la version mas reciente de una dependencia:
```bash
npm install <nombre_dependencia>@latest
```
Instalar las dependencias que se encuentren en package.json:
```bash
npm install
```
