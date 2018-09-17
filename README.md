#rest-api-extension-archetype

##Disclaimer
* Use a JRE/JDK 1.8

##How to build the archetype

```
git clone https://github.com/bonitasoft/bonita-project-archetype.git
cd bonita-project-archetype
mvn clean install -DskipTests
```

##How to use the archetype

```
mvn archetype:generate \
-DarchetypeGroupId=org.bonitasoft \ 
-DarchetypeArtifactId=bonita-project-archetype \ 
-DarchetypeVersion=1.0.0-SNAPSHOT \
-DgroupId=org.company \
-DartifactId=myProject \
-Dversion=0.0.1-SNAPSHOT
```

###Optionnal archetype parameters


| Parameter         | Default value                     | Description                                                                            										   |
| ------------------|-----------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| -DbonitaVersion   | 7.0.1                             | The version of bonita used for this project								   |
| -Dedition         | community                      | community or sp dependencies									       |
| -DdisplayName  | My Rest API extension             | A display name for your project										   |
| -Ddesc         | My Rest API extension description | A short description of the project						   |