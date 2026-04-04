# java_gui</BR>

# Scene Builder</BR>
Scene Builder: https://gluonhq.com/products/scene-builder/thanks/?dl=https://download2.gluonhq.com/scenebuilder/</BR>

# Eclipse Setup</BR>
1. javafx - e(fx)clipse</BR>
2. Create Java FX Project, delete module-java file</BR>
3. Mouse right click project, Build Path --> Configure Build Path...</BR>
4. Libraries Tab --> Classpath --> Add Library... --> User Library -->JavaFX24</BR>
5. Click Run --> Run Configuration --> (x)=Arguments </BR>
6. VM arguments = --module-path "C:\Program Files\Java\javafx-sdk-24\lib" --add-modules javafx.controls,javafx.fxml --enable-native-access=javafx.graphics</BR>
7. Click Dependencies Tab --> Click Modulepath Entries  --> Click Advance --> Select Add Library --> User Library --> JavaFX24</BR>


https://gluonhq.com/products/javafx/</BR>
https://openjfx.io/</BR>
https://pragmaticways.com/how-to-add-javafx-to-eclipse-the-easy-way/</BR>


```
<dependency></BR>
    <groupId>org.openjfx</groupId></BR>
    <artifactId>javafx</artifactId></BR>
    <version>25-ea+11</version></BR>
</dependency></BR>
```

Swing - windowBuilder</BR>
