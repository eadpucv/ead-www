
.PHONY: less


server:
	jekyll server --watch --baseurl=

local:
	jekyll server --watch --baseurl= --port=4444

less:
	lessc less/giornata.less css/giornata.css --clean-css

css: less

dist: 
	cp -R bower_components/stampa/fonts .