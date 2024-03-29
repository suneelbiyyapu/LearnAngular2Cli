# Angular2Cli
Leverages Angular CLI commands


To install Angular CLI
=====================================
	npm install -g @angular/cli

		(or)

	npm i -g @angular/cli

To check Angular CLI version
=====================================
	ng -v

To create a project
=====================================
	ng new MyFirstApp

To run the app into default browser
=====================================
	ng serve --open

To run all unit test
=====================================
	ng test

To run all the end to end tests
=====================================
	ng e2e

To create component
=====================================
	ng generate component {component name}

	(or)

	ng g c {component}

Generate component in different folder
=====================================
	ng g c abc/xyz

Create component without folder
=====================================
	ng g c xyz --flat

For inline template, inline style and No spec files
=======================================================
	ng g c {component-name} -it -is --spec=false

For specific style type
=====================================
	ng g c {component-name} --style=scss

For dry run
=====================================
	ng g c {component-name} -d 



Services
=========

	To create service
	==========================================
		ng generate service {service-name}

		(or)

		ng g s {service-name}

	Create and register service
	==========================================
		ng g s {service-name} --module=app.module

		(or)

		ng g s {service-name} -m=app.module

	To create separate folder for each service
	==========================================
		ng g s {service-name} -m=app.module --flat=false


Module
==============

	To create module
	=============================================
		ng generate module {module-name}

		(or)

		ng g m {module-name}

	Create and register module
	==========================================
		ng g m {module-name} --module=app.module

		(or)

		ng g m {module-name} -m=app.module

	Not to create separate folder for each service
	===============================================
		ng g s {service-name} -m=app.module --flat=true

	To create spec file
	===============================================
		ng g s {service-name} -m=app.module --spec=true


Directives
==================================

	To create directive
	================================================
		ng generate directive {directive-name} --skip-import

		(or)

		ng g d {directive-name} --skip-import

	Create and register directive
	==========================================
		ng g d {directive-name} -m=app.module


Pipes
==================================

	To create Pipe
	================================================
		ng generate pipe {pipe-name}

		(or)

		ng g p {pipe-name}

	Create and register Pipe
	==========================================
		ng g p {pipe-name} -m=app.module


Guard
==================================

	To create Guard
	================================================
		ng generate guard {guard-name}

		(or)

		ng g g {guard-name}

	Create and register Guard
	==========================================
		ng g g {guard-name} -m=app.module
		

Type script 
=============================

	To create class
	=============================
		ng generate class {class-Name}

		(or)

		ng g cl {class-Name}

	To create Interface
	=============================
		ng generate interface {interface-Name}

		(or)

		ng g i {interface-Name}

	To create Enum
	=============================
		ng generate enum {enum-Name}

		(or)

		ng g e {enum-Name}
