# Remedios caseros
## Introduction
	Remedios caseros means "home remedies" in english. It is a web designed to 
	store recipes that help you to alleviate some annoyance that you might have,
	it could be drinks or food. Every day shows a random recipe from the 
	community and allows to search for recipes but not to add one to the list.
	If you register you can create a recipe as well as navigate from the recipes
	or ingredients lists.
	See the demo to see it in action in Youtube: [Remedios caseros]()

## Structure
	- Framework: Flask
	- Templating language: jinja
	- Folders:
		* static: css, images, javascript files
		* templates: html files
	- application.py: server-side application
	- remedies.db: database
	- helpers.py: decorators for application.py
	- requirements: libraries needed
	- sql-statements: sqlite3 sql staments
		

	It was designed using the micro web framework Flask. Therefore it is 
	structured  whit the following schema: templates files are stored in the 
	templates directory (html files) and the static files
	(images, css, javascript) are stored in the static folder. In addition to 
	those two folders there is the server-side application (application.py), 
	the database (using sqlite3, remedies.db) a helpers.py file with a decorator
	for login, libraries required, and sql-statements. It also uses the jinja 
	syntax in the html files as the templating language.