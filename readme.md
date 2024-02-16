## NPM

Instalar dependencias:
```bash
proyecto> npm install <nombre_dependencia> 
proyecto> npm install <nombre_dependencia> --save
desarrollo> npm install -D <nombre_dependencia>
desarrollo> npm install <nombre_dependencia> --save-dev
global> npm install -g <nombre_dependencia>
```
- Listar dependencias globales:
```bash
npm list -g
```
- Listar dependencias de un proyecto:
```bash
npm list
```
- Intalar de forma opcional:
```bash
npm install <nombre_dependencia> -o
```
- Simular instalacion sin instalar:
```bash
npm install <nombre_dependencia> --dry-run
```
- Instalar una versión en particular:
```bash
npm install <nombre_dependencia>@<version>
```

- Instalar la version mas reciente de una dependencia:
```bash
npm install <nombre_dependencia>@latest
```
- Instalar las dependencias que se encuentren en package.json:
```bash
npm install
```

### Agregar scripts
```json
"scripts": {
    "start": "node index.js"
  }
```
- Ejecutar script:
```bash
npm run start
npm start
```

- Ejecutar con &&:
```json
"scripts": {
    "node": "node index.js && echo 'Terminado'"
  }
```
- Ejecutar:
```bash
npm run node
```
 ### Ejecutar con npx
```bash
npx <nombre_dependencia>
```
npx = node package execute
npm = node package manager

### Actualizar dependencias
```bash
npm update
```
### Dependencias por actualizar
```bash
npm outdated
```

### auditoria informe de vulnerabilidades au
```bash
npm audit
```

### Aditoria en json
```bash 
npm audit --json
```
### Auditoria con el fix
```bash
npm audit fix
```

### Auditoria y fix de forma forzada
```bash
npm audit fix --force
```
