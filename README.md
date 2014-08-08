# Building the binary

(1) Create a folder named "root" and put your template files into this folder.

(2) Run the following command, where XXX is the name of the template file in the root folder (e.g. template.html):

```
gradle -Pstandalone -Prootfile=XXX buildAll
```

If you don't have gradle installed, you can use the gradlew script provided:

```
./gradlew -Pstandalone -Prootfile=XXX buildAll
```

This should build the binaries without a gradle installation on your computer.

The gradle script will produce a zipped standalone version for all platforms. The zip files are located in the build/distributions folder.


