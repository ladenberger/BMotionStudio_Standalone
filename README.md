# Building the binary

(1) Create a folder named "root" and put your template files into this folder.

(2) run 'gradle -Prootfile=XXX buildAll' 
    where XXX is the name of the template file in the root folder (e.g. template.html)

If you don't have gradle installed, you can use the gradlew script provided.

./gradlew -Prootfile=XXX buildAll

will work without a gradle installation on your computer.

This will produce a zipped standalone version for all platforms. 
The zip files are located in the build/distributions folder.


