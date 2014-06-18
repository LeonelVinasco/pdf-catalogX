pdf-catalogX
============

Publish PDF Catalog to the web. Automatically generates thumbnails &amp; searchable catalog (extracting metadata from PDF titles).


## Stack:

- Node.js
- Grunt (JS Task Runner)
- ExpressJS Web Framework
- Handlebars.js Templating Library
- pdfutils.js npm module (for reading PDF metadata & generating thumbnails)
- Mongoose ORM
- MongoDB


## Install:

Make sure Node.js v0.10.29 or up and npm are installed.

Clone this repo:
```
git clone https://github.com/badarahmed/pdf-catalogX.git
```

Run npm install to install all node dependencies:
```
npm install
```

Install MongoDB. Follow instructions here:
http://docs.mongodb.org/manual/installation/


## Generating PDF Catalog:
Run the populatedata.js script in dbx folder:
```
node populatedata.js
```
*This script assumes MongoDB database is setup at localhost/pdfcatalogx. This is configurable. Please make sure to create a MongoDB database before attempting to generate the catalog.*

## Start Web Application:

You can use grunt (default target) to start a local webserver & serve the app over it:
```
grunt
```

**PDF CatalogX is now live!**
