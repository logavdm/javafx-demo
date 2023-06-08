# javafx-demo

1.JavaFX SDK download link : https://download2.gluonhq.com/openjfx/20.0.1/openjfx-20.0.1_windows-x64_bin-sdk.zip

2.Unzip downloaded file and add all the jars inside lib folder to project module path

3. just import this project in eclipse

4. add provided mysql connector jar in build path ( lib/mysql-connector-j-8.0.32.jar )

5. create database  ( library )

6. import sql script -> db/library.sql

7. Add below VM arguments in Eclipse 
    --module-path "Your JavaFX lib folder" --add-modules javafx.controls,javafx.fxml
