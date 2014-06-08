grails-plugin-compatibility
===========================

Gradle script that tries to compile all popular grails plugins against a certain grails version (Hackergarten project)

git clone https://github.com/mifi/grails-plugin-compatibility.git
cd grails-plugin-compatibility.git
wget 'http://grails.org/plugins/?filter=installed&offset=10&max=100' -O 1.html
gradle testAllPlugins
