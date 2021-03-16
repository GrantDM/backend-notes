# Backend notes

## Full Stack Python article

Databases are used for storing data so we can have a lot of it accessable and easy to gave whenever we need to. Helps us to setup that data in an ordered or structured way so that large amounts of it are more easily dealt with.

We get to turn data into dictionary like structures where they will have keys that we can call specifically and the data or object will be associated with whatever key it is given when the data is generated. 

common databases

* PostegreSQL
* MySQL

### PostegreSQL Database

recomended relational database, well established and loads of features. This has has a very wide and long time usage by people all over

### MySQL Database

this database is easier to get into but is less feature rich as PostegreSQL

### Connecting Databases

in order to use the databases outside of the built in SQLite we will need to add libraries. Psycopg2 for PostegreSQL, MySQL (will need to find some drivers for this), Oracle moved their open source driver to GitHub.

### Other Stuff

Recommending learning some SQL to be able to right basic schemas and better understand what is happening behind th scenes with the ORM. learning tools such as [Select Star SQL](https://selectstarsql.com/) will help teach SQL and allow the developer to do more to better their product.

With much much more to read up on and learn.

This information came from the page [Full Stack Python](https://www.fullstackpython.com/databases.html) 



## Full Stack Python Deployment

Deployment pertains to the idea of taking an app and turning it out to either the public or to the client so that they will be able to have a working version of this app. We know from the side that this allows us to have a working version on the frontlines but for us to be making changes or improvements in the barground that we can deploy onto the currently working version to fix issues or turn out new features.

### Deployment hosting

* "Bare metal" servers
* Virtualized Servers
* Infrastructure-as-a-service
* Platform-as-a-service

the first 3 servers work in similar ways. You get some servers with Linux distribution, system packages, web server, WSGI server, database and Python environment all installed then you can finally pull your app to that server to host it from.

There are a few deployment tools, Teletraan. pants. Screwdriver

### Other Stuff

There are a bunch of deployment resources at the bottom of this page that could come in handy later. [Full Stack Python Deployment](https://www.fullstackpython.com/deployment.html)



## Django Podcast

The [podcast](https://talkpython.fm/episodes/show/301/deploying-and-running-django-web-apps-in-2021)

### General notes to be refined after the fact

Guests: [Will Vincent](https://wsvincent.com/) and Carlton Gibson on Twitter (@caltongibson)

django frameworks last generally 3 years

you should always try to stay up to date with Django, even if it temporarily breaks. If you cannot stay 100% up to date then you should always stay up to date on the LTS version.

Non LTS version updates roughly once per eight months. While LTS version lasts about 3 years. 

flask vs django - django is more feature rich and a bit more complicated framework. Flask is simpler to use but you will have to add micro-frameworks to get to the same level of features

newer version of django will have more PK's so bigger sites won't have a problem running out









