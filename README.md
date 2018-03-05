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

### [Creando Cloud Tutorial](https://rominirani.com/creating-google-cloud-shell-tutorials-a1774cc4eb93)
I love creating developer tutorials. A recently released feature on Google Cloud Platform allows you to create a tutorial that runs inside Google Cloud Shell. This definitely opens up multiple possibilities and all I need to do to keep this tutorial updated is probably minimal text changes and code updates. I think it has very good potential and I am excited about it.

This blog post will be about how to go about creating tutorials that provide a seamless experience to the user in terms of packaging all the code necessary to run your tutorial, provision that on the Cloud Shell and provide step by step instructions that helps the reader follow along, in true tutorial style.

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

### Git - GitHub
[A developer’s introduction to GitHub](https://medium.freecodecamp.org/a-developers-introduction-to-github-1034fa55c0db)
As a developer, you can’t avoid using GitHub or another Git-based tool on a daily basis as part of your work. It’s used to either host your code or to collaborate on other people’s code. This article explains some key concepts of GitHub, and how to use some of its features to improve your workflow.

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

[Visual Studio Code: HTML, CSS & JS Tips](https://youtu.be/bJiIzz8mFMs)

### Firebase
[CRUD en Firebase](https://youtu.be/W-NS2RZm7QM) conectando nuestra app web con firebase

### Frontend 

[Flutter](https://flutter.io/)
[Google lanza Flutter](https://www.esferaiphone.com/desarrolladores-2/primera-beta-flutter-google/)
Build beautiful native apps in record time.
Flutter is Google’s mobile UI framework for crafting high-quality native interfaces on iOS and Android in record time. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source. 

[Little UI details](https://twitter.com/i/moments/880688233641848832)
A collections of little tips from @steveschoger to improve your visual design skills with the little details that make a big difference 👏

