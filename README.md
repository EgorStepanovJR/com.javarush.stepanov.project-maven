===================================================================================================================================
RU
===================================================================================================================================

Для сборки и проекта следует пройти следующие шаги:

- в терминале пишем:
  // mvn clean install
  
- если desktop-game-engine.jar не резолвится, добавляем его через терминал командой:
  // mvn install:install-file -Dfile=!!!ПУТЬ ДО "lib/desktop-game-engine.jar"!!!  -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar
  // в моем случае так: mvn install:install-file -Dfile=C:/Java/ProjectRepository/com.javarush.stepanov.project-maven/lib/desktop-game-engine.jar -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar

- далее пробуем еще раз собрать наше проект через терминал:
  // mvn clean install

- ждем заветное:
  
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  01:14 min
[INFO] Finished at: 2025-01-26T14:07:59+03:00
[INFO] ------------------------------------------------------------------------

- теперь можно приступать к запуску проекта. Открывает командную строку и пишем (не забываем указать свой путь к проекту):
  // java -jar "C:\Java\ProjectRepository\com.javarush.stepanov.project-maven\target\project-maven-1.0.jar"

===================================================================================================================================
EN
===================================================================================================================================

To build and project, follow these steps:

- in the terminal we write:
// mvn clean install

- if desktop-game-engine.the jar does not resolve, we add it through the terminal with the command:
  // mvn install:install-file -Dfile=!!!THE PATH TO "lib/desktop-game-engine.jar "!!!  -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar
  // in my case: mvn install:install-file -Dfile=C:/Java/ProjectRepository/com.javarush.stepanov.project-maven/lib/desktop-game-engine.jar -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar

- next, we try to build our project again through the terminal:
// mvn clean install

- we are waiting for the cherished:
  
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  01:14 min
[INFO] Finished at: 2025-01-26T14:07:59+03:00
[INFO] ------------------------------------------------------------------------

- now you can start launching the project. Opens the command prompt and writes (do not forget to specify your path to the project):
  // java -jar "C:\Java\ProjectRepository\com.javarush.stepanov.project-maven\target\project-maven-1.0.jar"
