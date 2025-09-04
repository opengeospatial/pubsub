
build:
	docker run -v "${PWD}":/metanorma -v ${HOME}/.fontist/fonts/:/config/fonts  metanorma/metanorma  metanorma compile --agree-to-terms -t ogc -x xml,html,doc,pdf document.adoc

clean:
	rm -f *.html *.xml *.xml.abort *.xml_tmp *.doc *.pdf *.pdf.err *.log.txt

.PHONY: build clean
