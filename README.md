Angular Template Project
=========================================

This project is a grunt project. You need a running grunt (and nodeJS) installation.

Installation:
	npm install

Features:

This project is a skeleton to use for new angular projects. It works out of the box without changes and uses the
following libarries:

	* angularJS (of course)
	* bower (for dependeny management of javascript libraries to be loaded in browser)
	* requireJS (for javascript module loading)
	* jslint (for quality javascript code)
	* grunt-manifest (an appcache manifest will be created while creating a deployable artifact)
	* grunt-targethtml (filtering of html files for deployment on production servers)
	* karma (as a test runner for unit tests and ui tests)


While running local web server following actions will be run automatically:
	* unit-tests (after changes in javascript files)
	* live reloading of ressources (after changes in HTML/JS/CSS files)

To start the local web server:
	grunt web

Create a deployable artifact for your real webserver:
	grunt install