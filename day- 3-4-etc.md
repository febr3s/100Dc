- terminar de vaciar cuenta google
- hacer mercado
- cuadrar con Tony


# Requesting a Google API key for Google Maps

- Go to console.cloud.google.com
- Go to the Dashboard of one of your projects (if you haven't created a project, retweet, follow me, leave a comment saying the name of your project and I will send you a guide to create it)
- menu botton >> hover api and services >> click on credentials
- top menu, click "+ create credentials", select api key
- edit, this is a restrictions overview: https://youtu.be/2_HZObVbe-g?t=99
- https://developers.google.com/maps/get-started#enable-api-sdk (I found out the url by running the api, exploring the console and clicking on the url it provided to fix the problem)
- Resulta que hay más de una API de Google Maps... no hice captura de la parte más importante
- Te da una API key distinta a la que aparece en la consola.. no entiendo por qué
- pide certificado ssl https://web.dev/how-to-use-local-https/

# Creating a Google Cloud project

- console.cloud.google.com
- log in (if you don't have a cloud account...)
- on the top right corner click on de drop-down menu of projects and/ or click on new project
- 

# Google Maps billing

https://developers.google.com/maps/billing-and-pricing/billing

En resumen: son tres meses gratis hasta cierto punto. Después hay que pagar. ¿Cuánto?

https://cloud.google.com/free/docs/free-cloud-features?_gl=1*18e4v1k*_ga*MTkyMzkxMDA1MC4xNjc1NjI5Mzcw*_ga_NRWSTWS78N*MTY3NTYzMzY3Mi4yLjEuMTY3NTYzNDA3My4wLjAuMA..#how-to-upgrade



# Types of credentials with examples

OAuth 2.0 keys: OAuth 2.0 is an open standard for authorization that enables third-party applications to obtain limited access to an HTTP service. In the context of GCP, OAuth 2.0 keys can be used to authenticate to GCP services and access resources on behalf of a user.

API keys: An API key is a simple encrypted string that is passed in by a client to identify the calling project and to provide access to the resources associated with that project. API keys can be used for authentication for certain GCP services, such as Google Maps.

Service Accounts: A service account is a special type of Google account that belongs to your application or a virtual machine (VM), instead of to an individual end user. Service accounts can be used to perform automated tasks, such as running a batch process or accessing GCP resources programmatically. Service accounts can be granted permissions to access GCP resources and services, and can be used for server-to-server authentication.

In summary, OAuth 2.0 keys are used for authorization and provide access to resources on behalf of a user, API keys are used for authentication for certain services and provide access to resources associated with a project, and Service Accounts are used for automated tasks and provide access to resources programmatically.

# Day 5

Learning about Github Workflows: https://docs.github.com/en/actions/using-workflows/about-workflows

> A workflow is a configurable automated process that will run one or more jobs. Workflows are defined by a YAML file checked in to your repository and will run when triggered by an event in your repository, or they can be triggered manually, or at a defined schedule.

> Workflows are defined in the .github/workflows directory in a repository, and a repository can have multiple workflows, each of which can perform a different set of tasks. For example, you can have one workflow to build and test pull requests, another workflow to deploy your application every time a release is created, and still another workflow that adds a label every time someone opens a new issue.

To workaround the fact that you cannot run plugins on the GitHub server: https://github.com/jeffreytse/jekyll-deploy-action

Side note about Visual Studio Code: On Mac you can hit cmdshift. in the open file dialog, to see hidden files.

I made it until the yml file. I don't understand this: "To schedule a workflow, you can use the POSIX cron syntax in your workflow file. The shortest interval you can run scheduled workflows is once every 5 minutes. For example, this workflow is triggered every hour." I am going to browse the repositories that are using it to get it. I have to understand the "personal action token" thing too.

# Day 5

Today I am only going to list the immediate modifications necessary for MOREL to be at its MVP. Afterwards I might think of working on a new exciting feature such as maps

- Filter out books without facsimilar cover from Index [done]
- Make the whole book clickable [done]
- Finish transition form md to csv
- Integrate MOREL to Zotero
- Integrate MOREL to archive.org
- Start working on step by step tutorial
- Add zotero metadata generator
- Obra "Gaucha"

Pido dinero para:

- Promotion (among users)
- Affiliate marketing
- POP material integration

# 6

Hoy aprendí que no se ejecutan scripts de python sobre un browser abierto, por regla general. Si lo quieres hacer, hay workarounds que habría que explorar. Está uno en el folder de guías por si chatgtp está inaccesible la próxima vez que experimente.

También refresqué lo de los ambientes de Python.

# 7

It turns out that there was a better approach to copy the urls: https://www.howtogeek.com/723144/how-to-copy-the-url-addresses-of-all-open-tabs-in-chrome/

# 8

Non-featured books list:

https://morel.la/obras/cuentos-quiroga
https://morel.la/obras/argentina-ruy-diaz-guzman
https://morel.la/obras/arte-revolucion-cesar-vallejo
https://morel.la/obras/circo-papel-alfaro
https://morel.la/obras/felisberto-casa-inundada
https://morel.la/obras/fermin-toro-martires
https://morel.la/obras/horacio-quiroga-cuentos
https://morel.la/obras/horacio-quiroga-cuentos-amor-locura
https://morel.la/obras/jotabeche-articulos
https://morel.la/obras/juguete-rabioso-arlt
https://morel.la/obras/lazarillo-ciegos-araujo
https://morel.la/obras/literatura-y-estetica-mariategui
https://morel.la/obras/martin-fierro-jose-hernandez
https://morel.la/obras/maria-jorge-isaacs
https://morel.la/obras/monja-casada-riva-palacio
https://morel.la/obras/nataniel-aguirre-juan-rosa
https://morel.la/obras/palma-tradiciones-peruanas-dos
https://morel.la/obras/poemas-humanos-vallejo-cesar
https://morel.la/obras/poemas-alfonsina-storni
https://morel.la/obras/poesias-completas-alfonso-moreno
https://morel.la/obras/simon-rodriguez-gonzalo-picon
https://morel.la/obras/tradiciones-peruanas-uno
https://morel.la/obras/anecdotario-froylan-turcios

cuentos-quiroga.md
argentina-ruy-diaz-guzman.md
arte-revolucion-cesar-vallejo.md
circo-papel-alfaro.md
felisberto-casa-inundada.md
fermin-toro-martires.md
horacio-quiroga-cuentos.md
horacio-quiroga-cuentos-amor-locura.md
jotabeche-articulos.md
juguete-rabioso-arlt.md
lazarillo-ciegos-araujo.md
literatura-y-estetica-mariategui.md
martin-fierro-jose-hernandez.md
maria-jorge-isaacs.md
monja-casada-riva-palacio.md
nataniel-aguirre-juan-rosa.md
palma-tradiciones-peruanas-dos.md
poemas-humanos-vallejo-cesar.md
poemas-alfonsina-storni.md
poesias-completas-alfonso-moreno.md
simon-rodriguez-gonzalo-picon.md
tradiciones-peruanas-uno.md
anecdotario-froylan-turcios.md

Parece que logré exitosamente agregar metadata en el yaml con un script. De paso me quedó un script para convertir una lista sencilla en un array.

# 9

Trying the metadata script.
Worked. But I had to add another script to strip it from a previous "feature" tag.
Worked on internal server. Struggling a little bit with the branches and stuff.
Stayed here: Permission to morelcoop/morelcoop.github.io.git denied to febr3s.

# 10

Added febr3s to repo and pushed changes.
La mejor forma de agregar una mayor zona clickeable es convertir en link el texto del overlay, nada más. Hay que ponerle el estilo nuevo que creé para que no se oscurezca. Sin embargo, eso me hizo dar cuenta de que probablemente la plantilla que estoy editando está desactualizada. Hay que cotejar para seguir.

# 11

En efecto, la última versión de la plantilla es aalt-morel, y aunque sea muy fastidioso, la reconstrucción por pasos y migración a la plantilla actualizada va a ser necesaria para que toda otra modificación valga la pena.

Es decir, hay que volver a las líneas rotas. Y quizá en paralelo hacer los mínimos cambios que faltan para hacer la promoción con marcalibros.

Managed to do the script to fix the line breaks in poems so they can be stored on a csv.

# 12


Making the list of poem pages to use the script add-metadata and fix breaking lines
Haciendo el primer corte en _Lógica viva_
Segunda tanda por accidente guardada en Firefox. Hasta _Litigio_

# 13 

Finished the list of poem pages

# 14

Creating a python script to create the array from a simple list

Not necessary, I had already done that.

Hours trying to appending ../../src to the python scripts that were in the src folder, to execute them from the virtual environment, but the fact is tat such environment is activated regardless of where the command line is... therefore it wasn't necessary. But I learned a couple of things about PYTHONPATH, PATH, and PYTHONHOME that may be useful in the future.
Also it was good to know that "modules" in Python are just scripts

# 15

Added genre: poetry to all the poetry pages found manually on the site.
I have to run the line breaks scripts on them, and try how they look on a pre-csv table.
Also have to open morel on visual studio code and find out what are all those commits. In two words: catching up with origin.

# 16

Catched up with origin. Waiting deploy to confirm everything is ok.
Para seguir con md to csv:

1 - hay que cambiar en los poemas todo doble line break por un single line break antes de hacer el cambio por <br>
2 - hay que correr el script por todos los textos porque los fragmentos con diálogo también se joden en la tabla
3 - habría que ver cómo se almacenan las notas en zotero para emular en lo posible el mismo formato

# 17

1. Abort. What I will do is to run the script once it is on a csv, working directly with the html tags.

2. Listo para correr el script. Hay que mover de morelcoop.github... lo que está dentro de la carpeta _books y correr el script sobre ella para pasar a crear el csv

# 18

Se rompia la tabla. Después de mucho probar, limitando el número de books a 25 funciona. Tocará irlos pasando manualmente de 25 en 25.

A menos que encuentre una forma de hacerlo con un script en los próximos 10 minutos.

It is worth noting that today I learned about striping whitespace on Liquid https://shopify.github.io/liquid/basics/whitespace/

Also, used the iteration tag parameter "limit". Tomorrow I will proably use "offset" https://shopify.dev/docs/api/liquid/tags/iteration-tags


# 19

Ya md-to-csv está listo para empezar a mover los datos. Quizá doble chequear que el formato sirva para movernos a Zotero sin mucho trauma. Para eso hay que traerse el disco duro a la cama. De hecho debería comenzar probando la transición a Zotero con los primeros 25. Y quizá de hecho podría ser mejor importar a Zotero de 25 en 25 y comenzar a trabajar con esa base de datos. Mosca que en las páginas de libro originales está el dato de la fecha de nacimiento del autor, que sería bueno recuperar. Aunque en este punto quizá mejor probar la integración con la API de Wikipedia. 