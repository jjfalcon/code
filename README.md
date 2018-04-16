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

### [Implementing SOLID and the onion architecture](https://dev.to/remojansen/implementing-the-onion-architecture-in-nodejs-with-typescript-and-inversifyjs-10ad)
Este artículo describre la arquitectura de cebolla. Esta arquitectura, es una arquitectura de aplicaciones software que sigue los principios SOLID. Usa ampliamente el principio de inyección de dependencias, y está influenciada por los principios Domain Driven Design (DDD) y algunos principios de programación funcional.

### [Herramientas para programadores](https://medium.freecodecamp.org/tools-i-wish-i-had-known-about-when-i-started-coding-57849efd9248)
Extensiones Chrome y Extensiones VisualCode para programadores web

## Test

### [The Practical Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
Es un artículo con código de ejemplo que explica la metáfora "Pirámide de Test", que nos agrupa los diferentes tests a realizar a un software, en unitarios, integración, aceptación.
Nos da una idea gráfica de cuantos tests debemos tener en cada uno de esos grupos, así como el rango de coste asociado.

![Pirámide de Test](https://martinfowler.com/articles/practical-test-pyramid/testPyramid.png)

### [End to End Testing with Google's Puppeteer and Jest](https://egghead.io/courses/end-to-end-testing-with-google-s-puppeteer-and-jest)

## Desarrollo Producto
[¿Qué pruebas debemos hacerle a nuestro software y para qué?](https://www.genbetadev.com/trabajar-como-desarrollador/que-pruebas-debemos-hacerle-a-nuestro-software-y-para-que)

[6 Tips to Design an MVP of Your Promising Idea](https://dzone.com/articles/6-tips-to-design-an-mvp-of-your-promising-idea)

### [Como crear una app de éxito](http://richardmorla.com/crear-una-app-exito/)
Como montar un negocio basado en una aplicación móvil. Pero crear una app de éxito no es solo programarla, hay mucho más detrás.

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

### [The Agile Fluency Model](https://martinfowler.com/articles/agileFluency.html)
Agile methods are solidly in the mainstream, but that popularity hasn't been without its problems. Organizational leaders are complaining that they’re not getting the benefits they expected. This article presents a fluency model that will help you get the most out of agile ideas. Fluency evolves through four distinct zones, each with its own benefits, required proficiencies, and key metrics. 

![The Agile Fluency Model](https://martinfowler.com/articles/agileFluency/agile-fluency-model-v2-simple-2-1.png)

### OTROS
[Aprendizajes con Google Forms](https://medium.com/@ladypain/aprendizajes-con-google-forms-4c26b4c9151a) Pregunta para validar hipotesis antes de desarrollar una app.

[Every Agile Software Project Needs a User Story Map ](https://dzone.com/articles/every-agile-software-project-needs-a-user-story-ma)

[StackOverflow Developer Survey Results 2018](https://insights.stackoverflow.com/survey/2018/)

## Herramientas
[Getting Started With Jenkins: The Ultimate Guide](https://dzone.com/articles/getting-started-with-jenkins-the-ultimate-guide?oid=twitter)

[Repl.it: programa desde tu navegador gratis y con más de 40 lenguajes](https://www.genbeta.com/web/repl-it-programa-desde-tu-navegador-gratis-y-con-mas-de-40-lenguajes)

[Tools I wish I had known about when I started coding on web](https://medium.freecodecamp.org/tools-i-wish-i-had-known-about-when-i-started-coding-57849efd9248)
In the tech world, there are thousands of tools that people will tell you to use. How are you supposed to know where to start?  If you are just starting to learn how to program, this will hopefully offer you some guidance. If you are a seasoned developer, hopefully you will still learn something new. I am going to recomend:

Chrome Extensions
* WhatFont. This is an easy way of finding out the fonts that your favorite website is using
* Pesticide. Useful for seeing the outlines of your <div>s and modifying CSS.
* Colorzilla.  Useful for copying exact colors off of a website.
* CSS Peeper.   Useful for looking at colors and assets used on a website.
* Wappalizer.  Useful for seeing the technologies being used on a website. 
* JSON Formatter .  Useful for making JSON look cleaner in the browser. 
* Vimeo Repeat and Speed . Useful for speeding up Vimeo videos.
* [Page Ruler](https://chrome.google.com/webstore/detail/page-ruler/jlpkojjdgbllmedoapgfodplfhcbnbpn?hl=es) Dibuja una regla para obtener las dimensiones en píxeles. Mide objetos de cualquier página web.

VS Code extensions
* Auto Rename Tag . Auto rename paired HTML tags.
* HTML CSS Support . CSS support for HTML documents.
* HTML Snippets . Useful code snippets. Another nice time saver. Pair this with Emmet and you barely ever have to type real HTML again.
* Babel ES6/ES7 . Adds JavaScript Babel syntax coloring.
* Bracket Pair Colorizer . Adds colors to brackets for easier block visualization. 
* ESLint . Integrates ESLint into Visual Studio Code.
* Guides . Adds extra guide lines to code.
* JavaScript Console Utils . Makes for easier console logging. 
* Code Spell Checker . Spelling checker that accounts for camelCase.
* Git Lens.  Makes it easier to see when, and by whom, changes were made. 
* Path Intellisense . File path autocompletion.
* Prettier . Automatic code formatter. 
* VSCode-Icons . Adds icons to the file tree. 
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) Launch a development local Server with live reload feature for static & dynamic page.

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

### Rest
[REST API Security](https://dzone.com/refcardz/rest-api-security-1?chapter=1) Rest API security is the single biggest challenge organizations want to see solved in the years ahead. This Refcard provide a better understanding of REST APIs, authentication types, and other aspects of security.

### Frontend 
[Flutter](https://flutter.io/) [Anuncio Lanzamiento](https://developers-latam.googleblog.com/2018/03/anuncio-de-flutter-beta-1-crea-bonitas.html)
[Google lanza Flutter](https://www.esferaiphone.com/desarrolladores-2/primera-beta-flutter-google/)
Build beautiful native apps in record time.
Flutter is Google’s mobile UI framework for crafting high-quality native interfaces on iOS and Android in record time. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source. 
[

[Little UI details](https://twitter.com/i/moments/880688233641848832)
A collections of little tips from @steveschoger to improve your visual design skills with the little details that make a big difference 👏

[Paligo. La nueva generacion de documentación técnica](https://intojs.github.io/architecting-single-page-applications/)
Una único origen de contenido completo y publicación multicanal. Genera tu contenido una vez y publicalo donde quieras.
Publica tu contenido como centro de ayuda HTML5, PDF de alta calidad, móvil,SCORM para eLearning, MS Word, presentación HTML5, y muchos más formatos.

## Ejemplos

[Desarrolla integraciones con bots a través de la plataforma y la API de Hangouts Chat ](https://developers-latam.googleblog.com/2018/03/desarrolla-integraciones-con-bots.html)

## Videos
[¿Cobras poco? Carreras profesionales en software | David Bonilla en T3chFest 2018](https://www.youtube.com/watch?v=d2_CUOeCgVE&app=desktop) Bonilla

