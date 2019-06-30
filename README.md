# Angular-8-PWA-SSR

Angular 8 Progressive Web Application with Server Side Rendering. ng8pwassrtemplate

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.6.

## Install global packages: Angular CLI, TypeScript, Firebase Tools

```
npm install -g @angular/cli  
npm install -g firebase-tools  
```
## common ng new command switches

### --minimal

The minimal option creates a minimal angular project. No testing files included and inline template code for components.

### --inline-template

The inline-template option will generate inline HTML inside the component ts file.

### --inline-style

The inline-style option will generate inline CSS inside the component ts file.

### --style=[css | scss | less | sass | styl]

The style option specifies what CSS preprocessor is used in building the project. the options are: css, scss, less, sass, styl.

### --routing

The routing option generates a file app-routing.module.ts file.

### --prefix=appname

By default all your component selector prefixes are set to app. The prefix option

### --skip-git

Creates a new project without a Git repository.

## Code scaffolding

```
ng new ng8pwassrtemplate --routing --style scss --enable-ivy --skip-install --skip-git
CREATE ng8pwassrtemplate/README.md (1034 bytes)
CREATE ng8pwassrtemplate/.editorconfig (246 bytes)
CREATE ng8pwassrtemplate/.gitignore (629 bytes)
CREATE ng8pwassrtemplate/angular.json (3600 bytes)
CREATE ng8pwassrtemplate/package.json (1290 bytes)
CREATE ng8pwassrtemplate/tsconfig.json (435 bytes)
CREATE ng8pwassrtemplate/tslint.json (1988 bytes)
CREATE ng8pwassrtemplate/browserslist (429 bytes)
CREATE ng8pwassrtemplate/karma.conf.js (1029 bytes)
CREATE ng8pwassrtemplate/tsconfig.app.json (267 bytes)
CREATE ng8pwassrtemplate/tsconfig.spec.json (270 bytes)
CREATE ng8pwassrtemplate/src/favicon.ico (5430 bytes)
CREATE ng8pwassrtemplate/src/index.html (304 bytes)
CREATE ng8pwassrtemplate/src/main.ts (372 bytes)
CREATE ng8pwassrtemplate/src/polyfills.ts (2838 bytes)
CREATE ng8pwassrtemplate/src/styles.scss (80 bytes)
CREATE ng8pwassrtemplate/src/test.ts (642 bytes)
CREATE ng8pwassrtemplate/src/assets/.gitkeep (0 bytes)
CREATE ng8pwassrtemplate/src/environments/environment.prod.ts (51 bytes)
CREATE ng8pwassrtemplate/src/environments/environment.ts (662 bytes)
CREATE ng8pwassrtemplate/src/app/app-routing.module.ts (245 bytes)
CREATE ng8pwassrtemplate/src/app/app.module.ts (393 bytes)
CREATE ng8pwassrtemplate/src/app/app.component.scss (0 bytes)
CREATE ng8pwassrtemplate/src/app/app.component.html (1152 bytes)
CREATE ng8pwassrtemplate/src/app/app.component.spec.ts (1128 bytes)
CREATE ng8pwassrtemplate/src/app/app.component.ts (222 bytes)
CREATE ng8pwassrtemplate/e2e/protractor.conf.js (810 bytes)
CREATE ng8pwassrtemplate/e2e/tsconfig.json (214 bytes)
CREATE ng8pwassrtemplate/e2e/src/app.e2e-spec.ts (646 bytes)
CREATE ng8pwassrtemplate/e2e/src/app.po.ts (251 bytes)
```

### Adding a service worker to your project (PWA)

[Getting started with service workers](https://angular.io/guide/service-worker-getting-started)

```
ng add @angular/pwa --project ng8pwassrtemplate
Installed packages for tooling via npm.
CREATE ngsw-config.json (585 bytes)
CREATE src/manifest.webmanifest (1091 bytes)
CREATE src/assets/icons/icon-128x128.png (1253 bytes)
CREATE src/assets/icons/icon-144x144.png (1394 bytes)
CREATE src/assets/icons/icon-152x152.png (1427 bytes)
CREATE src/assets/icons/icon-192x192.png (1790 bytes)
CREATE src/assets/icons/icon-384x384.png (3557 bytes)
CREATE src/assets/icons/icon-512x512.png (5008 bytes)
CREATE src/assets/icons/icon-72x72.png (792 bytes)
CREATE src/assets/icons/icon-96x96.png (958 bytes)
UPDATE angular.json (3776 bytes)
UPDATE package.json (1363 bytes)
UPDATE src/app/app.module.ts (604 bytes)
UPDATE src/index.html (486 bytes)
```

### Add Server-side Rendering (SSR)

[Server-side Rendering (SSR): An intro to Angular Universal](https://angular.io/guide/universal)

Run the command:

```
ng add @nguniversal/express-engine --clientProject ng8pwassrtemplate
CREATE src/main.server.ts (220 bytes)
CREATE src/app/app.server.module.ts (318 bytes)
CREATE tsconfig.server.json (204 bytes)
CREATE webpack.server.config.js (1360 bytes)
CREATE server.ts (1500 bytes)
UPDATE package.json (1903 bytes)
UPDATE angular.json (4325 bytes)
UPDATE src/main.ts (432 bytes)
UPDATE src/app/app.module.ts (649 bytes)
```
### Add needed packages only if using Firebase

ws: a Node.js WebSocket library

xhr2 : XMLHttpRequest Emulation for node.js. It implements the W3C XMLHttpRequest specification on top of the node.js APIs.

bufferutil: is what makes ws fast. It provides some utilities to efficiently perform some operations such as masking and unmasking the data payload of WebSocket frames.

utf-8-validate: Check if a buffer contains valid UTF-8 encoded text.

```
npm install ws xhr2 bufferutil utf-8-validate  --save-dev
```

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Run the command:

```
ng add @angular/pwa --project ng8pwassrtemplate
```

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
