# code
En este documento se recopila la información general para programar y desarrollar software, independiente del lenguaje, plataforma, tecnología o modas.

[A Developer’s Guide to Setting and Smashing Career Goals](https://simpleprogrammer.com/developers-setting-career-goals/)

[Tu marca personal como desarrollador de software](https://www.genbeta.com/desarrollo/tu-marca-personal-como-desarrollador-software)

### [Interesante ciclo desarrollo to-DO](https://medium.com/finizens-engineering/nuestro-ciclo-de-desarrollo-to-do-fe7acdac8ce5)

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

### [Evolutionary Database Design](https://www.martinfowler.com/articles/evodb.html)
Can database schemas be developed using Agile practices? This article says Yes! 
Over the last decade we've developed and refined a number of techniques that allow a database design to evolve as an application develops. This is a very important capability for agile methodologies. The techniques rely on applying continuous integration and automated refactoring to database development, together with a close collaboration between DBAs and application developers. The techniques work in both pre-production and released systems, in green field projects as well as legacy systems.

### [Auditoria de Apps](http://blog.koalite.com/2018/05/auditoria-quien-ha-hecho-que/) Patrones para guardar un registro de los cambios realizados en entidades.

### [No subestimes el poder de un log](http://blog.koalite.com/2014/09/no-subestimes-el-poder-de-un-log/)

### [Herramientas para programadores](https://medium.freecodecamp.org/tools-i-wish-i-had-known-about-when-i-started-coding-57849efd9248)
Extensiones Chrome y Extensiones VisualCode para programadores web

[Refcard Lean Software Development](https://dzone.com/storage/assets/9163261-dzone-refcard93-leansoftwaredevelopment.pdf)

[Application Agility Canvas](https://dzone.com/articles/application-agility-canvas)

## Test

### [The Practical Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)
Es un artículo con código de ejemplo que explica la metáfora "Pirámide de Test", que nos agrupa los diferentes tests a realizar a un software, en unitarios, integración, aceptación.
Nos da una idea gráfica de cuantos tests debemos tener en cada uno de esos grupos, así como el rango de coste asociado.

![Pirámide de Test](https://martinfowler.com/articles/practical-test-pyramid/testPyramid.png)

### [End to End Testing with Google's Puppeteer and Jest](https://egghead.io/courses/end-to-end-testing-with-google-s-puppeteer-and-jest)

[Testing in Production - Quality Software Faster](https://www.youtube.com/watch?v=9C0efJkT0Hg&feature=em-uploademail)
Una presentación rompedora de como realizar testing directamente en producción, donde el resumen sería:
* realiza operaciones periodicas en producción que quieras testear
* realiza operaciones en los periodos valle donde no tienes excesva carga y tienes margen de solucionar antes de cuello botella
* las operaciones que no se registren en datos vivos para no alterar el sistema.

[101 TDD Tips](http://www.codemanship.co.uk/files/101TddTips.pdf)

[TDD](http://www.codemanship.co.uk/tdd_jasongorman_codemanship.pdf) TDD course book absolutely free. 222 pages of clear and to-the-point tutorials and exercises that take you from the basics of Red-Green-Refactor to advanced skills in software design, refactoring, Continuous Integration and beyond. This book goes further than any other TDD book or course on the market. Whether you’re completely new to TDD, or an experienced practitioner, this book - and its associated training workshop - will challenge and improve you.

## Desarrollo Producto

[5 Design Mistakes Your Clients will Never Forgive and How to Avoid Them Using Pre-Built Websites](https://webdesignledger.com/5-design-mistakes-your-clients-will-never-forgive-and-how-to-avoid-them-using-pre-built-websites/amp/)

[The benefits of side projects](https://dzone.com/articles/the-benefits-of-side-projects)

[El Product Owner y cómo interpretar su rol](https://vanesatejada.com/2018/06/04/el-product-owner-y-como-interpretar-su-rol)

[A Step-by-Step Guide to Build a Minimum Viable Product (MVP) ](https://dzone.com/articles/a-step-by-step-guide-to-build-a-minimum-viable-pro)

[Rapid Prototyping: What To Do And What To Avoid](https://webdesignledger.com/rapid-prototyping-avoid/amp/)

[Why Should You Choose Rapid App Prototyping Prior to Building Your MVP?](https://dzone.com/articles/why-should-you-choose-rapid-app-prototyping-prior)

[¿Qué pruebas debemos hacerle a nuestro software y para qué?](https://www.genbetadev.com/trabajar-como-desarrollador/que-pruebas-debemos-hacerle-a-nuestro-software-y-para-que)

[6 Tips to Design an MVP of Your Promising Idea](https://dzone.com/articles/6-tips-to-design-an-mvp-of-your-promising-idea)

[Seguridad desde diseño](https://www.continuumsecurity.net/)

[One page product design - Jorge Barroso](https://www.youtube.com/watch?v=9wVJHZEeTY0)

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

[Las 4 grandes mentiras de un proyecto en equipo ](http://thinkwasabi.com/mentiras-proyecto-equipo/)

[Komercia una startup colombiana que Google Launchpad Start cambio en una semana](https://developers-latam.googleblog.com/2018/07/komercia-una-startup-colombiana-que.html)

[Experiencias trabajando en remoto](https://twitter.com/nyan_dev/status/1014968748737024000?refsrc=email&s=11&ref_src=twcamp%5Eshare%7Ctwsrc%5Eios%7Ctwgr%5Eemail) Experiencia de trabajo remoto en empresa 100% remota. La gran ventaja es contratar gente de cualquier parte del mundo (mas oferta, y más especialización). Cada desarrollador crear un nuevo repositorio en Github, y una nueva aplicación en Heroku. Programa, testea, despliega, mantiene, monitoriza, y todos los automatismos (scripts) necesarios que lo soportan. Utilizar las herramientas que mejor se adapte a cada contexto, lo que por supuesto se aplica al codigo, y a todos los ámbitos (comunicación, etc) Por ejemplo usan Trello en lugar de Jira. Con un board por proyecto y una tarjeta por tarea. Para comunicación asícrona sobre tareas, se escribe comentario en tarjeta, y el responsable la contesta sobre la misma tarejta cuando pueda. Di hola cuando empiezas, adios cuando te vas, y avisa cuando no vas a estar. Recuerda que no pueden verte y se trata de responsabilidad. Empatiza con el horario de tus compañeros. No dejes un marron al final del día de un compañero, si no es estricamente necesario. Piensa si a ti te gustaría. Puedes posponer el aviso hasta su mañana para evitarle el susto. También se usa Slack para comunicación no asociada directamente a las tareas. Negarse a herramientas de monitorizacion del tiempo estilo TimeDoctor.

Para las reuniones sincronas ineludibles se concierta un horario común, y se escriben las conclusiones de esas conversaciones en un lugar común al que pueda acceder cualquiera que por alguna razón no haya podido acudir.

### OTROS

[Aprendizajes con Google Forms](https://medium.com/@ladypain/aprendizajes-con-google-forms-4c26b4c9151a) Pregunta para validar hipotesis antes de desarrollar una app.

[Every Agile Software Project Needs a User Story Map ](https://dzone.com/articles/every-agile-software-project-needs-a-user-story-ma)

[StackOverflow Developer Survey Results 2018](https://insights.stackoverflow.com/survey/2018/)

[One day resolutions](https://one-day-resolutions.codecademy.com/) Pequeñas formaciones de un dia. Directas al grano!

### Comercial

[Las 15 lecciones de nuestro curso de ventas SumaCRM](https://www.sumacrm.com/blog/vas-a-vender-mas?utm_campaign=vuelve-el-blog-con-un-superpoder-este-ano-con-sumacrm-vas-a-vender-mas&utm_medium=email&utm_source=acumbamail)

## Cloud

[Build a Serverless Online Quiz with Google Cloud Functions and Cloud Firestore](https://rominirani.com/build-a-serverless-online-quiz-with-google-cloud-functions-and-cloud-firestore-1e3fbf84a7d8)

[Google- Anuncio de nivel gratuito de MongoDB Atlas en GCP](https://developers-latam.googleblog.com/2018/07/anuncio-de-nivel-gratuito-de-mongodb.html)

[Blog de Google Cloud Platform: Momento de presentar “Hello, World”: VM vs. contenedores, PaaS y FaaS ](https://developers-latam.googleblog.com/2018/06/blog-de-google-cloud-platform-momento_20.html)

[Tutorial : Analyzing Reviews using Google Sheets and Cloud Natural Language API](https://rominirani.com/tutorial-analyzing-reviews-using-google-sheets-and-cloud-natural-language-api-240ec8f3090c)

[Cloud Source Repositories: más que un repositorio Git privado ](https://developers-latam.googleblog.com/2018/06/cloud-source-repositories-mas-que-un.html)

[Lanzamiento de Cloud Functions para Firebase v1.0](https://developers-latam.googleblog.com/2018/04/lanzamiento-de-cloud-functions-para.html) 

[Ahora puedes documentar automáticamente tus API con Cloud Endpoints](https://developers-latam.googleblog.com/2018/04/ahora-puedes-documentar-automaticamente.html)

[Nivel gratuito de Google Cloud Platform](https://cloud.google.com/free/)

[Google Cloud Platform Project Setup](https://rominirani.com/google-cloud-functions-tutorial-writing-our-first-google-cloud-function-a62de60b5c90)

[Google Cloud Functions Tutorial](https://rominirani.com/google-cloud-functions-tutorial-overview-of-computing-options-3c27781e8ced)

[Modern Distributed Application deployment with Kubernetes and mongodb atlas](https://scotch.io/tutorials/modern-distributed-application-deployment-with-kubernetes-and-mongodb-atlas)

[Netlify](https://www.netlify.com/)Build, deploy, and managemodern web projects 

## Herramientas

[Usar AVA para tests en una API hecha en Node.js y Express](https://blog.adrianistan.eu/2018/07/15/usar-ava-para-tests-en-una-api-hecha-en-node-js-y-express/)

### Como optimizar nuestros sistemas operativos

[Windows]()
[Mac]()
[GNU-Linux](https://blog.desdelinux.net/como-optimizar-gnu-linux/)

[DevDocs](https://medium.freecodecamp.org/devdocs-is-joining-the-freecodecamp-community-ae185a1c14a6) https://github.com/jjfalcon/node/blob/master/README.md

[Station](https://getstation.com/) Station is the first smart workstation for busy people.
A single place for all of your web-applications. 

[hackr.io](https://wwwhatsnew.com/2018/05/19/hackr-un-buscador-de-los-mejores-cursos-y-tutoriales-de-programacion/?utm_source=dlvr.it&utm_medium=twitter) hackr, un buscador de los mejores cursos y tutoriales de programación

[MarkText](https://marktext.github.io/website/) Mark Text is a Markdown multi-platform (build with electron) editor for Mac, Windows, and Linux. It is a concise text editor, dedicated to improving your editing efficiency.

[Getting Started With Jenkins: The Ultimate Guide](https://dzone.com/articles/getting-started-with-jenkins-the-ultimate-guide?oid=twitter)

[Google Cloud Functions Tutorial : Writing our first Google Cloud Function](https://rominirani.com/google-cloud-functions-tutorial-writing-our-first-google-cloud-function-a62de60b5c90)

[Repl.it: programa desde tu navegador gratis y con más de 40 lenguajes](https://www.genbeta.com/web/repl-it-programa-desde-tu-navegador-gratis-y-con-mas-de-40-lenguajes)

[Creating Google Cloud Shell Tutorials](https://rominirani.com/creating-google-cloud-shell-tutorials-a1774cc4eb93)

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

[Top JavaScript VSCode Extensions for Faster Development](https://codeburst.io/top-javascript-vscode-extensions-for-faster-development-c687c39596f5)

### Git - GitHub
[A developer’s introduction to GitHub](https://medium.freecodecamp.org/a-developers-introduction-to-github-1034fa55c0db)
As a developer, you can’t avoid using GitHub or another Git-based tool on a daily basis as part of your work. It’s used to either host your code or to collaborate on other people’s code. This article explains some key concepts of GitHub, and how to use some of its features to improve your workflow. 

[El nuevo laboratorio de aprendizaje de GitHub te enseña todo sobre la plataforma y el desarrollo colaborativo](https://www.genbeta.com/actualidad/el-nuevo-laboratorio-de-aprendizaje-de-github-te-ensena-todo-sobre-la-plataforma-y-el-desarrollo-colaborativo)

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

## Ejemplos/Apps

[Cómo descargar vídeos de YouTube, Facebook y otros sitios usando la terminal en Windows, Linux o Mac](https://www.genbeta.com/paso-a-paso/como-descargar-videos-youtube-facebook-otros-sitios-usando-terminal-windows-linux-mac)

[Paligo. La nueva generacion de documentación técnica](https://intojs.github.io/architecting-single-page-applications/)
Una único origen de contenido completo y publicación multicanal. Genera tu contenido una vez y publicalo donde quieras.
Publica tu contenido como centro de ayuda HTML5, PDF de alta calidad, móvil,SCORM para eLearning, MS Word, presentación HTML5, y muchos más formatos.

## Ejemplos

[Desarrolla integraciones con bots a través de la plataforma y la API de Hangouts Chat ](https://developers-latam.googleblog.com/2018/03/desarrolla-integraciones-con-bots.html)

## Videos
[¿Cobras poco? Carreras profesionales en software | David Bonilla en T3chFest 2018](https://www.youtube.com/watch?v=d2_CUOeCgVE&app=desktop) Bonilla

[9 charlas comunidad CODE](https://twitter.com/comunidadcode/status/1017832172407918592) Entre las que se encuentran:
* Continuos delivery
* Ilusionismo con GitHub Pages
* Kubernetes
* Por que fallan los tests en Jenkins. Elastec te ayuda a descubrirlo
* Larga vida al legacy
* Un viaje por CosmosDB
* Microservices from the trenches
* El camino hacia evolvables APIs
* Cuando los propósitos de año nuevo se cumplen. Comparando Angular, React y Aurelia

