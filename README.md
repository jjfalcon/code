# code
En este documento se recopila la información general para programar y desarrollar software, independiente del lenguaje, plataforma, tecnología o modas.

### [Algunos trucos para escribir código](https://jesuslc.com/2018/02/05/algunos-trucos-para-escribir-codigo/)
Es un artículo resumen de [este repositorio](https://github.com/jupeter/clean-code-php), donde se presentan recomendaciones que inciden sobre la lectura de código para acercarse a principios SOLID y CleanCode, como los siguientes:
* utilizar variables que puedas pronunciar y expilcativas del contexto
* utilizar constantes para minimiza los números mágicos  if (user.access == USER_ACCESS_UPDATED) { ... }
* encasular condicionales en funciones   if (article.isReserved()) { ... }
* evitar elses y usar early returns para comprobar al principio, lectura lineal, y menor identacion
* evitar demasiado contexto. Dejarlo natural a la lectura.
* evitar nombres genericos (handld, object, etc.)
* evitar flags en funciones demasiado genericas, y especializar funciones
* crear variables tan proximas como sea posible
* usar la minima identacion
* tener paciencia, un buen nombre no se consigue a la primera
* usar comentarios de bloque para indicar la intencion (porque) lo hacemos así al que lo lee.
* evitar comentarios para describir codigo, definelo en el propio codigo

### [Herramientas para programadores](https://medium.freecodecamp.org/tools-i-wish-i-had-known-about-when-i-started-coding-57849efd9248)
Extensiones Chrome y Extensiones VisualCode para programadores web

## Test

### [The Practical Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
Es un artículo con código de ejemplo que explica la metáfora "Pirámide de Test", que nos agrupa los diferentes tests a realizar a un software, en unitarios, integración, aceptación.
Nos da una idea gráfica de cuantos tests debemos tener en cada uno de esos grupos, así como el rango de coste asociado.

![Pirámide de Test](https://martinfowler.com/articles/practical-test-pyramid/testPyramid.png)

## Desarrollo Producto

### [Causas de fallo del desarrollo de producto](https://medium.com/@itortv/reflexi%C3%B3n-sobre-la-inc%C3%B3moda-charla-the-root-cause-of-product-failure-de-marty-cagan-6704783e10)
Una empresa orientada a producto debe tener como misión masterizar este proceso. Estudiar los problemas actuales, buscar alternativas e inspiraciones para descubrir y entregar más rápido. Sino, el riesgo aumenta, y el dinero disminuye.
Para saber más: Inspired, how to create product customers love. By Marty Cagan. 

### [How to Build a Secret Product](https://dzone.com/articles/how-to-build-a-secret-product)
Project Proton has been an ambitious project from the beginning, and while I can’t go into the details yet, I can share the biggest lessons that we’ve learned as a company and reveal some useful tools that we’ve used along the way, such as:
* Start the way you mean to finish;
* Articulating the "why";
* Get the hell out of the building;
* Keep competitors in the rear-view mirror;
* Focus on building value, not features; and,
* Document, document, and document.

## Herramientas

### Visual Studio Code
[Visual Studio Code - Tutorial Español](https://youtu.be/Esnj9pntvyU) Tutorial básico para puesta en marcha
Extensiones recomendadas:
* VSCode icons, permite identificar iconos de los ficheros del proyecto/abiertos
* HTML Snippets permite escribir html/js/css con snippets para ahorrar codigo (consultar archivos/preferences/atajos)
* Javascript (ES6) code snippets
* HTML CSS suport
* Beautify
* ESLint, integra ESLint dentro de VSCode
* Saas, identado y autocompletado

(*) despues de instalar una extension reiniciar vscode para que tenga efecto

### Firebase
[CRUD en Firebase](https://youtu.be/W-NS2RZm7QM) conectando nuestra app web con firebase
