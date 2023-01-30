# dHealth23

## Usability testing of a multi-level modeling framework for just-in-time adaptive interventions (JITAIs) in mobile health

### Usability test 1

- [Slides and tasks](https://github.com/LBI-DHP/dHealth23/blob/main/Usability%20Test%201%20-%20Basic%20Multi-Level%20Modeling%20in%20RDF%20and%20SHACL.pdf)
- [Prototype](https://resources.lbi-dhp.at/mlm4jitais/ddo-playground-basic.jar)
- [Survey](https://github.com/LBI-DHP/dHealth23/blob/main/Usability%20Test%201%20-%20Survey.pdf)

### Usability test 2

- [Slides and tasks](https://github.com/LBI-DHP/dHealth23/blob/main/Usability%20Test%202%20-%20Deep%20Domain%20Object%20plus.pdf)
- [Prototype](https://resources.lbi-dhp.at/mlm4jitais/ddo-playground-v1.jar)
- [Survey](https://github.com/LBI-DHP/dHealth23/blob/main/Usability%20Test%202%20-%20Survey.pdf)

### Prototypes

Please note that we used two different versions of the prototype for the usability tests. For the first usability test, we reduced the functionality and provided a fixed model. For the second usability test, we provided the prototype with its full functionality.

To run the prototypes, you need at least (Oracle) JDK version 18 (e.g., see [here](https://www.oracle.com/java/technologies/downloads/)). In case your JDK does not come with the JavaFX SDK (e.g., OpenJDK), you also need to download the JavaFX SDK (e.g., see [here](https://openjfx.io/)).

Double click or run the prototypes via console:
- java -jar ddo-playground-basic.jar
- java -jar ddo-playground-v1.jar

In case you had to additionally download the JavaFX SDK, you have to run the protoypes via console:
- java --module-path "\<path to your JavaFX SDK lib folder\>" --add-modules javafx.controls,javafx.fxml -jar ddo-playground-basic.jar
- java --module-path "\<path to your JavaFX SDK lib folder\>" --add-modules javafx.controls,javafx.fxml -jar ddo-playground-v1.jar
