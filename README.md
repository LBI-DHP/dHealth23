# dHealth23

Usability Test 1 - Prototype: https://resources.lbi-dhp.at/mlm4jitais/ddo-playground-basic.jar 

Usability Test 2 - Prototype: https://resources.lbi-dhp.at/mlm4jitais/ddo-playground-v1.jar

To run the prototypes, you need at least (Oracle) JDK version 18 (e.g., see https://www.oracle.com/java/technologies/downloads/). In case your JDK (e.g., OpenJDK) does not come with the JavaFX SDK, you also need to download it (e.g., see https://openjfx.io/).

Double click or run the prototypes via console:
- java -jar ddo-playground-basic.jar
- java -jar ddo-playground-v1.jar

In case you had to additionally download the JavaFX SDK, you have to run the protoypes via console:
- java --module-path "<path to your JavaFX SDK lib folder>" --add-modules javafx.controls,javafx.fxml -jar ddo-playground-basic.jar
- java --module-path "<path to your JavaFX SDK lib folder>" --add-modules javafx.controls,javafx.fxml -jar ddo-playground-v1.jar
